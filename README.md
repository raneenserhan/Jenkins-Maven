# Jenkins-Maven  
This is for bulding jenkins job of the maven sample project  
### Job building steps:  
#### 1. Press Create New Item then -> Add name and choose freestyle project ####    
![image](https://user-images.githubusercontent.com/82150368/119909773-5fcc7d00-bf5e-11eb-8c2d-3edf285525b0.png)

#### 2.  Add Discrebtion ####    
![image](https://user-images.githubusercontent.com/82150368/119909835-81c5ff80-bf5e-11eb-9ffe-467d240857e8.png)


#### 3. In the Source Code Managment -> Add the github repository url of the project ####  
url: https://github.com/jglick/simple-maven-project-with-tests

![image](https://user-images.githubusercontent.com/82150368/119910107-13ce0800-bf5f-11eb-85e8-1e61811a310b.png)

#### 4. In the Build -> Add this command to build the project `mvn -Dmaven.test.failure.ignore=true clean package` ####     
![image](https://user-images.githubusercontent.com/82150368/119910481-e5046180-bf5f-11eb-91ac-4b273ae80e53.png)

#### 5. Press Build Now ####  

![image](https://user-images.githubusercontent.com/82150368/119910818-a58a4500-bf60-11eb-848c-a7943fc6d07d.png)

#### 6. Dashboard #### 

![image](https://user-images.githubusercontent.com/82150368/119910875-cbafe500-bf60-11eb-8630-cc364547aada.png)

-----------------------------------------------------------------------------------------------------------

## Pre-requisite  ##
----------------------------------------------------------------------------------------------------------    
Install maven ,use the following command:  
`apt install maven -y`
