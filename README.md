<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Lab1.css">
</head>
<body>
<div style="width: 1310px; margin: 0 auto;">
    <header>
        <h1 style=" color: black; background-color:white;font-size: 45px;">Dod D.Dog</h1>
    </header>
    <div>
        <div>
            <h1>About</h1>
            <p>Woof woof!</p>
            <p>Hi, I'm Dog. I love <strong style="color:rgb(52, 108, 197);">User Interface Design.</strong></p>
        </div>
        <div>
            <h1>Courses</h1>
            <p>Here are some courses I've taken:</p>
            <table border="1" cellspacing="0">
                <tr>
                    <th>Course Number</th>
                    <th>Course Title</th>
                    <th>Semester Taken</th>
                </tr>
                <tr>
                    <th colspan="3">For credit</th>
                </tr>
                <tr style="background-color: rgb(230, 225, 221);">
                    <td><b style="color:rgb(52, 108, 197)">6.813</b></td>
                    <td><b style="color:rgb(52, 108, 197)">User Interface Design</b></td>
                    <td><b style="color:rgb(52, 108, 197)">Spring 2014</b></td>
                </tr>
                <tr>
                    <td><b style="color:rgb(52, 108, 197)">6.034</b></td>
                    <td>Artificial Intelligence</td>
                    <td>Fall 2013</td>
                </tr>
                <tr style="background-color: rgb(230, 225, 221);">
                    <td><b style="color:rgb(52, 108, 197)">6.006</b></td>
                    <td>Introduction to Algorithms</td>
                    <td>Fall 2013</td>
                </tr>
                <tr>
                    <th colspan="3">Listener</th>
                </tr>
                <tr style="background-color: rgb(230, 225, 221);">
                    <td><b style="color:rgb(52, 108, 197)">6.867</b></td>
                    <td>Machine Learning</td>
                    <td>Fall 2013</td>
                </tr>
                <tr>
                    <td><b style="color:rgb(52, 108, 197)">6.830</b></td>
                    <td>Database Systems</td>
                    <td>Fall 2012</td>
                </tr>
            </table>
        </div>
        <div>
            <h1>Interests</h1>
            <p>I am interested in <strong>HCL</strong>, memes, and YouTube videos.</p>
        </div>
        <div>
            <h1>Submit Pet Information</h1>
            <p>Would love to know what kinds of pets you 'own' (you'll never own me). Submit below!</p>
            <form action="">
                <label for="Name">Name:</label>
                <input type="text" id="Name"> <br>
                <label for="Phylum">Phylum:</label>
                <input type="text" id="Phylum"> <br>
                <label for="Gender">Gender:</label>
                <input type="text" id="Gender"> <br>
                <input style="background-color: rgb(190, 190, 190);" type="submit" value="submit">
            </form>
        </div>
    </div>
    <div class="box"></div>
</div>
</body>
</html>
