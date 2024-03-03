<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration form</title>
</head>
<body>
    <form method="post">
        <label for="fname">First name:</label>
        <input type="text" id="fname" name="fname" placeholder="Enter your name"><br><br>

        <label for="lname">Last name:</label>
        <input type="text" id="lname" name="lname" placeholder="Enter your last name"><br><br>

        <label for="Email">Email:</label>
        <input type="text" id="email" name="email"><br><br>
        
        <label for="Mobile no">Mobile no:</label>
        <input type="tel" id="mobile number" number="mobile number"><br><br>

        <p>Select Gender:</p>
        <input type="radio" name="gender" value="male">
        <label>Male</label>
        <input type="radio" name="gender" value="female">
        <label>Female</label><br><br>

       <label for="Date Of Birth">Date Of Birth:</label>
       <input type="date" name="DOB" value="date"><br><br>
       
       <label for="address">Address:</label>
       <input typr="text" id="address" name="address"><br><br>

       <label for="city">City:</label>
       <input type="text" id="city" name="city"><br><br>

       <label for="area PIN">Area PIN:</label>
       <input type="number" id="PIN" name="PIN"><br><br>

       <label for="State">State:</label>
       <input type="text" id="text" name="text"><br><br>

       <label for="qualification">Qualification:</label>
       <input type="text" id="text" name="text"><br><br>

       <label for="Specification">Specification:</label><br><br>
       <input type="checkbox" id="specification1" name="specification1" value="Computer Science">
       <label for="specification1">Computer Science</label><br>
       <input type="checkbox" id="specification2" name="specification2" value="Information Technology">
       <label for="specification2">Information Technology</label><br>
       <input type="checkbox" id="specification3" name="specification3" value="Artificial Intelligence">
       <label for="specification3">Artificial Intelligence</label><br>
       <input type="checkbox" id="specification4" name="specification4" value="Computer Architecture">
       <label for="specification4">Computer Architecture</label><br>

       <label for="password">Password:</label>
       <input type="password" id="password" name="password" placeholder="Enter valid password"><br><br>
       <input type="Submit">
       </select><br><br>
        
    </form>
</body>
</html>
