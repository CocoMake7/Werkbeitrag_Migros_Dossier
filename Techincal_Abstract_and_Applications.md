Cocomake7 Hardware
==================

The CocoMake7 hardware is a human-computer interface. The core feature of the device are capacitive touch inputs. These inputs act as a tangible interface between the user and the computer.

The CocoMake7 board comes in a variety of forms featuring different ways to interact with. The board is attached to the computer via USB and acts either as a USB keyboard, a USB MIDI controller or as a simple serial device each of which can be freely programmed by the user.

Once plugged in, the CocoMake7 is working out of the box as we know it from other human interface devices such as computer mice and usb keyboards. However, the CocoMake7 programming interface allows the user to reprogram the device software (called firmware) and define what the touch inputs should do or trigger. This is accomplished with the well supported and ubiquitous arduino development environment. We have put a lot of effort in making the CocoMake7 board fully compatible with arduino.

Possible Applications
=====================

Web based sample player
-----------------------

Imagine the CocoMake7 is connected as a USB keyboard and its touch inputs are connected to electrically conductive material. Imagine further, that a keystroke is triggered when the user touches the conductive material. Now in the browser it is possible and very easy to fetch the different keystrokes and play samples and sounds based on the triggers. With little effort, the browser becomes a tangible and lively musical instrument.

MIDI controller
---------------

MIDI stands for musical instrument digital interface and is the standard way to interact with synthesizers and computer software since 1982. The CocoMake7 as MIDI device can send for example musical notes (pitch) to software such as ableton live, fruity loops, pure data and many other. The key thing is: how the device looks and works is up to the maker. While there are many MIDI controllers commercially available, experimental musical interfaces are very fun and intuitive to make.

What has been done
==================

CocoMake7 serial device. This needs only a very low number of electonic parts and the raw data is sent directly to the serial port.
![alt tag](link zum bild hinzufügen!)

The board as pluggable stick (USB keyboard or MIDI controller)
![alt tag](http://hackteria.org/wiki/images/2/25/Cocomake7-usb.png)

