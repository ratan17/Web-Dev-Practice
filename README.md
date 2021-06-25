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

Question2: (testdome)
Update the website's HTML, without using JavaScript or CSS, to make use of semantic elements so that:

The classless outer div element is replaced with a more appropriate element.
The divs with the image and caption classes are replaced with self-contained content elements.
The divs with the lorem-ipsum and description classes are replaced with elements, so that by default only the contents of the description element are shown. When the contents of the description element are clicked, the visibility of the rest of the lorem-ipsum element is toggled.

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Semantics</title>
  </head>
  <body>
    <div>
      <h1>Lorem Ipsum</h1>
      
      <div class="image">
        <img src="https://goo.gl/zF9eky" alt="Lorem Ipsum">
        <div class="caption">Lorem Ipsum</div>
      </div>
      
      <div class="lorem-ipsum">
        <div class="description">Lorem ipsum dolor sit amet, consectetur adipiscing elit...</div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
          Curabitur vitae hendrerit mauris. Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
          Mauris lacinia scelerisque nibh nec gravida. 
          Duis malesuada nec nibh sit amet pulvinar. 
          Phasellus congue porttitor arcu, ut suscipit nibh aliquam vel. 
          Nunc arcu lectus, egestas ut sem ac, euismod porttitor eros. 
          Phasellus tincidunt consequat pharetra. Maecenas sodales purus at nulla finibus dapibus. 
          Nullam varius at nisl vel euismod. Fusce aliquet ligula non tempor fermentum. 
          Nam fermentum posuere mauris, quis aliquam nibh dictum sed.</p>
      </div>
    </div>
  </body>
</html>
