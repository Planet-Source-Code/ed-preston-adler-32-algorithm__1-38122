<div align="center">

## Adler\-32 algorithm


</div>

### Description

Pure visual basic implementation of the Adler-32 algorithm. It is much faster than the CRC32 algorithm yet still provides an extremely low probability of undetected errors. Commonly used in the ZLIB/Deflate Compressed Data Format Specification version 3.3. More info can be found at http://www.info-zip.org/pub/infozip/zlib/rfc-zlib.htm
 
### More Info
 
When passing byte arrays be carefull of the file size. It is best to break the file into chunks and call Adler32 multiple times. Byte array is limited to the amount of addressable memory in the process space. The outcome is, pass a 712 meg array and watch your machine grind to a halt while the hard disk tries to page things in and out of memory. Use chunks!


<span>             |<span>
---                |---
**Submitted On**   |2002-08-20 21:58:10
**By**             |[Ed Preston](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ed-preston.md)
**Level**          |Advanced
**User Rating**    |5.0 (40 globes from 8 users)
**Compatibility**  |VB 6\.0
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__1-3.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[Adler\-32\_a1202618202002\.zip](https://github.com/Planet-Source-Code/ed-preston-adler-32-algorithm__1-38122/archive/master.zip)








