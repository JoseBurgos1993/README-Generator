# 09_Homework



For this assignment, I was tasked to create a README generator. I used Inquirer and many Awaits to prompt the user for various pieces of information. When the prompts get to the credits section, the user will be asked how many contributors and sources they want to credit. This will cause the code to loop around and prompt the correct number of times. It is at this point that the program gets messy. Since I used ` ` instead of '' or "" for my strings because I wanted to be able to `${thing}`, I had to make the huge string indent correctly. So some lines are all the way to the left. It looks weird, but it serves it purpose. After the whole page is written, the application will then generate the glorious newREADME.md.