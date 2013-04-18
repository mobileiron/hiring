Write a simple Spring MVC application in Java, deploy it to Heroku and send me a link to your Github repo with the source code.

The application will have the following 3 models (backed by a SQL database):

   * users - name, email
   * devices - phone_number, operating_system
   * applications - name, description

Following relationships exist:

   * user can have multiple devices
   * multiple applications can be installed on the same device

I expect to be able to:

   * add a new user and view the list of users
   * add a new device, associate it with an existing user and view the list of devices associated with the user
   * add a new application, associate an existing application with an existing device
   * view the list of applications that are installed on a given device

You will need:

   * Heroku - free account
   * Github - free account 
   * STS/Eclipse - free download

Links you may find useful:

   * https://github.com/
   * http://java.heroku.com/ 
   * http://www.springsource.org/sts
   * http://www.springsource.org/tutorials
   * http://stackoverflow.com/questions/tagged/spring-mvc

Important:

   * small, incremental git commits with a good description of changes as you iterate

Not important:

   * don't worry (much) about user interface. use twitter bootstrap & the default styles it comes with
   * don't worry about authentication - or you can use openid, twitter, facebook, oauth as a bonus

