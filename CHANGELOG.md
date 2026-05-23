## [1.0.2] 2025-05-23
- Added new a few new theme options.
- Adjusted so more elements are affected by themes.

## [1.0.1] 2025-05-22
- Added Build your Own Search Engine.
Add the following snippet to the HTML of any browser Journal page.
```
<div id="browser-app-search"></div>
<div id="browser-app-search-results"></div>
```
When rendered in the browser app, a search bar will appear and results will autopopulate in the results. You can add the following line to the top of any page to change the description in the search results.
```
<div id="browser-app-description">I go on the top line.</div>
```
You can add the following to ensure a page is not shown.
```
<div id="browser-app-no-index"></div>
```