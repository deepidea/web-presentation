---
layout: post
---
Example of custom function. you can you any library or HTTP method to ferch data

```
<script type="text/javascript">
    function ajaxDataProviderFunction(){
        return $.ajax({
            dataType: 'json',
            url: 'https://raw.githubusercontent.com/kupolua/web-presentation/master/json/db.json',
            success: function(jsonData){
                return jsonData;
            }
        });
    }
</script>
```
```
data-provider-function="ajaxDataProviderFunction"
```

*Please pay attention that we returning asynchronous method which returns data when making async call