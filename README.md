# Clase "Date()" en JavaScript

Esta clase de JavaScript se utiliza para la manipulación de fechas y distintas medidas de tiempo. El objetivo de esta clase es generar un número basado en el tiempo actual. Entre los métodos que contiene esta función se encuentran:

- getFullYear()
- getMonth()
- getDate()
- getDay()
- getHours()
- getMinutes()
- getSeconds()
- getMilliseconds()
- getTime()

## Sintaxis
La sintaxis para crear un objeto con la clase "Date()" es "variable = new Date().método()". Un ejemplo podría ser:

```js
let day = new Date().getDay()
```

## Explicación métodos

|Método|Explicación|
| ---- | ---- |
|Date()|Obtiene la fecha actual junto con la hora presente (Depende del horario local).|
|getFullYear()|Obtiene un numero de 4 digitos  (El año actual).|
|getMonth()|Obtiene un numero de 0 a 11  (El mes presente).|
|getDate()|Obtiene un numero de 1 a 31  (El numero del dia de la fecha presente).|
|getDay()|Obtiene un numero de 0 a 6  (El dia actual de la semana).|
|getHours()|Obtiene un numero de 0 a 23  (El numero de la hora).|
|getMinutes()|Obtiene un numero de 0 a 59  (El minuto en el que nos encontramos).|
|getSeconds()|Obtiene un numero de 0 a 59  (El segundo en el que nos encontramos).|
|getMilliseconds()|Obtiene un numero de 0 a 999  (El milisegundo en el que nos encontramos).|
|getTime()|Obtiene un numero de milisegundos que han pasado desde Enero 1 de 1970.|

## Ejemplos
A continuación se presentan ejemplos de cada uno de estos métodos.
- "Date()":
```js
let date = new Date() 
console.log(date)
```
Este ejemplo devolverá la fecha y hora actual: "Tue Feb 13 2024 08:15:50 GMT-0500 (hora estándar de Colombia)".

---
- "getFullYear()":
```js
let year = new Date().getFullYear 
console.log(year)
```
Este ejemplo devolverá el año actual: "2024".

---
- "getMonth":
```js
let month = new Date().getMonth 
console.log(month)
```
Este ejemplo devolverá el mes actual: "1" (recordemos que este método genera un número con un rango inicial de 0).

---
- "getDate()":
```js
let date = new Date().getDate() 
console.log(date)
```
Este ejemplo devolverá el día del mes actual: "13".

---
- "getDay()":
```js
let day = new Date().getDay() 
console.log(day)
```
Este ejemplo devolverá el día actual de la semana: "2" (recordemos que este método genera un número con un rango inicial de 0).

---
- "getHours()":
```js
let hour = new Date().getHours()
console.log(hour)
```
Este ejemplo devolverá la hora actual: "8".

---
- "getMinutes()":
```js
let minute = new Date().getMinutes()
console.log(minute)
```
Este ejemplo devolverá el minuto actual: "15".

---
- "getSeconds()":
```js
let second = new Date().getSeconds()
console.log(second)
```
Este ejemplo devolverá el segundo actual: "50".

---
- "getMilliseconds()":
```js
let millisecond = new Date().getMilliseconds()
console.log(millisecond)
```
Este ejemplo devolverá el milisegundo actual: "756".

---
- "getTime()":
```js
let actualTime = new Date().getTime()
console.log(actualTime)
```
Este ejemplo devolverá : "1707830968673" (el número de milisegundos que han pasado desde el 1 de enero de 1970).

---