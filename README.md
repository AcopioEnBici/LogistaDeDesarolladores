# LogisticaDeDesarolladores

## Idea Basica

a) Donadores de viveres registran su intencion y ubicacion en plataforma web

b) Admin de AcopioEnBici registra ciclistas y centros de acopio en plataforma web

c) Ciclistas recogen donaciones hasta donde puedan y luego se les guia al centro de acopio más cercano por app movil.

## Equipos

Añadan info relevante

Backend: NodeJS ( https://github.com/AcopioEnBici/API-REST ) creo que @artgoce, @organillero y Marco estaban viendo este tema

Frontend Web: ? Quienes

Apps: Ionic ??? Quienes

Apple: SWIFT @backmota


## Requerimientos

Liga de requerimientos:

https://docs.google.com/document/d/1lT_O_qe-NLbq1Na36kDRadQA5EDQtB7xkSb5QFfQnuA/edit?usp=sharing

https://hangouts.google.com/call/1-hoTMFwyxlCMKkKBC3VAAkE

## TODO:
Lista de pendientes actualizada:
crud de centros en la referencia 'centers', debe llevar { name, active, latitude, longitude }, lleva un mapa con pin arrastrable
que al registrar donacion guarde la ubicacion actual en la donacion en las props, latitude y longitude (ya hace todo lo demás, solo es agregar eso + el mapa con el pin arrastrable tmb)
falta tomar la ubicacion del voluntario dinamicamente en la directiva de map-near-points, asi como comentar los datos dummy en VolunteersCtrl y descomentar los datos reales (estan justo abajo)
falta arreglar el filtro para sacar las ubicaciones cercanas
terminar de probar el flujo del voluntario recogiendo y entregando la donación
en vivo el mapa de google pide un api key hay que ponerle una
y por el momento no puedo pensar en otro punto, yo mañana le sigo, aunque no podré darle todo el día, si tienen dudas con gusto les respondo cuando este, de preferencia por correo para que no haya pierde a edgardo.robledo@gmail.com
por último les comento que para subir los cambios a la github page solo hay que hacer push de la carpeta compilada app al repo de acopioenbici.github.io
esta es la libreria de los mapas y hay algunos ejemplos en el modulo para entregar
https://ngmap.github.io
