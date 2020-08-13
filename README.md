# Project Title: Horiseon Website Code Refactor
___
## Objective
The objective of this task was to refactor the HTML and CSS code within the Horiseon website, resulting in improved web accessibility:
- for those individuals with physical and/or socio-economic disabilities.
- by using search engine optimization (SEO) key words and semantic elements.
___
## HTML Refactoring Changes
**The following items were added/changed to meet Web Content Accessibility Guidelines (WCAG) 2.0**
- A title was added to the **hero div** class to provide a description of the background image.
- **alt** attributes were added for the three images in the **content div** class to provide a description for each.
- **alt** attributes were added for the three images in the **benefit-type div** class to provide a description for each.
- A title was added to the **hero div** to provide a description of the background image.

**The following items were added/changed to increase search engine optimization (SEO)**
- **meta** tag: title and content containing descriptive Horiseon website related terms.
- **title** tag: was given more descriptive text for Horiseon.
- Semantic elements were added: **main, section, aside, and footer**.

**The following items were added/changed to provide a better flow and structure to the website, or correct the code**
- Added **id="search-engine-optimization"** to the **div** tag to redirect user to the search engine optimization section of the page. 
- **The online-reputation-management** image was floated left to be consistent with the images above and below it.
- The closing tag **/>** was changed to **>** for all of the images in the **content div** class and **benefit-type div** class.
- Comments were included in areas of the code to add clarity.
___

## CSS Refactoring Changes
- The **.float-right** selector was removed since all images in the "content" **div** class were changed to **.float-left**
- Three **.content-type** selectors were created to consolidate redundant properties of other associated selectors.
- Three **.benefit-type** selectors were created to consolidate redundant properties of other associated selectors.
- The **.content-type img** selector was given a width property of **300px** to show visual consistency for the three images in the **content div** class.
- Some selectors were moved to better follow the layout of the HTML elements.
- Comments were included to add clarity.
___
## Summary
Accessibility has an important role in web development. Developers are obligated to include features that allow disabled individuals to have the same access to content as those who are non-disabled.  The use of **alt** attributes, and creating pages that follow an orderly visual structure improve all users experience.
Search engine optimization (SEO) practices can also increase the volume of users to the website.  Adding more descriptive terms in elements such as **title**  and **meta** tags can accomplish this.  Users searching for similar descriptive content that the website provides will more likely be directed to it.
