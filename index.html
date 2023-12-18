<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Add your CSS styles here */
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f3f3f3;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .credit-simulator {
      background-color: #ffffff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
      width: 400px;
    }

    label {
      display: block;
      margin-top: 15px;
      color: #333;
      font-size: 14px;
    }

    select,
    input[type="number"],
    input[type="range"],
    input[type="text"],
    button {
      width: 100%;
      padding: 12px;
      margin-top: 8px;
      margin-bottom: 20px;
      box-sizing: border-box;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    select,
    input[type="number"],
    input[type="range"],
    input[type="text"] {
      font-size: 16px;
    }

    button {
      background-color: #4caf50;
      color: #fff;
      cursor: pointer;
      font-size: 18px;
      border: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #45a049;
    }

    .result {
      margin-top: 30px;
    }

    h2 {
      color: #4caf50;
      font-size: 20px;
      margin-bottom: 15px;
    }
  </style>
  <title>Credit Simulator</title>
</head>
<body>
  <div class="credit-simulator">
    <label for="loanType">Loan Type</label>
    <select id="loanType">
      <option value="cash">Cash Loan</option>
      <option value="home">Home Loan</option>
    </select>

    <label for="loanAmount">Loan Amount ($)</label>
    <input type="number" id="loanAmount" value="5000" min="0">

    <label for="duration">Loan Duration (in months)</label>
    <input type="range" id="duration" min="12" max="120" value="60">
    <output id="durationValue">60</output>

    <label for="downPayment">Down Payment (%)</label>
    <input type="range" id="downPayment" min="0" max="50" value="20">
    <output id="downPaymentValue">20</output>

    <label for="interest">Interest Rate (%)</label>
    <input type="text" id="interest" value="3.5">

    <button onclick="calculateLoan()">Calculate</button>

    <div class="result">
      <h2>Loan Summary</h2>
      <p id="loanAmountText">Loan Amount after Downpayment: $0</p>
      <p id="monthlyPayment">Monthly Payment: $0</p>
      <p id="totalPayment">Total Payment: $0</p>
    </div>
  </div>

  <script>
    document.addEventListener('DOMContentLoaded', function () {
      const durationSlider = document.getElementById('duration');
      const durationValue = document.getElementById('durationValue');
      const downPaymentSlider = document.getElementById('downPayment');
      const downPaymentValue = document.getElementById('downPaymentValue');

      durationSlider.addEventListener('input', function () {
        durationValue.textContent = this.value;
      });

      downPaymentSlider.addEventListener('input', function () {
        downPaymentValue.textContent = this.value;
      });
    });

    function calculateLoan() {
      const loanType = document.getElementById('loanType').value;
      const loanAmount = parseFloat(document.getElementById('loanAmount').value);
      const duration = parseInt(document.getElementById('duration').value);
      const downPayment = parseInt(document.getElementById('downPayment').value);
      const interest = parseFloat(document.getElementById('interest').value);

      const loanAmountText = loanType === 'home' ? `Loan Amount: $${loanAmount.toFixed(2)}` : '';

      const loanAmountAfterDownPayment = loanAmount - (loanAmount * downPayment / 100);
      const loanAmountFinal = loanAmountAfterDownPayment < 0 ? 0 : loanAmountAfterDownPayment;

      const loanAmountFinalText = `Loan Amount after DownPayment: $${loanAmountFinal.toFixed(2)}`;

      const loanAmountDisplay = loanAmountFinalText || loanAmountText;

      const loanAmountOutput = document.getElementById('loanAmountText');
      loanAmountOutput.textContent = loanAmountDisplay;

      const monthlyPayment = calculateMonthlyPayment(loanAmountFinal, duration, interest);
      const totalPayment = monthlyPayment * duration;

      updateResult(monthlyPayment, totalPayment);
    }

    function calculateMonthlyPayment(loanAmount, duration, interest) {
      const monthlyInterest = interest / 1200;
      const totalPayments = duration;
      const monthlyPayment =
        (loanAmount * monthlyInterest) /
        (1 - Math.pow(1 + monthlyInterest, -totalPayments));
      return monthlyPayment;
    }

    function updateResult(monthlyPayment, totalPayment) {
      document.getElementById('monthlyPayment').textContent = `Monthly Payment: $${monthlyPayment.toFixed(2)}`;
      document.getElementById('totalPayment').textContent = `Total Payment: $${totalPayment.toFixed(2)}`;
    }
  </script>
</body>
</html>
