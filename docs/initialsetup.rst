====================
Initial Setup For Windows/Mac
====================

You need to have:

PC - Windows 7 or above

Mac - macOS High Sierra or above

Arduino for Windows (Windows user)

Arduino for Mac (Mac user)

CH340 Driver for Windows

CH340 Driver for Mac

Mac (macOS High Sierra and above)
============

First, download the latest Arduino_ for Mac:

.. _Arduino: https://www.arduino.cc/en/Main/Software

Then install CH340_ driver for Mac (High Sierra and above):

.. _CH340: https://github.com/MPParsley/ch340g-ch34g-ch34x-mac-os-x-driver

or Python 2:

.. code-block:: console

    pi@raspberrypi:~$ sudo apt install python-gpiozero

If you're using another operating system on your Raspberry Pi, you may need to
use pip to install GPIO Zero instead. Install pip using `get-pip`_ and then
type:

.. code-block:: console

    pi@raspberrypi:~$ sudo pip3 install gpiozero

or for Python 2:

.. code-block:: console

    pi@raspberrypi:~$ sudo pip install gpiozero

To install GPIO Zero in a virtual environment, see the :doc:`development` page.

PC/Mac
======

In order to use GPIO Zero's remote GPIO feature from a PC or Mac, you'll need
to install GPIO Zero on that computer using pip. See the :doc:`remote_gpio`
page for more information.


.. _Raspbian: https://www.raspberrypi.org/downloads/raspbian/
.. _Raspberry Pi Desktop: https://www.raspberrypi.org/downloads/raspberry-pi-desktop/
.. _raspberrypi.org: https://www.raspberrypi.org/downloads/
.. _get-pip: https://pip.pypa.io/en/stable/installing/
