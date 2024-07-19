<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Age Calculator</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <h1>Age Calculator</h1>
        <form id="ageCalculator">
            <label for="dob">Enter your date of birth:</label>
            <input type="date" id="dob" required>
            <button type="button" onclick="calculateAge()">Calculate Age</button>
        </form>
        <div id="result"></div>
    </div>
    <script src="script.js"></script>
</body>

</html>

------------------------------------------------------------------------

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.container {
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    text-align: center;
}

h1 {
    margin-bottom: 20px;
}

form {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

label {
    font-size: 1rem;
}

input {
    padding: 10px;
    border-radius: 4px;
    border: 1px solid #ccc;
    font-size: 1rem;
}

button {
    padding: 10px;
    border-radius: 4px;
    border: none;
    background-color: #007bff;
    color: white;
    font-size: 1rem;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}

#result {
    margin-top: 20px;
    font-size: 1.2rem;
    color: #333;
}
