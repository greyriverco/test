# test

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume Writing and Editing Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        main {
            padding: 2rem;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: white;
            padding: 2rem;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #4CAF50;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        label {
            margin: 1rem 0 0.5rem;
        }
        input[type="file"],
        input[type="email"],
        textarea {
            padding: 0.5rem;
            margin-bottom: 1rem;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            padding: 0.5rem;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #4CAF50;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Resume Writing and Editing Services</h1>
    </header>
    <main>
        <div class="container">
            <h2>About Me</h2>
            <p>Welcome to my resume writing and editing services. I specialize in crafting professional resumes that highlight your skills and experience, helping you stand out in the job market.</p>

            <h2>Services</h2>
            <ul>
                <li>Resume Writing</li>
                <li>Resume Editing</li>
                <li>Cover Letter Writing</li>
                <li>LinkedIn Profile Optimization</li>
            </ul>

            <h2>Contact Me</h2>
            <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
                <label for="email">Your Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <label for="resume">Upload Your Resume:</label>
                <input type="file" id="resume" name="resume" accept=".doc,.docx,.pdf" required>

                <input type="submit" value="Submit">
            </form>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 Resume Writing and Editing Services. All rights reserved.</p>
    </footer>
</body>
</html>
