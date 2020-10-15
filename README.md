# Calculator

Calculator is a simple text-based calculator app made in Java.
   

## Operands
   
Composed of real numbers which fit within the bounds of an 8-byte double variable.
   

## Binary operators
Syntax: *&lt;expression&gt; &lt;operator&gt;  &lt;expression&gt;*

<table>
    <tr>
        <th>Operation</th>
        <th>Symbol</th>
        <th>Example</th>
    </tr>
    <tr>
        <td>Addition</td>
        <td style="text-align:center">+</td>
        <td>1 + 2 = 3</td>
    </tr>
    <tr>
        <td>Subtraction</td>
        <td style="text-align:center">-</td>
        <td>2 - 3 = -1</td>
    </tr>    
    <tr>
        <td>Multiplication</td>
        <td style="text-align:center">*</td>
        <td>2 * 3 = 6</td>
    </tr>    
    <tr>
        <td>Division</td>
        <td style="text-align:center">/</td>
        <td>4 / 2 = 2</td>
    </tr>
    <tr>
        <td>Exponentiation</td>
        <td style="text-align:center">^</td>
        <td>2 ^ 3 = 8</td>
    </tr>
</table>
   

## Unary operators
Syntax: *&lt;expression&gt; &lt;operator&gt;*

<table>
    <tr>
        <th>Operation</th>
        <th>Symbol</th>
        <th>Example</th>
    </tr>
    <tr>
        <td>Negation</td>
        <td style="text-align:center">-</td>
        <td></td>
    </tr>
    <tr>
        <td>Sine</td>
        <td style="text-align:center">sin</td>
        <td></td>
    </tr>    
    <tr>
        <td>Cosine</td>
        <td style="text-align:center">cos</td>
        <td></td>
    </tr>    
    <tr>
        <td>Tangent</td>
        <td style="text-align:center">tan</td>
        <td></td>
    </tr>
    <tr>
        <td>Cotangent</td>
        <td style="text-align:center">cot</td>
        <td></td>
    </tr>
    <tr>
        <td>Natural log (log<sub>e</sub>)</td>
        <td style="text-align:center">ln</td>
        <td></td>
    </tr>
    <tr>
        <td>Decimal log (log<sub>10</sub>)</td>
        <td style="text-align:center">log</td>
        <td></td>
    </tr>
</table>

Note: these mathematical functions are considered unary operators because they require only one term as input.
  
## Grouping "operator"
Syntax: *(&lt;expression&gt;)*
   
Use parentheses to elevate the evaluation precedence of an expression or sub-expression.
  

# Usage

With command-line argument:
```
calculator (12-(2^2)*2)/-4
Output: 4
```

Without command-line argument:
```
calculator
Enter an expression: (12-(2^2)*2)/-4
Output: 4
```
   
## Rules
* Each operator must be used with its respective number of operands.
    - eg. The expression "*10/5*" is valid, but "*/5*" is missing its left operand.
* No mismatched grouping parentheses; each '(' requires a matching ')'.
* Whitespace padding is optional.