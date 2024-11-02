# Deploy Applications using Azure DevOps CI & CD Pipeline

In this project, we will be deploying applications using Azure DevOps CI/CD pipelines :
- automate builds,
- testing,
- deployment to various environments

## Environment

### Web App

- create Web App for dev, uat and prod
<img src="/pictures/webapp.png" title="web app"  width="900">
<img src="/pictures/webapp1.png" title="web app"  width="900">

### Create Project

- create 
<img src="/pictures/project.png" title="project"  width="900">

- build project
```
dotnet build
```

- run app
```
cd CICDApp
dotnet bin/Debug/net6.0/CICDApp.dll
```

### Create CI Pipeline

- create 
<img src="/pictures/ci.png" title="ci pipeline"  width="900">

- add trigger
<img src="/pictures/ci1.png" title="ci pipeline"  width="900">
```

### Create Release Pipeline

- create 
<img src="/pictures/release.png" title="release pipeline"  width="900">

- add staging slot
<img src="/pictures/release1.png" title="release pipeline"  width="900">
<img src="/pictures/release2.png" title="release pipeline"  width="900">

- add a swap task
<img src="/pictures/release3.png" title="release pipeline"  width="900">

- final stages
<img src="/pictures/release4.png" title="release pipeline"  width="900">