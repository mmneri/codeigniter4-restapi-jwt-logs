# Codeigniter 4 API + JWT + Logs system


<img align="left" alt="Codeigniter" width="40px" src="https://iconape.com/wp-content/files/bx/33981/svg/blackfire-inverted-1.svg" />
<img align="left" alt="JWT" width="40px" src="https://cdn.auth0.com/blog/jwtalgos/logo.png" />
<img align="left" alt="MySQL" width="40px" src="https://cdn.icon-icons.com/icons2/1381/PNG/512/mysqlworkbench_93532.png" />

</br>

## Framework & Tools

- Codeigniter4 
- JWT
- MySQL


</br>

## Installation   
Clone this repo  ```git clone https://github.com/wtt-kku/codeigniter4-restapi-jwt-logs.git```

</br>
</br>

## Setup 
1. Import Database  **api_db.sql** from **db** folder
2. Copy ```env``` to ```.env``` then uncomment and assign  ```baseURL = http://localhost:8080/```   **!Important** must have  ```/```
always trailing.

3. Update composer ``` composer update```

4. Run web ``` php spark serve```

</br>

## Usage

</br>

<img align="center" alt="Postman" width="60px" src="https://miro.medium.com/max/512/1*fVBL9mtLJmHIH6YpU7WvHQ.png" /></br>

For test API we recommanded use **POSTMAN** 

### Get User Data


**METHOD** <img align="" alt="POST METHOD" width="40px" src="https://www.img.in.th/images/e97e368f6e066d59fb7fbcca917e93ab.png" />
</br>
**URL** ```http://localhost:8080/api/v1/user/profile```


</br>

### User Register


**METHOD**  <img align="" alt="POST METHOD" width="40px" src="https://www.img.in.th/images/e97e368f6e066d59fb7fbcca917e93ab.png" />
</br>
**URL** ```http://localhost:8080/api/v1/user/regis```
</br>
**Body** 
```javascript 
{
  "username": "your_username",
  "password": "your_password",
  "repassword": "your_password_again",
  "firstname": "your_firstname",
  "lastname": "your_lastname",   
}
```

</br>

### User Login


**METHOD** <img align="" alt="POST METHOD" width="40px" src="https://www.img.in.th/images/e97e368f6e066d59fb7fbcca917e93ab.png" />
</br>
**URL** ```http://localhost:8080/api/v1/user/profile```
</br>
**Body** 
```javascript 
{
  "username": "your_username",
  "password": "your_password",  
}
```

</br>

>If you want to improve or develop more, Don't forget to uncomment and assign ```CI_ENVIRONMENT = development``` in ```.env```



