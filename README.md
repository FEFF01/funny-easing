## funny-easing

> * [Examples](https://feff01.github.io/funny-anime/dist/test_easing.html)


```
    npm install funny-anime
```

```javascript
    import Easing from 'funny-easing';
    //const Easing = require('funny-easing');

    let easeing=Easing.easeInOutBounce.toFunction();
    //Easing.elastic(1,0.5).mirror().toFunction();
    //Easing.elastic(1, 0.5).mirror().symmetry().toFunction();
    //Easing.easeReverse.concat(Easing.easeBack).toFunction();

    console.log(easeing(0.5));
```
