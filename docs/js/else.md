# Co jeszcze w JS?


## Warunki (conditions)

```js
let direction = "left";

if(direction == "left"){
  console.log("direction jest left");
}else{
  console.log("direction nie jest left");
}



if(wysokosc > 180){
    return "koszykarz";
}else{
    return "liliput"
}


wysokosc > 180 ? "koszykarz" : "liliput";


// SWITCH !!!
```

## Wydarzenia (events)
```js
const leftArr = document.querySelector(".left");
leftArr.onclick = () => { przyklad("lewa") }
```

## Operatory (operators) 
```js
let currentSlide = 0;
currentSlide++;
console.log(currentSlide); // 1
currentSlide--;
console.log(currentSlide); // 0
```

## Deklaracje zmiennych
**ECMAScript** – stworzona przez ECMA ustandaryzowana specyfikacja skryptowego języka programowania, której najbardziej znane implementacje to JavaScript, JScript i ActionScript. Specyfikacja ta oznaczona jest jako ECMA-262 i ISO/IEC 16262.

Źródło: https://pl.wikipedia.org/wiki/ECMAScript


<div class="standardWrapper">
<div>W zasadzie możemy stosować się do 3 prostych reguł:

- var jest odradzany w specyfikacji ES6 (ECMAScript 2016 - standaryzacja języka JS)
- wszystkie zmienne powinny być domyślnie deklarowane przy użyciu const
- użyj let, jeśli zmienia się wartość zmiennej
</div>
<div style="display:flex;justify-content:center;">
  <table>
    <tr>
      <th>keword</th>
      <th>const</th>
      <th>let</th>
      <th>var</th>
    </tr>
    <tr>
      <td>global scope</td>
      <td>NO</td>
      <td>NO</td>
      <td>YES</td>
    </tr>
    <tr>
      <td>function scope</td>
      <td>YES</td>
      <td>YES</td>
      <td>YES</td>
    </tr>
    <tr>
      <td>block scope</td>
      <td>YES</td>
      <td>YES</td>
      <td>NO</td>
    </tr>
    <tr>
      <td>can be reassigned</td>
      <td>NO</td>
      <td>YES</td>
      <td>YES</td>
    </tr>
  </table>
</div>
</div>