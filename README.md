# AMIIN by Idraet Group - E-commerce Platform

[![Laravel](https://img.shields.io/badge/Laravel-11-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com)
[![Livewire](https://img.shields.io/badge/Livewire-3.0-FB70A9?style=for-the-badge&logo=livewire&logoColor=white)](https://livewire.laravel.com)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![PHP](https://img.shields.io/badge/PHP-8.2+-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![MercadoPago](https://img.shields.io/badge/MercadoPago-Integrated-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mercadopago.com.ar)

**Plataforma e-commerce personalizada para la marca AMIIN de Idraet Group.** Diseno fiel a la identidad de marca, panel administrativo intuitivo, integracion con MercadoPago y ShipNow, multiples metodos de pago y gestion de tiendas fisicas con retiro en sucursal.

---

## Screenshots

### Pagina Principal
<img width="1440" height="852" alt="image" src="https://github.com/user-attachments/assets/7c07e0c6-7d72-44e4-a09a-2289652ae962" />
<img width="1440" height="899" alt="image" src="https://github.com/user-attachments/assets/8ae1db94-d6e2-45a9-8360-c4689e98b82c" />
<img width="1439" height="995" alt="image" src="https://github.com/user-attachments/assets/c489a5d7-202c-4026-8c09-998e652381fd" />
<img width="1445" height="1147" alt="image" src="https://github.com/user-attachments/assets/671c6cf8-964d-4591-b7fa-ea77f540e8da" />
<img width="1438" height="577" alt="image" src="https://github.com/user-attachments/assets/d489ba69-7522-4ede-96e5-68c5fa5530c3" />
<img width="1442" height="714" alt="image" src="https://github.com/user-attachments/assets/4ad5f3b0-cc51-4711-84e2-80b6a94a9bf5" />

### Rutinas
<table>
  <tr>
    <td><img width="400" alt="Vista Rutina" src="https://github.com/user-attachments/assets/2a69be85-c374-4435-aea4-723d6161e3aa"/></td>
    <td><img width="400" alt="Modal Rutina" src="https://github.com/user-attachments/assets/72861d7f-2bf1-4bd7-9052-6139aaedcbb6" /></td>
    <td><img width="400" alt="Confirmacion Rutina" src="https://github.com/user-attachments/assets/b75f444c-a3ce-49af-86fb-ba035e16d00d" /></td>
  </tr>
</table>

### Producto
<table>
  <tr>
    <td><img width="400" alt="Ver Producto" src="https://github.com/user-attachments/assets/fdece27c-d9a7-456f-984a-6bf34ad569a1"/></td>
    <td><img width="400" alt="Detalle Producto" src="https://github.com/user-attachments/assets/a26bc798-ee1e-4ab9-95e7-fa914b1fee69" /></td>
    <td><img width="400" alt="Modal de confirmacion agregacion carrito" src="https://github.com/user-attachments/assets/ce18ac58-ff5a-41bb-b9da-45aed9258016" /></td>
  </tr>
</table>

### Panel Administrativo
<table>
  <tr>
    <td><img width="400" alt="Productos" src="https://github.com/user-attachments/assets/544f3b1e-a997-4298-bc67-e9921de312b3" /></td>
    <td><img width="400" alt="Pedidos" src="https://github.com/user-attachments/assets/1233dd82-f588-4771-b076-1dbf459dcc7b" /></td>
    <td><img width="400" alt="Configuracion" src="https://github.com/user-attachments/assets/bf19183c-1381-478f-9ceb-083e6ea81389" /></td>
  </tr>
</table>

### Emails con estados de pedido
<table>
  <tr>
    <td><img width="400" alt="Orden Creada" src="https://github.com/user-attachments/assets/6cc2e4f0-0c50-4573-bf91-3cfb032e349b" /></td>
    <td><img width="400" alt="Pago Confirmado" src="https://github.com/user-attachments/assets/b3d106a9-93b0-4d65-ad9f-7b27f6a90130" /></td>
    <td><img width="400" alt="Listo para Retirar" src="https://github.com/user-attachments/assets/cf33d1dc-39a2-4143-b4b7-13ef0c199010" /></td>
    <td><img width="400" alt="Orden Completada" src="https://github.com/user-attachments/assets/270d1acb-0d27-4e90-8ce1-6dc32c4bce2b" /></td>
  </tr>
</table>

### Emails de autenticación
<table>
  <tr>
    <td><img width="400" alt="Verificar Email" src="https://github.com/user-attachments/assets/11f5d5ee-8ebe-470d-96b7-f369c80446ba" /></td>
    <td><img width="400" alt="Resetear Password" src="https://github.com/user-attachments/assets/de6278d4-4435-4a48-a9f0-49953ccf0417" /></td>
  </tr>
</table>

---

## Stack Tecnico

<table>
<tr>
<td width="50%">

### Frontend
- **Componentes**: Livewire / Volt (reactivos, SPA-like)
- **Estilos**: TailwindCSS 3.4 + SCSS
- **Build**: Vite 6.0
- **Mapas**: Leaflet (ubicacion de tiendas)
- **Interactividad**: Alpine.js (integrado con Livewire)

</td>
<td width="50%">

### Backend
- **Framework**: Laravel 11 + Shopper Framework 2.1
- **Auth**: Sanctum + Socialite (Google OAuth)
- **Base de datos**: MySQL + Eloquent ORM
- **Pagos**: MercadoPago SDK (Checkout Pro + Bricks)
- **Envios**: ShipNow API (multi-carrier)
- **Admin**: Filament (panel extendido)

</td>
</tr>
</table>

---

<details>
<summary><strong>Problema de Negocio & Solucion</strong></summary>

### Problemas Identificados
- **Venta limitada a canales tradicionales**: Sin presencia digital propia para la venta directa de productos skincare
- **Gestion manual de pedidos**: Seguimiento por WhatsApp/email sin trazabilidad ni estados automatizados
- **Falta de identidad digital**: Necesidad de un e-commerce que refleje la estetica premium de la marca AMIIN
- **Envios sin automatizar**: Cotizaciones manuales con cada transportista, sin comparacion en tiempo real
- **Multiples puntos de venta**: Tiendas fisicas sin gestion centralizada de horarios y ubicaciones

### Solucion Implementada
- **E-commerce a medida**: Tienda online con diseno fiel a la marca, rutinas de skincare interactivas y catalogo completo
- **Checkout inteligente**: Flujo de compra con validacion de direcciones, cotizacion automatica de envios y multiples medios de pago
- **Panel administrativo**: Gestion completa de productos, ordenes, descuentos, newsletters y tiendas desde un solo lugar
- **Integraciones nativas**: MercadoPago para pagos, ShipNow para envios multi-carrier y Google OAuth para autenticacion
- **Notificaciones automaticas**: Emails transaccionales en cada cambio de estado del pedido

</details>

---
<details>
    <summary>
        <strong>
            Arquitectura del Sistema
        </strong>
    </summary>
    
### Flujo de Estados de Ordenes
    
```mermaid
graph LR
    A[NUEVA] --> B[PENDIENTE]
    B --> C[REGISTRADA]
    C --> D[PAGADA]
    D --> E[LISTA PARA RETIRAR]
    D --> F[ENVIADA]
    E --> G[COMPLETADA]
    F --> H[ENTREGADA]
    H --> G
    A --> I[CANCELADA]
    B --> I
    C --> I
    D --> I
```

### Flujo de Checkout
```mermaid
graph TD
    A[Carrito] --> B[Login / Registro]
    B --> C[Datos de Envio]
    C --> D{Tipo de Entrega}
    D -->|Delivery| E[Cotizacion ShipNow]
    D -->|Retiro en Tienda| F[Seleccionar Sucursal]
    E --> G[Metodo de Pago]
    F --> G
    G -->|MercadoPago| H[Redirect MP]
    G -->|Transferencia| I[Datos Bancarios]
    H --> K[Orden Confirmada]
    I --> K
```
    
</details>

---

<details>
    <summary>
        Caracteristicas Principales
    </summary>

### Tienda Online
- Catalogo de productos con variantes, precios y stock
- Sistema de rutinas de skincare en 5 pasos interactivos
- Busqueda de productos y filtrado por categorias
- Lista de favoritos/wishlist por usuario
- Diseno responsive (mobile, tablet, desktop)

### Carrito & Checkout
- Carrito persistente con calculo automatico de totales
- Checkout en pasos: direccion, envio, pago, confirmacion
- Validacion de stock en tiempo real antes de confirmar
- Descuentos por cupon y campanas globales de descuento

### Medios de Pago
- **Tarjetas Credito/Debito**: Pago con tarjeta via MercadoPago checkout seguro
- **Transferencia bancaria**: Pago por deposito con instrucciones automaticas
- Actualizacion automatica del estado del pedido segun resultado del pago

### Envios Multi-Carrier (ShipNow)
- Cotizacion en tiempo real con multiples transportistas
- Envio a domicilio o retiro en sucursal del transportista
- Calculo automatico del costo de envio segun destino y peso

### Tiendas Fisicas
- Gestion de multiples sucursales con direccion y contacto
- Horarios de atencion por dia (7 dias, apertura/cierre)
- Estado en tiempo real (abierto/cerrado + proxima apertura)
- Mapa interactivo con ubicaciones (Leaflet)
- Retiro en tienda como opcion de envio en checkout

### Notificaciones por Email
- **Orden creada**: Confirmacion con resumen del pedido
- **Pago recibido**: Notificacion de pago aprobado
- **Lista para retirar**: Aviso cuando el pedido esta disponible en tienda
- **Enviada**: Informacion de despacho con datos de seguimiento
- **Completada**: Confirmacion de entrega exitosa
- **Cancelada**: Notificacion de cancelacion

### Panel Administrativo
- Gestion de productos: alta, baja, modificacion, variantes, secciones de contenido
- Gestion de ordenes: estados, pagos, envios, datos del cliente
- Descuentos: cupones, campanas globales, descuentos por suscriptor newsletter
- Marketing: newsletters con campanas, programacion y seguimiento
- Configuracion: tiendas, zonas de envio, metodos de pago, paginas legales
- Auditoria: registro de cambios con usuario, fecha y valores anteriores/nuevos

### Autenticacion & Seguridad
- Login con Google (OAuth 2.0) o email/contrasena
- Verificacion de email obligatoria
- Recuperacion de contrasena segura
- Roles y permisos para administradores
</details>



