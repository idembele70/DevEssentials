# Multiple Issue Templates Arranged by Type


## Test issue template
#### Title: 
```
feat: create test for <use_case_title> use case <user_case_number>
```

#### Labels: 
| Name          | color         |
| ------------- | ------------- |
| Test          | #0201A7       |

```
**User Story**
----
As a developer, I want to make sure that when I push code to <branch_name>, users can still <explain_your_action>.

**Quick description**
----
- On <page_name> page, allow <explain_your_action>.

**Nominal Process:**
----

1. Your First process
2. Your second process
3. Third process
4. process XYZ
```
## Bug issue template
#### Title:
```
fix: <brief_description>
```
#### Labels:
| Name          | color         |
| ------------- | ------------- |
| Bug          | #d73a4a        |

```
**Describe the bug**
------
A clear and concise description of what the bug is. Ex. As a [user or developer], I want to...

**Steps to reproduce**
------
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. Run the following command line: <your_bash_script>
5. See error

**Screenshots**
------
If applicable, add screenshots to help explain your problem.

**Reproducable on**
------
- [ ] <branch_name Ex.dev>
- [ ] <branch_name Ex.local>
- [ ] <branch_name Ex.staging>
- [ ] <branch_name Ex.prod>


**Expected output**
-----
<your_expected_output>.

**Additional context**
-----
Add any other context about the problem here.
```

## Feature issue template
#### Title: 
```
feat: <brief_description>
```

#### Labels: 
| Name                                 | color         |
| ------------------------------------ | ------------- |
| <enchancement\|feature\|feat>        | #a2eeef       |

```
**User story**
------
A clear and concise description of what the feature is. Ex. As a [user or developer], I want to...

 **Objective**
------
 The main goal of your feature. Ex. Make sure that the user sees the success popup when, they validate a form.

 **Expected output**
-------------
A list of what to expect as a result, screenshot can be added
1. Your First expect
2. Your second expect
3. Third expect
4. expect XYZ 

**Some use cases**
-----------
A list of use cases from your documentation
1. Your First use case
2. Your second use case
3. Third use case
4. use case XYZ 

**Screenshots** (if any)
--------
Additional Screenshots here

**Definition of done**
--------
- [ ] <merged into branch_name? Ex.dev>
- [ ] <dev auto test? Ex.Test cases>
- [ ] <Added to the documentation? ex.Documentation>
```

## Move test cases to a new scenario issue template
#### Title: 
```
Move <E2E|unit> test cases for <yourOldUseCaseNumber> '<yourUseCaseTitle>' functionality into the new scenario as <yourNewUseCaseNumber>.
```

#### Labels:
| Name          | color         |
| ------------- | ------------- |
| Test          | #0201A7       |

```
**User story**
----
As a developer, I want to migrate E2E test case for '<yourOldUseCaseTitle>' into the new scenario, ensuring that this functionality is properly tested according to best practices and remains free of regressions.

**Quick description**
----
Move E2E test file related to the UC <yourOldUseCaseNumber> '<yourUseCaseTitle>' functionality into the new scenario as <yourNewUseCaseNumber>.

**Nominal process**
----
1. Your First process
2. Your second process
3. Third process
4. process XYZ
 ```

## Fix CI/CD Broken e2e tests
#### Title: 
```
Feature: fix e2e test cases from CI-CD run #<yourCiCdNumber>
```
#### Branch name: 
```
feature/fix-e2e-broken-test-cases-from-ci-cd-run-<yourCiCdNumber>-#<yourIssueNumber>
 ```
The label should be called: Support with color: #4F047E, Test with color: #0201A7

If there's a issue type: Bug with color: #fff0ee
```
**User Story**
----
As a developer, I want to make sure that when I push code to <branch_name>,test from this [CI-CD pipeline](https://github.com/org/repo/actions/runs/<yourCiCdNumber>) don't fail due to broken test cases.

**Quick description**
----
- Fix the broken test cases identified in the [Github Actions pipeline](https://github.com/org/repo/actions/runs/\<yourCiCdNumber\>)

**Nominal Process:**
----
Fix those broken test files: 
- [ ] Test_A
- [ ] Test_B
- [ ] Test_C
 ```

**New list Item starter**
 -----
## <template_type> issue template
#### TITLE: <feat|fix|...>: <brief_description>
 
#### Label:
| Name          | color              |
| ------------- | ------------------ |
| Name          | #hexadecimal       |

```
<paste_your_template>
 ```
