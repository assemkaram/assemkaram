Claude
Created a file, shared files
I made the workflow file that generates your green contribution snake. The README already points to the images it creates, so you only need to set it up once:

In your profile repo (assemkaram/assemkaram), add this file at .github/workflows/snake.yml.
Go to Settings → Actions → General → Workflow permissions, choose Read and write permissions, and save.
Go to the Actions tab, open Generate Snake, and click Run workflow. After about a minute it creates an output branch with the two SVG files.
After that it updates itself every day and on each push to main. The snake and the contribution squares use your 
#39D98A green, with a darker green version for light mode.

If your default branch is master instead of main, change that name in the push section of the file.

Snake
YML
1794067016133_image.png
the broken images

Ran a command, shared files
The two broken images were the github-readme-stats.vercel.app cards (the stats card and the top languages card). That free public server often gets rate-limited or goes down, and you can’t fix it from your side. The profile-details card below them loads fine in your screenshot, so I replaced the two broken ones with cards from the same working service (github-profile-summary-cards):

Stats card: shows your stars, commits, PRs and issues.
Most commit language card: replaces the top languages card.
Copy the updated README.md into your profile repo and refresh. These cards use GitHub’s dark theme, so they won’t be green like the rest of the page. The service has no custom colors, but it does have other themes you can try by changing theme=github_dark in the URL.

If you want green stat cards, the reliable way is to deploy your own copy of github-readme-stats on Vercel (a free account is enough). Tell me if you want the steps.

Readme
Document
·MD
1794067116983_image.png
contribution activity graph

Ran a command, shared files
The activity graph was broken for the same reason as the stats cards: it came from github-readme-activity-graph.vercel.app, another free public server that is often down. I replaced it with a green contribution calendar from ghchart.rshah.org, which is much more stable and takes its color straight from the URL (39D98A). The streak card below it already loads fine in your screenshot, so I left it alone.

Copy the updated README.md into your profile repo and refresh. The calendar’s empty days show as light gray, which is slightly brighter than the dark background. The calendar will look a bit empty at first because your account has only a few contributions so far, and it fills in as you commit.

Readme
Document
·MD
1794067231170_image.png
delete this only

Ran a command, shared files
I removed the contribution calendar, and nothing else changed. The Contribution Activity section now has just the streak stats card and the snake animation. Copy the updated README.md into your profile repo to apply it.

Readme
Document
·MD



Claude is AI and can make mistakes. Please double-check responses.


Readme · MD
<div align="center"> <img src="https://capsule-render.vercel.app/api?type=venom&color=0:0b2e1f,50:1f7a4d,100:39D98A&height=260&section=header&text=Assem%20Karam&fontSize=65&fontColor=0A0A0A&animation=fadeIn&fontAlignY=40&desc=Front-End%20Developer%20%7C%20React%20Developer&descSize=18&descAlignY=62&descColor=e9f7ef" width="100%" /> <br/> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=39D98A&center=true&vCenter=true&width=650&lines=Front-End+Developer;Building+Modern+Web+Interfaces;Exploring+React+and+Tailwind+CSS;Always+Learning+and+Improving" alt="Typing SVG" />
<br/><br/>

<a href="https://github.com/assemkaram/portfolio"> <img src="https://img.shields.io/badge/Portfolio-Visit%20Website-39D98A?style=for-the-badge&logo=googlechrome&logoColor=white" /> </a> <a href="https://www.linkedin.com/in/assemkaram"> <img src="https://img.shields.io/badge/LinkedIn-Connect-1f7a4d?style=for-the-badge&logo=linkedin&logoColor=white" /> </a> <a href="https://github.com/assemkaram"> <img src="https://img.shields.io/badge/GitHub-Follow-0b2e1f?style=for-the-badge&logo=github&logoColor=white" /> </a>
<br/><br/>

<img src="https://komarev.com/ghpvc/?username=assemkaram&label=Profile%20Views&color=39D98A&style=for-the-badge" /> </div>
👨‍💻 About Me
I'm Assem Karam, a Computer Science student and Front-End Developer passionate about building modern, responsive, and user-friendly web applications.

💻 Focused on Front-End Development.
⚛️ Currently exploring React and modern web technologies.
🎨 Interested in UI implementation and responsive design.
🚀 Building practical projects to improve my development skills.
🤝 Open to freelance projects, internships, and collaboration.
🌱 Always learning and improving.
javascript
const assem = {
  name: "Assem Karam",
  role: "Front-End Developer",
  location: "Egypt",
  education: "Computer Science & AI",
  skills: [
    "HTML",
    "CSS",
    "JavaScript",
    "Bootstrap",
    "Tailwind CSS",
    "React"
  ],
  tools: ["Git", "GitHub", "VS Code"],
  currentlyLearning: ["React", "Advanced JavaScript"],
  goal: "Build meaningful digital experiences"
};
🛠️ Tech Stack
<div align="center">
Frontend Development
<img src="https://skillicons.dev/icons?i=html,css,js,react,bootstrap,tailwind" />
Tools & Workflow
<img src="https://skillicons.dev/icons?i=git,github,vscode" /> </div>
Category	Technologies
Languages	HTML5, CSS3, JavaScript
Frontend	React, Bootstrap, Tailwind CSS
Concepts	Responsive Design, UI Implementation, API Integration
Tools	Git, GitHub, VS Code
🚀 Featured Projects
<div align="center"> <table> <tr> <td width="50%" valign="top">
📋 TaskFlow
A productivity management application for organizing tasks and daily activities.

Highlights:

Task management and dashboard
Multiple views and task filters
Focus mode and productivity features
Live Demo

</td> <td width="50%" valign="top">
💱 Flux FX
A currency converter application with real-time exchange rates.

Highlights:

Currency conversion
API integration
Responsive interface
Live Demo

</td> </tr> <tr> <td width="50%" valign="top">
💬 First Chat
A responsive web project built using HTML, CSS, JavaScript, and Bootstrap.

Highlights:

Responsive chat-style interface
Built with Bootstrap
Live Demo

</td> <td width="50%" valign="top">
✅ To-Do App
A JavaScript task management application.

Highlights:

Add and manage daily tasks
Built with vanilla JavaScript
Live Demo

</td> </tr> <tr> <td width="50%" valign="top">
🎲 Random Quotes
A simple application that displays random quotes.

Highlights:

Random quote generator
Clean, minimal interface
Live Demo

</td> <td width="50%" valign="top"> </td> </tr> </table> </div>
📈 Contribution Activity
<div align="center">
<img src="https://streak-stats.demolab.com?user=assemkaram&theme=dark&hide_border=true&background=0b2e1f&ring=39D98A&fire=39D98A&currStreakLabel=39D98A" width="70%" alt="GitHub Streak Stats" />

<br/><br/>

<img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/assemkaram/assemkaram/output/github-contribution-grid-snake-dark.svg" width="100%" />

</div>
📊 GitHub Statistics
<div align="center"> <img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=assemkaram&theme=github_dark" /> <img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=assemkaram&theme=github_dark" />
<br/><br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=assemkaram&theme=github_dark" width="95%" /> </div>
🎓 Education & Learning
Fayoum University — Faculty of Computers and Artificial Intelligence.
NTI — Web Design Training.
DEPI — Front-End React Development.
Rowad Misr — React Development & Soft Skills.
🌐 Connect With Me
<div align="center"> <a href="https://github.com/assemkaram/portfolio"> <img src="https://img.shields.io/badge/Portfolio-39D98A?style=for-the-badge&logo=googlechrome&logoColor=white" /> </a> <a href="https://www.linkedin.com/in/assemkaram"> <img src="https://img.shields.io/badge/LinkedIn-1f7a4d?style=for-the-badge&logo=linkedin&logoColor=white" /> </a> <a href="https://github.com/assemkaram"> <img src="https://img.shields.io/badge/GitHub-0b2e1f?style=for-the-badge&logo=github&logoColor=white" /> </a> </div>
<div align="center">
✨ Thanks for visiting my profile!
Always learning, building, and improving.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b2e1f,50:1f7a4d,100:39D98A&height=120&section=footer" width="100%" /> </div>





Claude finished the response
