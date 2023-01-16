# Barcode-Scanner-Breakout


<img src= https://github.com/sbcshop/Barcode-Scanner-Breakout/blob/main/images/breakout.jpg />

2D Barcode Scanner Breakout Board features with DE2120 barcode scanner module. This module reads 20 different barcode symbologies using a camera coupled with onboard image processing to identify and decode various UPCs to QR codes. 
The DE2120 module also has two LEDs:one for illumination and one to project the red laser line.
The module interfaces over USB Serial and TTL UART and it can operate in several modes including USB Keyboard (default), USB COM, USB HID and TTL.
Configure the communication modes by scanning barcodes or you can send serial commands from the Scan

<img src= https://github.com/sbcshop/Barcode-Scanner-Breakout/blob/main/images/breakout2.png />

# USB Setup 
## USB-COM Mode
  * The bar code can be set to USB virtual serial communication mode if the host application programme gets data via serial connection. The necessary driver must be installed on       the host before this function can be used.
  * Plug barcode scanner breakout to a computer or laptop  via a USB cable. Scan the USB-COM mode barcode,mention below (the module is defaults to USB-Keyboard mode)
  
    <img src= https://github.com/sbcshop/Barcode-Scanner-Breakout/blob/main/images/usb_com.JPG />

## USB-KBW Mode
There are two types of communication protocols to choose from when using the USB interface. The default mode is USB-KBW, which simulates a USB keyboard for data transmission to the host. to enable this mode, you need to scan below barcode. using this mode if you open notepad,word amd cmd etc, scan barcode, barcode is display in these tools

   <img src= https://github.com/sbcshop/Barcode-Scanner-Breakout/blob/main/images/usb_key.JPG />
   
## UART Mode (TTL/RS232)
The serial communication interface is a popular approach to connect barcode and host devices,like PCs and POS systems.To ensure data transmission accuracy when using the barcode scanner's serial communication interface, the barcode scanner and the host device must be completely matched in the serial communication protocol's setup parameters.To enable this mode you need to scan below barcode

   <img src= https://github.com/sbcshop/Barcode-Scanner-Breakout/blob/main/images/uart.JPG />
   
   <img src= https://github.com/sbcshop/Barcode-Scanner-Breakout/blob/main/images/img_.JPG /> 

  
  

### <a href="https://learn.sb-components.co.uk/Barcode-Scanner-Breakout" > Barcode Scanner Breakout Wiki Portal </a>



## Related Products

* [Zero Barcode HAT](https://shop.sb-components.co.uk/products/zero-barcode-hat?_pos=3&_sid=f80a0123d&_ss=r)

 ![Zero Barcode HAT](https://cdn.shopify.com/s/files/1/1217/2104/products/4_75f6c562-c6a1-4eb2-9fb0-686b64f20010.jpg?v=1669181323&width=400)

* [PICO Barcode HAT](https://shop.sb-components.co.uk/products/barcode-hat?_pos=1&_sid=c93c41208&_ss=r)

 ![PICO Barcode HAT](https://cdn.shopify.com/s/files/1/1217/2104/products/02.png?v=1669181209&width=400)
 
## Product License

This is ***open source*** product. Kindly check LICENSE.md file for more information.

Please contact support@sb-components.co.uk for technical support.
<p align="center">
  <img width="360" height="100" src="https://cdn.shopify.com/s/files/1/1217/2104/files/Logo_sb_component_3.png?v=1666086771&width=300">
</p>

