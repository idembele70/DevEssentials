### Chatper 3: Finding Live Web Elements
1. Chrome DevTools
  - A Locator: will return all elements that match its query
  - Ids are the best types for locators by HTML standars the ID attribute must have a unique value on a given page.
  - Locate elements using attribute value in this order: ID or input name or class
  - Ensure your attribute value is unique on the page.
  - Each input element within a form should have a unique name and oftentimes the names are unique for the whole page as well.
  - Class name can be used by a single or multiple elements, its usefull when you want to locate a set of elements
2. It doesn't require no extra thought to write the locators when they don't appear as a tester I'll often ask developers to add them if I'm familiar with the code base and I have time, then I might even go add them myself in the worst case I'll use a more advanced locator like a CSS selector or an XPath
