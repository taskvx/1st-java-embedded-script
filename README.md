# 1st-java-embedded-script
!DOCTYPE html>
<head>
    <title>First Javascript</title>
<script>
    window.onload = function()
    {
        var age = 42;
        var ageIn10Years = age + 10;
        document.getElementById("output").innerHTML = "<h1>You are " + age +" years old</h1>";
        document.getElementById("output").innerHTML += "in ten years you will be " + ageIn10Years + " years old.";
    
    }
</script>
</head>
<body>
    <div id="output"></div>
</body>
</html>
