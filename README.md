# Ex09 Event Registration Web Application
## Date:19-12-24

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
CSS :
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Christmas Event</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            color: #000;
        }
        .container {
            width: 100%;
            max-width: 400px;
            margin: 20px auto;
            text-align: center;
            background: url('background.jpg') no-repeat center center/cover;
            border-radius: 10px;
            padding: 20px;
            color: white;
        }
        .login {
            padding: 10px;
        }
        input, button {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }
        .blue-btn {
            background: blue;
            color: white;
            font-weight: bold;
            cursor: pointer;
        }
        .event-section h3 {
            color: #d51243;
        }
        .submitted {
            margin-top: 30px;
            background: #fff;
            color: green;
            padding: 10px;
        }
    </style>
</head>
```
```
<!-- Page 1: Login -->
    <div class="container">
        <h2>Christmas EVENT</h2>
        <div class="login">
            <input type="text" placeholder="User name">
            <input type="password" placeholder="Password">
            <button class="blue-btn">Login</button>
        </div>
    </div>
```
```
<!-- Page 2: Event Details -->
    <div class="container">
        <h3>EVENT DETAILS</h3>
        <div class="event-section">
            <h4>> Cultural Events</h4>
            <p>- Carol Singing Competitions</p>
            <p>- Dance Performances</p>
            <p>- Music Concerts</p>
        </div>
        <div class="event-section">
            <h4>> Fun Activities</h4>
            <p>- Secret Santa Gift Exchange</p>
            <p>- Christmas Decoration Contest</p>
        </div>
        <div class="event-section">
            <h4>> Sports and Games</h4>
            <p>- Christmas-themed Games</p>
            <p>- Sports Tournaments</p>
        </div>
    </div>
```
```
<!-- Page 3: Registration -->
    <div class="container">
        <h3>Registration</h3>
        <form>
            <input type="text" placeholder="Name">
            <input type="text" placeholder="Reg No">
            <input type="text" placeholder="Event Name">
            <button class="blue-btn">Submit</button>
        </form>
    </div>
```
```
<!-- Page 4: Submission Response -->
    <div class="container submitted">
        <h3>Your Response is Submitted</h3>
        <a href="#" style="color: blue;">Add Another Response</a>
        <p>Gifts are waiting for you...</p>
    </div>
```
## OUTPUT:
![alt text](<Screenshot 2024-12-18 113255.png>)
![alt text](<Screenshot 2024-12-18 125836.png>)
![alt text](<Screenshot 2024-12-18 125855.png>)
![alt text](<Screenshot 2024-12-18 125916.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
