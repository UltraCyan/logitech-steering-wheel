# logitech-steering-wheel

Intended to give force feedback options for the logitech g29 steering wheel.
This is not a complete python package, just a proof of concept for force feedback in python for Windows.
This is a current work in progress.
Currently supports constant forces with varying levels.


# Requirements
Requires hidapi and pyhidapi. hidapi is installed by putting the files in the
release to the location of your python install (/AppData/Local/Programs/Python/Python38).
https://stackoverflow.com/questions/62620247/how-to-determine-where-to-install-hidapi-dll
pyhidapi cann be installed via pip, pip install hid
