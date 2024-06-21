# Maven
Maven is an open-source build automation tool
it is used to create artifact (war, jar, ear)
maven read pom.xml file [pom.xml file having all project info and configration details]
##Maven commands

1. compiler 
The compiler plugin is used to compile the source code of a Maven project. 
              
                syntax: mvn compile
 
2. test
 to test the code
               
               syntax:  mvn test
                
3. Package: To package your project into a distributable format (ex - WAR), use the following command:   
           
              syntax:  mvn package
  
4.  Install:
    To install your project artifacts into the local Maven repository 
         
              syntax:   mvn install

5. clean
mvn clean command removes the target directory and any other files generated during the build process.
             
             syntax: mvn clean package

6. build->
   builds the Maven project and installs the project files ( JAR , WAR , pom. xml , etc.) to the local repository            
              
              syntax: mvn build
  
7. Deploy 
 deploys the packaged artifacts to a remote repository. Typically, it's used to deploy artifacts to a Maven repository manager or a remote server.
 
            syntax:   mvn deploy
            
8. check mvn version

            syntax:  mvn -version
