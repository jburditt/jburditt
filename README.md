## Introduction👋

Senior full-stack developer with over 20 years of experience. Continually improving skills, currently focusing on Angular, DevOps, and C# LeetCode practice and system design challenges.  
<br>

## Skill Matrix :hammer:
| Skill      | Level |
| :-----------| -----: |
| C# | :star::star::star::star::star: |
| GIT | :star::star::star::star::star: |
| Angular | :star::star::star::star: |
| JavaScript | :star::star::star::star: |
| MVC | :star::star::star::star: |
| EF | :star::star::star::star: |
| Java | :star::star::star: |
| MSSQL | :star::star::star: |
| Azure | :star::star::star: |
| AWS | :star::star::star: |
| TypeScript | :star::star::star: |
| Docker | :star::star::star: |
| Kubernetes | :star::star: |
| NodeJS | :star::star: |
| SASS | :star::star: |
<br>

## Philosophy :scroll:
- [Company Efficiency](https://blog.fullsweb.com/blog/company-metric)
- [Development Cost](https://blog.fullsweb.com/blog/develop-cost)
<br>

## Highlighted Projects :bulb:

### Angular, OAuth
3 years of work experience, all hosted on GitHub under the Government of BC, and the following hobby projects:
- [Shared Library/Blog](https://github.com/jburditt/fullswing-angular-library)
- [Bootstrap/Demo/OAuth](https://github.com/jburditt/Angular-Bootstrap)
- [Gamify Workout](https://github.com/jburditt/GamifyWorkout)

### C#, Entity Framework
20 years of work experience, and hobby projects:
- [LeetCode Submissions](https://github.com/jburditt/Leet-Code)
- [EF Core + Odata](https://github.com/jburditt/Angular-Bootstrap/tree/main/Api)

### Design Patterns
- [Design Patterns](https://github.com/jburditt/DotNet-Bootstrap/tree/main/Demo/Design%20Patterns)

### React
- [Demo](https://github.com/jburditt/react-demo)

### Azure
3 years of work experience. The following is a work-in-progress learning path:
```mermaid
architecture-beta
    group api(cloud)[Azure Architecture]
    service nosql(database)[CosmosDB] in api
    service server(server)[App Service] in api
    service db(database)[MSSQL] in api
    service blob(database)[Blob Storage] in api
    service message(cloud)[Message Queue] in api
    message:L <--> R:server
    message:B <--> T:nosql
    message:R <--> L:db
    blob:T --> B:server

    group blog(cloud)[Blog]
    service blogapp(server)[App Service] in blog
    service blogblob(database)[Blob Storage] in blog
    service deploy(internet)[GitHub Action] in blog
    deploy:T --> B:blogblob
    blogblob:R --> L:blogapp

    group wordpress(cloud)[Wordpress Azure Container App]
    service wordpress_php(server)[Wordpress Container] in wordpress
    service wordpress_db(database)[MySQL Container] in wordpress
    service wordpress_nginx(internet)[NginX Container] in wordpress
    service wordpress_certbot(disk)[Certbot Sidecar Container] in wordpress
    wordpress_php:T <--> B:wordpress_db
    wordpress_php:L <-- R:wordpress_nginx
    wordpress_certbot:T --> B:wordpress_nginx
```
<!-- 
database, server, cloud, disk, internet
NOTES: Add GitHub Action CI/CD, Entra ID
-->
<br>

## Let's Connect :sunglasses:
- [LinkedIn](https://www.linkedin.com/in/jburditt/)
<br>

## Learning Path :books:
- [ ] Microsoft Learn: AZ-900
- [ ] Microsoft Learn: SC-900T00-A
<br>
