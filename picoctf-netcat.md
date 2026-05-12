# PicoCTF - Netcat

## El reto
Conectarme a un servidor usando netcat para obtener la flag.

## Lo que intenté
- nc -p49672 (incorrecto, -p es para puerto local)

## Solución
nc fickle-tempest.picoctf.net 49672

## Lo que aprendí
La sintaxis correcta de netcat es nc [host] [puerto].
La flag la obtuve conectándome directamente al servidor.
