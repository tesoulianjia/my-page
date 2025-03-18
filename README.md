<!DOCTYPE html>  
<html lang="zh-CN">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>个人主页 - 张三</title>  
    <style>  
        * {  
            margin: 0;  
            padding: 0;  
            box-sizing: border-box;  
            font-family: 'Segoe UI', sans-serif;  
        }  

        body {  
            background-color: #f5f5f5;  
            line-height: 1.6;  
        }  

        header {  
            background-color: #2c3e50;  
            color: white;  
            text-align: center;  
            padding: 4rem 2rem;  
        }  

        nav {  
            background-color: #34495e;  
            padding: 1rem;  
            position: sticky;  
            top: 0;  
        }  

        nav a {  
            color: white;  
            text-decoration: none;  
            margin: 0 1.5rem;  
            transition: color 0.3s;  
        }  

        nav a:hover {  
            color: #3498db;  
        }  

        section {  
            padding: 3rem 2rem;  
            max-width: 1200px;  
            margin: 0 auto;  
        }  

        .project-card {  
            background: white;  
            padding: 1.5rem;  
            margin: 1rem 0;  
            border-radius: 8px;  
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);  
        }  

        footer {  
            background-color: #2c3e50;  
            color: white;  
            text-align: center;  
            padding: 2rem;  
            margin-top: 3rem;  
        }  
    </style>  
</head>  
<body>  
    <header>  
        <h1>张三</h1>  
        <p>全栈开发者 | 技术爱好者</p>  
    </header>  

    <nav>  
        <a href="#about">关于我</a>  
        <a href="#skills">技能</a>  
        <a href="#projects">项目</a>  
        <a href="#contact">联系</a>  
    </nav>  

    <section id="about">  
        <h2>自我介绍</h2>  
        <p>我是拥有3年开发经验的全栈开发者，擅长使用JavaScript和Python构建现代化Web应用。热爱技术创新和开源社区。</p>  
    </section>  

    <section id="skills">  
        <h2>技术技能</h2>  
        <ul>  
            <li>前端：HTML/CSS/JavaScript (React/Vue)</li>  
            <li>后端：Node.js/Python (Django/Flask)</li>  
            <li>数据库：MySQL/MongoDB</li>  
            <li>DevOps：Docker/AWS</li>  
        </ul>  
    </section>  

    <section id="projects">  
        <h2>项目展示</h2>  
        <div class="project-card">  
            <h3>在线教育平台</h3>  
            <p>基于React和Django构建的在线学习系统，支持课程管理和视频直播功能。</p>  
        </div>  
        <div class="project-card">  
            <h3>智能家居控制系统</h3>  
            <p>使用IoT技术和Node.js开发的智能家居管理平台。</p>  
        </div>  
    </section>  

    <section id="contact">  
        <h2>联系方式</h2>  
        <p>📧 <a href="mailto:zhangsan@example.com">zhangsan@example.com</a></p>  
        <p>📱 微信：zhangsan_dev</p>  
    </section>  

    <footer>  
        <p>© 2025 张三 - 保留所有权利</p>  
    </footer>  
</body>  
</html>  
