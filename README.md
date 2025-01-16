# IntroToDirbTool

Overview: In this repository I will be covering what the dirb tool is, how I've used it so far, and my thoughts/opinions on it.

What is Dirb?
Dirb is a simple and fast brute-forcing tool for web content discovery. It uses wordlists yo make HTTP requests and checks for the existence of directories or files. Simply put, it helps discover hidden directories and files on a web server. 

My experience with dirb: I like dirb it's very helpful with finding a lot of useful information. Since i've only been using it within my homelab I just ran it against my target machine's IP to practice using the tool, understanding how it works, and what type of information can be gathered. One thing that was a big help for me was understanding what the status codes mean, this was benefical because a 200 status code basically means that file exists. For me personally my initial step would be to start with files that have a 200 status code which makes the discovery process a bit easier, after running dirb against the my target machine and checking to see what files existed, I actually found the login credentials.

My thoughts on dirb: I like the dirb and I think it's a really good tool. However, I don't feel that it's competing with Nikto.
