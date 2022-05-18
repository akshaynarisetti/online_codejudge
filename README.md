# SRMASV Coding Assigments Grader CLI App

### **Installing the grader application**

```bash

cd ~/

git clone https://github.com/akshaynarisetti/online_codejudge/
```

### Once the repo is cloned

```bash
cd online_codejudge

ls

----># Here you will see the installation as srmasv-grader-sfc

#Adding the executable to bashrc
echo alias srmasv-grader-sfc=\"~/online_codejudge/srmasv-grader-sfc\" >> ~/.bashrc

## CLOSE THE CURRENT INSTANCE OF THE TERMINAL AND OPEN A NEW TERMINAL
```


```bash
# cd to the folder where you unzip the skeleton files.
#THEN

source ~/.bashrc

#Now you are ready to use the application
```

Before you can start using the checker run

```bash
srmasv-grader-sfc -auth

#Enter your email --- Enter your SRM EMAIL ID
#Enter your password   <<COLLECT THIS FROM ME>> ##Not your srm id's password

## AFTER YOU ARE DONE WITH AUTHENTICATION.. YOU CAN START USING THE Grader
```

To check your assignment

```bash
srmasv-grader-sfc -check [E*] [A*] [pathToCodeFile]

## So for Ex1 Assignment 1 run
srmasv-grader-sfc -check E1 A1 [pathToCodeFile]

## So for Ex1 Assignment 2 run
srmasv-grader-sfc -check E1 A2 [pathToCodeFile]

## So for Ex1 Assignment 3 run
srmasv-grader-sfc -check E1 A3 [pathToCodeFile]

## So for Ex1 Assignment 4 run
srmasv-grader-sfc -check E1 A4 [pathToCodeFile]
```
**Support this Repository by starring 🌟 it!**
