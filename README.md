# internship-page
#creation of internship page

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Internship Programs</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(to right, #1e3c72, #2a5298);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
        }
        .container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            width: 80%;
            max-width: 1000px;
        }
        .card {
            background: rgba(255, 255, 255, 0.2);
            padding: 20px;
            border-radius: 15px;
            backdrop-filter: blur(10px);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            text-align: center;
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
            border: 1px solid rgba(255, 255, 255, 0.3);
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
            border-color: rgba(255, 255, 255, 0.6);
        }
        h2 {
            font-size: 22px;
            color: white;
            margin-bottom: 10px;
        }
        p {
            font-size: 16px;
            color: white;
            margin: 5px 0;
        }
        .btn {
            display: inline-block;
            padding: 12px 25px;
            margin-top: 10px;
            font-size: 16px;
            color: white;
            background: linear-gradient(45deg, #007bff, #00d4ff);
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            transition: background 0.3s ease-in-out, transform 0.2s;
            box-shadow: 0 4px 10px rgba(0, 123, 255, 0.5);
        }
        .btn:hover {
            background: linear-gradient(45deg, #0056b3, #0094ff);
            transform: scale(1.1);
            box-shadow: 0 6px 15px rgba(0, 123, 255, 0.7);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="card">
            <h2>Web Development Internship Program</h2>
            <p><strong>Duration:</strong> 1 month/2 months</p>
            <p><strong>Location:</strong> Virtual</p>
            <p><strong>Stipend:</strong> -</p>
            <p><strong>Start date:</strong> 05/11/2023</p>
            <a href="#" class="btn">View Details</a>
        </div>
        <div class="card">
            <h2>App Development Internship Program</h2>
            <p><strong>Duration:</strong> 1 month/2 months</p>
            <p><strong>Location:</strong> Virtual</p>
            <p><strong>Stipend:</strong> -</p>
            <p><strong>Start date:</strong> 05/11/2023</p>
            <a href="#" class="btn">View Details</a>
        </div>
        <div class="card">
            <h2>Python Programming Internship Program</h2>
            <p><strong>Duration:</strong> 1 month/2 months</p>
            <p><strong>Location:</strong> Virtual</p>
            <p><strong>Stipend:</strong> -</p>
            <p><strong>Start date:</strong> 05/11/2023</p>
            <a href="#" class="btn">View Details</a>
        </div>
        <div class="card">
            <h2>Java Programming Internship Program</h2>
            <p><strong>Duration:</strong> 1 month/2 months</p>
            <p><strong>Location:</strong> Virtual</p>
            <p><strong>Stipend:</strong> -</p>
            <p><strong>Start date:</strong> 05/11/2023</p>
            <a href="#" class="btn">View Details</a>
        </div>
    </div>
</body>
</html>

