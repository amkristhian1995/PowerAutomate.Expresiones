# **Power Automate > Formulas**

## **Expresiones | String function | Substring**

Devuelve una sección de un texto mediante definida por el indice inicial y una cantidad de caracteres.

El resultado de la expresión es un **"texto"**.

### Sintaxis

```
substring(text, startIndex, length?)
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
            <td>length</td>
            <td>4</td>
            <td>Número</td>
        </tr>
    </tbody>
</table>

```
substring(text, startIndex, length)
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
substring(text, startIndex)
```

#### **Output**

```
'Automate'
```