# Nasıl Kullanılır?

Öncelikle jquery kütüphanesini,  jTerminal.v1.1.js, jTerminal.v1.1.css dosyalarını sayfanıza include edin.

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

textSize: yazı boyutu.
textFont: yazı fontu.
textSpeed: yazının açılma hızı
textAlign: ekranın neresine yaslasın? 3 seçenek var left center right
textColor: yazı rengi.
textStyle: yazı stili.
textBold: yazı bold olsun mu? true false
textToUpper: büyük harf yapar.
textToLower: küçük harf yapar.
linkUnderline: linklerin altı çizilimi olsun ? true false
linkColor: link rengi. default #fff
cursorHide: İmleçi gizler.
cursorClose: Tüm yazılar açılınca imleç gizlensin mi ? true false
cursorToggle: tüm yazılar açıldıktan sonra imleç yanıp sönsün mü? imputlardaki gibi. true false
cursorColor: imleç rengi
cursorWidth: imleç kalınlıgı
backgroundColor: arkaplan rengi
cursorSpeed: imleç yanıp sönme hızı
contextmenu: sağ tık engellensin mi ? true false


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
                        linkColor       : "#fff"     ,
			textToUpper     :  false     ,  
			textToLower     :  false     , 
			cursorClose     :  false     ,  
			cursorToggle    :  true      ,  
			cursorColor     :  "#fff"    ,  
			backgroundColor	:  "#000"    ,  
			cursorSpeed    	:  500       ,  
			cursorWidth  	  :  "40px"    ,  
			contextmenu     :  true
		});
```

