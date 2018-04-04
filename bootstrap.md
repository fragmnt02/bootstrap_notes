# SISTEMA DE REGILLAS:
los contenedores van en el siguiente orden container -> row -> col

Contenedores:
```
containe
container-fluid
row
col
```
`container-fluid` si se quiere que ocupe el ancho completo

tamaños:
```
col-xs 
col-sm 
col-md
col-lg 
col-xl 
```
Nota: `col`(xs) `col-12` `col-sm-12` `col-md-12` `col-lg-12` `col-xl-12` si se pone `col-12` va a a tomar 12 en todos los tamaños

# OCULTACIÓN
para que no se vea d-none y eso afectara del mas pequeño al mas grande para cortar ese efecto usar d-md-block en el tamaño deseado
```
d-xs-none
d-sm-none
d-md-none
d-lg-none
d-xl-none
d-sm-block
d-sm-inline
```

# ALINEACIÓN
para alinear contenido se usa `float-left` y `float-right`, se puede usar en tamaño, ejemplo `float-xl-left`.

border se utiliza para dibujar un borde

`clearfix` se utiliza para cuando haya mucho contenido no se choquen
```
mx-auto
justify-content-start
justify-content-center
justify-content-end
justify-content-between
justify-content-around
align-items-start 
align-items-center 
align-items-end 
align-self-start 
align-self-center 
align-self-end
fixed-top
fixed-bottom
 ```

# TAMAÑO 
`w` (ancho): utiliza un porcentaje por ejemplo `w-75` ->utiliza el 75% del ancho del contenedor

`h` (alto): el mismo caso del anterior

`p` (padding): se combina con los de abajo -> margin es el espacio entre el contenido con el contenedor

`m` (margin): funciona igual que el anterior -> margen es el espacio entre el contenedor y el area de trabajo. Se utilizan asi: `mt-23` que significa `margin-top:23px;`
`t` (top)

`b` (bottom)

`l` (left)

`r` (right)

# TIPOGRAFÍA
`display` cambia fuente va de 0 a 4... ejemplo `display-4`.

`small` hace fuente chica
`mark` da sombreado

 Nota: 
`font-weight-bold` es negritas 

`font-weight-normal` es normal 

`font-weight-light` suave 

`font-italic` cursiva

`text-justify` jusitfica el texto

`text-left` texto a la izquierda

`text-right` texto a la derecha

`text-center` texto al centro

`text-nowrap` - que sea solo una linea

`text-lowercase` minuscula

`text-uppercase` mayuscula

`text-capitalize` Cada Palabra Empieza En Mayuscula Asi

# BACKGROUND  Y COLORES
`bg-primary` azul

`bg-secondary` gris oscuro

`bg-success` verde 

`bg-info` azul agua

`bg-warning` amarillo

`bg-danger` rojo

`bg-dark` gris mas oscuro casi negro

`bg-light` blanco

 Nota: los colores funcionan con `text`, `table` igual

# TABLAS
para dar diseño a tablas:
 - table: solo una linea divisores de columnas
 - table-striped igual que el anterior pero sombrea
 - table-bordered tabla comun rayas grises

 - table-hover se sombrea cuando pasa el mouse por encima

 para colorear tabla
 - table-primary
 - table-secondary
 - table-success
 - table-danger
 - table-info
 - table-warning
 - table-active
 - table-dark
 - table-light

 - table-sm reduce de tamaño la tabla 
 - table-responsive la hace responsive
 a partir de cual es responsive:
 - table-responsive-sm
 - table-responsive-md
 - table-responsive-lg
 - table-responsive-xl
  
# IMÁGENES 
 - rounded bordes redondeados
 - rounded-circle le da forma circulo

 - img-thumbnail crea un marco en la imagen

 alinea izquierda o derecha:
 - float-left
 - float-right

 - img-fluid que se adapta a el tamaño del contenedor

Nota: le funcionan w y h, por ejemplo h-20 -> height:20px;

  
# JUMBOTRON
 - jumbotron lo resalta o mete en una caja
 - jumbotron-fluid no deja espacio de margen entre la caja y el texto
 
# ALERT 
 - alert lo resalta mediante espaciado

 colorea el alert
 - alert-success
 - aler-info
 - alert-warning
 - alert-danger
 - alert-primary
 - alert-secondary
 - alert-light
 - alert-dark

 - alert-link
 - alert-dismissable agrega boton para cerrar el remarcado, se necesita crear un boton de clase close, data-dismiss alert y contenido &times;
   
# BOTONES  
 - btn clase que hay que agregar para diseño de bootstrap

 colores de boton
 - btn-primary
 - btn-secondary
 - btn-success
 - btn-info
 - btn-warning
 - btn-danger
 - btn-dark
 - btn-linht

 - btn-link

 color borde boton (boton blanco)
 - btn-outline-primary
 - btn-outline-secondary
 - btn-outline-success
 - btn-outline-info
 - btn-outline-warning
 - btn-outline-danger
 - btn-outline-dark
 - btn-outline-light
 - btn-outline-link

tamaño boton
 - btn-lg grande 
 - btn-sm chico
 - btn-block ocupa todo el ancho de la pagina
 remarca boton por activo o desabilitado (no deja usar)
 - active
 - disabled

# GRUPO DE BOTONES 
 - btn-group clase para grupo de botones (horizontal)
 
 tamaños de botones
 - btn-group-lg 
 - btn-group-sm 
 - btn-group-xs 

 modifica a grupo vertical
 - btn-group-vertical 
 
 - dropdown-toggle crea menu desplegable en boton
 - dropdown-menu crea un menu desplegable, esto va en un div
 - dropdown-item  crea un item de un menu desplegable, esto en un a

# INSIGNIAS 
 - badge remarca un texto como para marcar algo asi como jefe

 color de insignia
 - badge-primary
 - badge-secondary
 - badge-success
 - badge-danger
 - badge-warning
 - badge-info
 - badge-light
 - badge-dark

 - badge-pill  le cambia tantito la forma como de pildora
 - inside para ponerlo dentro de botones

# BARRA DE PROGRESO 
 - progress  clase contenedora de la barra de progreso
 - progress-bar clase en un tag donde escribes el porcentaje tal cual y aparece la barra, funciona con height and weight

agrega lineas a la barra
 - striped
 - progress-bar-striped

 - progress-bar-animated agrega animacion
  
# PAGINACIÓN 
 - pagination barra de navegacion como < prev 1 2 3 next >, esto va en un ul tag
- page-item va en un li y representa cada numero de la barra

activa o desactiva boton
 - active
 - disabled

 - sizing
cambia tamaño, va en pagination
 - pagination-lg
 - pagination-sm

otra barra de navegacion diferente estilo directorio, se maneja igual
 - breadcrumb -> breadcrumb-item
 
# LISTAS  
funciona como html
 - list-group ul
 - list-group-item li

 activar o desactivar item
 - active
 - disabled  
igual funciona con div y a tags
- list-group-item-action: cambia el color de un item

# TARJETAS  
 - card div funciona con w y h
 componentes:
 - card-header
 - card-body
 - card-footer
 - card-title
 - card-text 
 - card-link

# DROPDOWN MENU 
va en un div con clase dropdown
    dentro va un boton con data-toggle dropdown y clase dropdown-toggle
 - dropdown-menu clase del div contenedor del menu
 - dropdown-item clase del a tag que compone al menu
 - dropdown-divider div que se cierra y se abre en la misma linea que sirve para dividir el menu
 - dropdown-header div para agregar titulo al menu
 - dropup si se cambia dropdown por dropup en el div principal, el menu se despliega hacia arriba

# PLEGABLES  
 - collapse data-toggle que se le agrega a un boton, ademas de un data-target con el id del contenido a mostrar cuando se accione
    el contenido a mostrar debe tener el id del data target anterior y clase collapse
 - show

# MENÚS DE NAVEGACIÓN
va dentro de column
 - nav clase del ul que contiene cada item
 - nav-item clase del li
 - nav-link clase del a que va dentro del li
 - disabled desabilita algun boton del menu
 - justify-content-start mueve los botones a la izquierda
 - justify-content-center mueve los botones al centro
 - justify-content-end mueve los botones a la derecha
 - flex-column pone el menu vertical
 - nav-pills da forma de pildora a los botone s del menu
 - nav-justified se separan los botones y distribuyen a lo ancho
 - dropdown se agrega la clase a un boton mas la estructura del dropdown para hacer un dropdown en un boton
  
# BARRA DE NAVEGACIÓN  -  3:39:32
 - navbar clase del nav que contiene a todo
 - navbar-nav clase del ul que contiene a los items
 - navbar-item clase del li que representa cada item del menu
 - navbar-link clase del a tag que va dentro del li
 - nav-expand-sm a partir de que tamaño se vuelve horizontal
 - navbar-brand clase para el logo que es un a tag, antes del ul

 para hacer un menu mobile desplegable se utiliza un boton con clase navbar-toggler, data-toggle collapse y data-target con el id del div objetivo. Dentro un span con clase navbar-toggler-icon.
 posteriormente un div con clase collapse navbar-collapse y el mismo id que en el data-target del boton, este div debe cubrir todo el lu.
 igual al nav contenedor se le agrega la clase nav-expand-sm

igual se pueden agregar dropdown como en el nav anterior

 - fixed-top se agrega en la clase del nav principal para fijar el navbar
 - fixed-bottom lo mismo pero abajo en vez de arriba

# FORMULARIOS  -  3:59:12
 - form-control
 - form-check-label
 - form-check-input
 - form-control
 - disabled
 - textarea
 - form-check
 - form-check-input 
 - form-check-inline
 - form-check-label
 - radio-inline
 - select

# CAROUSEL  -  4:16:09
 - carousel
 - slide
 - carousel-indicators
 - carousel-inner
 - carousel-item
 - carousel-caption
 - carousel-control-prev
 - carousel-control-next
 - carousel-control-prev-icon
 - carousel-control-next-icon

# MODAL  -  4:29:45
 - modal 
 - fade
 - modal-dialog
 - modal-content
 - modal-header
 - modal-title
 - modal-dialog
 - modal-body
 - modal-footer
