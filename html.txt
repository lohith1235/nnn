<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EditKaro.in</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <img src="path_to_logo.png" alt="Logo" /> <!-- Replace with your logo path -->
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    
    <div class="content" id="home">
        <p class="intro">Professional marketing solutions, including social media management and video editing.</p>
        <h1 class="welcome-text">Welcome to</h1>
        <h1 class="editkaro-text">EditKaro.in</h1>
        <p>We specialize in creative editing solutions that enhance your brand's message.</p>
        
        <a href="#portfolio" class="cta-button">Our Work</a>
        
        <div id="about" class="about-section">
            <div class="about-text">
                <h2>About Us</h2>
                <p>At EditKaro.in, we are passionate about transforming your creative vision into reality. Founded by a team of dedicated professionals with expertise in video editing, digital marketing, and content creation, our mission is to empower brands by delivering high-quality, engaging content that resonates with their target audience.</p>
                <p>We believe that every brand has a unique story to tell. Our collaborative approach ensures that we understand your goals and aspirations, allowing us to deliver customized solutions that exceed your expectations.</p>
                <a href="#contact" class="cta-button">Get Started</a>
            </div>
        </div>

        <div id="services" class="services-box">
            <div class="services-title">Our Services</div>
            <div class="service-item" onclick="toggleActive(this)">
                <i class="fas fa-video service-icon"></i>
                <p class="service-name">Video Editing</p>
                <p class="service-description">Our team transforms raw footage into professional, engaging videos that tell your brand's story effectively.</p>
            </div>
            <div class="service-item" onclick="toggleActive(this)">
                <i class="fas fa-chart-line service-icon"></i>
                <p class="service-name">Digital Marketing Strategy</p>
                <p class="service-description">We develop targeted strategies to increase your online presence and drive traffic to your brand.</p>
            </div>
            <div class="service-item" onclick="toggleActive(this)">
                <i class="fas fa-pencil-alt service-icon"></i>
                <p class="service-name">Content Creation</p>
                <p class="service-description">Our team creates compelling content that resonates with your audience, helping you establish authority in your niche.</p>
            </div>
            <div class="service-item" onclick="toggleActive(this)">
                <i class="fas fa-flag service-icon"></i>
                <p class="service-name">Brand Development</p>
                <p class="service-description">We help you build a strong brand identity that resonates with your target audience and stands out in the market.</p>
            </div>
        </div>

        <div id="portfolio">
            <div class="portfolio-title">Our Portfolio</div>
            <div class="category-buttons">
                <a href="#short-form-videos" class="category-button" onclick="playVideo('Iman Gadhzi Tryout (3).mp4')">Short-Form Videos</a>
                <a href="#long-form-videos" class="category-button" onclick="playVideo('Ruri Ohama Re-edited (1).mp4')">Long-Form Videos</a>
                <a href="#gaming-videos" class="category-button" onclick="playVideo('Gaming Edited YT Video (1) (1).mp4')">Gaming Videos</a>
                <a href="#football-edits" class="category-button" onclick="playVideo('Ronaldo vs messi (1) (1).mp4')">Football Edits</a>
                <a href="#ecommerce-ads" class="category-button" onclick="playVideo('1st Mockup Edit (1).mp4')">eCommerce Ads</a>
                <a href="#documentary-style" class="category-button" onclick="playVideo('Mohak Mangal Documentry Style (1).mp4')">Documentary Style</a>
                <a href="#color-grading" class="category-button" onclick="playVideo('Color Grading (2) (1).mp4')">Color Grading</a>
                <a href="#anime-videos" class="category-button" onclick="playVideo('Comp 1_1 (1) (1).mp4')">Anime Videos</a>
                <a href="#ads" class="category-button" onclick="playVideo('Coca Cola Landing Page AD (1) (1).mp4')">Ads</a>
            </div>

            <div class="category-buttons">
                <div class="portfolio-box" onclick="playVideo('Iman Gadhzi Tryout (3).mp4')">
                    <img src="image-5-2-1024x852.webp" alt="Short-Form Videos" class="portfolio-image">
                    <div>Short-Form Videos</div>
                </div>
                <div class="portfolio-box" onclick="playVideo('Ruri Ohama Re-edited (1).mp4')">
                    <img src="blog_img_long-form_video.jpg" alt="Long-Form Videos" class="portfolio-image">
                    <div>Long-Form Videos</div>
                </div>
                <div class="portfolio-box" onclick="playVideo('Gaming Edited YT Video (1) (1).mp4')">
                    <img src="pexels-photo-442576.webp" alt="Gaming Videos" class="portfolio-image">
                    <div>Gaming Videos</div>
                </div>
                <div class="portfolio-box" onclick="playVideo('Ronaldo vs messi (1) (1).mp4')">
                    <img src="1002614356.jpg" alt="Football Edits" class="portfolio-image">
                    <div>Football Edits</div>
                </div>
                <div class="portfolio-box" onclick="playVideo('1st Mockup Edit (1).mp4')">
                    <img src="showing-cart-trolley-shopping-online-sign-graphic_53876-133967.jpg" alt="eCommerce Ads" class="portfolio-image">
                    <div>eCommerce Ads</div>
                </div>
                <div class="portfolio-box" onclick="playVideo('Mohak Mangal Documentry Style (1).mp4')">
                    <img src="65071c540a5c94b4afbe990e_5ec507c22916739d68a067dd_Melissa27Shaughnessy-2.jpeg" alt="Documentary Style" class="portfolio-image">
                    <div>Documentary Style</div>
                </div>
                <div class="portfolio-box" onclick="playVideo('Color Grading (2) (1).mp4')">
                    <img src="il_570xN.4635819255_i7zo.webp" alt="Color Grading" class="portfolio-image">
                    <div>Color Grading</div>
                </div>
                <div class="portfolio-box" onclick="playVideo('Comp 1_1 (1) (1).mp4')">
                    <img src="pngtree-anime-boy-lofi-cloud-sunset-image_16124755.jpg" alt="Anime Videos" class="portfolio-image">
                    <div>Anime Videos</div>
                </div>
                <div class="portfolio-box" onclick="playVideo('Coca Cola Landing Page AD (1) (1).mp4')">
                    <img src="digital-marketing-commerce-online-sale-600nw-2493638089.webp" alt="Ads" class="portfolio-image">
                    <div>Ads</div>
                </div>
            </div>
        </div>

        <div id="contact" class="contact-section">
            <div class="contact-info">
                <h2>Contact Us</h2>
                <p>Phone: +1 (123) 456-7890</p>
                <p>Email: info@editkaro.in</p>
                <p>Address: 123 EditKaro Lane, Creative City, CR 12345</p>
                <button class="cta-button" onclick="openForm()">Contact Form</button>
                <div class="contact-form" id="contactForm">
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <textarea placeholder="Your Message" rows="4" required></textarea>
                    <button type="submit">Send Message</button>
                    <button onclick="closeForm()">Close</button>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <p>&copy; 2024 EditKaro.in. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
