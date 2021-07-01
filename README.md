# BrokerCheck
I am SOOOO proud of this project! Normally, a project like this would take a few days (probably more than a week) to scrape everything using selenium. This is because I was just using one selenium page at a time. Instead, I multithreaded the project and it took about 2.5 hours (96 searches per minute from a few trials I ran). I split the project into 13 different files and injected code into each one. Then, I multithreaded importing them all, taking advantage of __import__() instead of import. I know a few ways that I could have made this project more efficient, but it actually turned out really well. 

The hardest part was definitely figuring out multithreading and then applying it to Selenium. I could not find anything about Selenium and multithreading on the internet that made sense, so I just figured out myself which was pretty difficult. At the end of the day, now I have a framework that I can apply to pretty much every project I do to speed it up 10000 fold.

Typing \n each time during the injected code was super annoying too.

Other than that, great project! :D
