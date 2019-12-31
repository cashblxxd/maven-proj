# Not an .md actually
1. check Java and Maven: (as of Debian 10)
java -version
mvn --version
2. Project is already built, however you can run `mvn package` and see BUILD SUCCESS
3. To see "Hello world!", run: (in my-app)
java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
4. To see the source, run: (in my-app)
cd src/main/java/com/mycompany/app
cat App.java
5. :^)
