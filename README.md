# champuru_stories
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Welcome to Champuru Stories - A vibrant space for blogs, vlogs, and community discussions.">
    <title>Champuru Stories</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #FDF3F0; /* Pastel pink */
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #F8B195; /* Pastel peach */
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        h1 {
            font-size: 3rem;
            margin: 0;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 2rem;
            max-width: 1000px;
            margin: 0 auto;
        }
        .content-block {
            margin-bottom: 3rem;
        }
        footer {
            background-color: #355C7D; /* Pastel dark purple */
            color: white;
            text-align: center;
            padding: 1rem 0;
        }

        /* Specific Sections */
        .about-me {
            background-color: #C06C84; /* Pastel light purple */
            border-radius: 8px;
            padding: 2rem;
            text-align: center;
        }

        .gallery img {
            max-width: 100%;
            margin: 10px;
            border-radius: 8px;
        }

        .comments, .discussion {
            background-color: #99B898; /* Pastel green */
            border-radius: 8px;
            padding: 1.5rem;
        }

        .reaction {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-top: 1rem;
        }

        .reaction button {
            font-size: 1.5rem;
            border: none;
            background: none;
            cursor: pointer;
        }

        /* Responsive Design */
        @media only screen and (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }
            .reaction button {
                font-size: 1.2rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Champuru Stories</h1>
        <nav>
            <a href="#blog">Blog</a>
            <a href="#vlog">Vlog</a>
            <a href="#about">About Me</a>
            <a href="#gallery">Gallery</a>
            <a href="#discussion">Community</a>
        </nav>
    </header>

    <section id="about" class="about-me content-block">
        <h2>About Me</h2>
        <p>Welcome to Champuru Stories! This is where I share my thoughts, experiences, and stories through blogs and vlogs. Enjoy the journey!</p>
    </section>

    <section id="blog" class="content-block">
        <h2>Blog</h2>
        <article>
            <h3>Blog Title 1</h3>
            <p>This is a blog post. Stay tuned for more content!</p>
        </article>
        <article>
            <h3>Blog Title 2</h3>
            <p>This is another blog post.</p>
        </article>
    </section>

    <section id="vlog" class="content-block">
        <h2>Vlog</h2>
        <video controls>
            <source src="vlog1.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <video controls>
            <source src="vlog2.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>

    <section id="gallery" class="gallery content-block">
        <h2>Gallery</h2>
        <img src="gallery1.jpg" alt="Gallery image 1">
        <img src="gallery2.jpg" alt="Gallery image 2">
    </section>

    <section id="comments" class="comments content-block">
        <h2>Comments</h2>
        <div>
            <p>User 1: This is amazing!</p>
            <p>User 2: Great content!</p>
        </div>
        <textarea placeholder="Leave a comment"></textarea>
        <button>Submit</button>
    </section>

    <section id="discussion" class="discussion content-block">
        <h2>Community Discussion</h2>
        <p>Join the conversation! Share your thoughts below:</p>
        <textarea placeholder="Start a discussion..."></textarea>
        <button>Submit</button>
    </section>

    <section class="reaction content-block">
        <h2>React to this page:</h2>
        <div class="reaction">
            <button>&#128512;</button> <!-- Smiley face emoji -->
            <button>&#128525;</button> <!-- Heart eyes emoji -->
            <button>&#128546;</button> <!-- Sad face emoji -->
            <button>&#128077;</button> <!-- Thumbs up emoji -->
        </div>
    </section>

    <footer>
        <p>© 2024 Champuru Stories | Created with passion and joy!</p>
    </footer>

</body>
</html>
