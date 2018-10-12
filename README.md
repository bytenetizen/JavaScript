# JavaScript
 alert(window.location.href);
 
 if(navigator.userAgent.match(/Android/i)){
   //Код андроид
}
 
 https://habr.com/post/309430/
 
 <a href="https://shookes.com/upper/upper.php" target="_blank" onclick="this.href=\'fhdhdfhfd.html\'">Домашний фикус</a>
  var link = document.getElementById('Lnk');
        link.setAttribute("onclick","popupWin = window.open(this.href,'contacts','location,width=490,height=368,top=0'); popupWin.focus(); return false");



        var goo = device.android();
        if (goo == true){
            console.log(goo + ' ok ipad');
            $('.ios-url').attr('href', 'viber://chat?number=380670094964');
		}else{
            console.log(goo + ' no ipad');
            $('.ios-url').attr('href', 'viber://chat?number=+380670094964');
		}

 
 
 Вращение объектов в jQuery UI с помощью CSS transform
 http://vremenno.net/js/jquery-ui-rotation-using-css-transform/
 понадобится:
jquery.js
jquery.ui.core.js
jquery.ui.widget.js
jquery.ui.mouse.js
jquery.ui.draggable.js


 http://touchpunch.furf.com/
 
 $(document).ready(function() {
        $('th').filter(function(i, el) {
            return el.text().indexOf('Ваше фото') > -1;
        }).text('');
        )};
        
        
        $('th').filter(function(i, el) {
  return $(el).text().indexOf('Ваши фото') > -1;
}).text('');
        
          // (function() {
    //     var text = 'Ваше фото', // Текст, который надо найти
    //         regexp = new RegExp(text, 'i');
    //
    //     if (regexp.exec(document.getElementById('text').innerHTML)) {
    //         // Если нашло, то выполнить это
    //         var reg = new RegExp(text, 'g');
    //         document.getElementById('text').innerHTML = document.getElementById('text').innerHTML.replace(reg, '<span style="color: red">' + text + '</span>');
    //     } else {
    //         // Если не нашло, то выполнить это
    //         console.log('Текст не найдет');
    //     };
    // }());
