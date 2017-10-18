---
layout: post
---
To fetch selected rows use next function
```
<script type="text/javascript">
    function fetchSelectedRows(id){
        let selectedRows = jsonTableFunctions.fetchSelectedRows(id);

        alert('\'fetch selected rows\' hook result:' + JSON.stringify(selectedRows, null, 4));
    }
</script>
```
```
<button onclick="fetchSelectedRows('1')">Click to fetch selected rows</button>
```

