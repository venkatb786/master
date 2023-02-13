# React Code
Coding url https://blog.bitsrc.io/most-important-javascript-coding-challenge-aa14c956d2df
### toFindDuplicates
```
const arry = [1, 2, 1, 3, 4, 3, 5];
const toFindDuplicates = arry => arry.filter((item, index) => arr.indexOf(item) !== index)
const duplicateElementa = tofindDuplicates(arry);
console.log(duplicateElements);

// Output: [1, 3]
```
### toCountDuplicates Ex:1
```
const myArray = ['a', 'b', 'c', 'c', 'b', 'd'];

const elementCounts = {};
myArray.forEach(element => {
  elementCounts[element] = (elementCounts[element] || 0) + 1;
});
console.log(elementCounts);
```
### toCountDuplicates ex:2:
```
const myArray = ['a', 'b', 'c', 'c', 'b', 'd'];
var elementCounts = myArray.reduce((count, item) => (count[item] = count[item] + 1 || 1, count), {});
console.log(elementCounts);
```
### toCountJSONDuplicates ex: 1
```
const myArray = [
{name: 'test', age: 20},
{name: 'test', age: 22},
{name: 'test', age: 30},
{name: 'test', age: 27}
];

const counts = {};
myArray.forEach(element => {
if(!counts[element.age]){
	counts[element.age] = [element.age]
}else{
counts[element.age].push([element.age])
} 
});

console.log(counts);
```
 
### Reverse
```
function reverseBySeparator(string, separator) {
  return string.split(separator).reverse().join(separator);
}
```

### Recursion
```
function add(number) {
  if (number <= 0) {
    return 0;
  } else {
    return number + add(number - 1);
  }
}
add(3) => 3 + add(2)
          3 + 2 + add(1)
          3 + 2 + 1 + add(0)
          3 + 2 + 1 + 0 = 6 
```
### HOC
```
import React from 'react';
// Take in a component as argument WrappedComponent
const higherOrderComponent = (WrappedComponent) => {
// And return another component
  class HOC extends React.Component {
    render() {
      return <WrappedComponent />;
    }
  }
  return HOC;
};

```

### Use Context
```
import React from 'react';

const DaylightContext = createContext({});
export function DaylightContextProvider(props) {
  const currentDate = new Date();
  const hour = currentDate.getHours();
  const isDaylight = hour > 8 || hour < 20;
  
  return (
    <DaylightContext.Provider value={{ isDaylight: isDaylight }}>
      {props.children}
    </DaylightContext.Provider>
  );
}

export const useDaylightContext = () => useContext(DaylightContext);
```
