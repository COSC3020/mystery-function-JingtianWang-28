# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    //If the length is 1, return the only element.

    var foo = mystery(a.slice(1, a.length))
    //Call the mystery function and pass in the array start at the second element in sequence,         and     calculate the maximum value after recursion and store it in foo.
    
    if(foo > a[0]) return foo;
    else return a[0];
    //After calling the recursion, it will be compared with the first element in the array. If it     is greater than the first element, foo is returned.
    If it is less than, the first element is returned.
}
```
