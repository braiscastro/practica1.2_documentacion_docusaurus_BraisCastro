# Diseño del sistema: diagrama de clases

## Clase Cliente

Atributos:
- id: identificador.
- nombre: nombre completo.
- email: correo electrónico.

Responsabilidad: almacenar los datos de cada cliente.

## Clase Producto

Atributos:
- id: identificador.
- nombre: nombre del producto.
- precio: precio unitario.
- stock: unidades disponibles.

Responsabilidad: representar los productos del negocio.

## Clase Pedido

Atributos:
- id: identificador.
- cliente: cliente asociado.
- productos: productos incluidos.
- total: importe total.

Responsabilidad: registrar compras y calcular su importe.

## Relaciones

- Un cliente puede realizar varios pedidos.
- Cada pedido pertenece a un único cliente.
- Un pedido puede incluir varios productos.
- Un producto puede aparecer en diferentes pedidos.
