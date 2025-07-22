<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cheptoyek Bill - Software Engineer</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@500&family=Share+Tech+Mono&display=swap');

        body {
            font-family: 'Fira Code', monospace;
            background-color: #0d1117; /* GitHub Dark Mode Background */
            color: #c9d1d9; /* GitHub Dark Mode Text */
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            overflow-x: hidden; /* Prevent horizontal scroll from animations */
            position: relative;
        }

        /* Basic container for content */
        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
            background-color: #161b22; /* Slightly lighter than body for contrast */
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 255, 159, 0.2); /* Neon glow */
            position: relative;
            z-index: 10; /* Ensure content is above background effects */
        }

        h1, h2, h3, h4, h5, h6 {
            color: #00ff9f; /* Highlight color */
            text-align: center;
            font-family: 'Share Tech Mono', monospace;
            text-shadow: 0 0 8px rgba(0, 255, 159, 0.5); /* Subtle text glow */
        }

        p {
            text-align: center;
        }

        hr {
            border: none;
            border-top: 1px dashed #30363d;
            margin: 40px 0;
        }

        /* Terminal-like code blocks */
        pre {
            background-color: #010409;
            border: 1px solid #30363d;
            border-left: 5px solid #00ff9f;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
            font-family: 'Share Tech Mono', monospace;
            white-space: pre-wrap; /* Wrap long lines */
        }

        pre code {
            display: block; /* Ensures typing effect works per line */
            min-height: 1em; /* Prevent collapse during typing */
        }

        /* Animated typing cursor */
        .typing::after {
            content: '|';
            animation: blink 0.7s infinite;
        }

        @keyframes blink {
            0%, 100% { opacity: 1; }
            50% { opacity: 0; }
        }

        /* Hover effects for images/icons */
        img, .badge {
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }

        img:hover, .badge:hover {
            transform: translateY(-5px) scale(1.05);
            box-shadow: 0 5px 20px rgba(0, 255, 159, 0.6);
            cursor: pointer;
        }

        /* Connect links - badges */
        .connect-links a {
            display: inline-block;
            margin: 5px;
        }

        /* Particle background - Conceptual, needs library for true effect */
        .background-particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none; /* Allows clicks through particles */
            z-index: 1;
            /* Placeholder for actual particle JS library (e.g., particles.js, tsParticles) */
            /* You'd initialize particles.js here if using it */
            /* background: radial-gradient(circle at center, rgba(0,255,159,0.05) 0%, transparent 70%); */
        }

        /* Glitch effect for text - Simple CSS example */
        .glitch-text {
            animation: glitch 1.5s infinite alternate;
            position: relative;
        }

        @keyframes glitch {
            0% { text-shadow: 2px 0 #00ff9f, -2px 0 #ff0077; transform: translateX(0); }
            25% { text-shadow: -2px 0 #00ff9f, 2px 0 #ff0077; transform: translateX(2px); }
            50% { text-shadow: 2px 0 #00ff9f, -2px 0 #ff0077; transform: translateX(-2px); }
            75% { text-shadow: -2px 0 #00ff9f, 2px 0 #ff0077; transform: translateX(0); }
            100% { text-shadow: 2px 0 #00ff9f, -2px 0 #ff0077; transform: translateX(0); }
        }

        /* Small pulsating animation for core items */
        .core-pulsate {
            animation: pulsate 1.5s infinite alternate;
        }

        @keyframes pulsate {
            0% { transform: scale(1); opacity: 1; }
            100% { transform: scale(1.02); opacity: 0.9; }
        }
    </style>
</head>
<body>
    <div class="background-particles"></div>

    <div class="container">
        <h1 align="center">
            <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&pause=1000&center=true&vCenter=true&width=435&lines=Hi%2C+I'm+Cheptoyek+Bill!;Software+Engineer+%7C+Technologist+%7C+Visionary;Building+Impactful+Platforms+for+Africa" alt="Typing SVG" />
        </h1>

        <p align="center">
            <img src="https://komarev.com/ghpvc/?username=bill-cheptoyek&label=Terminal%20Scans&color=00ff9f&style=flat-square" alt="Profile Views"/>
        </p>

        ---

        <h2 class="glitch-text">🧠 Booting Developer Mode...</h2>

        <pre><code id="booting-sequence"></code></pre>

        <p>
            <strong>IDENTITY</strong>: <span class="core-pulsate">Cheptoyek Bill</span><br>
            <strong>ORIGIN</strong>: Uganda<br>
            <strong>STACK</strong>: Full-Stack Dev / AI / Systems Design<br>
            <strong>CORE</strong>: <span class="core-pulsate">`Node.js ⚙️ + React.js ⚛️`</span><br>
            <strong>MISSION</strong>: Build next-gen platforms solving real-world African challenges
        </p>

        ---

        <h2>🎓 Education</h2>

        <pre><code id="education-command"></code></pre>

        <p>
            🎓 <strong>Bachelor of Science in Software Engineering</strong><br>
            📍 Makerere University, Uganda
        </p>

        ---

        <h2>⚙️ Tech Stack Core</h2>

        <pre><code id="tech-stack-command"></code></pre>

        <ul>
            <li>⚛️ <strong>React.js</strong> – Interactive & modular UIs</li>
            <li>🟢 <strong>Node.js</strong> – API-first backend, async power</li>
            <li>🐍 Python (Django / DRF)</li>
            <li>🌱 Vue.js</li>
            <li>🔥 Laravel</li>
            <li>📱 Android (Java/Kotlin)</li>
            <li>🐳 Docker</li>
            <li>🛢️ PostgreSQL / MySQL</li>
            <li>📊 Machine Learning · Jupyter · Transformers</li>
        </ul>

        ---

        <h2>🚦 Real-Time System Stats</h2>

        <p align="center">
            <img src="https://github-readme-stats.vercel.app/api?username=bill-cheptoyek&show_icons=true&theme=tokyonight" height="180" alt="GitHub Stats" />
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=bill-cheptoyek&theme=tokyonight" height="180" alt="GitHub Streak Stats" />
        </p>

        ---

        <h2>📊 Code Language Usage</h2>

        <p align="center">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bill-cheptoyek&layout=compact&theme=tokyonight" height="150" alt="Top Languages"/>
        </p>

        ---

        <h2>📡 Contribution Pulse</h2>

        <p align="center">
            <img src="https://github-readme-activity-graph.vercel.app/graph?username=bill-cheptoyek&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" />
        </p>

        ---

        <h2>🧰 Tools & Frameworks I Use</h2>

        <p align="center">
            <img src="https://skillicons.dev/icons?i=nodejs,react,python,js,java,vue,laravel,docker,git,github,vscode,androidstudio,postgres,mysql,jupyter" alt="Tools & Frameworks" />
        </p>

        ---

        <h2>🔌 Let’s Connect</h2>

        <p align="center" class="connect-links">
            <a href="https://www.linkedin.com/in/cheptoyekbill1" target="_blank" class="badge">
                <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
            </a>
            <a href="https://stackoverflow.com/users/yourprofile" target="_blank" class="badge">
                <img src="https://img.shields.io/badge/StackOverflow-F58025?style=for-the-badge&logo=stack-overflow&logoColor=white" alt="Stack Overflow"/>
            </a>
            <a href="https://www.kaggle.com/cheptoyekbill" target="_blank" class="badge">
                <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"/>
            </a>
            <a href="https://twitter.com/trojan__bill" target="_blank" class="badge">
                <img src="https://img.shields.io/badge/Twitter-14171A?style=for-the-badge&logo=twitter&logoColor=1DA1F2" alt="Twitter"/>
            </a>
        </p>

        ---

        <h2>🎯 About Me</h2>

        <pre><code id="about-me-command"></code></pre>

        <p>
            💡 I’m <strong>Cheptoyek Bill</strong>, a software engineer passionate about scalable solutions, clean code, and using tech to create <strong>equity, opportunity, and sustainability</strong>. I believe in building for <strong>impact</strong>, not hype.
        </p>

        <p>
            <strong>Current Explorations</strong>:<br>
            - 🧠 LLMs for education & finance<br>
            - 💸 School wallets to replace physical cash<br>
            - ⚡ Smart dashboards for public infrastructure<br>
            - 📡 Offline-first mobile apps for remote areas
        </p>

        ---

        <h2>🎥 Fun Fact</h2>

        <blockquote>
            “Some build for users. I build for <em>generations</em>.”
        </blockquote>

        <p>
            When I’m not coding, I’m prototyping wild ideas, lifting tech for Africa’s future, or listening to lo-fi beats while writing code that feels like poetry.
        </p>

        ---

        <h2>📫 Ping Me</h2>

        <pre><code id="ping-me-command"></code></pre>

        <p>
            📧 <a href="mailto:billcheptoyek60@gmail.com">billcheptoyek60@gmail.com</a><br>
            🌐 <a href="https://bill-cheptoyek.github.io/CHEPTOYEK-BILL/#home" target="_blank">My Portfolio</a>
        </p>

        <pre><code id="shutdown-command"></code></pre>
    </div>

    <script>
        // JavaScript for typing effects and more interactivity
        const typeEffect = (elementId, textArray, delay = 50, lineDelay = 1000) => {
            const element = document.getElementById(elementId);
            if (!element) return;

            let lineIndex = 0;
            let charIndex = 0;
            let isTyping = true;

            const typeLine = () => {
                if (lineIndex < textArray.length) {
                    const currentLine = textArray[lineIndex];
                    if (charIndex < currentLine.length) {
                        element.innerHTML += currentLine.charAt(charIndex);
                        charIndex++;
                        setTimeout(typeLine, delay);
                    } else {
                        element.classList.remove('typing');
                        lineIndex++;
                        charIndex = 0;
                        if (lineIndex < textArray.length) {
                            setTimeout(() => {
                                element.innerHTML += '\n'; // Add newline for next line
                                element.classList.add('typing');
                                typeLine();
                            }, lineDelay);
                        }
                    }
                }
            };

            element.classList.add('typing');
            typeLine();
        };

        // Booting sequence
        const bootingLines = [
            "> Initializing system...",
            "> Loading modules... &#9608;&#9608;&#9608;&#9608;&#9608;&#9608;&#9608;&#9608;&#9608;&#9608; 100%",
            "> Connecting to Africa.dev.network &#9989;",
            "> Authenticating... &#9989;"
        ];
        typeEffect('booting-sequence', bootingLines, 50, 500); // Faster typing, shorter line delay

        // Education command
        setTimeout(() => {
            typeEffect('education-command', ["> cat /education/degree.md"], 70);
        }, 3000); // Start after booting

        // Tech Stack command
        setTimeout(() => {
            typeEffect('tech-stack-command', ["> npm start system-engine", "> build success &#9881; React.js + Node.js active..."], 60, 500);
        }, 6000); // Start after education

        // About Me command
        setTimeout(() => {
            typeEffect('about-me-command', ["> nano /home/bill/mission.txt"], 70);
        }, 9000); // Start after tech stack

        // Ping Me command
        setTimeout(() => {
            typeEffect('ping-me-command', ["> echo \"billcheptoyek60@gmail.com\" | mail dev@africa --subject \"Let's Build Something\""], 70);
        }, 12000); // Start after about me

        // Shutdown command
        setTimeout(() => {
            typeEffect('shutdown-command', ["> shutdown -h now", "Session closed &#129504;"], 80, 500);
        }, 15000); // Start after ping me

        // Optional: Simple particle effect (conceptual, for complex you'd use a lib)
        // This is a very basic CSS-only attempt to show dots
        // For actual particle animations, libraries like particles.js are recommended.
        const createParticle = () => {
            const particle = document.createElement('div');
            particle.className = 'particle';
            document.body.appendChild(particle);

            const size = Math.random() * 3 + 1; // 1 to 4px
            particle.style.width = `${size}px`;
            particle.style.height = `${size}px`;
            particle.style.background = `rgba(0, 255, 159, ${Math.random() * 0.7 + 0.3})`;
            particle.style.borderRadius = '50%';
            particle.style.position = 'fixed';
            particle.style.zIndex = '1';
            particle.style.left = `${Math.random() * 100}vw`;
            particle.style.top = `${Math.random() * 100}vh`;
            particle.style.opacity = '0';
            particle.style.animation = `floatUp ${Math.random() * 10 + 5}s infinite ease-out, fadeInOut ${Math.random() * 5 + 2}s infinite ease-in-out`;

            const floatUpKeyframes = `
                @keyframes floatUp {
                    0% { transform: translateY(0); opacity: 0; }
                    50% { opacity: 1; }
                    100% { transform: translateY(-100vh); opacity: 0; }
                }
            `;
            const fadeInOutKeyframes = `
                @keyframes fadeInOut {
                    0%, 100% { opacity: 0; }
                    50% { opacity: 1; }
                }
            `;

            // Append keyframes to a style tag if not already present
            if (!document.querySelector('#particle-keyframes')) {
                const styleTag = document.createElement('style');
                styleTag.id = 'particle-keyframes';
                styleTag.innerHTML = floatUpKeyframes + fadeInOutKeyframes;
                document.head.appendChild(styleTag);
            }

            setTimeout(() => {
                particle.remove(); // Clean up particles after they animate off-screen
            }, (Math.random() * 10 + 5) * 1000); // Match animation duration
        };

        // Create a few particles initially and then periodically
        for (let i = 0; i < 20; i++) {
            createParticle();
        }
        setInterval(createParticle, 500); // Create a new particle every 0.5 seconds
    </script>
</body>
</html>
