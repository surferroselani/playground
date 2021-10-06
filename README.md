<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOM Examples: setAttribute</title>
</head>
<body>
    <h1>setAttribute</h1>
    

    <form>
        <label><input type="checkbox"> yes</label>
    </form>

    <script>
        var myCheckBox = document.querySelector('input');
        myCheckBox.setAttribute("checked", "checked");
    </script>
</body>
</html>
