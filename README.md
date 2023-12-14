<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event 1</title>
    <style>
        
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
        }

        input, select {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            box-sizing: border-box;
        }

        button {
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button.cancel {
            background-color: #f44336;
        }
    </style>
</head>
<body>

   

    <center> <h2>Event 1</h2></center>
    <div class="div">
    <form action="#" method="post" enctype="multipart/form-data">
       <center> <label for="availableSeats">Number of Available Seats: 23</label></center>
        <input type="number" id="availableSeats" name="availableSeats" required>

        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="numSeats">Number of Seats:</label>
        <input type="number" id="numSeats" name="numSeats" required>

        <label for="attendanceName">Name of Attendance: 2</label>
        <input type="text" id="attendanceName" name="attendanceName" required>
    </div>
        

        <button type="submit">Submit</button>
        <button type="button" class="cancel">Cancel</button>
    </form>

</body>
</html>

