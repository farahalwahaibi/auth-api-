# auth-api

## LAB - 08

## **Deployment Test**
## **Author: Farah AlWahaibi**

[PR LINK](https://github.com/farahalwahaibi/auth-api-/pull/1)

[Heroku APP](https://auth-api-2021.herokuapp.com/)

[Report Test](https://github.com/farahalwahaibi/auth-api-/actions)



## **Installation**
* **dependencies :**
  * "@code-fellows/supergoose"
  * "base-64"
  * "bcrypt"
  * "cors"
  * "dotenv"
  * "express"
  * "jsonwebtoken"
  * "mongoose"
  * "morgan"

* **devDependencies :**
  * eslint"
  * "jest"
  * "supertest"



## **Setup**
* .env requirements
  * **PORT** - 3000
  * **MONGOOSE_URI**
  * **SECRET** - used to create jwt



## **Running the app**
* **npm start**
* **Endpoints:**
   * (/signup)
   * (/signin)
   * (/users)
   * (/secret)
   * (/api/v1/food)
   * (/api/v1/food/:id)
   * (/api/v1/clothes)
   * (/api/v1/clothes/:id)
   


## **Tests**
* **Unit Tests:** npm run test (tests for server, routes, and user model currently implemented):

  * Auth Middleware
    * user authentication
      * ✓ fails a login for a user (admin) with the incorrect basic credentials 
      * ✓ logs in an admin user with the right credentials 
      
  * Auth Router
    * admin users
      * ✓ can create one 
      * ✓ can signin with basic 
      * ✓ can signin with bearer 
    * bad logins
      * ✓ basic fails with known user and wrong password 
      * ✓ basic fails with unknown user 
      * ✓ bearer fails with an invalid token 
      * ✓ basic fails with known user and wrong password  
      * ✓ basic fails with unknown user 
      * ✓ bearer fails with an invalid token 
      * ✓ basic fails with known user and wrong password  
      * ✓ basic fails with unknown user 
      * ✓ bearer fails with an invalid token 
    * editor users
      * ✓ can create one 
      * ✓ can signin with basic 
      * ✓ can signin with bearer 
    * user users
      * ✓ can create one 
      * ✓ can signin with basic 
      * ✓ can signin with bearer 
      
  * Auth Middleware
    * user authentication
      * ✓ fails a login for a user (admin) with an incorrect token 
      * ✓ logs in a user with a proper token
      
* **Lint Tests:** npm run lint


![test1](1.JPG)
![test2](2.JPG)


## **UML DIAGRAM**

![test1](3.JPG)

***

***Thank you!!***
