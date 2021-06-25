# Online Practice
Question1:(testdome)
With the new HTML5 features, modify the form so that:

The formula input field suggests the following options when the user starts to type: "sin", "cos", "tan" and "cot".
The iterations input field is a slider with possible values from 1 to 10.
The precision input field is a number picker with possible values from 1 to 100, where 50 is the default value.

Code:
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Advanced form</title>
</head>
<body>
  <form>
    
    Formula: <input name="formula" type="text" list="formulaOptions">
    <datalist id="formulaOptions">
      <option value="sin">
      <option value="cos">
      <option value="tan">
      <option value="cot">
    </datalist>
    <br />
    
    Iterations: <input name="iterations" type="range" min="1" max="10">
    
    
    <br />
    
    
    Precision: <input name="precision" type="number" min="1" max="100" value="50">
    
    <br />
  </form>

</body>
</html>
