# java-maven-documentation
- #### Start by going to our starting repository
- #### Make a fork of the repository
![image](https://user-images.githubusercontent.com/103019032/166653758-7d97d172-f66b-4e54-9d68-f4d000517364.png)
- #### The project consists of two Java classes, where App.java contains the main method which creates an instance of the class DeepThought and calls for an answer
![image](https://user-images.githubusercontent.com/103019032/166654062-29098648-5c46-4342-ae72-fca47c99b927.png)
- #### The pom file is used to configure the maven project. It has been configured so that it knows that App.java contains the main method and that the project should be packaged with its dependencies
![image](https://user-images.githubusercontent.com/103019032/166654373-33947ff5-cf80-4530-9c69-413e79e622b6.png)
## *Build maven Project*
- #### It is now time to create and configure your first workflow. The first thing you want to know is if your maven project builds without any errors. Thus that is exactly what the first job in our workflow will find out.
- #### Click on the Actions tab
![image](https://user-images.githubusercontent.com/103019032/166655296-01b7159b-39b2-402a-b50c-0553fe5b26c1.png)
- #### Click on configure to Set up a workflow yourself.
![image](https://user-images.githubusercontent.com/103019032/166655949-cf7909ba-de65-49b4-854d-5a3331102759.png)
- #### You will then be greeted by this screen
![image](https://user-images.githubusercontent.com/103019032/166656561-7961d3c3-5b3d-483e-b979-b6722c8432e4.png)
- #### Replace the pre-populated workflow code with the one below
![image](https://user-images.githubusercontent.com/103019032/166657310-2e87c658-a53c-492d-b08a-d6b761460c91.png)

