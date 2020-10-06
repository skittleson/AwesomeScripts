# Image processing scripts

Time laspe with gphoto https://www.moreno.marzolla.name/software/linux-time-lapse/
Work with raw photos https://www.dechifro.org/dcraw/


## DSLR 

gphoto2 --capture-image-and-download && dcraw capt0000.nef && rm capt0000.nef

gphoto2 --summary |  grep Battery


gphoto2 --set-config /main/capturesetting/burstnumber=10

## Super Resolution