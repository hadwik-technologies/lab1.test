<!DOCTYPE html>
<html>
  <head>
    <title>Event Handler Example</title>
    <script type="text/javascript">
      function myAlert() {
        alert("I am an event handler....");
      	return;
      }
    </script>
  </head>
  <body>
    <span onmouseover="myAlert();">
    Bring your mouse here to see an alert
    </span>
  </body>
</html>
