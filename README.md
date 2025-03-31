
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements Implementation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f4f4f4;
        }
    </style>
</head>
<body>
    
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List with Roman Numerals</h2>
    <ol type="I">
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
    </ol>
    
    <!-- External Image -->
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Car Image" width="500">
    
    <!-- Table with Contacts -->
    <h2>Contacts Table</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>123 Main St, NY</td>
            <td>+1 234 567 890</td>
            <td>john@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Elm St, CA</td>
            <td>+1 987 654 321</td>
            <td>jane@example.com</td>
        </tr>
        <tr>
            <td>Mike Johnson</td>
            <td>789 Pine St, TX</td>
            <td>+1 456 789 123</td>
            <td>mike@example.com</td>
        </tr>
        <tr>
            <td>Lisa Brown</td>
            <td>101 Maple Ave, FL</td>
            <td>+1 321 654 987</td>
            <td>lisa@example.com</td>
        </tr>
        <tr>
            <td>David Wilson</td>
            <td>202 Oak St, WA</td>
            <td>+1 789 123 456</td>
            <td>david@example.com</td>
        </tr>
    </table>
    
    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form>
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Create a password" required><br><br>
        
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>
        
        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="other" required>
        <label for="other">Other</label><br><br>
        
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="USA">USA</option>
            <option value="Canada">Canada</option>
            <option value="UK">UK</option>
            <option value="Australia">Australia</option>
        </select><br><br>
        
        <label>Interests:</label><br>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label>
        <input type="checkbox" id="tech" name="interests" value="tech">
        <label for="tech">Technology</label><br><br>
        
        <button type="submit">Register</button>
    </form>

    <!-- Audio and Video Elements -->
    <h2>Multimedia Elements</h2>
    
    <h3>Audio</h3>
    <audio controls>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
        Your browser does not support the audio element.
    </audio>
    
    <h3>Video</h3>
    <video width="500" controls>
        <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

</body>
</html>

