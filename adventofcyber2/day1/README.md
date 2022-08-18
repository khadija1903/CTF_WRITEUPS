# ADVENT OF CYBER 2
## DAY 1
Firstly, we should write our IP adress and enter the website.Then we should register and login there.

![img1](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/adventofcyber2/day1/img/1.png)

### QUESTION 1,2,3
After logging in we use F12 to view Browser’s Developer Tools we go to Storage and click on cookies now we see name and value of cookie.

![img2](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/adventofcyber2/day1/img/2.png)

#### ANSWER: auth and hexadecimal

### QUESTION 4
We copy the value and convert it from hexadecimal to text format

![img3](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/adventofcyber2/day1/img/3.png)

#### ANSWER: json

### QUESTION 5
We changed username admin to “santa” and decoded it again 

![img4](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/adventofcyber2/day1/img/4.png)

#### ANSWER: 7b22636f6d70616e79223a22546865204265737420466573746976616c20436f6d70616e79222c2022757365726e616d65223a2273616e7461227d

### QUESTION 6
After finding Santa’s cookie value we come back to developer tools and change it with this value

![img5](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/adventofcyber2/day1/img/5.png)

Then when we refresh the site we will have our flag

![img6](https://github.com/khadija1903/CTF_WRITEUPS/blob/main/adventofcyber2/day1/img/6.png)

#### ANSWER : THM{MjY0Yzg5NTJmY2Q1NzM1NjBmZWFhYmQy}

---

# CONTACT : huseynovaax.7@gmail.com
