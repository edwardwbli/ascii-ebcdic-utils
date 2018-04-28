# ascii-ebcdic-utils
ASCII/EBDIC utility functions

## Usage

Node js  
```javascript
var asciiEbcdicUtils = require('ascii-ebcdic-utils');
```
Browser
```javascript
<script src="a2e.js"></script>

```

## Examples

```
asciiEbcdicUtils.asciiStrToEbcdicStr('db2jcc');
>> [ '84', '82', 'F2', '91', '83', '83' ]
```

```
asciiEbcdicUtils.bytesToAscii(['84', 'F2', '91', '83', '83']);
>> INDòPU1NBHNBH
```

```
asciiEbcdicUtils.bytesToEbdic(['84', 'F2', '91', '83', '83']);
>> db2jcc
```
```javascript
var ebcdic = a2e.asciiStrToEbcdicChr('!@##$%^&*()_+=-?><,./~`012345678ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz')
var ascii = a2e.ebcdicStrToAsciiChr(ebcdic)
</script>
```