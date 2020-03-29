# reglas de HTML
Desarrollo WEB by ingcesaroman

# Inicio de cualquier archivo HTML
<_!DOCTYPE html_>

# Estructura basica
<_html_>\
<_head_>\
    <_title>Title<_/title_>\
<_/head_>\
<_body_>\
<_/body_>\
<_/html_>

# Tags mas ocupadas
* <img src="image.jpg or url""> (agregar imagenes)
* <a href="www.url.com"">go to url</a> (agregar un link o otra pagina en html)

# Listas y tablas
*  
*

# HTML Forms (sin _)
* <_form_> action="/sing-in-url" method="post" <_/form_>
* <_input type=""_>\
Tipos de inputs: \
"text", "date", "color", "file", "checbox", "radio", "select", "textarea"\
codigo para select\
<_select name="fildname"_> \
<_option>opcion1<_/option_>\
<_option>opcion2<_/option_>\
<_/select_>

* <_label_> Text: <_inpu type_> <_/label_>\
Syntaxis alterna usando atributos "for" & "id" \
<_label for="fildname"_> Text: <_/label_>\ 
<_inpu id="fildname" type_> 
* Validacion (marcar campos obligatorios)\
<_input type="" required_>\
