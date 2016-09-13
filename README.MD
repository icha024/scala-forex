## Demo foreign currency exchange rate server in Scala

To build:

```
mvn clean install
```

Everything is built into `target/scala-forex-1.0-SNAPSHOT-bin.zip`

### Deploy to Cloud Foundry:
```
cf push yourServiceName -p scala-forex-1.0-SNAPSHOT-bin.zip
```
