# array in method callbacks

## what is array in javascript
ya kantenereki ay element iborat ast va element az index

push( );

yagon element ilova kardan ay ohir

```javascript
let array = [1,2,3,4,5]
let ad=arr.push(true)
console.log(ad) // 6
console.log(array)/// [1,2,3,4,5,true]
```


pop( );

yak element ro az ohir nest mekna



<!-- const fruits = ['apple', 'banana', 'orange'];
const lastFruit = fruits.pop(); // 'orange'
console.log(fruits); // ['apple', 'banana']
 -->

unshift( );

ay aval element dabavit mekna
```javascript
const fruits = ['banana', 'orange'];
fruits.unshift('apple'); // ['apple', 'banana', 'orange']
console.log(fruits); // ['apple', 'banana', 'orange']

```

shift( );

ay aval yata element udalit mekna

```javascript
const fruits = ['apple', 'banana', 'orange'];
const firstFruit = fruits.shift(); // 'apple'
console.log(fruits); // ['banana', 'orange']

```

toString ( );

array ro string mekna

```javascript
const fruits = ['apple', 'banana', 'orange'];
const fruitString = fruits.toString(); // 'apple,banana,orange'
console.log(fruitString); // 'apple,banana,orange'
```

indexOf ( );

mesanja ki hami element da jandm indexsay
```javascript
const fruits = ['apple', 'banana', 'orange'];
const index = fruits.indexOf('banana'); // 1
console.log(index); // 1

```

incudes( );

mebina ki hami element hastay da daruni masiv


```javascript
const fruits = ['apple', 'banana', 'orange'];
const hasBanana = fruits.includes('banana'); // true
console.log(hasBanana); // true
```
slice ( );

ay chandm to chandm indexsa bgira


join( );

Объединяет все элементы массива в строку.

```javascript
const fruits = ['apple', 'banana', 'orange'];
const fruitString = fruits.join(', '); // 'apple, banana, orange'
console.log(fruitString); // 'apple, banana, orange'
```

concat( )

Объединяет два или более массива и возвращает новый массив.

```javascript
const fruits = ['apple', 'banana'];
const moreFruits = ['orange', 'grape'];
const allFruits = fruits.concat(moreFruits); // ['apple', 'banana', 'orange', 'grape']
console.log(allFruits); // ['apple', 'banana', 'orange', 'grape']
```

splice( );
Изменяет содержимое массива, удаляя существующие элементы и/или добавляя новые.

```javascript
const fruits = ['apple', 'banana', 'orange'];
const removedFruits = fruits.splice(1, 1, 'grape'); // ['banana']
console.log(fruits); // ['apple', 'grape', 'orange']
console.log(removedFruits); // ['banana']
```


## javascript array methods callbacks

map( );

baroi elementoi masiva izminit kardan


forEach( );

baroi har yak elementi masiva izminit kardan

find ( );

mesanja yagonjiza moda element meta 

filter ( );

mesanja yagonjiza moda masiv meta 
