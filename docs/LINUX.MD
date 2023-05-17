[Go Back](../README.md)
___
# General Commands

### while true

**Execute command with inity loop** 

```shell
 while true;do curl https://viacep.com.br/ws/29162206/json; echo; sleep 0.5; done
```


### watch

**Execute a command by specif time(seconds)** 

```shell
 watch -n5 curl https://viacep.com.br/ws/29162206/json 
```

### Hash / Crypt

```shell
# MD5 encode
md5 -r filename.txt 

# base64 encode
echo -n "eef98d12e7ca8bf0f3a08a6a714431d4" | base64
```
___
[Go Back](../README.md)
