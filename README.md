# Sistema de Gestión de E-commerce en Go

Proyecto académico de la asignatura **Programación Estructurada y Funcional 2**, de la **Universidad Internacional del Ecuador (UIDE)**.

## Objetivo

Planificar y desarrollar una aplicación de consola en **Go (Golang)** para administrar productos, controlar existencias y simular operaciones de compra, aplicando principios de programación funcional.

## Estado del proyecto

**Etapa 1: planeación y configuración inicial del repositorio.** La lógica de negocio aún no está implementada.

## Módulos previstos

| Módulo | Responsabilidad |
| --- | --- |
| Productos | Registrar, consultar, buscar y actualizar artículos |
| Inventario | Consultar y validar existencias |
| Carrito | Agregar y retirar artículos; calcular subtotales y total |
| Pedidos | Validar compras, generar resúmenes y registrar pedidos |

## Enfoque de desarrollo

- Lenguaje: **Go**.
- Interfaz: **consola**.
- Datos: archivos locales **JSON**.
- Principios: funciones puras para cálculos y validaciones, y separación de las operaciones de entrada/salida.
- Dependencias previstas: biblioteca estándar de Go; sin paquetes de terceros en la primera versión.

## Estructura

```text
gestion-ecommerce-go/
├── go.mod
├── main.go
├── internal/
│   ├── productos/productos.go
│   ├── inventario/inventario.go
│   ├── carrito/carrito.go
│   └── pedidos/pedidos.go
├── datos/
│   ├── productos.json
│   └── pedidos.json
├── docs/README.md
├── README.md
└── .gitignore
```

## Ejecución de la estructura inicial

Con Go instalado, desde la raíz del repositorio:

```bash
go run .
```

Por ahora solo se muestra un mensaje de inicio; los módulos se desarrollarán en una fase posterior.

## Alcance

No se incluyen pagos reales, autenticación avanzada, plataforma web ni gestión de envíos reales.

## Autoría

Proyecto desarrollado individualmente con fines académicos.
