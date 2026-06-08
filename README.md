![MasterHead](init.gif)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=6EE7F7&center=true&vCenter=true&width=700&lines=Hey%2C+I'm+Piyush+Gupta+%F0%9F%91%8B;Full+Stack+Developer;MERN+%2B+Next.js+%2B+AI;Building+things+that+actually+work" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Piyush495&color=6EE7F7&style=for-the-badge&label=PROFILE+VIEWS" />
</p>

---

## 💫 About Me

Full Stack Developer based in Delhi — I build real products, not just demos.
My focus is clean architecture, measurable performance, and shipping things that actually work.

- 🤖 Just shipped **FridgeToFork** — an AI meal planner powered by GPT-4o-mini that generates personalized recipes from ingredients you already own
- ⚡ Built real-time systems sustaining **50 concurrent connections** at **181ms average latency** under load testing
- 🛒 Engineered a full e-commerce platform with Redis-optimized backend and JWT-secured auth
-  💼 **Full Stack Developer Intern @ WriteCream** — building and shipping real features in production
- 🧠 **400+ DSA problems** solved · Strong foundation in OOP & system design
- 🌱 Currently leveling up in: **Next.js advanced patterns · AI integrations at scale · System design**
- 🔍 Actively looking for **full-stack roles/SDE** at product companies and startups

---

## 🌐 Socials

<p align="left">
  <a href="https://linkedin.com/in/-piyush--gupta" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/Piyush_Gupta99/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-300%2B%20Problems-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
  <a href="mailto:piyushaggarwal1221@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 💻 Tech Stack

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433e38?style=for-the-badge&logo=react&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**Database**
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

**AI / Cloud / Tools**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

**Languages**
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

## 🚀 Projects

### 🍽️ FridgeToFork — AI Meal Planner
> *Open your fridge. Type what's inside. Get a real recipe in seconds.*

- GPT-4o-mini generates personalized recipes from user ingredients and cuisine preferences
- Rate limited to **10 API calls/user/day** to keep OpenAI costs controlled at scale
- 3 MongoDB schemas covering auth, recipe generation, saving, and meal planning
- **100% protected route coverage** via centralized Next.js middleware

**Stack:** Next.js · TypeScript · MongoDB · OpenAI API

<p align="left">
  <a href="https://fridge-to-fork-weld.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Live Demo-6EE7F7?style=for-the-badge&logo=vercel&logoColor=black" />
  </a>
  <a href="https://github.com/Piyush495/FridgeToFork" target="_blank">
    <img src="https://img.shields.io/badge/Source Code-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

### 💬 QuickChat — Real-Time Chat App
> *No-fluff chat. Fast, secure, tested under load.*

- Bi-directional WebSocket communication — **50 concurrent connections**, **0 failures**, **181ms avg round-trip latency** under load testing
- JWT auth on every API route and Socket.io handshake — unauthorized connections blocked at middleware level
- Zustand eliminates prop drilling across **8+ components**, managing auth, presence, and real-time state globally
- **7+ RESTful endpoints** handling auth, profiles, and persistent chat history

**Stack:** React · Node.js · Express · Socket.io · MongoDB · JWT

<p align="left">
  <a href="https://quick-chat-frontend-jet.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Live Demo-6EE7F7?style=for-the-badge&logo=vercel&logoColor=black" />
  </a>
  <a href="https://github.com/Piyush495/quick-chat" target="_blank">
    <img src="https://img.shields.io/badge/Source Code-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats-nu-six-24.vercel.app/api?username=Piyush495&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" width="48%" />
  <!-- <img src="https://github-readme-stats-nu-six-24.vercel.app/api/top-langs/?username=Piyush495&layout=compact&theme=tokyonight&hide_border=true" width="48%" /> -->
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Piyush495&theme=tokyonight&hide_border=true&mode=weekly" width="100%" />
</p>

---

## 🐍 Contribution Graph

<p align="center">
  <img src="https://raw.githubusercontent.com/Piyush495/Piyush495/output/github-contribution-grid-snake-dark.svg" />
</p>

---

## 📬 Let's Talk

I'm actively looking for full-stack/SDE roles at product companies and startups where I can own features end-to-end.

📧 [Contact Me](mailto:piyushaggarwal1221@gmail.com)
💼 [Connect on LinkedIn](https://linkedin.com/in/-piyush--gupta)
