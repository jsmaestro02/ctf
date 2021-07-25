# HackableII
First, we find the IP of our vulnerable machine using nmap.
![picture](Screenshot_2021-07-25_04_01_05.png)
Then we scan for open ports using nmap
![picture](Screenshot_2021-07-25_04_01_49.png)
port 80 is open so we check it out in the browser. We don't get anything from the webpage so we start crawling and finding directories of the server using dirbuster
![picture](Screenshot_2021-07-25_04_04_40.png)
We find /files. There is a file name CALL in that directory. maybe it's clue.
![picture](Screenshot_2021-07-25_04_05_05.png)
![picture](Screenshot_2021-07-25_04_05_08.png)
