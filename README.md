# log4j-testing


Run in the Docker 
```
docker run --network host deimergrueso/log4j-testing:latest
```

Confirm if is running with 

```
docker ps 
```

From the Attacker machine download the target folder and the exploit.py on the same folder

```
python3 exploit.py 
```
![Alt text](https://github.com/deimergruesobar/log4j-testing/blob/main/log4j/img/exploit.png)

In a split shell execute 
```
nc -lnvp 9001
```
![Alt text](https://github.com/deimergruesobar/log4j-testing/blob/main/log4j/img/nc.png)


Follow the wizard in the exploit.py shell 
![Alt text](https://github.com/deimergruesobar/log4j-testing/blob/main/log4j/img/jndi.png)