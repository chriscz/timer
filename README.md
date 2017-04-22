A GUI countdown timer written in Python using the Tkinter framework.

![Timer in Use](/screenshot.png?raw=true "Timer in use")

The timer has been tested on Ubuntu 14.04 with the following versions of Python.
- Python 2.7.6
- Python 3.5.2
- Python 3.4.3

But it should work on macOS and Windows. 
Please report any issues you experience on these platforms!

## Features
- Add multiple timers
- Add labels to each timer
- Simple scrolling to increase the value of each timer.

## Execution
As simple as:

```
python timer.py
```
### Setting Time
1. Scroll over the seconds, minutes or hours while the timer is paused to set each.
2. Click on the timer to pause/start it.

## TODO / Known Issues
- Need to build in time correction (ticker might be off by a few miliseconds, and that adds up)
- Notifications using pynotify
