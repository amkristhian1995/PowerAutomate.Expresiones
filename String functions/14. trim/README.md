# **Power Automate > Formulas**

## **Expresiones | String function | trim**

Elimina los espacios en blanco iniciales y finales de un texto.

El resultado de la expresión es un **"texto"**.

### Sintaxis

```
trim(text)
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
            <td>' Power apps - Power Automate - Power BI '</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
trim(text)
```

#### **Output**

```
'Power apps - Power Automate - Power BI'
```