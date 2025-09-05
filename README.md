<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>Francis Kasimba Mwendwa — Professional Portfolio</title>
    <meta name="description" content="Portfolio of Francis Kasimba Mwendwa — Software developer, product builder, Firebase & web specialist." />
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">

    <style>
         :root {
            --bg: #f5f7fb;
            --card: #ffffff;
            --accent: #0d47a1;
            --muted: #6b7280;
            --glass: rgba(255, 255, 255, 0.7);
            --success: #16a34a;
        }
        
        * {
            box-sizing: border-box
        }
        
        html,
        body {
            height: 100%;
            margin: 0;
            font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial;
            color: #0f172a;
            background: linear-gradient(180deg, var(--bg), #e9eef8)
        }
        
        .container {
            max-width: 1100px;
            margin: 36px auto;
            padding: 28px
        }
        
        .header {
            display: flex;
            gap: 20px;
            align-items: center
        }
        
        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 16px;
            background: linear-gradient(135deg, #cfe7ff, #e6f1ff);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 700;
            color: var(--accent);
            font-size: 22px;
            box-shadow: 0 8px 30px rgba(13, 71, 161, 0.12)
        }
        
        .name-block {
            flex: 1
        }
        
        h1 {
            margin: 0;
            font-size: 28px;
            letter-spacing: -0.4px
        }
        
        .lead {
            margin: 6px 0 0;
            color: var(--muted)
        }
        
        .cta-row {
            display: flex;
            gap: 10px;
            margin-top: 14px
        }
        
        .btn {
            background: var(--accent);
            color: white;
            padding: 10px 14px;
            border-radius: 10px;
            border: none;
            cursor: pointer;
            font-weight: 600;
            box-shadow: 0 6px 18px rgba(13, 71, 161, 0.12)
        }
        
        .btn.secondary {
            background: #fff;
            color: var(--accent);
            border: 1px solid #e1e7f2
        }
        
        .grid {
            display: grid;
            grid-template-columns: 1fr 360px;
            gap: 28px;
            margin-top: 28px
        }
        
        .main {
            background: var(--card);
            padding: 20px;
            border-radius: 14px;
            box-shadow: 0 10px 40px rgba(12, 34, 64, 0.06)
        }
        
        .aside {
            position: sticky;
            top: 28px;
            height: fit-content;
            background: var(--card);
            padding: 18px;
            border-radius: 12px;
            box-shadow: 0 10px 40px rgba(12, 34, 64, 0.04)
        }
        
        .section {
            margin-bottom: 20px
        }
        
        .section h2 {
            margin: 0 0 12px;
            font-size: 18px
        }
        
        .profile p {
            margin: 0;
            color: var(--muted);
            line-height: 1.6
        }
        
        .row {
            display: flex;
            gap: 12px;
            align-items: center
        }
        
        .kv {
            display: flex;
            flex-direction: column
        }
        
        .kv strong {
            font-size: 14px
        }
        
        .kv span {
            color: var(--muted);
            font-size: 13px
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px
        }
        
        .skill {
            background: #f1f7ff;
            padding: 8px 10px;
            border-radius: 8px;
            color: var(--accent);
            font-weight: 600;
            font-size: 13px
        }
        
        .card {
            background: linear-gradient(180deg, #fff, #fbfdff);
            padding: 14px;
            border-radius: 10px;
            border: 1px solid #f0f5ff
        }
        
        .experience .item {
            margin-bottom: 12px
        }
        
        .item h3 {
            margin: 0;
            font-size: 15px
        }
        
        .item .meta {
            color: var(--muted);
            font-size: 13px;
            margin-top: 4px
        }
        
        .project {
            border-radius: 10px;
            padding: 12px;
            border: 1px solid #eef6ff;
            margin-bottom: 12px
        }
        
        .project h4 {
            margin: 0
        }
        
        .project p {
            margin: 8px 0 0;
            color: var(--muted)
        }
        
        .contact-row {
            display: flex;
            flex-direction: column;
            gap: 8px
        }
        
        .contact-row input,
        .contact-row textarea {
            padding: 10px;
            border-radius: 8px;
            border: 1px solid #e6eef9;
            font-size: 14px;
            width: 100%
        }
        
        .footer {
            margin-top: 24px;
            color: var(--muted);
            font-size: 13px;
            text-align: center
        }
        
        .tag {
            display: inline-block;
            background: #f0f8ff;
            color: var(--accent);
            padding: 6px 8px;
            border-radius: 8px;
            font-weight: 600;
            font-size: 13px
        }
        
        .print-hide {
            display: inline-block
        }
        
        @media(print) {
            .btn,
            .nav,
            .print-hide {
                display: none!important
            }
            body {
                background: #fff
            }
            .container {
                max-width: 100%;
                margin: 0;
                padding: 0
            }
        }
        
        @media(max-width:900px) {
            .grid {
                grid-template-columns: 1fr;
            }
            .header {
                flex-direction: row-align
            }
            .avatar {
                width: 96px;
                height: 96px
            }
        }
    </style>
</head>

<body>
    <div class="container" id="page">
        <header class="header">
            <div class="avatar" id="avatar">FK</div>
            <div class="name-block">
                <h1>Francis Kasimba Mwendwa</h1>
                <div class="lead">Software Engineer • Web & Firebase Specialist • Product Builder</div>
                <div class="cta-row">
                    <button class="btn" id="downloadResumeBtn">Download Resume</button>
                    <a class="btn secondary" href="mailto:kasiifrancis305@gmail.com">Contact</a>
                </div>
            </div>
        </header>

        <div class="grid">
            <!-- MAIN -->
            <main class="main">
                <section class="section profile">
                    <h2>About</h2>
                    <p>I’m Francis — a results-driven software engineer who builds delightful, reliable web products. I specialise in modern JavaScript, Firebase (RTDB / Firestore / Auth / Storage), and scalable front-end interfaces. I enjoy turning ideas
                        into user-centric features and shipping quality software fast.</p>
                </section>

                <section class="section">
                    <h2>Experience</h2>
                    <div class="experience">
                        <div class="item card">
                            <h3>Full Stack Developer — Visionary Youth Group</h3>
                            <div class="meta">2023 — Present • Nairobi, Kenya</div>
                            <p class="muted">Built member dashboards, loan application flows and real-time features using Firebase Realtime Database and Modern JS. Improved data flows, fixed authentication and delivered admin interfaces for financial operations.</p>
                            <ul>
                                <li>Designed and implemented robust RTDB structures for member financials and loan processing.</li>
                                <li>Implemented role-based authentication & admin panels.</li>
                                <li>Optimised front-end interactions — responsive, accessible and performance-conscious.</li>
                            </ul>
                        </div>

                        <div class="item card">
                            <h3>Frontend Engineer — Freelance</h3>
                            <div class="meta">2020 — 2023 • Remote</div>
                            <p class="muted">Built web apps, dashboards and landing pages for SMEs using React, vanilla JS and Tailwind. Focused on UI/UX and business outcomes.</p>
                        </div>
                    </div>
                </section>

                <section class="section">
                    <h2>Projects</h2>

                    <div class="project">
                        <h4>Visionary Youth Dashboard</h4>
                        <div class="meta">Web app • Firebase RTDB • Auth • Storage</div>
                        <p>Full member and admin dashboard with real-time updates, loan management, file uploads and CSV export. Built secure role-based routing and a friendly UX for non-technical users.</p>
                        <div style="margin-top:8px"><span class="tag">Realtime</span> <span class="tag">Firebase</span> <span class="tag">UX</span></div>
                    </div>

                    <div class="project">
                        <h4>Payment Tracking System</h4>
                        <div class="meta">Web app • SQL + JS</div>
                        <p>Designed a payment tracking and reporting tool for small groups with Excel export and automated reminders.</p>
                    </div>

                    <div class="project">
                        <h4>Membership Portal (Prototype)</h4>
                        <div class="meta">React • Node • Firebase</div>
                        <p>Prototype membership portal with onboarding, profile management and secure file uploads. Focused on accessibility and mobile-first design.</p>
                    </div>
                </section>

                <section class="section">
                    <h2>Education</h2>
                    <div class="card">
                        <strong>Bachelor of Science — Computer Science</strong><br>
                        <span class="muted">University (example) • 2016 — 2020</span>
                    </div>
                </section>

                <section class="section">
                    <h2>Testimonials</h2>
                    <div class="card">
                        <blockquote style="margin:0;padding:0 10px;color:#253151">
                            “Francis delivered a polished dashboard under tight deadlines. Clear communicator and reliable developer.” — <em>Project Manager</em>
                        </blockquote>
                    </div>
                </section>
            </main>

            <!-- ASIDE -->
            <aside class="aside">
                <div class="section">
                    <h2>Contact</h2>
                    <p style="margin:6px 0;color:var(--muted)">kasiifrancis305@gmail.com<br>+254 • Nairobi, Kenya</p>
                    <div style="margin-top:8px">
                        <a href="https://www.linkedin.com/in/your-linkedin" target="_blank" style="text-decoration:none;color:var(--accent)">LinkedIn</a> •
                        <a href="https://github.com/your-github" target="_blank" style="text-decoration:none;color:var(--accent)">GitHub</a>
                    </div>
                </div>

                <div class="section">
                    <h2>Skills</h2>
                    <div class="skills">
                        <div class="skill">JavaScript</div>
                        <div class="skill">Firebase</div>
                        <div class="skill">HTML & CSS</div>
                        <div class="skill">React</div>
                        <div class="skill">Node.js</div>
                        <div class="skill">SQL</div>
                        <div class="skill">UX Design</div>
                        <div class="skill">Product Thinking</div>
                    </div>
                </div>

                <div class="section">
                    <h2>Quick Facts</h2>
                    <div class="kv"><strong>Availability</strong><span class="muted">Open to freelance & full-time</span></div>
                    <div class="kv" style="margin-top:8px"><strong>Languages</strong><span class="muted">English, Swahili</span></div>
                </div>

                <div class="section">
                    <h2>Download</h2>
                    <button class="btn" id="downloadResumeBtnAside">Download Resume</button>
                </div>
            </aside>
        </div>

        <footer class="footer">
            © <span id="year"></span> Francis Kasimba Mwendwa — Built with care.
        </footer>
    </div>

    <script>
        // Populate year
        document.getElementById('year').textContent = new Date().getFullYear();

        // Resume generator (simple, editable)
        const resumeText = `Francis Kasimba Mwendwa
Email: kasiifrancis305@gmail.com
Location: Nairobi, Kenya

Profile
A results-driven software engineer specializing in web development and Firebase-powered applications. Strong background in building member dashboards, real-time systems, and admin tools.

Experience
Visionary Youth Group — Full Stack Developer (2023–Present)
- Built member and admin dashboards using Firebase RTDB and Auth.
- Implemented loan application workflows, CSV exports and file storage.

Freelance — Frontend Engineer (2020–2023)
- Built web apps, landing pages and small-scale SaaS prototypes.
- Focus on UX, performance and maintainability.

Education
B.Sc. Computer Science — University (example) (2016–2020)

Skills
JavaScript, Firebase (RTDB/Firestore/Auth/Storage), React, Node.js, HTML/CSS, SQL, UI/UX, Product Thinking

Contact
Email: kasiifrancis305@gmail.com
GitHub: https://github.com/your-github
LinkedIn: https://www.linkedin.com/in/your-linkedin
`;

        function downloadResume() {
            const blob = new Blob([resumeText], {
                type: 'text/plain'
            });
            const a = document.createElement('a');
            a.href = URL.createObjectURL(blob);
            a.download = 'Francis_Kasimba_Mwendwa_Resume.txt';
            a.click();
            URL.revokeObjectURL(a.href);
        }

        // wire both buttons
        document.getElementById('downloadResumeBtn').addEventListener('click', downloadResume);
        document.getElementById('downloadResumeBtnAside').addEventListener('click', downloadResume);

        // Optional: clicking avatar opens file picker to replace image (local preview)
        document.getElementById('avatar').addEventListener('click', () => {
            const input = document.createElement('input');
            input.type = 'file';
            input.accept = 'image/*';
            input.onchange = (e) => {
                const file = e.target.files[0];
                if (!file) return;
                const reader = new FileReader();
                reader.onload = () => {
                    document.getElementById('avatar').style.backgroundImage = `url(${reader.result})`;
                    document.getElementById('avatar').textContent = '';
                };
                reader.readAsDataURL(file);
            };
            input.click();
        });
    </script>
</body>

</html>
