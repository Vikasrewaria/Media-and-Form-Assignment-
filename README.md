# Media-and-Form-Assignment-
This assignment  contain the media and forms where we are putting the images, audio, video are going to web 
Question1:- Create an imahe gallery that holda multiple images.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Open Server</title>
</head>
<body>
    <img src="./AI wallpaper.jpg" width="400" alt="ai logo">
     <img src="./AI wallpaper.jpg" width="100" alt="ai logo2">
     <img src="./AI wallpaper.jpg" alt="ai logo3" srcset="">
     <img src="./AI wallpaper.jpg" alt="ai logo4" width="1000">
     <img src="./AI wallpaper.jpg" alt="ai log 5" width="300">
</body>
</html>
Question:2:-Use Video and audio tag to display video and audio with the playback, audio control.
Answer:-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body> <h1>this is belongs to html</h1> 
<audio controls src="./Do_You_Know_(Twinbeatz_Remix)___Diljit_Dosanjh___Tris_Dhaliwal___Latest_Punj.mp3"></audio>
<video controls src="https://www.youtube.com/watch?v=uYPbbksJxIg"></video>
</body>
</html>

Question:3:- Modify the previous assignment so audio and video play auutomatically as the page is loaded and they should play infinitely.
Answer:- 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body> <h1>this is belongs to html</h1> 
<audio controls autoplay loop src="./Do_You_Know_(Twinbeatz_Remix)___Diljit_Dosanjh___Tris_Dhaliwal___Latest_Punj.mp3"  ></audio>
<video controls autoplay loop src="https://www.youtube.com/watch?v=uYPbbksJxIg"></video>
</body>
</html>

Question:4:- usw iframe to embed the PhysicsWallha page properly.
Answer:- 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <iframe src="https://en.wikipedia.org/wiki/Physics_Wallah" frameborder="1" height="800px" 
    width="1600px" scrolling ="yes" allowfullscreen ></iframe>
</body>
</html>

Question:5:- Create a sign up and sign in form wit proper validation 
 a. sign up form should have first name, last name, email, password, confirm password, age, gender, and agree to term and conditions field at minimum (you can add any other if you like).
b. sign in form should have emial,password fields.
Answer:- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>form</title>
</head><h1><em>Sign up form</em></h1>
<body>
    <form action="./java.jps">
        <label for="First name">First Name:
        <input type="text" placeholder="Vikas" id="First name"></label>
        <br>
        <label for="lastname">Last Name:
        <input type="text" placeholder="Kumar"Name id="lastName"></label>
        <br>
        <label for="email"> Email address:</label>
        <input type="text" placeholder="vikas@gmail.com" id="email" required>
        <br>
        <label for="password">Password: 

            <input type="text" placeholder="********" id="password" required>
        </label>
        <br>
        <label for="confirmPassword">confirmPassword:
            <input type="text" name="Confirm password" placeholder="********" id="" required/>
         </label><br>
         <label for="age">Age:</label>
         <input type="text" name="age" placeholder="45"> <br>
         <label for="gender">Gender:</label>
         <input type="text" name="gender" placeholder="male/female" id="Gender">
         <button type="submit">Register</button>
<br>
<h1><em>Sign in Form</em></h1>
<Form>
    <label for="Emai">Emial id:</label>
    <input type="text" placeholder="abcd@gmail.com" id="Email id" required/> <br>
    <label for="password">Password</label>
   <input type="text" placeholder="********" name="" id="password" required>
   <button type="submit">Register</button>
</Form>
