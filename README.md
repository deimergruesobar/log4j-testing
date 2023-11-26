# log4j-testing


Run in the Docker 

docker run --network host deimergrueso/log4j-testing:latest

Confirm if is running with 

docker ps 


From the Attacker machine download the target folder and the exploit.py on the same folder

python3 exploit.py 

In a split shell execute 

nc -lnvp 9001

Follow the wizard in the exploit.py shell 