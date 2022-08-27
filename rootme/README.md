## ROOTME
- [x] 1
- [x] 2
- [x] 3
- [x] 4
- [x] 5
- [x] 6
- [x] 7
- [ ] 8
- [ ] 9
- [ ] 10

### QUESTION1 : HOW MANY PORTS ARE OPEN
We use nmap port scan 
#### nmap "IP address" -sV
![img1](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/rootme/img/1.png)

and we find that we have 2 open ports 
### ANSWER:2

### QUESTION2:WHAT VERSION OF APACHE IS RUNNING

![img2](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/rootme/img/2.png)

### ANSWER: 2.4.29

### QUESTION 3: WHAT SERVICE IS RUNNING ON PORT 22
 ![img3](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/rootme/img/3.png)
 
### ANSWER : ssh

### QUESTION 4,5 : WHAT IS THE HIDDEN DIRECTORY
![img4](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/rootme/img/4.png)

### ANSWER : /panel/

### QUESTION 6: FIND THE FLAG
First we should find the PHP reverse shell file and copy it. Then we should open new text editor and name it "rootme.php5" and paste the copied text to it.After changing IP to our own IP address we save it 

![img5](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/rootme/img/5.png)

![img6](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/rootme/img/6.png)

After this we will upload it to the site and now we should listen to port 1234 with 
#### nc -nvlp 1234 
now we are listening to port.
We should find the user.txt file and open it 

![img7](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/rootme/img/7.png)

### ANSWER: THM{y0u_ g0t_ a_sh3ll}

---
# CONTACT ME: huseynovvax.7@gmail.com

