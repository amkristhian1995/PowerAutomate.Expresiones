# **Power Automate > Formulas**

## **Expresiones | String function | split**

Divide un texto usando un separador.

El resultado de la expresión es una **"matriz de texto"**.

### Sintaxis

```
split(text, separator)
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
            <td>'Power apps - Power Automate - Power BI'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>separator</td>
            <td>' - '</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
split(text, separator)
```

#### **Output**

```
[
    'Power Apps',
    'Power Automate',
    'Power BI'
]
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
            <td>'Power apps - Power Automate - Power BI'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>separator</td>
            <td>' | '</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
split(text, separator)
```

#### **Output**

```
[
    'Power apps - Power Automate - Power BI'
]
```