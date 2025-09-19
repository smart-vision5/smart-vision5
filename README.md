<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            background-color: #0a0f1a;
            color: #fff;
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }

        h1, h3 {
            text-align: center;
            font-size: 2em;
            text-transform: uppercase;
            animation: glow 1.5s ease-in-out infinite alternate;
        }

        h1 {
            color: #00ff99;
        }

        h3 {
            color: #ff6347;
        }

        .section {
            margin: 50px auto;
            padding: 20px;
            max-width: 80%;
            text-align: center;
        }

        .section-title {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-transform: uppercase;
            color: #00ffff;
            animation: glow 2s ease-in-out infinite alternate;
        }

        .skills-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }

        .skill {
            margin: 20px;
            padding: 20px;
            border: 3px solid #00ff99;
            border-radius: 10px;
            transition: transform 0.3s;
            color: #fff;
        }

        .skill:hover {
            transform: scale(1.1);
            animation: pulse 1s infinite alternate;
        }

        .skill img {
            width: 50px;
            height: 50px;
        }

        .about-text {
            font-size: 1.2em;
            line-height: 1.8;
            max-width: 800px;
            margin: auto;
            color: #ccc;
        }

        @keyframes glow {
            0% {
                text-shadow: 0 0 5px #fff, 0 0 10px #ff6347, 0 0 15px #ff6347;
            }
            100% {
                text-shadow: 0 0 20px #00ff99, 0 0 30px #00ff99, 0 0 40px #00ff99;
            }
        }

        @keyframes pulse {
            0% {
                background-color: rgba(0, 255, 153, 0.3);
            }
            100% {
                background-color: rgba(0, 255, 153, 0.5);
            }
        }

    </style>
</head>
<body>

    <header>
        <h1>Hi everyone 👋</h1>
        <h3>🚀 Full-Stack Engineer | 🤖 AI Developer | Open-Source Contributor</h3>
    </header>

    <section class="section">
        <div class="section-title">ABOUT ME</div>
        <p class="about-text">
            🔭 I’m a Full Stack Engineer passionate about building scalable, user-centric web applications. <br>
            🤖 Currently diving deep into AI integration, leveraging tools like LangChain, TensorFlow, and LLMs to create intelligent full-stack solutions. <br>
            🌐 Skilled across frontend, backend, cloud, and DevOps, I enjoy bridging traditional full-stack development with cutting-edge AI/ML workflows. <br>
            💬 Ask me about modern web frameworks, REST/GraphQL APIs, cloud deployment, and AI integration strategies. <br>
            ⚡ Fun fact: When I’m not coding, you’ll find me exploring fitness science and performance optimization.
        </p>
    </section>

    <section class="section">
        <div class="section-title">SKILL SET</div>
        <div class="skills-container">
            <div class="skill"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" /></div>
            <div class="skill"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /></div>
            <div class="skill"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /></div>
            <div class="skill"><img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" /></div>
            <div class="skill"><img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" /></div>
            <div class="skill"><img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" /></div>
            <!-- Add more skills as necessary -->
        </div>
    </section>

</body>
</html>
