<!DOCTYPE html>

<html>
<head>
    <Title>Calculator</title>
    <link rel="stylesheet" type="text/css" href="assets/calc_style.css"/>
    <script language="JavaScript" src="code.js" type="text/javascript"></script>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet">
    <link rel="icon" type="image/png" href="assets/favicon.png"/>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
</head>
<body>
    <div id="calculator">
        <h1>Calculator</h1>
        <p id="last_operation_history"></p>
        <p id="box" class="box">0</p>
        <table id="table">
            <tr>
                <td><button onclick="calculate_percentage()">%</button></td>
                <td><button onclick="clear_entry()">CE</button></td>
                <td><button onclick="button_clear()">C</button></td>
                <td><button id="backspace_btn" onclick="backspace_remove()"></button></td>
            </tr>
            <tr>
                <td><button onclick="division_one()">¹∕ₓ</button></td>
                <td><button onclick="power_of()">𝑥²</button></td>
                <td><button onclick="square_root()">√𝑥</button></td>
                <td><button id="plusOp" value="+" class="operator" onclick="button_number('+')">+</button></td>
            </tr>
            <tr>
                <td><button onclick="button_number(7)">7</button></td>
                <td><button onclick="button_number(8)">8</button></td>
                <td><button onclick="button_number(9)">9</button></td>
                <td><button id="subOp" value="-" class="operator" onclick="button_number('-')">-</button></td>
            </tr>
            <tr>
                <td><button onclick="button_number(4)">4</button></td>
                <td><button onclick="button_number(5)">5</button></td>
                <td><button onclick="button_number(6)">6</button></td>
                <td><button id="multiOp" value="*" class="operator" onclick="button_number('*')">×</button></td>
            </tr>
            <tr>
                <td><button onclick="button_number(1)">1</button></td>
                <td><button onclick="button_number(2)">2</button></td>
                <td><button onclick="button_number(3)">3</button></td>            
                <td><button id="divOp" value="/" class="operator" onclick="button_number('/')">÷</button></td>
            </tr>
            <tr>
                <td><button onclick="plus_minus()">±</button></td>
                <td><button onclick="button_number(0)">0</button></td>
                <td><button id="dot" value="." onclick="button_number('.')">.</button></td>
                <td colspan="4"><button value="=" class="operator" id="equal_sign" onclick="button_number('=')">=</button></td>
            </tr>
        </table>
    </div>
</body>
</html>
