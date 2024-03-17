# **Power Automate > Formulas**

## **Expresiones | String function | slice**

Devuelve una sección de un texto definida por el índice inicial y el índice final.

El resultado de la expresión es un **"texto"**.

### Sintaxis

```
slice(text, startIndex, endIndex?)
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
            <td>'Power Automate'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>startIndex</td>
            <td>6</td>
            <td>Número</td>
        </tr>
        <tr>
            <td>endIndex</td>
            <td>10</td>
            <td>Número</td>
        </tr>
    </tbody>
</table>

```
slice(text, startIndex, endIndex)
```

#### **Output**

```
'Auto'
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
            <td>'Power Automate'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>startIndex</td>
            <td>6</td>
            <td>Número</td>
        </tr>
    </tbody>
</table>

```
slice(text, startIndex)
```

#### **Output**

```
'Automate'
```