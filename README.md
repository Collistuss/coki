<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coki - Your Digital Partner</title>
    <style>
        body {
            background-color: #f0f8ff; /* Light background for a fresh look */
            color: #333333; /* Dark text for readability */
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background: #1e90ff; /* Primary color for hero section */
            color: white;
            padding: 2em;
            text-align: center;
        }

        nav {
            background: #333333; /* Dark navigation bar */
            color: white;
            padding: 1em;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }

        nav a:hover {
            text-decoration: underline; /* Underline on hover */
        }

        h2 {
            color: #1e90ff; /* Primary color for headings */
        }

        h3 {
            color: #ff6347; /* Secondary color for subheadings */
        }

        a {
            color: #32cd32; /* Accent color for links */
            text-decoration: none; /* Remove underline */
        }

        a:hover {
            color: #1e90ff; /* Change color on hover */
            text-decoration: underline; /* Add underline on hover */
        }

        .section {
            padding: 2em;
            border-radius: 8px;
            margin: 1em 0;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .service-item, .tech-item, .feature-item, .review-item, .example-item {
            margin: 1.5em 0;
            padding: 1em;
            background: #ffffff; /* White background for items */
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .btn {
            background-color: #32cd32; /* Accent color */
            color: white;
            border: none;
            border-radius: 5px;
            padding: 10px 20px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #1e90ff; /* Change to primary color on hover */
        }

        footer {
            background: #333333; /* Dark footer */
            color: white;
            padding: 1em;
            text-align: center;
        }

        /* Responsive Styles */
        @media (max-width: 768px) {
            nav {
                font-size: 14px;
            }
            header, .section {
                padding: 1em;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Coki</h1>
    <p>Your partner in digital transformation.</p>
    <button class="btn">Get Started</button>
</header>

<nav>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#features">Features</a>
    <a href="#technologies">Technologies</a>
    <a href="#examples">Examples of Applications</a>
    <a href="#reviews">Customer Reviews</a>
    <a href="#contact">Contact Us</a>
</nav>

<section id="about" class="section">
    <h2>About Us</h2>
    <p>At Coki, we believe in harnessing the power of technology to transform businesses. Our journey began with a simple idea: to make digital solutions accessible to everyone. With a team of passionate experts, we have grown into a trusted partner for businesses looking to innovate and thrive in the digital age.</p>
    <p>Our mission is to empower our clients by providing tailored solutions that meet their unique needs. We are committed to quality, integrity, and excellence in everything we do.</p>
</section>

<section id="services" class="section">
    <h2>Our Services</h2>
    <p>At Coki, we pride ourselves on delivering top-notch services tailored to your needs. Here’s how we can help you:</p>
    <div class="service-item">
        <h3>🌟 Custom Software Development</h3>
        <p>We create bespoke software solutions that fit your unique business requirements. Our team works closely with you to understand your goals and deliver a product that enhances efficiency and productivity.</p>
    </div>
    <div class="service-item">
        <h3>🌐 Web Design & Development</h3>
        <p>Your website is your digital storefront. We design and develop responsive, user-friendly websites that not only look stunning but also drive engagement and conversions. Let us help you make a lasting impression online!</p>
    </div>
    <div class="service-item">
        <h3>📱 Mobile App Development</h3>
        <p>In today’s mobile-first world, having a robust mobile application is crucial. We build cross-platform apps that provide seamless user experiences, ensuring your customers can connect with you anytime, anywhere.</p>
    </div>
    <div class="service-item">
        <h3>📊 Database Management</h3>
        <p>Data is the backbone of any business. Our database management services ensure that your data is organized, secure, and easily accessible. We implement scalable solutions that grow with your business needs.</p>
    </div>
    <div class="service-item">
        <h3>💼 Consulting Services</h3>
        <p>Looking to leverage technology for growth? Our consulting services offer expert insights and strategies tailored to your business. We help you navigate the tech landscape to achieve your objectives efficiently.</p>
    </div>
</section>

<section id="features" class="section">
    <h2>Features</h2>
    <div class="feature-item">
        <h3>⚡ Fast Performance</h3>
        <p>Our solutions are optimized for speed, ensuring your applications run smoothly and efficiently.</p>
    </div>
    <div class="feature-item">
        <h3>🔒 Security First</h3>
        <p>We prioritize security in every project, implementing best practices to protect your data.</p>
    </div>
    <div class="feature-item">
        <h3>📱 Responsive Design</h3>
        <p>All our websites and applications are designed to work seamlessly on any device, be it a phone, tablet, or laptop.</p>
    </div>
    <div class="feature-item">
        <h3>🌐 Global Reach</h3>
        <p>Our solutions are designed to scale, enabling you to reach customers around the world.</p>
    </div>
</section>

<section id="technologies" class="section">
    <h2>Technologies We Use</h2>
    <p>At Coki, we leverage cutting-edge technologies to deliver exceptional solutions. Here’s a glimpse of the powerful tools and frameworks that drive our projects:</p>
    
    <div class="tech-item">
        <h3>💻 Programming Languages</h3>
        <p>We utilize a variety of programming languages including:</p>
        <ul>
            <li><strong>JavaScript:</strong> For dynamic web applications and interactive front-end experiences.</li>
            <li><strong>Python:</strong> Ideal for backend development, data analysis, and machine learning.</li>
            <li><strong>Java:</strong> A robust choice for enterprise-level applications.</li>
        </ul>
    </div>

    <div class="tech-item">
        <h3>🌐 Frameworks</h3>
        <p>Our development process is powered by modern frameworks such as:</p>
        <ul>
            <li><strong>React:</strong> For building responsive user interfaces.</li>
            <li><strong>Node.js:</strong> To create scalable server-side applications.</li>
            <li><strong>Django:</strong> A high-level framework for rapid development with Python.</li>
        </ul>
    </div>

    <div class="tech-item">
        <h3>📊 Databases</h3>
        <p>We ensure data integrity and performance with:</p>
        <ul>
            <li><strong>PostgreSQL:</strong> A powerful, open-source relational database.</li>
            <li><strong>MongoDB:</strong> For flexible, document-based data storage.</li>
            <li><strong>MySQL:</strong> A reliable choice for web applications.</li>
        </ul>
    </div>

    <div class="tech-item">
        <h3>☁️ Cloud Services</h3>
        <p>We harness the power of the cloud with:</p>
        <ul>
            <li><strong>AWS:</strong> Scalable cloud services for storage and computing.</li>
            <li><strong>Azure:</strong> Microsoft’s cloud platform for building, testing, and deploying applications.</li>
            <li><strong>Google Cloud:</strong> For data analytics and machine learning capabilities.</li>
        </ul>
    </div>

    <div class="tech-item">
        <h3>🔒 Security Tools</h3>
        <p>Your data is safe with us. We implement:</p>
        <ul>
            <li><strong>SSL Certificates:</strong> To secure data transfer.</li>
            <li><strong>OAuth:</strong> For secure authorization.</li>
            <li><strong>Firewalls:</strong> To protect your applications from threats.</li>
        </ul>
    </div>
</section>

<section id="examples" class="section">
    <h2>Examples of Applications</h2>
    <p>Here are some examples of what can be created using the different programming languages and technologies we utilize:</p>
    
    <div class="example-item">
        <h3>JavaScript</h3>
        <p><strong>Interactive Web Applications:</strong> Dynamic applications like Google Maps that allow users to interact without reloading the page.</p>
    </div>
    
    <div class="example-item">
        <h3>Python</h3>
        <p><strong>Data Analysis Tool:</strong> Applications like Jupyter Notebooks for creating and sharing documents with live code and visualizations.</p>
    </div>

    <div class="example-item">
        <h3>Java</h3>
        <p><strong>Banking Management System:</strong> Secure applications for managing transactions and customer data in enterprise settings.</p>
    </div>

    <div class="example-item">
        <h3>React</h3>
        <p><strong>E-commerce Website:</strong> Platforms like Amazon that offer responsive and dynamic user interfaces for shopping experiences.</p>
    </div>

    <div class="example-item">
        <h3>Node.js</h3>
        <p><strong>Real-Time Chat Application:</strong> Applications like Slack that facilitate instant communication among users.</p>
    </div>

    <div class="example-item">
        <h3>Django</h3>
        <p><strong>Blog Platform:</strong> Websites like Medium that provide user authentication and content management features.</p>
    </div>

    <div class="example-item">
        <h3>PostgreSQL</h3>
        <p><strong>Inventory Management System:</strong> Applications to track product details and stock levels efficiently.</p>
    </div>

    <div class="example-item">
        <h3>MongoDB</h3>
        <p><strong>Social Media Application:</strong> Platforms like Facebook that require flexible data storage solutions.</p>
    </div>

    <div class="example-item">
        <h3>AWS</h3>
        <p><strong>Scalable Web Application Hosting:</strong> Services like Netflix that need robust cloud infrastructure for millions of users.</p>
    </div>
</section>

<section id="reviews" class="section">
    <h2>Customer Reviews</h2>
    <div class="review-item">
        <h3>⭐ John Doe</h3>
        <p>"Coki transformed our business with their innovative solutions. Highly recommend!"</p>
    </div>
    <div class="review-item">
        <h3>⭐ Jane Smith</h3>
        <p>"The team at Coki is incredibly professional and responsive. Our project was a success!"</p>
    </div>
    <div class="review-item">
        <h3>⭐ Alex Johnson</h3>
        <p>"Excellent service and top-notch quality. Coki is our go-to partner for tech solutions."</p>
    </div>
</section>

<section id="contact" class="section">
    <h2>Contact Us</h2>
    <form action="#" method="post">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        
        <label for="subject">Subject:</label><br>
        <input type="text" id="subject" name="subject"><br><br>
        
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" required></textarea><br><br>
        
        <button type="submit" class="btn">Send Message</button>
    </form>
</section>

<footer>
    <p>&copy; 2024 Coki. All rights reserved.</p>
</footer>

</body>
</html>
