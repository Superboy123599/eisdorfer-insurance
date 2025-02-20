# eisdorfer-insurance<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eisdorfer Insurance - Get a Quote</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; text-align: center; }
        .container { max-width: 600px; margin: 50px auto; background: white; padding: 20px; border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); }
        h1 { color: #333; }
        form { display: flex; flex-direction: column; }
        input, select, textarea { margin: 10px 0; padding: 10px; width: 100%; border: 1px solid #ccc; border-radius: 5px; }
        button { background: #007BFF; color: white; padding: 10px; border: none; border-radius: 5px; cursor: pointer; }
        button:hover { background: #0056b3; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Eisdorfer Insurance</h1>
        <p>We provide Auto, Home, Renters, Life, Commercial Auto, and General Liability Insurance.</p>
        <h2>Get a Quote</h2>
        <form action="mailto:your-email@example.com" method="POST" enctype="text/plain">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <input type="tel" name="phone" placeholder="Your Phone Number" required>
            <select name="insurance_type" required>
                <option value="">Select Insurance Type</option>
                <option value="Auto">Auto Insurance</option>
                <option value="Home">Home Insurance</option>
                <option value="Renters">Renters Insurance</option>
                <option value="Life">Life Insurance</option>
                <option value="Commercial Auto">Commercial Auto Insurance</option>
                <option value="General Liability">General Liability Insurance</option>
            </select>
            <textarea name="details" placeholder="Additional Details (Optional)"></textarea>
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
