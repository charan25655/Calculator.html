# Calculator.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="calculator.css">
</head>
<body>
    <div class="calculator">
        <div  class="text"><h1>Basic Calculator</h1></div>
        <div class="display">
            <input type="text" id="result" disabled>
        </div>
        <div class="buttons">

            <button onclick="clearDisplay()">AC</button>
            <button onclick="deleteLast()">DEL</button>
            <button onclick="appendValue('%')">%</button>
            <button onclick="appendValue('/')">/</button>
            <button onclick="appendValue('7')">7</button>
            <button onclick="appendValue('8')">8</button>
            <button onclick="appendValue('9')">9</button>
            <button onclick="appendValue('*')">*</button>
            <button onclick="appendValue('4')">4</button>
            <button onclick="appendValue('5')">5</button>
            <button onclick="appendValue('6')">6</button>
            <button onclick="appendValue('-')">-</button>
            <button onclick="appendValue('1')">1</button>
            <button onclick="appendValue('2')">2</button>
            <button onclick="appendValue('3')">3</button>
            <button onclick="appendValue('+')">+</button>
            <button onclick="appendValue('0')">0</button>
            <button onclick="appendValue('00')">00</button>
            <button onclick="appendValue('.')">.</button>
            <button onclick="calculate()">=</button>
        </div>
    </div>
    <script src="calculator.js"></script>
</body>
</html>
