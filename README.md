# HTML-Day-17
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Responsive Cards Example</title>
    

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 40px; */
            gap: 20px;
        }

        .card {
            background-color: #f0f0f0;
            border: 1px solid #ccc;
            border-radius: 8px;
            padding: 20px;
            text-align: center;
            
            
            flex: 1 1 300px; 
            
        }

        
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                padding: 20px; 
            }

            .card {
                max-width: 100%;            }
        }
    </style>
</head>
<body>

    <h1 style="text-align:center; padding:20px;">Responsive Cards Example</h1>

    <div class="container">
        <div class="card">
            <h2>Card 1</h2>
            <p>This is a flexible, responsive card.</p>
        </div>
        <div class="card">
            <h2>Card 2</h2>
            <p>It adjusts to different screen sizes automatically.</p>
        </div>
        <div class="card">
            <h2>Card 3</h2>
            <p>Stacked on mobile, side-by-side on desktop.</p>
        </div>
    </div>

</body>
</html>
