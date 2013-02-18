```javascript
var scope = "global";
function checkScope(){
  var scope = "local";
  console.log(scope);
}
checkScope();
console.log(scope);
```

```javascript
var something = {
    prop: 10   
};

function myFunc(obj) {
    setTimeout(function() {
        console.log(obj);
    }, 10);   
}

myFunc(something);
something.prop = 20;
```
