# Arduino CD player

Using an Arduino Pro-mini and an IDE CD-ROM drive to create a standalone CD player.
Based on the [ATAPIDUINO](http://singlevalve.web.fc2.com/Atapiduino/atapiduino.htm) project - code for this in the `original` folder.

For more details, see project on [hackaday.io](https://hackaday.io/project/176545-arduino-cd-player).

# Supported IDE CD-ROM drives
Sources from [ATAPIDUINO](http://singlevalve.web.fc2.com/Atapiduino/atapiduino.htm) and [ArduinoCdPlayer](https://hackaday.io/project/176545-arduino-cd-player):

## Testing
* Philips DVDROM DROM6116/34 (2004)

## Compatible drives
* NEC CDR 1800A (1997)
* Ultima Electronics CHA-50 (????)
* LITE-ON LTN-403L (2000)
* LITE ON LTN486S (2001)
* HITACHI CDR-8130 (1997)
* HITACHI CDR-8230 (1997)
* LG CRD-8320B (1998)
* LG CRD-8322B (1999)
* LG CRD-8521B (2001)
* LG GCE-8527B (2005)
* SONY CDU5211 (2001)
* CREATIVE CD5233E (?) (Starts PLAY instead of remaining paused when NEXT/PREV is used on stopped unit)
* BTC F563E (2001)
* TEAC CD-532E (2000)
* SAMSUNG SC-148C (2001)
* AZTECH CDA66801I (1995)


## Non Compatible or possible defect Units
* Toshiba XM-6402B (1999) (fails init proc.)
* H.L Datastorage GCR-8481B (2002) (fails init proc.)
* LG DVD-ROM Drive GDR-H30N (2007) (fails init proc.)
* Compaq CRC#D-8241B (1998) (erratic, defect?)
* COMPAQ CR-588 (1998) (erratic, defect?)


# References
* https://hackaday.io/project/176545-arduino-cd-player
* https://hackaday.io/project/24905-using-old-cd-drive-as-a-music-player
* http://singlevalve.web.fc2.com/Atapiduino/atapiduino.htm 
* productized version of similar idea: [CD-ROM DVD-ROM IDE ROM Audio Player controller DIY kit ROM to Turntable](https://www.ebay.co.uk/itm/CD-ROM-DVD-ROM-IDE-ROM-Audio-Player-controller-DIY-kit-ROM-to-Turntable/324207457799?_trkparms=aid%3D1110006%26algo%3DHOMESPLICE.SIM%26ao%3D1%26asc%3D20190920091355%26meid%3D7421b4ffda7d4caebe88fb4209a17d13%26pid%3D100036%26rk%3D3%26rkt%3D12%26sd%3D193152820628%26itm%3D324207457799%26pmt%3D0%26noa%3D1%26pg%3D2047675%26algv%3DDefaultOrganic%26brand%3DUnbranded&_trksid=p2047675.c100036.m2109CD-ROM DVD-ROM IDE ROM Audio Player controller DIY kit ROM to Turntable)
