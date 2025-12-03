### 0.1.0
version: R++ #1
- You can now make function with func ... {{ }} and void ... { }
- print() syntax has been changed. You should write --> print("some text", variable); or use instead: print(f"sum = {variable1}, devision = {variable2}");
- Added break if (condition) and continue if (condition). More usable for 'for-loop'
- New variable type: double
- For-loop has now the possibility to chose a step for number change:
for (i in (z --> n); i++; target=n+1): --> for (i in (z --> n); i+m; target=n+1): //m is parameter for a step
for (i in (n <-- z); i--; target=n+1): --> for (i in (n <-- z); i-m; target=n+1): //m is parameter for a step
[Notice: the 1st example is for raising numbers and the 2nd is for decrease]

- print() also got a separation parameters for a line.
print("some text", sep.h.x); --> h = horizontal separation/spacing where x is amount of spaces
print("some text", sep.v.y); --> v = vertical separation/spacing where y is amount of spaces

- New function in Math-library: factorial()
- New library "Editing" which stays for work with texts (string). Functions:
1. reverse() --> an variable or text will be spelled in reverse
2. upper() --> small letters will becom ABCDE...
3. lower() --> big letters will become abcde...
4. length() --> the length of text in you variable or between brakets
Execution of code:

cd path\to\rrp\.\exe
.\Rpp.exe "C:\Path\to\file\file.rpp"

You can download rplusplus.vsix on clicking the link in documentation.

Link to digital document:

https://docs.google.com/document/d/1ZCzdmiSYzHkU3jgZGLPcZSw2sGpNjPXnrZKLs-2Vcz0/edit?usp=sharing
