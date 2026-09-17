# firstf

## How the command works
This is a command line tool that applies both grep and head functions. It allows a user to search for a specific pattern within the first lines, something that is specified by the user.
The command accepts commands via 
node firstf.js PATTERN FILENAME NUMBER_OF_LINES.
The command will search for the specified pattern in the file for the specified number of lines.
An example would look like
node firstf.js apple sample.txt 10. 
This would search for the pattern apple in the first ten lines of sample.txt
## AI Assisted Programming Reflection
I asked AI to generate sample text files to use as sample data to pull from. AI helped me save time as otherwise i would have had to generate all that data by hand. I had to think differntly when it came to troubleshooting within the codio enviornment as I was not able to ask the ai directly what i needed to change. I dont think ai got anything wrong however as i did not ask for it to do much besides sample data generation.
