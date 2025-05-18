<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UDM: Lost & Found</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            /* Background image with fallback color */
            background: #f5f5f5 url('udmbg.jpg') no-repeat center center fixed;
            background-size: cover;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: #333;
        }

        .container {
            text-align: center;
            background-color: rgba(255, 255, 255, 0.719); /* Semi-transparent white */
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 80%;
            max-width: 500px;
            backdrop-filter: blur(2px); /* Optional: slight blur effect */
        }

        .logo-img {
            width: 120px;
            height: auto;
            margin-bottom: 20px;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 40px;
            color: #2c3e50;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }

        .button-container {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .btn {
            padding: 15px 30px;
            font-size: 1.1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: bold;
            width: 100%;
            max-width: 250px;
            margin: 0 auto;
        }

        .btn-primary {
            background-color: #3498db;
            color: white;
        }

        .btn-primary:hover {
            background-color: #2980b9;
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .btn-secondary {
            background-color: #2ecc71;
            color: white;
        }

        .btn-secondary:hover {
            background-color: #27ae60;
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="udmlogo.png" alt="UDM Logo" class="logo-img">
        <h1>UDM: LOST & FOUND</h1>
        
        <div class="button-container">
            <button class="btn btn-primary" onclick="fileReport()">FILE A REPORT</button>
            <button class="btn btn-secondary" onclick="viewRecords()">RECENT RECORDS</button>
        </div>
    </div>

    <script>
        function fileReport() {
            alert("File a report functionality would go here");
        }

        function viewRecords() {
            alert("Recent records functionality would go here");
        }
    </script>
</body>
</html>
