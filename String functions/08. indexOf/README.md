# **Power Automate > Formulas**

## **Expresiones | String function | indexOf**

Devuelve el primer índice de un valor dentro de una cadena.

El resultado de la expresión es un **"número"**.

### Sintaxis

```
indexOf(text, searchText)
```

----

**<u>Ejemplo 01</u>**

#### **Input**

<table>
    <thead>
        <tr>
            <th>Nombre</th>
            <th>Valor</th>
            <th>Tipo</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>text</td>
            <td>'Power Apps - Power Automate - Power BI'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>searchText</td>
            <td>'Power'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
indexOf(text, searchText)
```

#### **Output**

```
0
```

----

**<u>Ejemplo 02</u>**

#### **Input**

<table>
    <thead>
        <tr>
            <th>Nombre</th>
            <th>Valor</th>
            <th>Tipo</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>text</td>
            <td>'Power Apps - Power Automate - Power BI'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>searchText</td>
            <td>'Apps'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
indexOf(text, searchText)
```

#### **Output**

```
6
```

----

**<u>Ejemplo 03</u>**

#### **Input**

<table>
    <thead>
        <tr>
            <th>Nombre</th>
            <th>Valor</th>
            <th>Tipo</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>text</td>
            <td>'Power Apps - Power Automate - Power BI'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>searchText</td>
            <td>'Powers'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
indexOf(text, searchText)
```

#### **Output**

```
-1
```