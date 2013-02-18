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
