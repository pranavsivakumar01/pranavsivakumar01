<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pranav's Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        .header {
            text-align: center;
            background-color: #0066cc;
            padding: 20px;
            color: white;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        .badge {
            padding: 10px 15px;
            margin: 5px;
            border-radius: 25px;
            color: white;
            text-decoration: none;
        }
        .badge.linkedin {
            background-color: #0077b5;
        }
        .badge.leetcode {
            background-color: #f7a800;
        }
        .badge.portfolio {
            background-color: #4caf50;
        }
        .tools img {
            margin: 5px;
        }
        .tools {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }
        .projects {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        .projects h3 {
            color: #0066cc;
        }
        .quote {
            font-style: italic;
            color: #777;
            text-align: center;
            margin-top: 40px;
        }
        .contact {
            text-align: center;
            margin-top: 30px;
        }
        .contact a {
            color: #0066cc;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Hi there, I'm <span style="color: #ffcc00;">Pranav</span> 👋</h1>
        <a class="badge linkedin" href="https://www.linkedin.com/in/pranav-siva-b77245259">LinkedIn</a>
        <a class="badge leetcode" href="https://leetcode.com/u/Pranav_siva/">LeetCode</a>
        <a class="badge portfolio" href="https://pranavsivakumar.netlify.app/">Portfolio</a>
    </div>

    <div class="tools">
        <h2>🚀 Technologies I Work With:</h2>
        <img src="https://img.shields.io/badge/-React-blue?style=flat&logo=react" alt="React" />
        <img src="https://img.shields.io/badge/-Node.js-green?style=flat&logo=node.js" alt="Node.js" />
        <img src="https://img.shields.io/badge/-MongoDB-green?style=flat&logo=mongodb" alt="MongoDB" />
        <img src="https://img.shields.io/badge/-TailwindCSS-blue?style=flat&logo=tailwindcss" alt="TailwindCSS" />
        <img src="https://img.shields.io/badge/-Python-blue?style=flat&logo=python" alt="Python" />
        <img src="https://img.shields.io/badge/-JavaScript-yellow?style=flat&logo=javascript" alt="JavaScript" />
        <img src="https://img.shields.io/badge/-PowerBI-orange?style=flat&logo=powerbi" alt="Power BI" />
        <img src="https://img.shields.io/badge/-VSCode-blue?style=flat&logo=visualstudiocode" alt="VSCode" />
    </div>

    <div class="projects">
        <h3>🌟 A Glimpse of My Journey</h3>
        <ul>
            <li><strong>🏆 Hackathon Finalist:</strong> Secured <strong>2nd place</strong> in the <strong>KEC 30-hour Hackathon</strong>.</li>
            <li><strong>🚀 Key Projects:</strong>
                <ul>
                    <li><strong>KEC Guest House Booking System:</strong> Built with <strong>Django</strong> and <strong>Bootstrap</strong>. <a href="http://pranavas.pythonanywhere.com/" target="_blank">[Live Link]</a></li>
                    <li><strong>Sign Language Recognition:</strong> Implemented using <strong>CNNs</strong> for gesture recognition.</li>
                    <li><strong>Product Recommendation System:</strong> Built with <strong>Machine Learning</strong> for personalized recommendations.</li>
                    <li><strong>Smart Business Dashboards:</strong> Designed for SMEs to visualize sales and growth data.</li>
                    <li><strong>Video Analytics System:</strong> Tracks and analyzes traffic data using video streams.</li>
                </ul>
            </li>
        </ul>
    </div>

    <div class="quote">
        <p>“Financial freedom is freedom from fear.” — <strong>Robert Kiyosaki</strong></p>
    </div>

    <div class="contact">
        <h3>📬 Let's Connect:</h3>
        <p>Email: <strong>pranavsivakumar328@gmail.com</strong></p>
        <p>Portfolio: <a href="https://pranavsivakumar.netlify.app/">Visit Here</a></p>
    </div>

</body>
</html>
