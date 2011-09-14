### FreeEMS CAS Disk Hardware

This repository is here to hold design files and information for physical CAS
disks for the soon-to-be-infamous [FreeEMS][FreeEMS] decoder.

Two types of housings exist that are useful for installing such a disk in:

 - Mitsubishi Electric (Mitsubishi Motors and Mazda at the least)
 - Nissan (and GM LT1)

The latter has better optics and higher precision. The former has some issues
with diffraction and can only be operated at lower window counts, and even then
only with great care to align things well.

How the CAS gets decoded depends upon the resolution of it and the capability
of the ECU doing the decoding.

Included is the spreadsheet which outlines behavioural properties of the design
and eventually proven DXF files. One image is provided now as a reference to
get the idea across in a more clear way.

![FreeEMS CAS](https://raw.github.com/fredcooke/FreeEMS-CAS-HW/master/images/thumbs/FreeEMS-CAS-v1.0.png "Thumbnail of a 144/72 8 inner window disk.")

A larger resolution version and perhaps some online documentation is available
on the yet-to-be-finished [FreeEMS CAS page][StatusPageCAS] of the FreeEMS
status site. Discussion about decoder development will be able to be found in
the decoders section of the [DIYEFI.org forum][Forum] once it has begun.

### Links

 - [Decoder Status Page][StatusPageCAS]
 - [FreeEMS Main Site][FreeEMS]
 - [DIYEFI.org Forum][Forum]
[StatusPageCAS]: http://status.freeems.org/firmware/decoders/FreeEMS/ 
[FreeEMS]:       http://freeems.org
[Forum]:  http://forum.freeems.org

Thanks for supporting [FreeEMS][FreeEMS]! :-)

Fred.

