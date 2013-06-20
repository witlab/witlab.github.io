WitLab's Gists
================
## 1. BarbeQR is a set of sample Java codes that write image files of barcodes, and QR codes.
###
HTML
<img src="./BarbeQR/codabar\_123456789.png"  alt="codabar_123456789.png" />

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">
<colgroup><col class="center" />
</colgroup>
<thead>
<tr><th scope="col" class="center">Generated Barcode Image Files</th></tr>
</thead>
<tbody>
<tr><td class="center"><img src="./BarbeQR/codabar\_123456789.png"  alt="codabar\_123456789.png" /></td></tr>
<tr><td class="center">CodaBar Barcode</td></tr>
<tr><td class="center"><img src="./BarbeQR/code128\_123456789.png"  alt="code128\_123456789.png" /></td></tr>
<tr><td class="center">Code128 Barcode</td></tr>
<tr><td class="center"><img src="./BarbeQR/code39\_123456789.png"  alt="code39\_123456789.png" /></td></tr>
<tr><td class="center">Code39 Barcode</td></tr>
<tr><td class="center"><img src="./BarbeQR/qrcode\_123456789.png"  alt="qrcode\_123456789.png" /></td></tr>
<tr><td class="center">QR Code</td></tr>
<tr><td class="center"><img src="./BarbeQR/qrcodeShiftJisJapanese\_123456789.png"  alt="qrcodeShiftJisJapanese\_123456789.png" /></td></tr>
<tr><td class="center">QR Code With Japanese Text</td></tr>
</tbody>
</table>

* ![CodaBar Barcode](./BarbeQR/codabar_123456789.png)
* ![Code128 Barcode](./BarbeQR/code128_123456789.png)
* ![Code39 Barcode](./BarbeQR/code39_123456789.png)
* ![QR Code Barcode](./BarbeQR/qrcode_123456789.png)
* ![QR Code With Japanese Text](BarbeQR/qrcodeShiftJisJapanese_123456789.png)

### Java Source Files

* ZXingEncoder class encodes the barcode content string and writes a PNG file.
[ZXingEncoder.java](https://gist.github.com/witlab/6e62441333410e3fd65d)

* ZXingDecoder class reads a PNG file with a barcode / QR code, and decodes it to a string value.
[ZxingDecoder.java](https://gist.github.com/witlab/4aedde8fa566229bbeee)

* TestZXingEncoderDecoder is a JUnit class to test ZXingEncode and ZXingDecoder classes.
[TestZXingEncoderDecoder.java](https://gist.github.com/witlab/5ec411ee74c4409d0b7e)

### Dependencies
* ZXing http://code.google.com/p/zxing/

-------------

