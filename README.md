# js exercise to help Taiwo Ogunleye

```
console.log('Hi Taiwo Ogunleye!')

const array1 = ['a', 'b', 'c', 'd'];
const array2 = ['x', 'y', 'z', 'd'];
function commonElement(arr1, arr2) {
    for (let i = 0; i < arr1.length; i++) {
        for (let j = 0; j < arr2.length; j++) {
            if (arr1[i] === arr2[j]) {
                console.log(arr1[i])
                console.log(arr2[j])
                return true;
            }
        }
    }
    return false;
}
console.log(commonElement(array1, array2))

```

An exercise using some() method 

```
const array11 = ['a', 'b', 'c', 'd'];
const array21 = ['w', 'x', 'y', 'a'];

function checkFactor2(someArr1, someArr2) {
    let commonProp = someArr1.some(function (item) {
        return someArr2.includes(item)
    })
    console.log(commonProp)
}
checkFactor2(array11, array21);
```
