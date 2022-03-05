# My-Projects

I have always been close to my mother and nothing makes her happier than a call or message from me, which I do most of the time, but I wanted to text her every morning and never miss that.
Therefore, I decided to use an R script that does the job.

Basically, the program is divided into 4 steps:
-Everyday, the program is trigged at 9.00 am by AWS .
-Then the program is slept for a random period before continuing. That way, the message is not sent at the same time every day.
-Then a body message is chosen randomly from 5 ways to say, “Good morning”.
-Finally, the message is sent, and the program is shutdown .

You can try it by following those steps:
-Create a free account on Twilio platform and get your credentials (token & SID);
-Download the R script from this repo and adapt it;
-Assuming you already have an account on AWS, follow this article to deploy the code on AWS lambda(https://lnkd.in/gwUpuCK);

PS: You need an approval from WhatsApp to send messages from your own number and it may take time. However, you can start messaging now using Twilio sandbox(https://lnkd.in/gBnRJf8)


![Alt text](screenshot.PNG?raw=true "Title")
