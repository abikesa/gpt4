<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Blog</title>
    <style>
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #282c34;
            color: #ffffff;
            text-align: center;
            padding: 1em 0;
        }
        header h1, footer p {
            margin: 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 0 20px;
        }
        .bio, .blog-posts, .contact {
            background: #ffffff;
            border-radius: 8px;
            margin: 20px 0;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .bio h2, .blog-posts h2, .contact h2 {
            border-bottom: 2px solid #f1f1f1;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .blog-post {
            margin-bottom: 20px;
        }
        .blog-post h3 {
            margin: 0 0 5px;
            color: #282c34;
        }
        .blog-post p {
            margin: 0;
        }
        .blog-post a {
            color: #61dafb;
            text-decoration: none;
        }
        .blog-post a:hover {
            text-decoration: underline;
        }
        .contact a {
            color: #61dafb;
            text-decoration: none;
        }
        .contact a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Personal Blog</h1>
    </header>
    <div class="container">
        <section class="bio">
            <h2>About Me</h2>
            <p>Welcome to my personal blog! I am passionate about sharing my thoughts and experiences on various topics. Stay tuned for my latest posts!</p>
        </section>
        <section class="blog-posts">
            <h2>Blog Posts</h2>
            <div class="blog-post">
                <h3>Blog Post Title 1</h3>
                <p>Published on: Date</p>
                <p>This is a brief summary of my first blog post. Click <a href="#">here</a> to read more.</p>
            </div>
            <div class="blog-post">
                <h3>Blog Post Title 2</h3>
                <p>Published on: Date</p>
                <p>This is a brief summary of my second blog post. Click <a href="#">here</a> to read more.</p>
            </div>
            <!-- Add more blog posts as needed -->
        </section>
        <section class="contact">
            <h2>Contact Me</h2>
            <p>You can reach me via email at: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 My Personal Blog. All rights reserved.</p>
    </footer>
</body>
</html>
