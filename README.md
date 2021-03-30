# Simple Distributed Pub/Sub

## Broker example

```
java -jar Broker.jar
```

## Client example

```
java -jar Executavel.jar -m 1 -bp 8084 -bkp 8082 -ipc 10.158.0.6 -ip 10.158.0.2 -mc 3
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
