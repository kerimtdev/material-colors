# 🎨 Material-Colors
[**Material.io - Color Tool**](https://material.io/resources/color/) kaynağına göre hazırlanmış, Javascript projelerinde kullanılabilecek renk paleti paketi.

Repoyu projelerinize direkt dahil edebileceğiniz gibi, renk detaylarının bulunduğu [**/colors**](/colors) dizininden **JSON formatındaki** renk dosyalarına erişebilirsiniz.


### Örnek Kullanımlar:
```jsx

import { BlueGrey } from './lib/material-colors'

console.log(BlueGrey[400].Hex);                     // "78909C"
console.log(BlueGrey[400].HexWithHash);             // "#78909C"
console.log(BlueGrey[400].Rgb);                     // "rgb(120,144,156)"

```

```jsx
const Colors = require('./lib/material-colors');

console.log(Colors.BlueGrey[400].Hex);              // "78909C"
console.log(Colors.BlueGrey[400].HexWithHash);      // "#78909C"
console.log(Colors.BlueGrey[400].Rgb);              // "rgb(120,144,156)"
```
