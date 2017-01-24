# bitaddress.org Derivative 

Instead of regular money that people usually receive in red envelopes, I thought it would be cool to surprise my friends with Bitcoin instead! It's much more memorable of me personally and is almost as useful as cash.

I made the following design and adapted it to a Bitcoin paper wallet generator. The dimensions are exactly those of a US Dollar, enabling the use of existing red envelopes. 
![image of bitcoin wallet]
(sampleWallet.png)

Original art painting by Liu ZhiKun, 2013. 

How to generate your own wallets:

1. Click "Clone or download" in Github. 
2. Extract archive 
3. Run "bitaddress.org.html" to generate offline keys 
4. Check the box that says "BIP38 Encrypt?". I did not adjust the javascript to format non-encrypted wallets correctly. 


How to replace the rooster image: The image of the rooster is encoded as a base64-encoded PNG in two different files. See commit history. Warning: 1MB text files. 

Comment on Reddit: https://www.reddit.com/r/Bitcoin/comments/5puyew/put_something_different_in_those_chinese_new_year/


Notice of Copyrights and Licenses:
---------------------------------------
The bitaddress.org project, software and embedded resources are
copyright bitaddress.org.

The bitaddress.org name and logo are not part of the open source
license.

Portions of the all-in-one HTML document contain JavaScript codes that
are the copyrights of others. The individual copyrights are included
throughout the document along with their licenses. Included JavaScript
libraries are separated with HTML script tags.

Summary of JavaScript functions with a redistributable license:

JavaScript function	|	License
-------------------	|	--------------
Array.prototype.map	|	Public Domain
window.Crypto | BSD License
window.SecureRandom	| BSD License
window.EllipticCurve	|	BSD License
window.BigInteger |	BSD License
window.QRCode | MIT License
window.Bitcoin | MIT License

The bitaddress.org software is available under The MIT License (MIT)
Copyright (c) 2011-2013 bitaddress.org

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
