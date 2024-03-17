# **Power Automate > Formulas**

## **Expresiones | String function | replace**

Reemplaza una sección de un texto por otro.

El resultado de la expresión es un **"texto"**.

### Sintaxis

```
replace(text, oldText, newText)
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
            <td>oldText</td>
            <td>'Automate'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>newText</td>
            <td>Apps</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
substring(text, oldText, newText)
```

#### **Output**

```
'Power Apps'
```