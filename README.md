<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6295/6295417.png" width="100" />
</p>
<p align="center">
    <h1 align="center">CREATi</h1>
</p>
<p align="center">
    <em>Creative Learning Platform</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/sadikatanisha/Creative-learning-platfrom?style=flat&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/sadikatanisha/Creative-learning-platfrom?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/sadikatanisha/Creative-learning-platfrom?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/sadikatanisha/Creative-learning-platfrom?style=flat&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&logo=JavaScript&logoColor=black" alt="JavaScript">
	<img src="https://img.shields.io/badge/PostCSS-DD3A0A.svg?style=flat&logo=PostCSS&logoColor=white" alt="PostCSS">
	<img src="https://img.shields.io/badge/Nodemon-76D04B.svg?style=flat&logo=Nodemon&logoColor=white" alt="Nodemon">
	<img src="https://img.shields.io/badge/React-61DAFB.svg?style=flat&logo=React&logoColor=black" alt="React">
	<img src="https://img.shields.io/badge/Axios-5A29E4.svg?style=flat&logo=Axios&logoColor=white" alt="Axios">
	<br>
	<img src="https://img.shields.io/badge/ESLint-4B32C3.svg?style=flat&logo=ESLint&logoColor=white" alt="ESLint">
	<img src="https://img.shields.io/badge/TypeScript-3178C6.svg?style=flat&logo=TypeScript&logoColor=white" alt="TypeScript">
	<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON">
	<img src="https://img.shields.io/badge/Express-000000.svg?style=flat&logo=Express&logoColor=white" alt="Express">
</p>
<hr>
<p align="center">
    <em>Overview</em>
</p>
<p align="center">
<!--   <img src="https://capsule-render.vercel.app/api?text=Hello!✨&animation=fadeIn&type=waving&color=gradient&height=100"/> -->
  <img align='center' src='Creati-home-page.gif' width='300"'>
</p>
<p align="center">
	<em>The Role-Based Application is a comprehensive platform designed to manage user roles and class enrollments efficiently. Built with a robust stack, the front end leverages TypeScript, Next.js, Redux, and Tailwind CSS to create a responsive and dynamic user interface. The backend is powered by Express.js and MongoDB, with JWT (JSON Web Tokens) for secure authentication.
</em>
</p>


## Functionalities:
 ** User:** Users can browse available classes and enroll in them seamlessly.
 ** Instructor:** Instructors have the capability to create, edit, and delete their classes, providing them with full control over their content.
 ** Admin:** Admins oversee the platform by approving classes and managing user roles, ensuring smooth operation and governance of the application.

## Lessons Learned:
This project was a significant learning experience, particularly in managing complex state with Redux and integrating TypeScript with Next.js for type-safe code. Implementing role-based access control taught me how to handle different user permissions effectively. I also gained deeper insights into backend development, particularly in securing RESTful APIs with JWT and optimizing MongoDB performance.

One of the most rewarding moments was successfully integrating the end-to-end user authentication flow and seeing how different user roles interact with the application seamlessly. This project has bolstered my skills in both front-end and back-end development and reinforced my understanding of building scalable, maintainable applications.


   <summary> Installation </summary>
   <p align="center">
    Client Setup
</p>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone https://github.com/sadikatanisha/Creative-learning-platfrom
   cd creative-learning-platform
   ```
3. **Navigate to the frontend directory:**
   ```sh
   cd frontend
   ```
4. **Install the dependencies:**
   ```sh
   npm install
   ```
   <summary>Configuration</summary>
4. **Create a .env file in the frontend directory:**
    ```sh
   touch .env
   ```

5. **Add the following environment variables to the .env file:** 
   ```sh
   NEXT_PUBLIC_SERVER_URI=
   GOOGLE_CLIENT_ID=
   GOOGLE_CLIENT_SECRET=
   SECRET
   ```

   <p align="center">
    Server Setup
</p>


1. **Navigate to the backend directory:**
   ```sh
   cd ../backend
   ```
4. **Install the dependencies:**
   ```sh
   npm install
   ```
4. **Create a .env file in the frontend directory:**
    ```sh
   touch .env
   ```

5. **Add the following environment variables to the .env file:** 
   ```sh
   PORT=8088
	ORIGIN=http://localhost:3000
	NODE_ENV=development
	DB_URL=
	CLOUD_NAME=
	CLOUD_API_KEY=
	CLOUD_API_SECRET=
	REDIS_URL=
	ACTIVATION_SECRET=
	ACCESS_TOKEN=
	REFRESH_TOKEN=
	ACCESS_TOKEN_EXPIRE=5
	REFRESH_TOKEN_EXPIRE=3
	SMTP_HOST=smtp.gmail.com
	SMTP_PORT=465
	SMTP_SERVICE=gmail
	SMTP_MAIL=sadikarahmantanisha@gmail.com
	SMTP_PASSWORD=
   ```
 <summary>Running the project</summary>
 **Additional Scripts**
Frontend
 ```sh
   npm run dev
   ```

Backend

 ```sh
   npm start
   ```
