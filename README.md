# Array practice

Identify the time complexity of each of these functions with a 1 sentence
justification for your answer. Assume `arr` is an array of length _n_.

## `arr.push()`

Time complexity: O(1)
Space complexity: O(1)
Justification: you do not have to move anything your just pushing one to the end and its done your only saving one also so it never changes. however if the arr needs to be resized then it is 0(n);

[push on MDN][push]


## `arr.pop()`

Time complexity: O(1)
Space complexity: O(1)
you are just removing one item and its done so that is why.

[pop on MDN][pop]

## `arr.shift()`

Time complexity: O(n)
Space complexity: O(1)
on time you are moving all characters over that is why its 0(n) and space is you are only adding one item into memory that is why it is constant.

[shift on MDN][shift]

## `arr.unshift()`

Time complexity: O(n)
Space complexity: O(1)
Justification: you have to move all characters over just like shift. and space is still constant because its just one item into memory. the array does get resized though.

[unshift on MDN][unshift]

## `arr.splice()`

Time complexity: O(n)
Space complexity: O(n)
Justification: depends on the elements and how big or small worst case is 0(n) for both space and time.

[splice on MDN][splice]

## `arr.slice()`

Time complexity: O(n)
Space complexity: O(n)
Justification: all elements has to be copied.

[slice on MDN][slice]

## `arr.indexOf()`

Time complexity: O(n)
Space complexity: O(1)
Justification: worst case it has to look. but only needs one space.

[indexOf on MDN][indexOf]

## `arr.map()`

Time complexity: O(n)
Space complexity: O(n)
Justification: its looping through and then creating a new array thats why 0(n)
[map on MDN][map]

## `arr.filter()`

Time complexity: O(n)
Space complexity: O(n)
Justification: pretty close the same as map.

[filter on MDN][filter]

## `arr.reduce()`

Time complexity: O(n)
Space complexity: O(1)
Justification: another loop but it only changes value on accumulator

[reduce on MDN][reduce]

## `arr.reverse()`

Time complexity: O(n)
Space complexity: O(1)
Justification: time is because having to change places of everything but space is not changed

[reverse on MDN][reverse]

## `[...arr]`

Time complexity: O(n)
Space complexity: O(n)
Justification: has to iterate through for space and creates a new array 

[spread on MDN][spread]

[push]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push
[pop]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop
[shift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift
[unshift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift
[splice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice
[slice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice
[indexOf]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf
[map]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
[filter]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
[reduce]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce
[reverse]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse
[spread]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax
