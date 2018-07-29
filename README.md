# JavaScript
 alert(window.location.href);
 
 
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
