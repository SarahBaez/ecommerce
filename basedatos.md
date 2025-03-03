# Decripcion base de datos
Los **procedimientos almacenados** en Alquiler Smart optimizan la gestión de apartamentos, inquilinos y contratos, permitiendo realizar operaciones clave de manera eficiente:

* _InsertarApartamento_: Agrega un nuevo apartamento a la base de datos.
* _actualizarApartamento_: Modifica los datos de un apartamento existente.
* _eliminarInquilino_: Borra a un inquilino registrado.
* _ObtenerDetallesContrato:_ Recupera información detallada de los contratos y sus inquilinos.
* _ObtenerPagosPorApartamento:_ Suma los pagos realizados por apartamento para un mejor control financiero.
Cada uno de estos procedimientos está asociado a botones en la interfaz que permiten agregar, editar, eliminar o consultar datos de manera sencilla.

**Índices**
Se han definido índices para mejorar el rendimiento de las consultas frecuentes en la base de datos:

* _idx_inquilino_apartamento:_ Acelera la búsqueda de inquilinos asociados a un apartamento.
* _idx_contrato_inquilino:_ Optimiza la gestión de contratos vinculados a inquilinos.
* _idx_pagare_contrato:_ Mejora el acceso a pagarés relacionados con contratos.
* _idx_estado_fecha:_ Facilita la búsqueda de contratos según estado y fecha de inicio.
* _idx_estado_vencimiento:_ Permite encontrar pagarés vencidos o pendientes según la fecha.
Estos índices optimizan consultas recurrentes, como filtrar contratos vigentes dentro de un periodo o identificar pagos vencidos, asegurando una mayor eficiencia en la gestión de datos.
