<!DOCTYPE html>
<html lang="en">
<head>
    
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
         h1 {
            display: none;
          }
          @media screen and (max-width: 576px) {
            .Mobile {
              display: block;
            }
            body {
              background-color: rgb(24, 211, 92);
            }
          }
          @media screen and ( max-width: 768px ) and (min-width:576px) {
            .Tablet{
                display: block;
            }
            body{
                background-color: red;
            }
          }

          @media screen and (max-width: 992px) and (min-width:768px) {
            .Laptop{
                display:block;
            }
            body{
                background-color: blue;
            }
            
          }

          @media screen and (max-width:1200px) and (min-width:992px) {
            .Desktop{
                display: block;
            }
            body{
                background-color: orange;
            }
            
          }

          @media screen and (max-width:2000px) and (min-width:1200px) {
            .Huge{
                display: block;

            }
            body{
                background-color: brown;
            }
            
          }
    </style>
</head>
<body>

    <h1 class="Mobile">Mobile</h1>
    <h1 class="Tablet">Tablet</h1>
    <h1 class="Laptop">Laptop</h1>
    <h1 class="Desktop">Desktop</h1>
    <h1 class="Huge">Huge</h1>






</body>
</html>
