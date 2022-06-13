```docker-compose up -d```

____________________________

To send a dummy log to fluentbit docker agent
```docker run --log-driver=fluentd -t ubuntu echo "Testing a log message"```
