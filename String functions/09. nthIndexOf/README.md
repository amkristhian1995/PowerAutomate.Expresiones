# **Power Automate > Formulas**

## **Expresiones | String function | nthIndexOf**

Devuelve el índice de la enésima aparición de un valor en una cadena.

El resultado de la expresión es un **"número"**.

### Sintaxis

```
nthIndexOf(text, searchText, ocurrence)
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
        <tr>
            <td>ocurrence</td>
            <td>1</td>
            <td>Número</td>
        </tr>
    </tbody>
</table>

```
nthIndexOf(text, searchText, ocurrence)
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
            <td>'Power apps - Power Automate - Power BI'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>searchText</td>
            <td>'Power'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>ocurrence</td>
            <td>2</td>
            <td>Número</td>
        </tr>
    </tbody>
</table>

```
nthIndexOf(text, searchText, ocurrence)
```

#### **Output**

```
13
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
            <td>'Power apps - Power Automate - Power BI'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>searchText</td>
            <td>'Power'</td>
            <td>Texto</td>
        </tr>
        <tr>
            <td>ocurrence</td>
            <td>3</td>
            <td>Número</td>
        </tr>
    </tbody>
</table>

```
nthIndexOf(text, searchText, ocurrence)
```

#### **Output**

```
30
```

----

**<u>Ejemplo 04</u>**

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
        <tr>
            <td>ocurrence</td>
            <td>4</td>
            <td>Número</td>
        </tr>
    </tbody>
</table>

```
nthIndexOf(text, searchText, ocurrence)
```

#### **Output**

```
-1
```

----

**<u>Ejemplo 05</u>**

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
        <tr>
            <td>ocurrence</td>
            <td>1</td>
            <td>Número</td>
        </tr>
    </tbody>
</table>

```
nthIndexOf(text, searchText, ocurrence)
```

#### **Output**

```
-1
```