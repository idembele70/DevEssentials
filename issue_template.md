# Multiple Issue Templates Arranged by Type


1. ### Test issue template
<b>TITLE</b> : feat: create test for "<use_case_title>" use case <user_case_number>

The label should be named: Test with color: #
```
**User Story**
----
As a developer, I want to make sure that when I push code to <branche_name>, users can still <explain_your_action>.

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
2. ### Bug issue template
<b>TITLE</b> : fix: <brief_description>
The label should be named: Bug with color: #<hexadecimal>
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

3. ## Feature issue template
<b>TITLE</b> : feat: <brief_description>
The label should be called: <enchancement|feature|feat> with color: #a2eeef
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

4. ## Move test cases to a new scenario issue template
<b>TITLE</b> : Move <E2E|unit> test cases for \<yourOldUseCaseNumber\> '\<yourUseCaseTitle\>' functionality into the new scenario as \<yourNewUseCaseNumber\>.
 
The label should be called: \<test\> with color: #\<0201A7\>
```
**User story**
----
As a developer, I want to migrate E2E test case for '<yourOldUseCaseNumber>' into the new scenario, ensuring that this functionality is properly tested according to best practices and remains free of regressions.

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

**New list Item starter**
 -----
<b>TITLE</b> : <feat|fix|...>: <brief_description>
<your_list_number>. ### <template_type> issue template
 
The label should be called: <template_type> with color: #<hexadecimal>
```
<paste_your_template>
 ```
