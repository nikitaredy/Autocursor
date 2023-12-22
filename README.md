![Logo](https://i.pinimg.com/originals/21/9a/09/219a09d5c2d9e50e4c2d20c9a03e09af.gif)
# Autocursor

I developed this program to help all of my fellows who are working from home ;)




## Deployment

To deploy this project run

```bash
import pyautogui as pag
import random
import time
while True:
    x = random.randint(900,1500)
    y = random.randint(400,800)
    pag.moveTo(x,y,0.2)
    time.sleep(1)

    for i in range(0, 18):
        pag.press('shift')
```


## Installation

Install my-project with npm

```bash
  you can install pycharm 
  OR
  Import pyautogui
```
    
