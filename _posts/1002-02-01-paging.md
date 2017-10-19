---
layout: post
---
Paging

![Picture example](https://raw.githubusercontent.com/kupolua/json-to-table/presentation/html/screenshot-with-paging-page-two.png)

user will be able to change number of row per page
or
use can set default values for pagin in css

```
<style type="text/css">
    .tableConfig {
        --header-toolbar-height: 35;
        --header-column-height: 30;
        --row-height: 26;
        --rows-per-page: 10;
        --rows-size-list: 10, 20, 50;
    }
</style>
```