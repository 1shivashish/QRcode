# QRcode
This is my first small QR code generator project 
import qrcode

img = qrcode.make(input("Enter data for QR code: "))
img.save("qrcode.png")
print("Saved qrcode.png")
