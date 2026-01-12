<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Hanc Christopher's Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #9acd32; /* Yellow Green */
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            text-align: center;
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #0053a6;
            font-size: 2.5rem;
            font-weight: bold;
            text-transform: uppercase;
        }
        p {
            margin: 1rem 0;
            font-size: 1.2rem;
            line-height: 1.8;
        }
        .btn {
            display: inline-block;
            padding: 0.75rem 1.5rem;
            color: white;
            background-color: #0078d7;
            text-decoration: none;
            border-radius: 4px;
            font-size: 1rem;
            font-weight: bold;
            transition: background-color 0.3s, transform 0.2s;
        }
        .btn:hover {
            background-color: #0053a6;
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to Hanc Christopher's Website</h1>
        <p>Explore the world of IT solutions and innovation with Hanc Christopher, an IT professional based in Mbeya. Let us help you achieve your technological goals with creativity and expertise.</p>
        <a href="hanc.html" class="btn">Enter Website</a>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hanc Christopher - IT Professional</title>
    <link rel="stylesheet" href="hanc.css">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #9acd32, #32cd32); /* Gradient with yellow-green tones */
            color: #333;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(90deg, #0078d7, #0053a6);
            color: white;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
            font-size: 3rem;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        header p {
            font-size: 1.5rem;
            margin-top: 0.5rem;
        }
        section {
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .about, .services, .contact, .work {
            margin-bottom: 2rem;
            background: white;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            padding: 2rem;
        }
        .about h2, .services h2, .contact h2, .work h2 {
            color: #0078d7;
            margin-bottom: 1rem;
            font-size: 2rem;
            text-transform: uppercase;
            border-bottom: 2px solid #0078d7;
            display: inline-block;
            padding-bottom: 0.5rem;
        }
        .services ul, .work ul {
            list-style: none;
            padding: 0;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }
        .services li, .work li {
            background: #f4f4f9;
            padding: 1.5rem;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .services li:hover, .work li:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .contact a {
            color: #0078d7;
            text-decoration: none;
            font-weight: bold;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        footer p {
            margin: 0;
            font-size: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Hanc Christopher</h1>
        <p>IT Professional | Based in Mbeya, Tanzania</p>
    </header>
    <section class="about">
        <h2>About Me</h2>
        <p>Hello! My name is Hanc Christopher, an IT professional with a passion for technology and innovation. Based in the beautiful city of Mbeya, I specialize in providing IT solutions that drive efficiency and growth. With years of experience in the field, I am dedicated to helping businesses and individuals achieve their technological goals.</p>
    </section>
    <section class="services">
        <h2>Services</h2>
        <ul>
            <li>IT Consulting</li>
            <li>Software Development</li>
            <li>Network Administration</li>
            <li>Technical Support</li>
        </ul>
    </section>
    <section class="work">
        <h2>My Work</h2>
        <p>I have worked on a variety of IT projects, ranging from software development to network administration. Here are some highlights of my work:</p>
        <ul>
            <li><strong>Custom Software Solutions:</strong> Developed tailored software applications to meet specific client needs, ensuring efficiency and scalability.</li>
            <li><strong>Network Infrastructure:</strong> Designed and implemented secure and reliable network systems for businesses.</li>
            <li><strong>Technical Support:</strong> Provided ongoing technical support and troubleshooting to ensure seamless operations.</li>
            <li><strong>IT Consulting:</strong> Advised businesses on the best IT strategies to achieve their goals.</li>
        </ul>
        <p>My commitment to excellence and innovation has helped my clients achieve their technological objectives effectively.</p>
    </section>
    <section class="contact">
        <h2>Contact</h2>
        <p>If you'd like to get in touch, feel free to reach out via email at <a href="mailto:hanc10jr9@gmail.com">hanc10jr9@gmail.com</a>.</p>
    </section>
    <footer>
        <p>&copy; 2026 Hanc Christopher. All rights reserved.</p>
    </footer>
</body>
</html>
