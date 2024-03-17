# **Power Automate > Formulas**

## **Expresiones | String function | formatNumber**

Devuelve un número con el formato especificado.

El resultado de la expresión es un **"texto"**.

### Sintaxis

```
formatNumber(number, format, locale?)
```

**1. Formato de moneda**

| Número | Formato | Expresion                 | Resultado   |
|--------|---------|---------------------------|-------------|
| 12345  | C       | formatNumber(12345, 'C')  | $12,345.00  |
| 12345  | C0      | formatNumber(12345, 'C0') | $12,345     |
| 12345  | C1      | formatNumber(12345, 'C1') | $12,345.0   |
| 12345  | C2      | formatNumber(12345, 'C2') | $12,345.00  |
| 12345  | C3      | formatNumber(12345, 'C3') | $12,345.000 |

**2. Formato con ceros a la izquierda**

| Número | Formato | Expresion                 | Resultado   |
|--------|---------|---------------------------|-------------|
| 123    | D       | formatNumber(123, 'D')    | 123         |
| 123    | D0      | formatNumber(123, 'D0')   | 123         |
| 123    | D1      | formatNumber(123, 'D1')   | 0123        |
| 123    | D2      | formatNumber(123, 'D2')   | 00123       |
| 123    | D3      | formatNumber(123, 'D3')   | 000123      |

**3. Formato con decimales**

| Número | Formato | Expresion                 | Resultado   |
|--------|---------|---------------------------|-------------|
| 12345  | F       | formatNumber(12345, 'F')  | 12345.00    |
| 12345  | F0      | formatNumber(12345, 'F0') | 12345       |
| 12345  | F1      | formatNumber(12345, 'F1') | 12345.0     |
| 12345  | F2      | formatNumber(12345, 'F2') | 12345.00    |
| 12345  | F3      | formatNumber(12345, 'F3') | 12345.000   |

**4. Formato con separador de mil**

| Número | Formato | Expresion                 | Resultado   |
|--------|---------|---------------------------|-------------|
| 12345  | N       | formatNumber(12345, 'N')  | 12,345.00   |
| 12345  | N0      | formatNumber(12345, 'N0') | 12,345      |
| 12345  | N1      | formatNumber(12345, 'N1') | 12,345.0    |
| 12345  | N2      | formatNumber(12345, 'N2') | 12,345.00   |
| 12345  | N3      | formatNumber(12345, 'N3') | 12,345.000  |

**5. Formato como porcentaje**

| Número | Formato | Expresion                 | Resultado   |
|--------|---------|---------------------------|-------------|
| 0.25   | P       | formatNumber(25, 'P')     | 25.00%      |
| 0.25   | P0      | formatNumber(25, 'P0')    | 25%         |
| 0.25   | P1      | formatNumber(25, 'P1')    | 25.0%       |
| 0.25   | P2      | formatNumber(25, 'P2')    | 25.00%      |
| 0.25   | P3      | formatNumber(25, 'P3')    | 25.000%     |

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
            <td>number</td>
            <td>20</td>
            <td>Número</td>
        </tr>
        <tr>
            <td>format</td>
            <td>'C'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
formatNumber(number, format)
```

#### **Output**

```
$20.00
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
            <td>number</td>
            <td>250000</td>
            <td>Número</td>
        </tr>
        <tr>
            <td>format</td>
            <td>'S/ #,##0.00'</td>
            <td>Texto</td>
        </tr>
    </tbody>
</table>

```
formatNumber(number, format)
```

#### **Output**

```
S/ 250,000.00
```