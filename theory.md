# Angular !!

Angular en el trabajo !== Angular en la vida real
En trabajo -> tienen miedo -> cliente
Angular pre 16 -> Angular viejo -> Modulos


## Conceptos base

Stand Alone Component -> componente que solo va a contener unicamente lo necesario para funcionar(Nueva forma, desfasada es con modulos)

Modulo -> Cada componente es un modulo



Backbone -> SPA -> AngularJS -> React

MVC -> M -> V -> C (EN ESTE CASO, MODELO ES LA PARTE DE ENTIDADES Y DATOS, ADEMAS DE REGLAS DE NEGOCIO, VISTA ES LA APRTE QUE LOS REPRESENTABA VISUALMENTE Y CONTROLADOR ES QUIEN SE ENCARGA DE COMUNICAR EL MODELO Y VISTA )

AngularJS -> comunidad -> directivas(lo que le da a Angular la categoria como plataforma estructural)
Plataforma estructural -> ¿Cuando es? -> Permite aumentar las funcionalidades en elementos del DOM que antes no lo tenian

E.g -> *ngIf -> Es una directiva -> Renderizar o no algo

Angular Way -> La manera de hacer las cosas segun Angular

SSR(Server-Side Rendering) -> html + js(sin embargo, primero se muestra el HTML y por detras une el JS y el html estatico para hacer la pagina dinamica, a esto se llama 'hidratacion')

QwikJs(parecido a Signal) inventa Resumability -> Server -> Html + json -> Boton -> ID_BOTON: script

Cambio component -> Todo Cambio(MAL Y ANTIGUAMENTE PASABA)
Cambio componente -> Donde impacta ese cambio?(BUENA PRACTICA)

Reactive Programming -> Antes con RxJS
Se base en:
- Canales -> Es un tubo con agujeritos
- En estos agujeritos hay espectadores -> Vam a mirar atraves de esos agujeritos
- Eventos -> Se pasa un objeto por el tubo

Cada espectador es humano, cada uno es su propio mundo, cada uno ve lo que quiere
- 1 -> paso una pelota
- 2 -> era verde
- 3 -> paso a 20 km/h

Signals -> Son nuestros canales(Por donde se transmiten los eventos)
- 1 -> Alguien tiene que mandar el evento
- 2 -> Alguien tiene que recibir el evento

Quienes se ven impactados por cambios ? los que usen el canal

RxJS -> Biblioteca que maneja observables
- Observables -> Tubo solo uno puede mandar una pelota | Unidireccional
- Subject -> Tubo donde todos pueden mandar una pelota | Bidireccional
- BehaviorSubject -> Tubo donde todos pueden mandar una pelota, PERO siempre queda la ultima pelota
