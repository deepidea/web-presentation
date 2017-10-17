---
layout: post
---

## Fetch data by ajax

```
<script type="text/javascript">
  function ajaxDataProviderFunction(){
       return $.ajax({
          dataType: 'json',
          url: 'https://raw.githubusercontent.com/kupolua/web-presentation/master/json/db.json',
          success: function(jsondata){

              return jsondata;
          }
       });
  }
</script>
```
