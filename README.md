# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-27 at 18 18 52_e887084d](https://github.com/user-attachments/assets/4f00f87c-e64f-4b85-908b-83f173f7353c)
![WhatsApp Image 2025-11-27 at 18 18 52_02dc167f](https://github.com/user-attachments/assets/e657fe28-697b-4183-bbe2-5f495f56b0eb)
![WhatsApp Image 2025-11-27 at 18 18 51_fea84f47](https://github.com/user-attachments/assets/2b8c38c4-0052-4606-a66c-099e0b48f3dc)
![WhatsApp Image 2025-11-27 at 18 18 51_41b51777](https://github.com/user-attachments/assets/f5061c63-b10b-498d-a503-88c8ff6dff8a)





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
