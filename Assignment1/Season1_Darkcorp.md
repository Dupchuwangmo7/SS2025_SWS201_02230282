# DarkCorp

![alt text](<DarkCorp_images/Screenshot from 2025-02-13 01-04-08.png>)

This is the seasonal machine for the week.

### 1. First step

I did ping IP address to see if the machine is up or not.

![alt text](<DarkCorp_images/Screenshot from 2025-02-13 01-08-26.png>)

We can see that the machine is up.

### 2. Second step

I want to do simple scan to see which ports are open.


![alt text](<DarkCorp_images/Screenshot from 2025-02-13 01-12-31.png>)

This was the simple namp scan and we can see that port 22 and 80 are open. 

![alt text](<DarkCorp_images/Screenshot from 2025-02-15 23-14-45.png>)

I also used nikto scan to see domain one after another.

### 3. Third Step

![alt text](<DarkCorp_images/Screenshot from 2025-02-15 23-48-37.png>)

This was the result for using gobuster for port 80.

![alt text](<DarkCorp_images/Screenshot from 2025-02-15 23-51-08.png>)

But the /dasboard is Forbidden.


### 4. Fourth Step

![alt text](<DarkCorp_images/Screenshot from 2025-02-16 00-16-10.png>)

I tried full TCP/UDP scan with version detection but it was forbidden.

