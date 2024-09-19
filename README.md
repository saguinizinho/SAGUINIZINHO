Skip to content
DEV Community
Search...
Powered by  Algolia
Log in
Create account

9
Jump to Comments
136
Save

Cover image for Creating an Engaging GitHub Profile: A Step-by-Step Guide
Zane
Zane
Posted on Jan 8 • Updated on Jan 15


66

2

3

3

4
Creating an Engaging GitHub Profile: A Step-by-Step Guide
#
tutorial
#
webdev
#
beginners
#
javascript
Crafting a GitHub profile that stands out requires a blend of technical showcase and personal branding. Here's how you can create a unique and engaging GitHub profile, inspired by dynamic and detailed examples.

1. Start with a Dynamic Header
Begin your profile with an eye-catching header. You can use a typing effect SVG to make an animated greeting:

GIFTerminal GH GIF

Code Snippet:
<div align="center">
    <h1>
        <img src="https://readme-typing-svg.herokuapp.com?font=Jetbrains+mono&size=40&duration=3000&color=33FF33&center=true&vCenter=true&width=435&lines=Hey..+I'm+[Your Name];This+is..;..my+Github..;" alt="Typing SVG"/>
    </h1>
</div>
2. Adding a Dynamic GIF
Add a dynamic GIF to your GitHub profile for a lively header:

GIFTerminal GH GIF
Choose or Create a GIF: Find a GIF that represents you or your work. It could be a cool animation related to coding, a snippet of your projects, or anything that adds personality to your profile.

Add the GIF to Your README: Use the following HTML snippet to embed the GIF into your profile README. Replace the src attribute with the URL of your chosen GIF.
<div align="center">
    <p>
        <img src="URL_OF_YOUR_GIF.gif" alt="Descriptive Text for the GIF" />
    </p>
</div>
This step will create an eye-catching header with your chosen GIF centered on your GitHub profile page, making it more engaging and visually appealing to visitors. Remember to ensure your GIF's size and content are appropriate and professional for your GitHub profile.

2. Introduce Yourself
Create a section about yourself, detailing your role, expertise, and a bit about your interests.

Image description

Code snippet:
<div align="center">
    <h2>🚀 About Me</h2>
    <p>I'm a [Your Job Title] specializing in [Your Specialization]. I enjoy [hobbies/interests].</p>
</div>
3. Enable Easy Connections
Use badges for linking to your LinkedIn, portfolio, or any other professional websites.

Image description

Code snippet:
<div align="center">
    <!-- Replace href with your links -->
    <a href="https://www.linkedin.com/in/[YourLinkedIn]/">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
</div>
4. Visualize Your Commit History
Add a GitHub contributions snake animation to visualize your daily activity.

GIFImage description

Code snippet:
<div align="center">
    <img src="https://raw.githubusercontent.com/[YourGitHub]/[YourGitHub]/output/github-contribution-grid-snake.svg" alt="GitHub Contribution Grid Snake Animation"/>
</div>
5. List Your Programming Languages
Showcase the languages you are proficient in with badges.

Image description

Code snippet:
<div align="center">
    <!-- Replace with your skills -->
    <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
    <!-- Add more badges similarly -->
</div>
6. Highlight Your Experience with Cloud Technologies
Detail your knowledge in cloud technologies with relevant badges.

Image description

Code snippet:
<div align="center">
    <!-- Replace with your cloud tech skills -->
    <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
    <!-- Add more badges similarly -->
</div>
7. Feature Your Framework Proficiency
Showcase the frameworks you're skilled at.

Image description

Code Snippet:
<div align="center">
    <!-- Replace with your framework skills -->
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
    <!-- Add more badges similarly -->
</div>
8. Showcase Your 3D Modeling, VR, and AR Expertise
Express your skills in the immersive technology space with a dedicated section for 3D Modeling, Virtual Reality, and Augmented Reality.

Image description

Code Snippet:
<div align="center">
    <h2 align="center" class="section-heading">👾 3D Modeling + VR + AR</h2>
    <p>In the immersive domains of 3D Modeling, Virtual Reality (VR), and Augmented Reality (AR), I apply my expertise to bring digital creations to life. Leveraging industry-leading tools, I sculpt, render, and animate with precision, while pioneering VR and AR experiences that bridge the gap between virtuality and reality.</p>
    <!-- Replace with your 3D/VR/AR skills -->
    <img src="https://img.shields.io/badge/Unreal_Engine-313131?style=for-the-badge&logo=unreal-engine&logoColor=white" alt="Unreal Engine"/>
    <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity"/>
    <!-- Add more badges similarly -->
</div>
By including this section, you highlight your ability to work with cutting-edge technology and create immersive digital experiences, showcasing a dynamic range of skills beyond traditional programming. Remember to replace placeholders and add or remove badges based on your specific skills and experiences.

9. Incorporate Stats and Visualizations
Include GitHub stats to provide a snapshot of your activity and contributions.

Image description

Code Snippet:
<div align="center">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=[YourGitHub]&theme=github_dark" alt="[Your Name]'s GitHub Stats"/>
</div>
10. Keep It Updated
Regularly revisit and update your profile as you acquire new skills, complete more projects, or want to refresh the look and content.

Conclusion
Your GitHub profile is the front page of your coding journey. With these steps and snippets, you can make it a dynamic, informative, and attractive space that effectively showcases your skills, projects, and personality.

My Complete GitHub Profile Code
Below is the full source code for creating a dynamic and engaging GitHub profile. This comprehensive code includes all the snippets and sections described earlier, allowing you to replicate or customize the profile setup for your own use. Remember to replace placeholders with your own information and feel free to add or remove sections as per your profile needs. My Github

<div align="center">
    <h1><img src="https://readme-typing-svg.herokuapp.com?font=Jetbrains+mono&size=40&duration=3000&color=33FF33&center=true&vCenter=true&width=435&lines=Hey..+I'm+Zane;This+is..;..my+Github..;" alt="Typing SVG"/></h1>
    <p><img src="termina-gh.gif" alt="Terminal GH GIF" /></p>
</div>

<div align="center">
    <h2>🚀 About Me</h2>
<!--     <p><img src="termina-gh.gif" alt="Terminal GH GIF" /></p> -->
    <p>I'm a Software Engineering specialist at Accenture with Aus/EU citizenship, specializing in fusing software development with operations. My technical range is broad, covering everything from cloud platforms and containerization to CRM systems and 3D modeling.</p>
</div>

<div align="center">
<h2 align="center" class="section-heading">🌐 Connect with Me</h2>
<p> To connect with me, you can find my professional profile and contact details on LinkedIn, or explore more about my projects and interests through my Linktree. Feel free to reach out for collaborations, opportunities, or just to exchange ideas about the latest in software development and technology. Let's innovate together! </p>
<div align="center">
  <a href="https://www.linkedin.com/in/zane-pearton">
    <img src="https://img.shields.io/badge/ZanePearton-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://linktr.ee/zanepearton">
    <img src="https://img.shields.io/badge/Linktree-39E09B?style=for-the-badge&logo=Linktree&logoColor=white" alt="Linktree"/>
  </a>
<a href="https://github.com/ZanePearton/ZanePearton" target="_blank">
    <img src="https://img.shields.io/badge/View%20on%20GitHub-%230077B5.svg?&style=for-the-badge&logo=github&logoColor=white" alt="GitHub Skyline"/>
</a>
<img src="https://komarev.com/ghpvc/?username=ZanePearton&style=for-the-badge" alt="Profile views" />
</div>

<div align="center">
  <h2>🚀 Github Commits</h2>
    <p>This section highlights my daily activity, showcasing the repositories I am currently working on. Each commit represents progress or fixes to ongoing projects, reflecting my commitment to continuous improvement and collaborative development. Dive into the commit messages for insights into what I've been up to!</p>
  <img src="https://raw.githubusercontent.com/zanepearton/zanepearton/output/github-contribution-grid-snake-dark.svg#gh-dark-mode-only" alt="GitHub Contribution Grid Snake Animation Dark Mode"/>
  <img src="https://raw.githubusercontent.com/zanepearton/zanepearton/output/github-contribution-grid-snake.svg#gh-light-mode-only" alt="GitHub Contribution Grid Snake Animation Light Mode"/>
</div>

<h2 align="center" class="section-heading">💻 Programming Languages</h2>
<p> As a multifaceted engineer, I've developed proficiency in a diverse set of programming languages, each serving as a pivotal tool in my development arsenal. Here are the languages I wield to turn complex problems into elegant solutions</p>
<div align="center">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white" alt="Swift"/>
  <img src="https://img.shields.io/badge/YAML-0A0A0A?style=for-the-badge" alt="YAML"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"/>

</div>
<h2 align="center" class="section-heading">☁️ Cloud Technologies</h2>
<p>In the dynamic realm of cloud computing, I am proficient in leveraging leading cloud platforms and technologies to architect, deploy, and manage scalable, highly available, and fault-tolerant systems. Here's a glance at the cloud technologies I specialize in:</p>
<div align="center">
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure"/>
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="GCP"/>
  <img src="https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins"/>
  <img src="https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Salesforce"/>
</div>

<h2 align="center" class="section-heading">🔧 Frameworks</h2>
<p>Frameworks are the backbone of my development process, providing the structure and tools necessary for building scalable, efficient applications. My expertise spans a broad spectrum of frameworks, each chosen for its ability to facilitate rapid development and deliver robust functionality</p>
<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white" alt="Svelte"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="Visual Studio Code"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green" alt="Django"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/> 
</div>

<h2 align="center" class="section-heading">👾 3D Modeling + VR + AR</h2>
<p>In the immersive domains of 3D Modeling, Virtual Reality (VR), and Augmented Reality (AR), I apply my expertise to bring digital creations to life. Leveraging industry-leading tools, I sculpt, render, and animate with precision, while pioneering VR and AR experiences that bridge the gap between virtuality and reality.</p>
<div align="center">
  <img src="https://img.shields.io/badge/Unreal_Engine-313131?style=for-the-badge&logo=unreal-engine&logoColor=white" alt="Unreal Engine"/>
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity"/>
  <img src="https://img.shields.io/badge/3DS_Max-0696D7?style=for-the-badge&logo=autodesk&logoColor=white" alt="3DS Max"/>
  <img src="https://img.shields.io/badge/Maya-0696D7?style=for-the-badge&logo=autodesk&logoColor=white" alt="Maya"/>
  <img src="https://img.shields.io/badge/Rhino-801010?style=for-the-badge&logo=rhinoceros&logoColor=white" alt="Rhino"/>
  <img src="https://img.shields.io/badge/MeshLab-FF4000?style=for-the-badge" alt="MeshLab"/>
  <img src="https://img.shields.io/badge/ZBrush-5491F1?style=for-the-badge" alt="ZBrush"/>
  <img src="https://img.shields.io/badge/Revit-FF9E0B?style=for-the-badge&logo=autodesk&logoColor=white" alt="Revit"/>
  <img src="https://img.shields.io/badge/ArchiCAD-0081CF?style=for-the-badge" alt="ArchiCAD"/>
  <img src="https://img.shields.io/badge/Oculus-1C1E20?style=for-the-badge&logo=oculus&logoColor=white" alt="Oculus"/>
</div>

<div align="center">
<h2 align="center" class="section-heading"> 💻 Github Stats</h2>
<p>Peek into my GitHub stats to see how I juggle code, coffee, and collaborations! Dive in to check out the milestones of my digital journey!</p>
 <table align="center" width="100%" height="100%" >
    <tr>
       <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>   
       <td><img style="border: none;" src="https://github-readme-streak-stats.herokuapp.com/?user=zanepearton&theme=merko" alt="Zane's Contribution Streak"/></td>
    </tr>
 </table>

 <table align="center" width="100%" height="100%" >
    <tr>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=zanepearton&theme=github_dark&utcOffset=10" alt="Zane's GitHub Stats"/>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>
    </tr>
 </table>
</div>

profile
Auth0
Promoted

Auth0

JWT Handbook 🧑‍💻
Every developer should have the JWT Handbook in their toolkit. With it you can access the most important aspects of the architecture of JWTs, including their binary representation and the algorithms used to construct them.

Start here

Top comments (9)
Subscribe
pic
Add to the discussion
 
 
ooosys profile image
oOosys
•
Jan 9

Hmmm ... you are encouraging to use external URL for animated SVG and to make the site unnecessary heavy in size. This might be of advantage from the perspective of companies which profit is based on getting attention at any cost ... but from the perspective of what I understand github is about it is abuse of the storage space ... making a github profile a profile of a voluntary soldier actively engaging in the war for attention.


5
 likes
Like
Reply
 
 
n1c01a5 profile image
Wagner Nicolas
•
Jan 10

Here is mine :

github.com/n1c01a5

Don't hesitate to follow me !


2
 likes
Like
Reply
 
 
random_ti profile image
Random
•
Jan 9

Great Tutorial . Thanks for sharing it👌
GitHub logo taqui-786 / taqui-786



A passionate software developer and tech Blog writer from India

🔭 I’m currently working on a Nexjs Projects

🌱 I’m currently learning C++,Typescript and Java

📚 Write's Blogs at Dev.to and Hashnode

💬 Ask me about Node.js, React, Firebase, MongoDB... or anything here

⚡ Fun fact World first developer was a women

   
⚒️ Languages-Frameworks-Tools ⚒️

 

⚡ Stats ⚡

streak stats readme stats
top langs
contribution graph



View on GitHub



3
 likes
Like
Reply
 
 
samuel2935 profile image
Samuel
•
Jan 11

Helpful


2
 likes
Like
Reply
 
 
lymah profile image
Lymah
•
Jan 9

Thanks for sharing.


2
 likes
Like
Reply
 
 
m__mdy__m profile image
mahdi
•
Jan 11

please checkOut my profile github

m-mdy-m (Mahdi) · GitHub
Junior web developer. m-mdy-m has 41 repositories available. Follow their code on GitHub.

github.com

1
 like
Like
Reply
 
 
dev_kiran profile image
Kiran Naragund
•
Jan 9

Checkout my profile:

GitHub logo Kiran1689 / kiran1689
Github readme profile. Feel free to fork and use the template.
Kiran1689 Banner Image


 ɪ'ᴍ ᴋɪʀᴀɴ!
Digital Craftsman (Developer / Programmer)

I am a Full Stack Developer and Machine Learning Enthusiast with a huge love for Python, React.js, Node.js, Django, RDBMS, REST API and Data Visualization.

✨ Student of life :)
🌱 I’m currently learning many things, I believe that everyday is a learning opportunity.
🏙 A lifetime insider and Mentor at Exercism.
✍ I write technical blogs, You can visit my blog site at DEV.
❤ Contributing to Open Source.
💻 Visit my Portfolio for more details about me.
Kiran1689



Lᴀɴɢᴜᴀɢᴇs ᴀɴᴅ Tᴏᴏʟs


🏆 Gɪᴛʜᴜʙ Tʀᴏᴘʜɪᴇs 🏆
GitHub Trophies

📊 Gɪᴛʜᴜʙ Sᴛᴀᴛs 📊
Gɪᴛʜᴜʙ Sᴛᴀᴛs
GitHub Stats

Sᴛʀᴇᴀᴋ Sᴛᴀᴛs
Streak Stats

Lᴀᴛᴇsᴛ Pʀᴏᴊᴇᴄᴛ
Awesome-Dev-Portfolios

Tᴏᴘ Cᴏɴᴛʀɪʙᴜᴛɪᴏɴs
Top Repo

📈 Cᴏɴᴛʀɪʙᴜᴛɪᴏɴ Gʀᴀᴘʜ 📈

🌟 Tʜᴏᴜɢʜᴛ ᴏғ ᴛʜᴇ Dᴀʏ 🌟


🤝 Cᴏɴɴᴇᴄᴛ Wɪᴛʜ Mᴇ 🤝
linkedin kirannaragund197@gmail.com kiran_a_n kiran__a__n Twitter
Buy Me A Coffee





View on GitHub



2
 likes
Like
Reply
 
 
lorenzocalabrese03 profile image
Lorenzo Calabrese
•
Jul 14 • Edited on Jul 14

github.com/LorenzoCalabrese03
This is my profile, if you can check it pls


Like
Reply
 
 
sammy6378 profile image
Samuel Mwangi N
•
Mar 17

Nice work done


1
 like
Like
Reply
Some comments have been hidden by the post's author - find out more

Code of Conduct • Report abuse
profile
AWS
Promoted

AWS Security LIVE! Stream

Get cloud security advice without the sales pitch
Ready to level up your cloud security skills? Tune in to AWS Security LIVE! for expert insights, live demos, and interactive Q&A sessions with AWS and AWS Partners.

Learn More

Read next
nozibul_islam_113b1d5334f profile image
Higher-Order Functions in JavaScript
Nozibul Islam - Sep 15

mrk0p profile image
Optimizing Web Performance: Best Practices and Techniques
Sachin wele - Sep 2

surajondev profile image
Top UI Component Libraries for React
Suraj Vishwakarma - Sep 16

shabbir_mw_03f56129cd25 profile image
How to Avoid Data Loss and Downtime During WordPress Migration
SHABBIR M.W. - Sep 2


Zane
Follow
Devops Engineer | Software Engineering Specialist @Accenture
Location
Melbourne
Joined
Jan 8, 2024
More from Zane
Rust vs. Go: The benchmark
#webdev #programming #rust #go
Terminal Style CV Using GitHub Pages
#webdev #javascript #programming #tutorial
Embracing Kubernetes: The Future of Containerized Applications
#webdev #programming #devops #kubernetes
profile
AWS
Promoted

AWS Security LIVE! Stream

Practical guidance for security practitioners
Don't miss AWS Security LIVE! Whether you're an AWS newbie or a seasoned pro, this show has something for everyone with actionable tips, expert advice, and security knowledge.

Learn More


<div align="center">
    <h1><img src="https://readme-typing-svg.herokuapp.com?font=Jetbrains+mono&size=40&duration=3000&color=33FF33&center=true&vCenter=true&width=435&lines=Hey..+I'm+Zane;This+is..;..my+Github..;" alt="Typing SVG"/></h1>
    <p><img src="termina-gh.gif" alt="Terminal GH GIF" /></p>
</div>

<div align="center">
    <h2>🚀 About Me</h2>
<!--     <p><img src="termina-gh.gif" alt="Terminal GH GIF" /></p> -->
    <p>I'm a Software Engineering specialist at Accenture with Aus/EU citizenship, specializing in fusing software development with operations. My technical range is broad, covering everything from cloud platforms and containerization to CRM systems and 3D modeling.</p>
</div>

<div align="center">
<h2 align="center" class="section-heading">🌐 Connect with Me</h2>
<p> To connect with me, you can find my professional profile and contact details on LinkedIn, or explore more about my projects and interests through my Linktree. Feel free to reach out for collaborations, opportunities, or just to exchange ideas about the latest in software development and technology. Let's innovate together! </p>
<div align="center">
  <a href="https://www.linkedin.com/in/zane-pearton">
    <img src="https://img.shields.io/badge/ZanePearton-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://linktr.ee/zanepearton">
    <img src="https://img.shields.io/badge/Linktree-39E09B?style=for-the-badge&logo=Linktree&logoColor=white" alt="Linktree"/>
  </a>
<a href="https://github.com/ZanePearton/ZanePearton" target="_blank">
    <img src="https://img.shields.io/badge/View%20on%20GitHub-%230077B5.svg?&style=for-the-badge&logo=github&logoColor=white" alt="GitHub Skyline"/>
</a>
<img src="https://komarev.com/ghpvc/?username=ZanePearton&style=for-the-badge" alt="Profile views" />
</div>

<div align="center">
  <h2>🚀 Github Commits</h2>
    <p>This section highlights my daily activity, showcasing the repositories I am currently working on. Each commit represents progress or fixes to ongoing projects, reflecting my commitment to continuous improvement and collaborative development. Dive into the commit messages for insights into what I've been up to!</p>
  <img src="https://raw.githubusercontent.com/zanepearton/zanepearton/output/github-contribution-grid-snake-dark.svg#gh-dark-mode-only" alt="GitHub Contribution Grid Snake Animation Dark Mode"/>
  <img src="https://raw.githubusercontent.com/zanepearton/zanepearton/output/github-contribution-grid-snake.svg#gh-light-mode-only" alt="GitHub Contribution Grid Snake Animation Light Mode"/>
</div>

<h2 align="center" class="section-heading">💻 Programming Languages</h2>
<p> As a multifaceted engineer, I've developed proficiency in a diverse set of programming languages, each serving as a pivotal tool in my development arsenal. Here are the languages I wield to turn complex problems into elegant solutions</p>
<div align="center">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white" alt="Swift"/>
  <img src="https://img.shields.io/badge/YAML-0A0A0A?style=for-the-badge" alt="YAML"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"/>

</div>
<h2 align="center" class="section-heading">☁️ Cloud Technologies</h2>
<p>In the dynamic realm of cloud computing, I am proficient in leveraging leading cloud platforms and technologies to architect, deploy, and manage scalable, highly available, and fault-tolerant systems. Here's a glance at the cloud technologies I specialize in:</p>
<div align="center">
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure"/>
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="GCP"/>
  <img src="https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins"/>
  <img src="https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Salesforce"/>
</div>

<h2 align="center" class="section-heading">🔧 Frameworks</h2>
<p>Frameworks are the backbone of my development process, providing the structure and tools necessary for building scalable, efficient applications. My expertise spans a broad spectrum of frameworks, each chosen for its ability to facilitate rapid development and deliver robust functionality</p>
<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white" alt="Svelte"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="Visual Studio Code"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green" alt="Django"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/> 
</div>

<h2 align="center" class="section-heading">👾 3D Modeling + VR + AR</h2>
<p>In the immersive domains of 3D Modeling, Virtual Reality (VR), and Augmented Reality (AR), I apply my expertise to bring digital creations to life. Leveraging industry-leading tools, I sculpt, render, and animate with precision, while pioneering VR and AR experiences that bridge the gap between virtuality and reality.</p>
<div align="center">
  <img src="https://img.shields.io/badge/Unreal_Engine-313131?style=for-the-badge&logo=unreal-engine&logoColor=white" alt="Unreal Engine"/>
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity"/>
  <img src="https://img.shields.io/badge/3DS_Max-0696D7?style=for-the-badge&logo=autodesk&logoColor=white" alt="3DS Max"/>
  <img src="https://img.shields.io/badge/Maya-0696D7?style=for-the-badge&logo=autodesk&logoColor=white" alt="Maya"/>
  <img src="https://img.shields.io/badge/Rhino-801010?style=for-the-badge&logo=rhinoceros&logoColor=white" alt="Rhino"/>
  <img src="https://img.shields.io/badge/MeshLab-FF4000?style=for-the-badge" alt="MeshLab"/>
  <img src="https://img.shields.io/badge/ZBrush-5491F1?style=for-the-badge" alt="ZBrush"/>
  <img src="https://img.shields.io/badge/Revit-FF9E0B?style=for-the-badge&logo=autodesk&logoColor=white" alt="Revit"/>
  <img src="https://img.shields.io/badge/ArchiCAD-0081CF?style=for-the-badge" alt="ArchiCAD"/>
  <img src="https://img.shields.io/badge/Oculus-1C1E20?style=for-the-badge&logo=oculus&logoColor=white" alt="Oculus"/>
</div>

<div align="center">
<h2 align="center" class="section-heading"> 💻 Github Stats</h2>
<p>Peek into my GitHub stats to see how I juggle code, coffee, and collaborations! Dive in to check out the milestones of my digital journey!</p>
 <table align="center" width="100%" height="100%" >
    <tr>
       <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>   
       <td><img style="border: none;" src="https://github-readme-streak-stats.herokuapp.com/?user=zanepearton&theme=merko" alt="Zane's Contribution Streak"/></td>
    </tr>
 </table>

 <table align="center" width="100%" height="100%" >
    <tr>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=zanepearton&theme=github_dark&utcOffset=10" alt="Zane's GitHub Stats"/>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>
    </tr>
 </table>
</div>


<div align="center">
    <h1><img src="https://readme-typing-svg.herokuapp.com?font=Jetbrains+mono&size=40&duration=3000&color=33FF33&center=true&vCenter=true&width=435&lines=Hey..+I'm+Zane;This+is..;..my+Github..;" alt="Typing SVG"/></h1>
    <p><img src="termina-gh.gif" alt="Terminal GH GIF" /></p>
</div>

<div align="center">
    <h2>🚀 About Me</h2>
<!--     <p><img src="termina-gh.gif" alt="Terminal GH GIF" /></p> -->
    <p>I'm a Software Engineering specialist at Accenture with Aus/EU citizenship, specializing in fusing software development with operations. My technical range is broad, covering everything from cloud platforms and containerization to CRM systems and 3D modeling.</p>
</div>

<div align="center">
<h2 align="center" class="section-heading">🌐 Connect with Me</h2>
<p> To connect with me, you can find my professional profile and contact details on LinkedIn, or explore more about my projects and interests through my Linktree. Feel free to reach out for collaborations, opportunities, or just to exchange ideas about the latest in software development and technology. Let's innovate together! </p>
<div align="center">
  <a href="https://www.linkedin.com/in/zane-pearton">
    <img src="https://img.shields.io/badge/ZanePearton-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://linktr.ee/zanepearton">
    <img src="https://img.shields.io/badge/Linktree-39E09B?style=for-the-badge&logo=Linktree&logoColor=white" alt="Linktree"/>
  </a>
<a href="https://github.com/ZanePearton/ZanePearton" target="_blank">
    <img src="https://img.shields.io/badge/View%20on%20GitHub-%230077B5.svg?&style=for-the-badge&logo=github&logoColor=white" alt="GitHub Skyline"/>
</a>
<img src="https://komarev.com/ghpvc/?username=ZanePearton&style=for-the-badge" alt="Profile views" />
</div>

<div align="center">
  <h2>🚀 Github Commits</h2>
    <p>This section highlights my daily activity, showcasing the repositories I am currently working on. Each commit represents progress or fixes to ongoing projects, reflecting my commitment to continuous improvement and collaborative development. Dive into the commit messages for insights into what I've been up to!</p>
  <img src="https://raw.githubusercontent.com/zanepearton/zanepearton/output/github-contribution-grid-snake-dark.svg#gh-dark-mode-only" alt="GitHub Contribution Grid Snake Animation Dark Mode"/>
  <img src="https://raw.githubusercontent.com/zanepearton/zanepearton/output/github-contribution-grid-snake.svg#gh-light-mode-only" alt="GitHub Contribution Grid Snake Animation Light Mode"/>
</div>

<h2 align="center" class="section-heading">💻 Programming Languages</h2>
<p> As a multifaceted engineer, I've developed proficiency in a diverse set of programming languages, each serving as a pivotal tool in my development arsenal. Here are the languages I wield to turn complex problems into elegant solutions</p>
<div align="center">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white" alt="Swift"/>
  <img src="https://img.shields.io/badge/YAML-0A0A0A?style=for-the-badge" alt="YAML"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"/>

</div>
<h2 align="center" class="section-heading">☁️ Cloud Technologies</h2>
<p>In the dynamic realm of cloud computing, I am proficient in leveraging leading cloud platforms and technologies to architect, deploy, and manage scalable, highly available, and fault-tolerant systems. Here's a glance at the cloud technologies I specialize in:</p>
<div align="center">
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure"/>
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="GCP"/>
  <img src="https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins"/>
  <img src="https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Salesforce"/>
</div>

<h2 align="center" class="section-heading">🔧 Frameworks</h2>
<p>Frameworks are the backbone of my development process, providing the structure and tools necessary for building scalable, efficient applications. My expertise spans a broad spectrum of frameworks, each chosen for its ability to facilitate rapid development and deliver robust functionality</p>
<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white" alt="Svelte"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="Visual Studio Code"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green" alt="Django"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/> 
</div>

<h2 align="center" class="section-heading">👾 3D Modeling + VR + AR</h2>
<p>In the immersive domains of 3D Modeling, Virtual Reality (VR), and Augmented Reality (AR), I apply my expertise to bring digital creations to life. Leveraging industry-leading tools, I sculpt, render, and animate with precision, while pioneering VR and AR experiences that bridge the gap between virtuality and reality.</p>
<div align="center">
  <img src="https://img.shields.io/badge/Unreal_Engine-313131?style=for-the-badge&logo=unreal-engine&logoColor=white" alt="Unreal Engine"/>
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity"/>
  <img src="https://img.shields.io/badge/3DS_Max-0696D7?style=for-the-badge&logo=autodesk&logoColor=white" alt="3DS Max"/>
  <img src="https://img.shields.io/badge/Maya-0696D7?style=for-the-badge&logo=autodesk&logoColor=white" alt="Maya"/>
  <img src="https://img.shields.io/badge/Rhino-801010?style=for-the-badge&logo=rhinoceros&logoColor=white" alt="Rhino"/>
  <img src="https://img.shields.io/badge/MeshLab-FF4000?style=for-the-badge" alt="MeshLab"/>
  <img src="https://img.shields.io/badge/ZBrush-5491F1?style=for-the-badge" alt="ZBrush"/>
  <img src="https://img.shields.io/badge/Revit-FF9E0B?style=for-the-badge&logo=autodesk&logoColor=white" alt="Revit"/>
  <img src="https://img.shields.io/badge/ArchiCAD-0081CF?style=for-the-badge" alt="ArchiCAD"/>
  <img src="https://img.shields.io/badge/Oculus-1C1E20?style=for-the-badge&logo=oculus&logoColor=white" alt="Oculus"/>
</div>

<div align="center">
<h2 align="center" class="section-heading"> 💻 Github Stats</h2>
<p>Peek into my GitHub stats to see how I juggle code, coffee, and collaborations! Dive in to check out the milestones of my digital journey!</p>
 <table align="center" width="100%" height="100%" >
    <tr>
       <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>   
       <td><img style="border: none;" src="https://github-readme-streak-stats.herokuapp.com/?user=zanepearton&theme=merko" alt="Zane's Contribution Streak"/></td>
    </tr>
 </table>

 <table align="center" width="100%" height="100%" >
    <tr>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=zanepearton&theme=github_dark&utcOffset=10" alt="Zane's GitHub Stats"/>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=zanepearton&theme=github_dark" alt="Zane's GitHub Stats"/></td>
    </tr>
 </table>
</div>

Thank you to our Diamond Sponsor Neon for supporting our community.

DEV Community — A constructive and inclusive social network for software developers. With you every step of your journey.

Home
DEV++
Podcasts
Videos
Tags
DEV Help
Forem Shop
Advertise on DEV
DEV Challenges
DEV Showcase
About
Contact
Free Postgres Database
Guides
Software comparisons
Code of Conduct
Privacy Policy
Terms of use
Built on Forem — the open source software that powers DEV and other inclusive communities.

Made with love and Ruby on Rails. DEV Community © 2016 - 2024.
