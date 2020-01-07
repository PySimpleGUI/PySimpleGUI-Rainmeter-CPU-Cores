# PySimpleGUI Rainmeter CPU Cores

## Rainmeter-Style Desktop Widget That Graphs Your CPU's Cores

![PSG CPU Cores Scrolling](https://user-images.githubusercontent.com/46163555/71864004-99cc8300-30cc-11ea-805c-de04b0b2296b.gif)


## Requirements

To use the GUI you'll need to install PySimpleGUI (http://www.PySimpleGUI.org for instructions)

One of these will install it for you.
```
pip install PySimpleGUI
pip3 install PySimpleGUI
```

You will also need to install the psutil package.

## Running

Once the pacakges are installed, you only need to run the single Python file found in this repository - `PySimpleGUI_Rainmeter_CPU_Cores.py`

When running on Windows, launching with `pythonw` instead of plain `python` will start the program without showing a console window.

## "Rainmeter" Styling

Achieving a "rainmeter" styling to your PySimpleGUI windows is not difficult.  It only requires setting a few parameters in the call to create the window.  Those 3 parameters are:

1. No titlebar
2. Grab anywhere
3. Alpha Channel of 0.8

The result is a bornerless window that's transparent and can be moved by grabbing the window by clicking anywhere in the window using your mouse and dragging.

![SNAG-0665](https://user-images.githubusercontent.com/46163555/71864394-ad2c1e00-30cd-11ea-85f5-9850ed7df69e.jpg)

## Hungry for more?

If you want more examples like tthis one to help in creating your GUI, then be sure and check out the many programs found at http://Demos.PySimpleGUI.org. 

![logo500](https://user-images.githubusercontent.com/46163555/71866174-62150980-30d3-11ea-8a27-451849cd88ed.png)
