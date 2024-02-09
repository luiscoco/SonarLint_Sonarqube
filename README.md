# How to start with SonarLint and SonarQube

**SonarLint for Visual Studio** Overview, a free and open source IDE extension: 

https://www.youtube.com/watch?v=nASTGaxYXOo

**SonarLint for IntelliJ** and other JetBrains IDEs Overview | a free and open source IDE extension: 

https://www.youtube.com/watch?v=6Bv1wmj0jZI

**SonarLint for VS Code** Overview, a free and open source IDE extension: 

https://www.youtube.com/watch?v=m8sAdYCIWhY

**What is SonarLint?**:

https://www.youtube.com/playlist?list=PL6nq5CLci1YA62OecfK5aYVgly0sQAC1J

**What is SonarQube?**: 



**GitHub Integration | Mapping your organization into SonarQube**: 

https://www.youtube.com/watch?v=6zvBuZr8CeI

**GitLab Integration** | Mapping your organization into SonarQube: 

https://www.youtube.com/watch?v=XX0ey4rRvms

**Azure DevOps Integration | Mapping your organization with SonarQube**:

https://www.youtube.com/watch?v=oYvMmN6G3F0

## 1. SonarLint



## 2. SonarQube

https://www.sonarsource.com/products/sonarqube/downloads/

**How To Sonarqube Setup From Scratch And Code Analysis (2024)**:

https://www.youtube.com/watch?v=6vdRvz_LnbQ

How to install SonarQube with Docker

First we **pull SonarQube** Docker image

```
docker pull sonarqube
```

We also pull and **run PostgreSQL** database Docker image

```
docker run -d --name sonarqube-db -e POSTGRES_USER=sonar -e POSTGRES_PASSWORD=sonar -e POSTGRES_DB=sonarqube postgres:alpine
```

We now **run SonarQube**

```
docker run -d --name sonarqube -p 9000:9000 --link sonarqube-db:db -e SONAR_JDBC_URL=jdbc:postgresql://db:5432/sonarqube -e SONAR_JDBC_USERNAME=sonar -e SONAR_JDBC_PASSWORD=sonar sonarqube
```


## 3. SonarCloud

Efficient GitHub Code Scanning with SonarCloud and GitHub Actions | SonarQube | GitHub | Code Scan:

https://www.youtube.com/watch?v=AYUaIiWZ-_w

