For our final project we decided to make a discord bot that is connected through an EC2 instance and draws in the Yahoo finance API.
The AWS instance id is i-0087e98e1dd21b75f.
If the bot somehow goes offline, to run it again through the EC2 instance click the instance, then click connect, then connect again, and then in the linux terminal 
enter ./run.sh or ./nrun.sh and the bot should run again. 

The bot has multiple commands. A help command, where when "help" is typed it gives a list of 3 help options from which the user can choose from.
The stock information command, where when "stock: " is typed followed by the ticker, stock information is given. 
The bot responds to "Hi".
The bot also welcomes people into the server. 

The python code for the project is also in the repo.
