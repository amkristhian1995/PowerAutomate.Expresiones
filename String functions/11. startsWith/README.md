# **Power Automate > Formulas**

## **Expresiones | String function | startsWith**

Comprueba si la cadena comienza con un valor.

El resultado de la expresión es un **"lógico"**.

### Sintaxis

```
startstWith(text, searchText)
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
            <td>searchText</td>
            <td>'Power'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
startsWith(text, searchText)
```

#### **Output**

```
true
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
            <td>searchText</td>
            <td>'Powers'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
startsWith(text, searchText)
```

#### **Output**

```
false
```