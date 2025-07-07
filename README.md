# Profile Page
## Date: 7/7/25
### NAME : HARISH RAGAV S
## Objective:

To design a simple Profile Page using HTML that displays a user's profile image, name, headings, and a short bio, suitable for personal or academic purposes.

## Tasks:

#### 1. Set Up the HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the basic structure.

Add an appropriate <title> such as "My Profile".

#### 2. Add Page Headings:

Insert a main heading using ```<h1>``` for the user's name.

Include subheadings such as ```<h2>``` or ```<h3>``` for titles or roles (e.g., "Student", "Web Developer").

#### 3. Insert a Profile Image:

Use the ```<img>``` tag to display the user’s profile picture.

Add alt text and set basic attributes like width and height.

#### 4. Include a Short Bio Section:

Add a paragraph using <p> to provide a short introduction or biography.

The content may include education, interests, or a personal statement.

#### 5. Organize Content Using HTML Elements:

Use ```<section>```, ```<div>```, or ```<article>``` for logical grouping.

Add a horizontal line (```<hr>```) to separate sections.

#### 6. Keep the Design HTML-Only:

Do not use CSS or JavaScript.

Focus on semantic HTML and readability.
## HTML Code:
```
<!DOCTYPE html>
<html>
<head>
    <title>My Profile</title>
</head>
<body>

    <h1>Harish Ragav S</h1>
    <h2>Student</h2>
    <h3>Aspiring Software Engineer</h3>

    <hr>

    <section>
        <img src="profile.png" alt="Profile picture of Harish Ragav S" width="200" height="200">
        <!-- Replace "profile.jpg" with your actual image file path -->
    </section>

    <hr>

    <section>
        <h2>About Me</h2>
        <p>
            I am a 3rd-year Computer Science student at Saveetha Engineering College. Passionate about full-stack development and AI-based applications, I aim to build practical tech solutions and contribute to impactful projects.
        </p>
    </section>

    <hr>

    <section>
        <h2>Education</h2>
        <p>
            XII – Green Park International School, Namakkal (85.4%)<br>
            X – Trinity International School, Namakkal (89%)<br>
            B.E. CSE – Saveetha Engineering College (Current CGPA: 7.6)
        </p>
    </section>

    <hr>

    <section>
        <h2>Interests</h2>
        <ul>
            <li>Web Development</li>
            <li>AI and Resume Ranking Tools</li>
            <li>Movies</li>
            <li>Cricket </li>
        </ul>
    </section>

</body>
</html>
```
## Output:

## Result:
A simple Profile Page using HTML that displays a user's profile image, name, headings, and a short bio, suitable for personal or academic purposes is designed successfully.
