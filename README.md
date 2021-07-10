# polymorphic-QR-code

deposit DOGE here to fund me , need DOGE coins to test dogecoin-electrum
<br>
![s1](https://raw.githubusercontent.com/c4pt000/polymorphic-QR-code/main/MY-PMQR-DOGE-recv.gif)

a QR code that supports a short animated loop of 10 seconds on repeat for the same QR code informational value

a piece of information generated from a standard QR code (made as 10 frames represting the same string of information encoded into the first QR code)

ten different QR code images with slighty different pin dots (all 10 QR codes generated import the same encoded string)

played as a loop with a 1 second pause between each QR code image creates an animated QR code (polymorphic QR code for import)
```
ffmpeg -i %3d.jpg  -framerate 10 MY-PMQR-DOGE-recv.gif
```


![s1](https://raw.githubusercontent.com/c4pt000/polymorphic-QR-code/main/IBM-polymorphic-QR-code.gif)


^^ for best visual really its 25 frames for the QR code animation

since most video and animation is 22-25 frames/s
12 frames are the same REAL importable generated QR code
12 frames are surreal QR codes with white space holes randomly for a visual effect

first frame is the REAL QR code, second frame is the surreal QR code 001.png, third frame is the REAL QR code, fourth frame is another different surreal QR code 002.png, fifth frame is a REAL QR code, so on and so on, 

where the frames interweave with a 1 second pause for a total of 25 frames,

only takes generating the QR code once (making 11 copies of the real QR code to have 12 jpegs of the real QR code)
then making another 12 copies of the real QR code and randomly putting holes in those 12 images
then interweaving all 25 frames as above


