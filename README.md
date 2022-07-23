# ToDo.io
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>ToDo</title>

    <link rel="stylesheet" type="text/css" href="styles.css">

    <!-- don't use this in production: -->
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
  </head>
  <body>

    <h1>ToDo</h1>

    <!-- we will put our teact component inside this div -->
    <div id="root"></div>

    <!-- load react -->
    <script src="https://unpkg.com/react/umd/react.development.js" crossorigin></script>
    <script src="https://unpkg.com/react-dom/umd/react-dom.development.js" crossorigin></script>

    <!-- load our react component. -->
    <script src="todo.js" defer type="text/babel"></script>        
    <script src="form.js" defer type="text/babel"></script>    
    <script src="index.js" defer type="text/babel"></script>

  </body>
</html>
