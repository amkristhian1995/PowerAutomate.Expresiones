# **Power Automate > Formulas**

## **Expresiones | String function | lastIndexOf**

Devuelve el último índice de un valor dentro de una cadena.

El resultado de la expresión es un **"número"**.

### Sintaxis

```
lastIndexOf(text, searchText)
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
            <td>searchText</td>
            <td>'Power'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
lastIndexOf(text, searchText)
```

#### **Output**

```
30
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
            <td>searchText</td>
            <td>'Powers'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
lastIndexOf(text, searchText)
```

#### **Output**

```
-1
```