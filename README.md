# Two Way
The simplest javascript two-way binding with 36 lines.

![preview](preview/preview.gif)

Live demo & playground at [here](https://jsfiddle.net/f0drz4g3/1/)


# Getting Started

```javascript
twoWay(object,input);
//access object.value will be input.value ( input.checked for checkbox )
```

If I want to have a notice when the value updated ?

```javascript
twoWay(object,input)
  .onUpdated(val=>{
    //do what you like
  })
  .onUpdated(val=>{
    //pretty cool. isn't it ?
  })
```


