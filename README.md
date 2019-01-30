# apiAjaxJS

### Simple library API Ajax to request Json And  response Json   

### by using the [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
Promises are a clean way to implement async programming in JavaScript (ES6 new feature).
 Prior to promises, Callbacks were used to implement async programming.

```
<script type="text/javascript" src="apiAjax.js"></script>
<script type="text/javascript">
   apiAjax.get(url,process,header).then((resp)=>{
        // done 
   }).catch((resp)=>{ 
       // Error  
   });
   apiAjax.post (url,data,process,header).then((resp)=>{
        // done 
   }).catch((resp)=>{ 
       // Error  
   });
   
</script>
```
METHODS PUT , VIEW , DELETE , GET , POST
<br><br>
<hr>
AND UPLOAD This To Upload files
```
apiAjax.upload(url, FormData, process, header)
    .then(resp=>{
        // done 
    }).catch(resp=>{ 
        // Error
    })
```
show this [exmpale with VueJs & Flask](https://github.com/AlaaProg/Flask-Vue-xhr/blob/master/admins/static/js/components/upload.js#L75)
