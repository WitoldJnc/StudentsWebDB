[![Build Status](https://travis-ci.org/WitoldJnc/students-web-app.svg?branch=master)](https://travis-ci.org/WitoldJnc/students-web-app)

### Студенческий сайт портал  
#### 
### Стек технологй:  
#### 
* Spring boot  
* Spring MVC  
* Spring Security  
* Internationalization - 2 language  
* MySQL  
* Hibernate  
* Liquibase  
* HTML/CSS(Bootstrap)  
* Handlebars  
* Gradle  

  ### Как запустить:  
* Субд - MySQL  
    создать ДБ - Students (sql: create database students)  
    username: root  
    password: root  
    опционально:в комманд лайн клиенте MySQL засетать глобал тайм зону на свой часовой пояс: (sql: SET GLOBAL time_zone = '+02:00';)
* Запустить файл application.java  
* В плагине миграции дб Liquibase запустить таски:  
     dropAll  
     update  
* Перейти по адрессу порта ( localhost:8080 )
     
  
