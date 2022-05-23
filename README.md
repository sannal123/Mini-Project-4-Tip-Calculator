# Mini-Project-4-Tip-Calculator
Mini Project #4 Tip Calculator
<!DOCTYPE HTML>
<html lang="en">
<head>
    <title>Mini Project #4 Tip Calculator</title>
</head>
    <body>
    <h1>Mini Project #4 Tip Calculator</h1>
    <script>
    function tip(totalAmount,tip=10){
        tip = tip/100;
        var tipAmount = totalAmount * tip
        totalAmount=totalAmount+tip
        return totalAmount
    }    
        var totalBill = tip(25,10)
        console.log(totalBill)
    </script>
    </body>
</html>
