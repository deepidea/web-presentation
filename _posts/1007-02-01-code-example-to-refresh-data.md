---
layout: post
---
```
<button onclick="jsonTableFunctions.refresh('1')">Click to refresh table</button>
```
```
<div class="json-table tableConfig"
     id="1"
     data-json-path="$..teachers"
     data-custom-fields='[
         {"fieldName":"firstName","columnName":"First Name","columnWidth":10},
         {"fieldName":"lastName","columnName":"Last Name","columnWidth":60},
         {"fieldName":"age","columnName":"Age","columnWidth":10},
         {"fieldName":"cellPhone","columnName":"Cell Phone","columnWidth":330}
     ]'
     data-column-text-length="50"
     data-hook-on-row-selected="hookFunction"
     data-provider-function="dataProviderFunction"
></div>
```
