# Restaurant-Calculator
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Unit 5 Graded Exercise 2</title>
</head>
<body>
  <header>
    <h1>
      Nathaniel Breeden, Restaurant Calculator //Header of page
    </h1>
  </header>
  <article>
    <label for="bill">Bill Amount:</label>
    <input type="text" id="bill"/> //input number for Bill Amount:
    <label for="tip">Tip %:</label>
    <input type="tip" id="tip"/> //input number for Tip %:
    <label for="people"># of People:</label>
    <input type="people" id="people"/> //input number for # of People
    
    <input type="submit" id="submitBtn" value="calculate" /> //create a submit button called calculate
    
  </article>
  <script>
      function calculator () {
        var billAmount = document.getElementById("bill).value
        var tip = document.getElementById("tip").value
        var people = document.getElementById("people").value
        var tipAmount = billAmount * .tip //gets tipAmount by multiplying billAmount and .tip
        var totalBill = billAmount + tipAmount //gets totalBill by adding billAmount and tipAmount
        var perPerson = totalBill / people //gets perPerson by diving totalBill by people
        document.write("Tip Amount; " + tipAmount + " Total Bill: " + totalBill + " Total per Person: "                         + perPerson) //displays tipAmount, totalBill, and perPerson
}
  </script>
</body>
<html>
