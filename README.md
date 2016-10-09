### AWS Lambda Test function in Java

This is a sample function for AWS Lambda.

## Deployment
To deploy, run maven with

```
mvn package
```

Upload the .jar-File to AWS Lambda.

Use the following configuration on AWS Lambda:

```
Runtime: Java 8
Handler: example.Hello::myHandler
```

Use a plain integer as test input, for example:

```
5
```
