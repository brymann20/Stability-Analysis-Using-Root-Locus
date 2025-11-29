# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
Open MATLAB software
Open a new script file.
Type the program.
Save and Execute the program.
Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
From the value of K, analyse the stability.
![WhatsApp Image 2025-11-27 at 23 16 05_03aaab3f](https://github.com/user-attachments/assets/52061395-55bb-4419-9aa0-18ec2d2cfc91)
![WhatsApp Image 2025-11-27 at 23 16 05_ae8afa65](https://github.com/user-attachments/assets/c1589619-773c-4cf8-afed-e2b751425e28)
![WhatsApp Image 2025-11-27 at 23 16 05_693a334a](https://github.com/user-attachments/assets/4a6e4dfc-1bb3-4a54-b1ec-6dc00fcbe975)
![WhatsApp Image 2025-11-27 at 23 16 06_185b0a13](https://github.com/user-attachments/assets/1ce3dfc5-1198-4a54-a8da-f499ad514f9a)





## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
```
num=[1];
den=[1 15 50 0];
sys=tf(num,den);
rlocus(sys);
[k,poles]=rlocfind(sys)
```
## Output:
<img width="699" height="626" alt="image" src="https://github.com/user-attachments/assets/efb210b9-801d-4a1a-b603-66c56093cb8b" />

## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 744.551 .
