## caesar 100 point 
```
picoCTF{gvswwmrkxlivyfmgsrhnrisegl}
picoCTF{crossingtherubicondjneoach}
```
## The numbers 50 point 
a-z = 1-26
```
numbers = "16 9 3 15 3 20 6 20 8 5 14 21 13 2 5 18 19 13 1 19 15 14"

flag = ''.join([chr(int(i) + ord('a') - 1) for i in numbers.split(" ")]).replace("picoctf", "picoCTF{") + "}"

print(flag.upper())
***
PICOCTF{THENUMBERSMASON}
```
