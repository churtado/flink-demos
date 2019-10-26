flink-demos

##Install instructions
Dev server: to run a flink dev server: docker-compose up
Gradle: installed using SDKMAN!, then:  sdk install gradle 5.6.3

##Setup instructions
Run the quickstart script
 
##Build instructions
To package your job for submission to Flink, use: 'gradle shadowJar'. Afterwards, you'll find the
jar to use in the 'build/libs' folder.

To run and test your application with an embedded instance of Flink use: 'gradle run'

