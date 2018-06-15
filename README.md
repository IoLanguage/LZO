# LZO 
The LZO object can be used to compress and uncompress data using the 
<a href=http://en.wikipedia.org/wiki/Lempel-Ziv-Oberhumer> Lempel-Ziv-Oberhumer (LZO)</a> 
lossless data compression algorithm.

Example use:
```Io
compressedData := LZO compress(uncompressedData)
uncompressedData := LZO uncompress(compressedData)
```

# Installation
```
eerie install https://github.com/IoLanguage/LZO.git
```
