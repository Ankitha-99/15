<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>anonymous </title>
</head>
<body>
    <h2> anonymous function </h2>
    <button id ="btn">click me</button>
    <p id="demo3" class="out"></p>
    <script>
        document.getElementById("btn").onclick=function()
        {
            document.getElementById("demo3").innerText="button clicked using anonymous function";
        };
    </script>
</body>
</html>
