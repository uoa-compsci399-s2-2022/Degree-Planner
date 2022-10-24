Name of project: An online tool to improve degree planning for BSc students.

A short description of what the project is about:

Our project is to create an interactive tool to help BSC students complete the course plan, including single major or double major.

Technologies that are used to build the project (include the languages used, the libraries and their versions).We used Element UI, Vue2.x, Axios for the front-end, Java8, Maven 3.8.2, Tomcat, SpringBoot, Mybatis-puls, Shiro, Druid for the back-end, and MySQL for the database.

Instructions on how to install and setup the project:

Our front-end uses the Vue architecture, so we first need to download Nodejs, configure the environment on the computer, then install dependencies (npm), and then open the front-end folder (choose-course-ui) cmd, input npm run serve, you can run the front-end part.

(nodejs--https://nodejs.org/en/)

(The tutorial of install and run vue --https://softauthor.com/up-and-running-with-vuejs3-project/)

![](media/b593d48b637310835c375d0bd9532fc6.png)

![](media/5019871643776a585cb2391aab16faf6.png)

In the previous part, we used a UI-library developed by a Chinese Internet company, which could cooperate well with vue to complete the development of the project.-(element-ui)

(install element-ui---- https://element.eleme.io/\#/zh-CN)

In the back-end part, we use springboot architecture, so we use IntelliJ IDEA(2022) to run the back-end code. The back-end code is in the choose-course-api folder. First, we use IntelliJ IDEA(2022) to open the back-end folder, and then we need to download java8, maven(3.8.6), Configure jdk1.8 and maven into IntelliJ IDEA, and then you can run the backend code properly.

(install Intellij IDEA --- <https://www.jetbrains.com/idea/)>

(install maven ----https://phoenixnap.com/kb/install-maven-windows)

(install java8 ----https://www.codejava.net/java-se/download-and-install-java-8-on-windows)

![](media/02366546552de282fbfef0d0ffacf7e2.png)

![](media/eaef6ae0b9f11660dd2782948d9b89b8.jpeg)

(open choose-course-api with IntelliJ IDEA(2022) )

(Configure maven into IntelliJ IDEA)

![](media/9533f308f334928a1a3ff9bf24c03eec.jpeg)

![](media/66165e3eb5b5d3ce26b37f982548a060.png)

(Configure jdk1.8 into IntelliJ IDEA)

![](media/f320c7fd6c0053768910e3f6dd2658b5.png)

(install navicat -- <https://www.navicat.com/en/products/navicat-premium)>

(install mysql -- <https://www.mysql.com/)>

The database part we use mysql language, put sql code into Navicat Premium 16 to run.

Create a database which called ‘student_choose_course’, then run the sql file.

![](media/f2e8f9b24a7da525c5856d3dfae3a3b4.png)

![](media/9b7f3e8b6de47f903bd5a649a50964d0.png)

![](media/5542049095687257dbc187db9be577ad.jpeg)

When you've configured all the environments, open the BusinessApiApplication.java.![](media/66d739458d8950d56be4bdf745877b3c.png)

Then the local password for the database is set in application-dev.yml(if your database password is not ‘123456’, set it to your real password in the .yml file)

![](media/58110d7481a5fa3a8fa3d7a244b5e194.png)

Then run the BusinessApiApplication.java by the SpringBoot.

![](media/c60ed21ef3410995b08e8d70aabe4d5a.png)

After a few seconds, if it runs it successfully, then open CMD as the administrator, cd to the choose-course-ui folder.

![](media/e83c25f69d05edfcec9ced28e94723fa.png)

If you do not install the ‘npm’, just input ‘npm install’, otherwise, just input ‘npm run serve’, after a few seconds, the website will be opened.

![](media/ac87a2c9d7376e41a271d73400377cd9.png)

URL of the website where the project has been deployed: We do not deployed the project on the server.

Future Plan: We will add the function that can allow the administrator to add or delete courses.

Acknowledgements (if any) - You can list tutorials used, projects referred to, people consulted etc:

We used an open source architecture on the Web-(Everyone framework)

To build the project, I used some online learning resources to help complete the development of the project, but this learning material is in Chinese version. I'll put the link below.

(http://t.csdn.cn/56seU)
