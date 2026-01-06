
<!DOCTYPE html>
<html>
<head>
    <title>School Class Selection</title>

    <style>
        body {
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        h1 {
            color: #1e90ff;
        }

        p {
            color: #333333;
            font-size: 16px;
        }

        form {
            background-color: white;
            width: 300px;
            margin: auto;
            padding: 20px;
            border-radius: 10px;
        }

        label {
            color: #1e90ff;
            font-weight: bold;
        }

        select {
            padding: 8px;
            width: 100%;
            border-radius: 5px;
        }

        button {
            background-color: #1e90ff;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
        }
    </style>

</head>
<body>

    <h1>Welcome to Our School Portal</h1>
    <p>Please select your class below:</p>

    <form>
        <label for="class">Choose a class:</label>
        <br><br>

        <select id="class" name="class">
            <option>Choose a class</option>
            <option>Grade 4</option>
            <option>Grade 5</option>
            <option>Grade 6</option>
        </select>

        <br><br>
        <button type="submit">Submit</button>
    </form>

</body>
</html>
