# CS Games Survival kit
After cloning this repo, turn off your internet connection to do the challenge. You don't need any external python library to do it. The goal of this challenege is to learn or practice the basic python skills without internet connection. You may have to use the offline documentation with the help command

## Challenge
You have to complete the python file main.py:
- The program takes a json file (data.json) as program argument;
- The program create a new json file with the value of the field "genre" changed;
- The program create a csv file with the new value of the field "genre" with each pair field/value on a separated row;

Example of a csv file:

```
field1,value1
field2,value2
field3,value3
```

Finally, you have to create a bash script named start.sh that takes a json file as program argument and call the python program.

The program can be execute with this command: `./start.sh data.json`

