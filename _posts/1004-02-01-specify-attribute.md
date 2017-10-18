---
layout: post
---
You can specify next attribute to define you custom function which will receive json object of selected row

```
<script type="text/javascript">
    function hookFunction(rowData){
        alert('\'on row selected\' hook result:' + JSON.stringify(rowData, null, 4));
    }
</script>
```
```
data-hook-on-row-selected="hookFunction"
```