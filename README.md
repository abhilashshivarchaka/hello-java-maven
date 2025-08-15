# Hello Java Maven + Jenkins CI/CD Project
This project demonstrates building a simple Java application using Maven, integrated with Jenkins for CI/CD. The app prints "Hello from Maven JAR!" and is packaged as a `.jar` file via Maven, with Jenkins automating the build process.  


**Project Structure:** `hello-java-maven/` → `src/main/java/HelloWorld.java`, `pom.xml`,README.md`.  

**Tools:** Java JDK 11, Apache Maven 3.8.6, Jenkins LTS (Docker), Git & GitHub. 

**Steps:** 
1️⃣ Created `HelloWorld.java` 
2️⃣ Added Maven `pom.xml` 
3️⃣ Set up Jenkins in Docker 
4️⃣ Configured Maven in **Global Tool Configuration** 
5️⃣ Created Jenkins Freestyle job linked to GitHub repo 
6️⃣ Added build step `mvn clean package` 
7️⃣ Triggered build → **BUILD SUCCESS** 
8️⃣ Verified output → `Hello from Maven JAR!`.  
**Jenkins Build Success Screenshot:  <img width="1893" height="907" alt="image" src="https://github.com/user-attachments/assets/797fb17a-7d66-462e-a064-fa390cce3279" />

