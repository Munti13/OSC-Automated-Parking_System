<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Automated Parking System</title>
</head>
<body>
    <h1>Parking System</h1>
    
    <?php
        // Display parking spaces and their availability
        include 'parking_status.php';
    ?>

    <form action="reserve_spot.php" method="post">
        <label for="spot_number">Enter Spot Number to Reserve:</label>
        <input type="text" id="spot_number" name="spot_number" required>
        <button type="submit">Reserve Spot</button>
    </form>
</body>
</html>
