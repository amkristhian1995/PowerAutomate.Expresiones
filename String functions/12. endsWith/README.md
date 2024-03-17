# **Power Automate > Formulas**

## **Expresiones | String function | endsWith**

Comprueba si la cadena termina con un valor.

El resultado de la expresión es un **"lógico"**.

### Sintaxis

```
endsWith(text, searchText)
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
            <td>'Automate'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
endsWith(text, searchText)
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
            <td>'Apps'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
endsWith(text, searchText)
```

#### **Output**

```
false
```