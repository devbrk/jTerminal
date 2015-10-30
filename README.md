#[DEMO](http://goo.gl/gqgiEf/)

# Nasıl Kullanılır?

Öncelikle jquery kütüphanesini,  jTerminal.v1.1.js, jTerminal.v1.1.css dosyalarını sayfanıza dahil edin.

Ve listelenmesini istediğiniz yazıları ul ile girin.

Örnek;
```html
<ul id="test">
 <li>Satır 1</ul>
 <li>Satır 2</ul>
</ul>
```
Gibi.

Bunları yaptıktan sonra  script tagları arasında
```javascript
 $("ul#test").jTerminal();
```
yazarak eklentiye listeletmek istediğiniz ul'yi gönderin.
 
 
 Eklentiyi parametre girerek özelleştirebilirsiniz. 19 parametre seçeneği vardır.
 
# Parametreler:

textSize: yazı boyutu.<br />
textFont: yazı fontu.<br />
textSpeed: yazının açılma hızı<br />
textAlign: ekranın neresine yaslasın? 3 seçenek var left center right<br />
textColor: yazı rengi.<br />
textStyle: yazı stili.<br />
textBold: yazı bold olsun mu? true false<br />
textToUpper: büyük harf yapar.<br />
textToLower: küçük harf yapar.<br />
linkUnderline: linklerin altı çizilimi olsun ? true false<br />
linkColor: link rengi. default #fff<br />
cursorHide: İmleçi gizler.<br />
cursorClose: Tüm yazılar açılınca imleç gizlensin mi ? true false<br />
cursorToggle: tüm yazılar açıldıktan sonra imleç yanıp sönsün mü? imputlardaki gibi. true false<br />
cursorColor: imleç rengi<br />
cursorWidth: imleç kalınlıgı<br />
backgroundColor: arkaplan rengi<br />
cursorSpeed: imleç yanıp sönme hızı<br />
contextmenu: sağ tık engellensin mi ? true false<br />


# Örnek parametre kullanımı
```javascript
	$("ul").jTerminal({
			textSize        :  "16px"    ,
			textFont        :  "Menlo, Consolas, Monaco, monospace" ,
			textSpeed       :  1         ,  
			textAlign       :  "left"    ,  
			textColor       :  "lime"    , 
			textStyle       :  "normal"  ,  
			textBold        :  false     ,  
			linkUnderline   :  true      ,
			linkColor       :  "#fff"    ,
			textToUpper     :  false     ,  
			textToLower     :  false     , 
			cursorClose     :  false     ,  
			cursorToggle    :  true      ,  
			cursorColor     :  "#fff"    ,  
			backgroundColor	:  "#000"    ,  
			cursorSpeed    	:  500       ,  
			cursorWidth  	:  "40px"    ,  
			contextmenu     :  true
	});
```

