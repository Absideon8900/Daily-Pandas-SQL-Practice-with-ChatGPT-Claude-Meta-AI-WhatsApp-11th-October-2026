# Daily Matplotlib Practice with ChatGPT, Claude & Meta AI (WhatsApp) 11th October 2026
<b>Matplotlib - Lesson 2: Understanding the X and Y</b></br>
Today we will practice with X and Y values in this session</br>
Today we will use only X
```Python
plt.plot(temoerature)
```
Then we would use X and Y
```Python
plt.plot(temperature,months)
```
# Solution 1:
<b>Using only Temperature</b></br>
```
Temperature = [20,30,32,31,35,37]
```
```Python
import matplotlib
import matplotlib.pyplot as plt
plt.title("Temperature")
plt.xlabel("The Temperature in C")
rainfall = [20,30,32,31,35,37]
plt.plot(rainfall)
plt.show()
```
<img width="556" height="454" alt="image" src="https://github.com/user-attachments/assets/fd66b7ac-cf49-4546-8885-c3a3eaa9a80b" />

# Solution 2:
<b>Using Days and Temperature</b></br>
```
days [1,2,3,4,5,6]
Temperature = [20,30,32,31,35,37]
```
```Python
import matplotlib
import matplotlib.pyplot as plt
plt.title("Understanding X and Y")
plt.xlabel("The days")
plt.ylabel("The Temperature")
days = [1,2,3,4,5,6]
temperature = [20,30,32,31,35,37]
plt.plot(months,rainfall)
plt.show()
```
<img width="576" height="454" alt="image" src="https://github.com/user-attachments/assets/21e8bbd4-05c0-4259-aa8d-dee0538f2f34" />
