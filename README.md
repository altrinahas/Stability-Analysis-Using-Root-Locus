# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:

![WhatsApp Image 2025-11-27 at 21 56 48_19efc738](https://github.com/user-attachments/assets/305fda7f-12b6-46b4-83a7-48fd51dbb78c)
![WhatsApp Image 2025-11-27 at 21 56 49_5d2f371d](https://github.com/user-attachments/assets/39faafd2-6b76-4a7e-95b9-81ea78521a86)

![WhatsApp Image 2025-11-27 at 21 56 50_723941fd](https://github.com/user-attachments/assets/59a629d2-4a0f-4333-b237-9fb54c32c694)

## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
```
num=[1]
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)
```

## Output:
<img width="702" height="629" alt="image" src="https://github.com/user-attachments/assets/ec9110d7-fc10-4674-a30d-f3badb428ad1" />



## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 301.0370
