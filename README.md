-<html>
    <head>
        <script type = "text/javaScript">
            var constant = 100;
            var kenyan_shillings;
            var input = prompt("Enter the amount: ");
            var unit = prompt("enter either dollar or kenyan shillings: ");
        
            if(unit == "dollar ")
            {
               kenyan_shillings =input * constant;
               document.write(input + " dollars is " + kenyan_shillings + " kenyan shillings");
            }
            else
            {
               dollar = input / constant;
               document.write( input + " kenyan shillings is " + dollar + " dollar");
            }
        </script>               

    </head>
</html>
