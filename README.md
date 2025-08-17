<div align="center">
  <br />
    <a href="https://promptly-ku56exxpo-noman-ahmed-siddiquis-projects.vercel.app/" target="_blank">
    </a>
  <br />



  <h3 align="center">Promptly – AI Prompt Sharing App</h3>

   <div align="center">
     A full-stack Next.js 14 application for discovering, creating, and sharing AI-powered prompts with the community.  
     <br />
     <b>👉 You can see it live here: <a href="https://promptly-ku56exxpo-noman-ahmed-siddiquis-projects.vercel.app/" target="_blank">https://promptly.vercel.app/</a></b>
    </div>
</div>

---

##  Table of Contents

1. [Introduction](#introduction)  
2. [Tech Stack](#tech-stack)  
3. [Features](#features)  
4. [Screenshots](#screenshots)  
5. [Quick Start](#quick-start)  

---

## <a name="introduction"> Introduction</a>

**Promptly** is a modern web app built with **Next.js 14, MongoDB, NextAuth, and TailwindCSS**.  
It allows users to:  
- Share AI prompts  
- Discover community prompts  
- Manage personal profiles with CRUD operations  
- Authenticate securely with Google  

This project was my learning step into **Next.js full-stack development** and **cloud deployment** using **Vercel + MongoDB Atlas**.  

---

## <a name="tech-stack"> Tech Stack</a>

- **Frontend**: Next.js 14, TailwindCSS  
- **Backend**: Next.js API Routes  
- **Database**: MongoDB Atlas  
- **Authentication**: NextAuth (Google OAuth)  
- **Deployment**: Vercel  

---

## <a name="features"> Features</a>

 Modern UI with **Glassmorphism design**  
 **CRUD prompts** (create, update, delete)  
 **Profile pages** for each user  
 **Community feed** to explore prompts  
 **Google login** via NextAuth  
 **Search by tag or keyword**  
 **Copy prompt to clipboard**  
 Fully **responsive**  

---

## <a name="screenshots"> Screenshots</a>


- **Homepage**
  <img width="1803" height="922" alt="homepage" src="https://github.com/user-attachments/assets/efcdb2e5-3fd1-4c23-aed5-c2e26d323d70" />


- **Profile Page**
  <img width="1702" height="882" alt="profilepage" src="https://github.com/user-attachments/assets/bb674483-5a85-4ccc-9926-cf7e71c4c4b9" />


- **Create Prompt**
  <img width="1745" height="907" alt="createpost" src="https://github.com/user-attachments/assets/5ff32872-0378-40d9-b740-81f9e5a83582" />


---

## <a name="quick-start"> Quick Start</a>

### Prerequisites
- [Node.js](https://nodejs.org/) (v18+)  
- [npm](https://www.npmjs.com/)  
- [Git](https://git-scm.com/)  

### Clone Repository
```bash
git clone https://github.com/yourusername/promptly.git
cd promptly

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_URL_INTERNAL=http://localhost:3000
NEXTAUTH_SECRET=
GOOGLE_ID=
GOOGLE_CLIENT_SECRET=
MONGODB_URI=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on these corresponding websites from [Google Cloud Console](https://console.cloud.google.com/welcome?rapt=AEjHL4MBaLLneW6OfAHf_zgms1eWZFw1wdy0_KIC4uh1nEqh2m4ojOvrXNlzJ4h7CZTkpiWgcsoHbUvS-FMdCP7WIkaVlPAeU7cnVR6Y0wJHeLMOtU6KAzA&project=promptopia-385410), [Cryptpool](https://www.cryptool.org/en/cto/openssl) (for random Auth Secret), and [MongoDB](https://www.mongodb.com/). 

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
