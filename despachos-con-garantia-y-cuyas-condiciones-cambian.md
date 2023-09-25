---
description: >-
  El robot configurado para este proceso es el "Robot de Clasificación y
  Definición de Inscripción y Garantía"
---

# Despachos con garantía y cuyas condiciones cambian

1. El criterio de exclusión se basa en el Código de Tipo de Bulto, el cual, según definición, excluye de clasificar despachos cuyo tipoBulto1 sea diferente a uno de los siguientes: 'CONT20', 'CONT40', 'REEFER20', 'REEFER40', 'CONTNOESP'
2. Se evalúa cada que el despacho se modifique para cumplir este requisito, o que en su defecto se modifique la asignación del Estado de Garantización, pero no se evalúa si el despacho ya cuenta con un registro de Garantía o Inscripción realizado, puesto que prevalece este último.
3. De acuerdo a lo anterior, el sistema permite cargar Registros de Garantia, solo cuando los criterios así lo establecen. Por ejemplo: cuando se crea el registro de Garantización, el despacho tenía como tipo de bulto el código "CONT40", cumpliendo con la regla.
4. Cuando ocurran estos casos, como por ejemplo, que originalmente tenga el código de Tipo de Bulto con los establecidos en el punto 1 y luego cambie a otro, se debe proceder a:

* Deben anular el registro de garantización existente. Con ello, el robot recalculará el Estado DIN y con ello el estado de Inscripción y Garantización.
