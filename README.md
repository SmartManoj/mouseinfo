MouseInfo
======

An application to display XY position and RGB color information for the pixel currently under the mouse. Works on Python 2 and 3.

Installation
------------

To install with pip, run:

    pip install mouseinfo

Quickstart Guide
----------------

To run this application, enter the following into the terminal:

    python3 -m mouseinfo

Or for Python 2, run:

    python -m mouseinfo

Alternatively, to run it from the interactive shell or a Python program:

    >>> import mouseinfo
    >>> mouseinfo.mouseInfo()

The Mouse Info application displays the current XY coordinates of the mouse cursor, as well as the RGB color information of the pixel directly under the cursor. This can be useful for planning out GUI automation tests where the mouse is controlled by a script (such as a Python script with PyAutoGUI) to click on the screen at specific coordinates.

The "Copy" buttons will copy this mouse information to the clipboard, while the "Log" buttons will add this mouse information to the text field in the application. The RGB color information is given as a comman-delimited, three-integer red, green, and blue values as decimals from 0 to 255. The hex values of the RGB value is also given.

For practical use, you should set the keyboard focus on these buttons by tabbing over them. This leaves you free to move the mouse into position and then press space or Enter to log the current mouse coordinates/RGB value.

The contents of the log text field can be saved by clicking "Save Log". This will automatically overwrite any file with the provided name. A screenshot can also be saved by clicking "Save Screenshot"

Contribute
----------

If you'd like to contribute to MouseInfo, check out https://github.com/asweigart/mouseinfo
