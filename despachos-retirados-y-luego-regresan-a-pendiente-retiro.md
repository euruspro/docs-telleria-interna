---
description: >-
  Tiene relación con la validación que realiza el robot que verifica los
  despachos parciales.
---

# Despachos retirados y luego regresan a Pendiente Retiro

1.- El diseño original del robot, debe recalcular el estado DIN para cuando se cumplan los criterios establecidos.

2.- De acuerdo al punto anterior, el robot de control de retiros de bultos, establece que no se puede marcar un despacho como retirado, sin que existan retiros.

3.- Es por los puntos anteriores, que un robot se contrapone contra el otro.

4.- Finalmente, cuando ocurren estos casos, se debe proceder a generar los respectivos retiros para que los depachos queden retirados.
