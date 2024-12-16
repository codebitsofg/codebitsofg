# About me

I'm a former designer working as a Frontend Developer.

* I live in Turkey. 🛩️
* I am especially interested in cloud and cloud infrastructure.
* You can find me in [Linkedin](www.linkedin.com/in/gencberat)
 
# 🛹 Side Projects

Here are some projects that are frontend, cloud and backend focused. I like implementing new experiemental features and beautiful designs that look stunning. And these are some of my work I've developed recently. Check my portfolio out for more of them. 

## 📑 [Rutin Hero Blog](https://blog.rutinhero.com/yazilar)


<p align="center">
 <a href="https://blog.rutinhero.com/yazilar"><img src="https://github.com/user-attachments/assets/a5b798ee-ce4a-40e7-8e2f-1312b9ae82b3" width="600"></a>
</p>


A Next.js + Strapi CMS Jamstack blog. Rutin Hero is a static export of a Next.js blog where performance and SEO optimization are of importance. Strapi CMS is used as the Headless CMS choice, and the images are served from an S3 bucket. Dynamic routes are configured by taking advantage the latest features of the Next.js App Router. Page-level SEO optimizations are implemented for higher ranking in search results.

## 📑 [Rutin Hero](https://blog.rutinhero.com/yazilar)


<p align="center">
 <a href="https://blog.rutinhero.com/yazilar"><img src="https://github.com/user-attachments/assets/117a89bb-2acf-41c8-9eca-784f3d7a5652" width="600"></a>
</p>


A multi-page web application where brands or individuals can create task based loyalty campaings for their brands or stores. It is still in progress but the user facing parts for now are the introductory pages and a sample product page which are written using Next.js, Tailwindcss and Shadcn. Recharts has been used for the data visualization. I will be implementing Auth.js (NextAuth) for the authentication. The backend will be written using Nest.js.


## 🗓️ [Task Manager](https://application.taskermanager.site/)


<p align="center">
 <a href="https://application.taskermanager.site/"><img src="https://github.com/soberbat/task-manager-frontend/assets/78652120/c53e0fde-b607-4c8d-a68d-738303f38699" width="600"></a>
</p>

Tasker Manager is an app where you can track your tasks with your team. Collaborate and be productive at what you do. It is written with Nest.js and deployed to Google Cloud. Fully automated with Github Actions. Both backend and frontend are deployed as docker containers and the Cloud SQL instance is provisioned to store user data. Prisma used as the ORM and styling is done with Tailwindcss.


## 📷 [A HEIC to JPEG Converter](https://heictojpeg.beratgenc.live/)

<p align="center">
 <a href="https://heictojpeg.beratgenc.live/"><img src="https://github.com/user-attachments/assets/bb1d0a64-4c20-4448-ba0a-42aa511bd291" width="600"></a>
</p>

The app is a fully functioning HEIC to JPEG converter. It was solely a production of curiosity, can I build my own converter? I've used some other tools for this purpose but creating my own was definitely something. It follows a very clean mono-repo structure with NX. The API is a container deployed as a Google Cloud Run Services. The backend handles the recieved form data from the frontend using multer and processes the image, changes its format as JPEG send sends it back to the client. 

## 🐕 [A Serverless landing page for an upcoming pet adoptation platform](http://infrastructurestack-nextjssitebucketbd1a5941-isspgruxxmoy.s3-website.eu-central-1.amazonaws.com/)

<p align="center">
 <a href="http://infrastructurestack-nextjssitebucketbd1a5941-isspgruxxmoy.s3-website.eu-central-1.amazonaws.com/"><img src="https://github.com/user-attachments/assets/7bba6428-8932-4c56-beb9-cc612a64949f" width="600"></a>
</p>

A responsive Next.js landing page that is deployed as a static export to AWS S3. It collects the user mails through an AWS Lambda function, talks to another through SQS, stores the data in DynamoDB and finally sends an email using Brevo. Tailwindcss is being used to style the landing page. The API along with the landing page is deployed using CDK. Repo created using NX. All in all it showcases a landing page coming alive with AWS services. Make sure to check your inboxes to see the mail if you have more than one.

## 🗂️ [R Resume](https://resumemaker.beratgenc.live/)

<p align="center">
 <a href="https://resumemaker.beratgenc.live/"><img src="https://github.com/soberbat/soberbat/assets/78652120/2f646784-eed0-4e6d-8566-1892bff44659" width="600"></a>
</p>

The app allows you to create a personalized resume to impress in your interviews. Frontend application manages complex data using Redux. The store has multiple slices for an enhanced developer experience. It features a minimalistic design that is both smooth and functional. Users can customize their resumes and download them. Reusable components &  React Hooks used throughout the app.

## 🛰️ [Space Factions Simulator](https://unniversecam.beratgenc.live/)

<p align="center">
 <a href="https://unniversecam.beratgenc.live/"><img src="https://github.com/soberbat/soberbat/assets/78652120/846bec0d-773e-4197-a481-498c1ed2f0cf" width="600"></a>
</p>

UnniverseCam is a space faction simulator with planets and starts. The application features a UI managed with React Context API for state management. It brings a complex design to life with elements such as select menus, carousel slides, and footers. A WebGL Typescript class handles logic for the 3D Scene. The codebase is written with modularity in mind. React UI and scene updates each other based on user input. This focus on modularity and synchronization makes the application a great example of how a modular UI can enhance immersive web experiences.

