# Description
This challenge was a part of the workshop linux fundamentals that was conducted for students to get familiar with Linux fundamentals and use some basic commands that are essential for every day linux use. The flag format is ```ACM{some_text}```
#
# Solution
To clone the repo in your kali linux directory use the command </br></br> ```git clone https://github.com/abubakr521/linux-for-dummies.git```</br></br>
Next use the grep command recursively to search for the flag text instead of using greo individually on each file.</br></br>
``` grep -r "ACM" linux-for-dummies ```</br></br>
### Flag
```ACM{dummy_n0_m0r3}```
