##### Create a folder:
```fish
mkdir qa
```
##### Switch to the derectory:
```bash
cd qa
```
##### Create 3 folders:
```bash
mkdir qa_hw qa_info qa_practice
```
##### Switch to the directory:
```
cd qa_hw
```
##### Create 5 files:
```
touch 1.txt 2.txt 3.txt 4.json 5.json
```
##### Create 3 folders:
```
mkdir hw1 hw2 hw3
```
##### List Files and Directories:
```
ls -la
```
##### Open any file:
```
vim 1.txt
```
##### Write something:
```
+i and print something, for example: "Test file"
```
##### Save and exit:
```
Esc + :wq
```
##### One level up from the current directory:
```
cd ..
```
##### Move 2 files to any directory:
```
mv 4.json 5.json ../qa_info/
```
##### Copy 2 files to any directory:
```
cp 2.txt 3.txt ../qa_info/
```
##### Find a file by name:
```
find -name "*.txt"

or

ls | grep .txt
```
##### Monitor a file for changes and display the last 10 lines:
```
tail -f /logfile
```
##### Show fist 2 lines of a text file:
```
cat 1.txt | head -n2
```
##### Show last 2 lines of a text file:
```
cat 1.txt | tail -n2
```
##### Display the content of a file, page by page is a file is too big:
```
less 1.txt
```
##### Show data and time:
```
date
```
#### Task:

##### Send an http request to a server:
```
curl -i "http://162.55.220.72:5005/object_info_3?name=Vadim&age=32&salary=1000"
```
##### Write a script which will execute steps 3, 4, 5, 6, 7, 8, 13.

~~~shell
# !/bin/bash

mkdir QA

cd QA

mkdir qa1 qa2 qa3

cd qa1

touch 1.txt 2.txt 3.txt 4.json 5.json

mkdir w1 w2 w3

ls
~~~
