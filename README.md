# CodingBot
New repo

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Cards</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="card student1">
            <h2>John Doe</h2>
            <p>Department: Computer Science</p>
            <p>Gender: Male</p>
        </div>
        <div class="card student2">
            <h2>Jane Smith</h2>
            <p>Department: Mathematics</p>
            <p>Gender: Female</p>
        </div>
        <div class="card student3">
            <h2>Emily Johnson</h2>
            <p>Department: Biology</p>
            <p>Gender: Female</p>
        </div>
    </div>
</body>
  body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f0f0f0;
}

.container {
    display: flex;
    gap: 20px;
}

.card {
    border-radius: 15px;
    padding: 20px;
    width: 200px;
    color: #333;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.student1 {
    background-color: #e0f7fa;
    border: 2px solid #00796b;
}

.student2 {
    background-color: #fce4ec;
    border: 2px solid #c2185b;
}

.student3 {
    background-color: #e8f5e9;
    border: 2px solid #388e3c;
}
</html>
