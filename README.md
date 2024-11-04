<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Muhammed Suhaib - Portfolio</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 20px;
        background-color: #f8f9fa;
        color: #333;
        line-height: 1.6;
      }
      h1,
      h2,
      h3 {
        transition: transform 0.3s ease;
      }
      h1:hover,
      h2:hover,
      h3:hover {
        transform: scale(1.05);
      }
      .container {
        max-width: 1200px;
        margin: auto;
        padding: 20px;
      }
      .about-me,
      .contact-info {
        margin: 20px 0;
        padding: 20px;
        background-color: #fff;
        border-radius: 8px;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        opacity: 0;
        transform: translateY(20px);
        animation: fadeInUp 0.6s forwards;
      }
      .about-me {
        animation-delay: 0.3s;
      }
      .contact-info {
        animation-delay: 0.5s;
      }
      @keyframes fadeInUp {
        from {
          opacity: 0;
          transform: translateY(20px);
        }
        to {
          opacity: 1;
          transform: translateY(0);
        }
      }
      img {
        transition: transform 0.3s ease;
      }
      img:hover {
        transform: scale(1.1);
      }
      table {
        margin: 20px auto;
        border-collapse: collapse;
        width: 100%;
        max-width: 900px;
      }
      td {
        padding: 10px;
        border: 1px solid #ddd;
        border-radius: 8px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        text-align: center;
      }
      td:hover {
        transform: translateY(-5px);
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      }
      footer {
        text-align: center;
        margin-top: 30px;
        font-size: 0.9em;
        color: #555;
      }
      a {
        color: #007bff;
        text-decoration: none;
      }
      a:hover {
        text-decoration: underline;
      }
      @media (max-width: 600px) {
        h1 {
          font-size: 2em;
        }
        h2 {
          font-size: 1.5em;
        }
        table {
          width: 100%;
        }
      }
    </style>
  </head>
  <body>
    <div class="container">
      <h1 align="center" style="margin-bottom: 10px">
        👋 Hi, I’m Muhammed Suhaib
      </h1>
      <h2 align="center" style="margin-bottom: 20px; color: #555">
        A Passionate Fullstack Developer
      </h2>

      <div align="center">
        <a href="https://www.instagram.com/suhaii.bb/" target="_blank">
          <img
            src="https://cdn4.iconfinder.com/data/icons/picons-social/57/38-instagram-2-512.png"
            alt="Instagram Logo"
            width="65"
            height="65"
            style="margin-bottom: 20px; transition: transform 0.2s"
          />
        </a>
      </div>

      <div class="about-me">
        <h3 align="center">About Me</h3>
        <ul style="list-style-type: none; padding: 0">
          <li>
            👀 I’m interested in playing games and web development. That's a
            great combination of interests!
          </li>
          <li>
            🌱 I’m currently learning more about web development and exploring
            new projects. If you have any cool ideas, feel free to share!
          </li>
          <li>
            💞 I’m looking to collaborate on interesting projects, especially
            those that combine creativity and technical challenges. Let's create
            something amazing together!
          </li>
          <li>
            📫 You can reach out to me on Instagram or via other channels for
            any questions or collaboration opportunities.
          </li>
        </ul>
      </div>

      <div class="contact-info">
        <h3>Contact Information</h3>
        <div style="margin: 5px 0">
          <i class="fa fa-phone" style="margin-right: 5px"></i> Phone:
          <a href="http://wa.me/09488339232" target="_blank">+730 689 0297</a>
        </div>
        <div style="margin: 5px 0">
          <i class="fa fa-envelope" style="margin-right: 5px"></i> Email:
          <a href="mailto:muhammedsuhaibpottayil@gmail.com"
            >muhammedsuhaibpottayil@gmail.com</a
          >
        </div>
        <div style="margin: 5px 0">
          <i class="fa fa-linkedin-square" style="margin-right: 5px"></i>
          LinkedIn:
          <a href="https://www.linkedin.com/in/muhammedsuhaib" target="_blank"
            >linkedin.com/in/muhammedsuhaib</a
          >
        </div>
      </div>

      <h3 align="center" style="margin-top: 20px">
        Creative and Technical Proficiency:
      </h3>
      <div align="center">
        <table>
          <tr>
            <td>
              <img
                src="https://skillicons.dev/icons?i=html"
                width="48"
                height="48"
                alt="HTML5"
              />
              <br />HTML5
            </td>
            <td>
              <img
                src="https://skillicons.dev/icons?i=css"
                width="48"
                height="48"
                alt="CSS"
              />
              <br />CSS
            </td>
            <td>
              <img
                src="https://techstack-generator.vercel.app/js-icon.svg"
                alt="JavaScript"
                width="65"
                height="65"
              />
              <br />JavaScript
            </td>
            <td>
              <img
                src="https://techstack-generator.vercel.app/ts-icon.svg"
                alt="TypeScript"
                width="65"
                height="65"
              />
              <br />TypeScript
            </td>
            <td>
              <img
                src="https://techstack-generator.vercel.app/react-icon.svg"
                alt="React"
                width="65"
                height="65"
              />
              <br />React
            </td>
            <td>
              <img
                src="https://techstack-generator.vercel.app/redux-icon.svg"
                alt="Redux Toolkit"
                width="62"
                height="62"
              />
              <br />Redux Toolkit
            </td>
            <td>
              <img
                src="https://i.pinimg.com/474x/91/23/7f/91237f1eca767ef74d722ca534f9281a.jpg"
                width="48"
                height="48"
                alt="MongoDB"
              />
              <br />MongoDB
            </td>
            <td>
              <img
                src="https://cdn3d.iconscout.com/3d/free/thumb/free-tailwind-3d-icon-download-in-png-blend-fbx-gltf-file-formats--html-logo-css-framework-customizable-coding-lang-pack-logos-icons-7577995.png?f=webp"
                alt="Tailwind CSS"
                width="48"
                height="48"
              />
              <br />Tailwind CSS
            </td>
          </tr>
          <tr>
            <td>
              <img
                src="https://skillicons.dev/icons?i=bootstrap"
                width="48"
                height="48"
                alt="Bootstrap"
              />
              <br />Bootstrap
            </td>
            <td>
              <img
                src="https://techstack-generator.vercel.app/github-icon.svg"
                alt="GitHub"
                width="65"
                height="65"
              />
              <br />GitHub
            </td>
            <td>
              <img
                src="https://static-00.iconduck.com/assets.00/nextjs-icon-2048x1234-pqycciiu.png"
                alt="Next.js"
                width="65"
                height="65"
              />
              <br />Next.js
            </td>
            <td>
              <img
                src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg"
                alt="Node.js"
                width="65"
                height="65"
              />
              <br />Node.js
            </td>
            <td>
              <img
                src="https://www.vectorlogo.zone/logos/expressjs/expressjs-icon.svg"
                alt="Express.js"
                width="65"
                height="65"
              />
              <br />Express.js
            </td>
            <td>
              <img
                src="https://cdn3d.iconscout.com/3d/free/thumb/free-vuejs-3d-logo-download-in-png-blend-fbx-gltf-file-formats--vue-company-brand-vol-1-pack-logos-3640297.png?f=webp"
                alt="Vue"
                width="65"
                height="65"
              />
              <br />Vue.js
            </td>
            <td>
              <img
                src="https://techstack-generator.vercel.app/restapi-icon.svg"
                alt="REST API"
                width="65"
                height="65"
              />
              <br />REST API
            </td>
            <td>
              <img
                src="https://techstack-generator.vercel.app/prettier-icon.svg"
                alt="Prettier"
                width="65"
                height="65"
              />
              <br />Prettier
            </td>
          </tr>
        </table>
      </div>

      <footer>
        <p>© 2024 Muhammed Suhaib - All Rights Reserved</p>
      </footer>
    </div>
  </body>
</html>
