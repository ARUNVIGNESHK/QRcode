# QRcode
import pyqrcode
import png
from   pyqrcode import QRCode

Site="https://swayam.gov.in/explorer?category=COMP_SCI_ENGG"
arun=pyqrcode.create(Site)
arun.svg("first.svg",scale=8)
arun.png("first.png",scale=6)
