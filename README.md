# FizzBuzz

### (68)

```js
for(i=0;i<100;)console.log(++i%3?i%5?i:'buzz':i%5?'fizz':'fizzbuzz')
```

### (87)

```js
i=0,f="fizz",b="buzz",a=[,,f,,b,f,,,f,b,,f,,,f+b];while(i<100)console.log(a[i++%15]||i)
```

### (98)

```js
console.log(Array.apply(0,Array(100)).map((e,i)=>(++i%3?'':'fizz')+(i%5?'':'buzz')||i).join('\n'))
```
