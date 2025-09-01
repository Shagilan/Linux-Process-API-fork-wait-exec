Operating systems Lab exercise
# Linux commands-Shell scripting
Linux commands-Shell scripting

# AIM:
To practice Linux Commands and Shell Scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Linux environment installed on the system or installed inside a virtual environment like virtual box/vmware or online linux JSLinux (https://bellard.org/jslinux/vm.html?url=alpine-x86.cfg&mem=192) or docker.

### Step 2:

Execute the following commands

### Step 3:

Testing the commands for the desired output. 

# COMMANDS:
### Create the following files file1, file2 as follows:
cat > file1
```
chanchal singhvi
c.k. shukla
s.n. dasgupta
sumit chakrobarty
^d
```
cat > file2
```
anil aggarwal
barun sengupta
c.k. shukla
lalit chowdury
s.n. dasgupta
^d
```
### Display the content of the files
cat < file1
## OUTPUT
<img width="288" height="147" alt="image" src="https://github.com/user-attachments/assets/425656a2-2105-4496-a9ed-63ee01d6586d" />



cat < file2
## OUTPUT

<img width="304" height="180" alt="image" src="https://github.com/user-attachments/assets/325bcf50-4658-4ce7-b89e-38d0feef9dab" />

# Comparing Files
cmp file1 file2
## OUTPUT
 <img width="359" height="73" alt="image" src="https://github.com/user-attachments/assets/65f984c5-bed1-49f0-93af-b8fbe7dd9002" />

comm file1 file2
 ## OUTPUT
<img width="405" height="229" alt="image" src="https://github.com/user-attachments/assets/7f9eeeec-8e69-444b-a645-ffd1eec2ad2e" />

 
diff file1 file2
## OUTPUT
<img width="264" height="276" alt="image" src="https://github.com/user-attachments/assets/b43d7824-f982-403a-9e24-1b5c91b9c4fd" />

#Filters

### Create the following files file11, file22 as follows:

cat > file11
```
Hello world
This is my world
^d
```
<img width="315" height="100" alt="image" src="https://github.com/user-attachments/assets/a4a290fa-28ac-4653-ac12-77aab58957a5" />

cat > file22
```
1001 | Ram | 10000 | HR
1002 | tom |  5000 | Admin
1003 | Joe |  7000 | Developer
^d
```
<img width="434" height="127" alt="image" src="https://github.com/user-attachments/assets/3ce8d6ae-3efd-40d4-b7e3-ff603ce99f74" />


cut -c1-3 file11
## OUTPUT




cut -d "|" -f 1 file22
## OUTPUT



cut -d "|" -f 2 file22
## OUTPUT
<img width="364" height="101" alt="image" src="https://github.com/user-attachments/assets/30492741-8376-46a6-b224-14ca0f0fa118" />


cat < newfile 
```
Hello world
hello world
^d
````
<img width="310" height="101" alt="image" src="https://github.com/user-attachments/assets/16f418eb-7d71-4956-bad1-869977a725ce" />

cat > newfile 
Hello world
hello world
 
grep Hello newfile 
## OUTPUT

<img width="398" height="82" alt="image" src="https://github.com/user-attachments/assets/e3f89789-d37c-499a-9744-7532ccba527a" />


grep hello newfile 
## OUTPUT

<img width="320" height="79" alt="image" src="https://github.com/user-attachments/assets/09cb4636-7d32-403e-a331-051fb33bcb3b" />
