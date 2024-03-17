# **Power Automate > Formulas**

## **Expresiones | String function | Concat**

Combina varias cadenas de textos.

El resultado de la expresión es un **"texto"**.

### Sintaxis

```
concat(text1, text2?, ...)
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
            <td>text1</td>
            <td>'Power Apps'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>text2</td>
            <td>' | Power Automate'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
concat(text1, text2)
```

#### **Output**

```
'Power Apps | Power Automate'
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
            <td>text1</td>
            <td>'Power Apps'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>text2</td>
            <td>' | Power Automate'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>text3</td>
            <td>' | Power BI'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
concat(text1, text2, text3)
```

#### **Output**

```
'Power Apps | Power Automate | Power BI'
```