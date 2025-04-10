## MÁV utastájékoztató

Ez a projekt a vonatok indulását és érkezését mutatja be.

### Funkciók
- 🚂 Induló és érkező vonatok
- 🕒 Vágány, érkező és induló vonatok idő szerint

### ❓ Hogyan használjuk?
Nyisd meg a `https://github.com/Csengeeeeee/2025_01_30_MAV.git` weboldalt.
A projekt megtekinthető az alábbi linken:  
[🔗 MÁV Utastájékoztató](https://csengeeeeee.github.io/2025_01_30_MAV/)

### 📖 Alap HTML kód
```html
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Máv utastájékoztató</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <table>
        <thead>
        <tr>
                <th>Tervezett érkezés</th>
                <th>Érkezés</th>
                <th>Vonat</th>
                <th>Honnan</th>
                <th>Hova</th>
                <th>Vágány</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="elsooszlop">8:30</td>
                <td id="keses">8:42</td>
                <td>IC</td>
                <td>Szeged</td>
                <td>Szatymaz-Kistelek</td>
                <td>5</td>
            </tr>
            <tr>
                <td class="elsooszlop">9:22</td>
                <td></td>
                <td>SZ</td>
                <td>Szentes</td>
                <td>Csongrád</td>
                <td>2</td>
            </tr>           
        </tbody>
    </table>
    <a href="indulovonatok.html">Induló vonatok</a>
</body>
</html>
```

## 🎨🖌️ CSS
```css
table {
    border: 1px solid;
    background-color: mediumorchid;
    color: rgb(255, 255, 255);
    font-family: 'Courier New', Courier, monospace;
    font-size: 30px;
  }

  td {
    background-color: rgb(148, 56, 171);
  }
  #keses {
    background-color: red;
} 
  .elsooszlop {
    background-color: rgb(90, 53, 124);
  }
  table, th, td {
    border: 1px solid;
    border-color: black;
  }
```