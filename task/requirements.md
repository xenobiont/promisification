1. Промисифицируйте функцию setTimeout, так чтобы ее можно было вызвать следующим образом

```js
setTimeoutPromisified(1000)
	.then(() => console.log('1 second passed'))
	.then(() => console.log('success'));
```

2. Промисифицируйте функцию loadScript.
   Вызовите ее таким образом, чтобы вывести в консоль URL загруженного скрипта при успехе или ошибку, если она возникнет.

_Обратите внимание: функцию нужно не переписать, а промисифицировать, т.е. сделать "обертку" над ней._

3. Напишите универсальную функцию для промисификации других функций, которые принимают коллбэк.
