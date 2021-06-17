# Zookeeper

https://user-images.githubusercontent.com/56825295/122482640-9df71280-cfd9-11eb-9572-fb4328a5dc1b.mp4


This project is aimed at our beginners. It helps you understand some syntax basics and learn how to work with variables, data storage types such as lists, and while loops.

## First step: 'Rush into print'

**Topics learned:**

> Introduction to Python

> Overview of the basic program

> Multi-line programs



###### Objectives

There are many animals in the zoo, and all of them need care. The animals must be fed, cleaned, surrounded by their kin, and kept happy. That is a difficult task for our large zoo, so one of your employers has suggested a more convenient way to keep track of everything. She wants to be able to pull up a video feed of any animal in the zoo with the help of a program. Being able to check on each habitat would help the zookeepers take care of our furry friends more efficiently!

In this project, you will create a program that helps the zookeepers check on the animals and make sure that they're doing well. Your product will be able to process commands from the zookeepers and display the animals on a monitor.

To begin with, you will develop a simple printer. Your program should display the text from the output example.
```
I love animals!
Let's check on the animals...
The deer looks fine.
The bat looks happy.
The lion looks healthy.
```

##  Second step: 'Show me an animal!'

**Topics learned:**

> PEP 8

> Comments

> Basic data types

> Quotes and multi-line strings



###### Objectives
For the second stage, you will need to develop an animal printer. Your program should display the animal identified in the code field.

Please, don't remove the r character at the start of the code template. It's a part of the string and it's important. So, the string should start with r""" sequence. This “r” at the beginning stands for “raw” and allows various characters to be used in a string without escaping. For instance, “\” in a non-raw string should be escaped as follows: “\\”.

## Third step: 'What's inside?'

**Topics learned:**

> Variables

> Taking input

> List

> Indexes


###### Objectives
In this stage your program should:

Ask for the number of the desired habitat using the following phrase: Please enter the number of the habitat you would like to view:

Use the input number as an index of your habitats to print its content.

End with the following phrase:
```
---
You've reached the end of the program. To check another habitat, please restart the watcher.
```

## Last step: 'Sustainable care <3'

**Topics learned:**

> Integer arithmetic

> Naming variables

> Program with numbers

> Boolean logic

> Comparisons

> If statement

> While loop

###### Description

Now it's time to make our project user-friendly. In this final stage, you'll make your software ready for the zoo staff to use. Your program should understand the habitat numbers, show the animals, and be able to work continuously without having to be restarted.

###### Objectives

Your tasks at this point:

* Your program should repeat the behavior from the previous stage, but now in a loop.

* Do not forget to include an exit opportunity: inputting exit should end the program.

* When the program is done running, it should print: See you later!

###### Example
```
                                  _
                                ,-"" "".
                              ,'  ____  `.
                            ,'  ,'    `.  `._
   (`.         _..--.._   ,'  ,'        \    \
  (`-.\    .-""        ""'   /          (  d _b
 (`._  `-"" ,._             (            `-(   \
 <_  `     (  <`<            \              `-._\
  <`-       (__< <           :
   (__        (_<_<          ;
    `------------------------------------------
The goose is staring intently at you... Maybe it's time to change the channel?
Please enter the number of the habitat you would like to view: > 1

Switching on the camera in the lion habitat...
                                               ,w.
                                             ,YWMMw  ,M  ,
                        _.---.._   __..---._.'MMMMMw,wMWmW,
                   _.-""        '''           YP"WMMMMMMMMMb,
                .-' __.'                   .'     MMMMW^WMMMM;
    _,        .'.-'"; `,       /`     .--""      :MMM[==MWMW^;
 ,mM^"     ,-'.'   /   ;      ;      /   ,       MMMMb_wMW"  @\
,MM:.    .'.-'   .'     ;     `\    ;     `,     MMMMMMMW `"=./`-,
WMMm__,-'.'     /      _.\      F'''-+,,   ;_,_.dMMMMMMMM[,_ / `=_}
"^MP__.-'    ,-' _.--""   `-,   ;       \  ; ;MMMMMMMMMMW^``; __|
           /   .'            ; ;         )  )`{  \ `"^W^`,   \  :
          /  .'             /  (       .'  /     Ww._     `.  `"
         /  Y,              `,  `-,=,_{   ;      MMMP`""-,  `-._.-,
        (--, )                `,_ / `) \/"")      ^"      `-, -;"\:
The lion is roaring!
Please enter the number of the habitat you would like to view: > exit
See you later!
```
