# Discord bots workshop

This is the Framework we will be using during the workshop

## Python Dependencies

You will need to have the following libraries:
* hikari
* hikari-lightbulb
* APScheduler

***Notes:-***
* For Linux you can install a library called `uvloop`. This is a faster version of the built in asyncio event loop. Not 100% needed for this workshop though! You can also install a slightly faster version of hikari as well with `pip install "hikari[speedups]"`. You will also need python-dev as well
* For Windows you will need to install VS C++ build tools. None of the speedup improvements are available to Windows yet
