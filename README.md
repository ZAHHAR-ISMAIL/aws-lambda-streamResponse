# aws-lambda-streamResponse

```
git clone .......
```
### Add Gson dependency to pom.xml
```
     <dependency>
      <groupId>com.google.code.gson</groupId>
      <artifactId>gson</artifactId>
      <version>2.8.5</version>
     </dependency>
```

### Use Maven To Generate the jar file (go to `/target` to find the jar)
```
mvn clean package
```


Edit Runtime settings of the Handler in aws Lambda console :  `com.amazonaws.lambda.demo.LambdaFunctionHandler::handleRequest`
