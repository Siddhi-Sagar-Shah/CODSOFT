# CODSOFT
Internships
<!DOCTYPE html>
<html>
<head>
<title>Calculator</title>
<link rel="stylesheet" href="style.css">
<style type="text/css">
  body
  .calculator {
  width: 300px;
  height: 400px;
  background-color: beige;
  border-radius: 30px;
  padding: 20px;
  flex-direction: column;
  align-items: center;
}

.display {
  width: 100%;
  height: 50px;
  background-color: #eee;
  border-radius: 5px;
  text-align: right;
  padding: 10px;
  font-size: 20px;
}

.keys {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 10px;
  margin-top: 20px;
}

button {
  align-items: center;
  width: 100%;
  height: 40px;
  background-color: teal;
  border-radius: 5px;
  font-size: 18px;
  cursor: pointer;
}


</style>
</head>
<body>
  <div class="calculator">
    <div class="display">
      <input type="text" height="30" width="30">

    </div>
    <div class="keys">

      <button class="number" onclick="appendNumber(7)">7</button>
      <button class="number" onclick="appendNumber(8)">8</button>
      <button class="number" onclick="appendNumber(9)">9</button>
      <button class="number" onclick="appendNumber(4)">4</button>
      <button class="number" onclick="appendNumber(5)">5</button>
      <button class="number" onclick="appendNumber(6)">6</button>
      <button class="number" onclick="appendNumber(1)">1</button>
      <button class="number" onclick="appendNumber(2)">2</button>
      <button class="number" onclick="appendNumber(3)">3</button>
      <button class="number" onclick="appendNumber(0)">0</button>
      <button class="decimal" onclick="appendNumber('.')">.</button>
        <button class="operator" onclick="appendOperator('+')">+</button>
      <button class="operator" onclick="appendOperator('-')">-</button>
      <button class="operator" onclick="appendOperator('*')">*</button>
      <button class="operator" onclick="appendOperator('/')">/</button>
      <button class="clear" onclick="clearDisplay()">C</button>

      <button class="equal" onclick="calculate()">=</button>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>

