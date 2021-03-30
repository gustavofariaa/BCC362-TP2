# Simple Distributed Pub/Sub

## Broker example

```
java -jar Broker.jar
```

## Client example

```
java -jar Executavel.jar -m 1 -bp 8082 -bkp 8081 -ipc 31.95.164.48 -ip 34.95.164.48 -mc 4
```

## Client arguments

| Arg  | Type    | Description          | Default     |
|------|---------|----------------------|-------------|
| -m   | Integer | Machine id           | -           |
| -bp  | Integer | Client port          | 8081        |
| -bkp | Integer | Broker port          | 8080        |
| -ipc | String  | Client IP            | "localhost" |
| -ip  | String  | Broker IP            | "localhost" |
| -mc  | Integer | Quantity of machines | 5           |
