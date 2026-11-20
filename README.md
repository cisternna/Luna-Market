## Descripción

Construcción e implementación (programación) de las interfaces de usuario para el sistema de gestión de pedidos de una cadena de supermercados.

## Equipo de trabajo

- Dahiana Gonzales P. -- **Jefa de Grupo** 
- Javiera Orellana L.  
- Fernanda Vergara A. 
- Matías Cisterna E.  

## Tecnologías utilizadas

- HTML5 (estructura semántica)
- CSS3 (estilos externos y diseño responsivo)
- JavaScript (lógica de las interfaces, sin frameworks)
- Navegador para simular la base de datos
- Git y GitHub para control de versiones

## Instrucciones de ejecución

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/cisternna/Luna-Market
   ```
2. Abrir la carpeta del proyecto.
3. Abrir el archivo `index.html` en un navegador web.

## Credenciales de prueba

| Perfil | Usuario | Contraseña |
|---|---|---|
| Administrador | `[admin]` | `[contraseña]` |
| Usuario | `[user]` | `[contraseña]` |

> Tras 3 intentos fallidos consecutivos la cuenta se bloquea (RIU 2).

## Perfiles y vistas

| Perfil | Vistas disponibles |
|---|---|
| **admin** | Home, Productos, Procesamiento de Pedido |
| **user** | Home, Pedidos, Pedidos Ingresados |

## Estructura del proyecto

```
/
├── README.md
├── index.html
├── css/
│   └── styles.css
├── js/
│   ├── auth.js
│   ├── data.js
│   └── main.js
├── pages/
│   ├── pedidos.html
│   ├── pedidos-ingresados.html
│   ├── productos.html
│   ├── producto-form.html
│   └── procesamiento.html
├── img/
│   └── logo.png
└── docs/
    └── prompts.md
```

## Estado de avance

| Hito | Descripción | Estado |
|---|---|---|
| 1 | Conformación del equipo, repositorio y corrección de la Evaluación 2 | En curso |
| 2 | Plantilla base, Login y control de perfiles (RIU 1, 2, 3, 8, 9, 10) | Pendiente |
| 3 | Interfaces perfil user: Pedidos y Pedidos Ingresados (RIU 4, 5) | Pendiente |
| 4 | Interfaces perfil admin: Productos y Procesamiento (RIU 6, 7) | Pendiente |
| 5 | Refactorización, diseño responsivo y Plan de Pruebas | Pendiente |
| 6 | Matriz de trazabilidad e informe final | Pendiente |

*Fecha de entrega: domingo 6 de diciembre de 2026, 23:59 hrs.*
