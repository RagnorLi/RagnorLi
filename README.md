<div align="center">

<div align="center">
  <svg width="400" height="400" viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg">
    <!-- 背景 -->
    <rect width="400" height="400" fill="#0A0A0A"/>
    
    <!-- Logo文字 - 移到上面确保可见性 -->
    <g id="logo-text">
        <text x="200" y="60" 
              font-family="Arial" 
              font-size="36" 
              fill="#ffffff" 
              font-weight="bold"
              text-anchor="middle">
            Tech<tspan fill="#4CAF50">Genesis</tspan>
        </text>
        
        <!-- 标语 - 调整位置确保清晰可见 -->
        <text x="200" y="95" 
              font-family="Arial" 
              font-size="14" 
              fill="#ffffff" 
              opacity="0.7"
              text-anchor="middle">
            From Fundamental to Future
        </text>
    </g>
    
    <!-- 原子结构 - 整体缩小并下移 -->
    <g id="atom-structure" transform="translate(200, 220) scale(0.85)">
        <!-- 外层电子轨道 -->
        <g id="outer-orbit">
            <ellipse cx="0" cy="0" 
                     rx="150" ry="50" 
                     fill="none" 
                     stroke="#4CAF50" 
                     stroke-width="2"
                     transform="rotate(0)">
                <animateTransform
                    attributeName="transform"
                    type="rotate"
                    from="0"
                    to="360"
                    dur="8s"
                    repeatCount="indefinite"/>
            </ellipse>
            <!-- 电子 -->
            <circle r="4" fill="#4CAF50">
                <animateMotion
                    path="M 150,0 A 150,50 0 1,1 150,0"
                    dur="8s"
                    repeatCount="indefinite"/>
            </circle>
        </g>

        <!-- 中层电子轨道 -->
        <g id="middle-orbit">
            <ellipse cx="0" cy="0" 
                     rx="120" ry="120" 
                     fill="none" 
                     stroke="#03A9F4" 
                     stroke-width="2"
                     transform="rotate(60)">
                <animateTransform
                    attributeName="transform"
                    type="rotate"
                    from="60"
                    to="420"
                    dur="6s"
                    repeatCount="indefinite"/>
            </ellipse>
            <!-- 电子 -->
            <circle r="4" fill="#03A9F4">
                <animateMotion
                    path="M 120,0 A 120,120 0 1,1 120,0"
                    dur="6s"
                    repeatCount="indefinite"/>
            </circle>
        </g>

        <!-- 内层电子轨道 -->
        <g id="inner-orbit">
            <ellipse cx="0" cy="0" 
                     rx="80" ry="30" 
                     fill="none" 
                     stroke="#FFC107" 
                     stroke-width="2"
                     transform="rotate(120)">
                <animateTransform
                    attributeName="transform"
                    type="rotate"
                    from="120"
                    to="480"
                    dur="4s"
                    repeatCount="indefinite"/>
            </ellipse>
            <!-- 电子 -->
            <circle r="4" fill="#FFC107">
                <animateMotion
                    path="M 80,0 A 80,30 0 1,1 80,0"
                    dur="4s"
                    repeatCount="indefinite"/>
            </circle>
        </g>

        <!-- 原子核 -->
        <g id="nucleus">
            <circle cx="0" cy="0" r="20" fill="url(#nucleus-gradient)">
                <animate
                    attributeName="r"
                    values="20;22;20"
                    dur="2s"
                    repeatCount="indefinite"/>
            </circle>
            <!-- 核心光效 -->
            <circle cx="0" cy="0" r="15" fill="#ffffff" opacity="0.3">
                <animate
                    attributeName="opacity"
                    values="0.3;0.6;0.3"
                    dur="1s"
                    repeatCount="indefinite"/>
            </circle>
        </g>

        <!-- 连接线 -->
        <g id="connections" opacity="0.3">
            <line x1="-40" y1="-40" x2="40" y2="40" stroke="#ffffff" stroke-width="1"/>
            <line x1="-40" y1="40" x2="40" y2="-40" stroke="#ffffff" stroke-width="1"/>
        </g>
    </g>

    <!-- 渐变定义 -->
    <defs>
        <radialGradient id="nucleus-gradient">
            <stop offset="0%" stop-color="#ffffff"/>
            <stop offset="50%" stop-color="#FFC107"/>
            <stop offset="100%" stop-color="#FF5722"/>
        </radialGradient>
    </defs>

    <!-- 背景粒子 -->
    <g id="background-particles">
        <circle cx="50" cy="50" r="1" fill="#ffffff" opacity="0.2"/>
        <circle cx="350" cy="50" r="1" fill="#ffffff" opacity="0.2"/>
        <circle cx="50" cy="350" r="1" fill="#ffffff" opacity="0.2"/>
        <circle cx="350" cy="350" r="1" fill="#ffffff" opacity="0.2"/>
    </g>
  </svg>
</div>
  
# Hi there 👋 I'm RagnorLi

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](your_linkedin_url)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](your_twitter_url)
[![Blog](https://img.shields.io/badge/-Blog-FF4088?style=for-the-badge&logo=hugo&logoColor=white)](your_blog_url)

</div>

## 🚀 About Me
AI Engineer | Full Stack Developer | Open Source Enthusiast

🔭 Currently working on: Large Language Models & AI Systems
🌱 Learning: Latest in AI/ML and System Design
💬 Ask me about: AI, Python, System Architecture

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![vLLM](https://img.shields.io/badge/-vLLM-8A2BE2?style=flat-square&logoColor=white)
![llama.cpp](https://img.shields.io/badge/-llama.cpp-FF4154?style=flat-square&logoColor=white)


## 📊 GitHub Stats
<div align="center">
  <img height="180em" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=RagnorLi&show_icons=true&theme=dark&count_private=true&include_all_commits=true"/>
  <img height="180em" src="https://github-readme-stats.anuraghazra1.vercel.app/api/top-langs/?username=RagnorLi&layout=compact&theme=dark"/>
</div>

## 🎯 Latest Projects
- [Mathematics](https://github.com/RagnorLi/Mathematics) 

## 📫 How to reach me
- Email: ragnor.li@outlook.com
- WeChat: RagnorLi
- Blog: [RagnorLi's CoffeeAI](link)

---
<div align="center">
  
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=RagnorLi.RagnorLi)
![GitHub followers](https://img.shields.io/github/followers/RagnorLi?label=Follow&style=social)

</div>
