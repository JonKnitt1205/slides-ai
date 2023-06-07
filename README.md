# Slides-AI
## Jonathan Knittel and Ram Bhagat
### HackBU 2023, February 4th

In order to use, a key file is needed to be created called keyFile.txt and placed in the same directory as index.js, with the first line being an OpenAI api key.
Run node index.js and then use a browser to go to localhost:7777, the console will notify you when the current request is finished and the slides can then be downloaded.

Works immediately for windows, I need to make a linux/mac python env or find a way to better set up python packages.

#### Resources
https://levelup.gitconnected.com/set-up-and-run-a-simple-node-server-project-38b403a3dc09 

https://python-pptx.readthedocs.io/en/latest/

https://www.npmjs.com/package/python-shell

# TODO
put all of the files into a database where each user has a their own files

have a way to tell user when the creation process finshes

have a way for the user to fine tune a previsouly made presentation

add more slide formats that are more dynamic to the slide content

add user accounts with authentication

add error handling on scripts to prevent server crashes
