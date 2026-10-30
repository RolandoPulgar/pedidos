# Sistema de Gestión de Pedidos Gcrea (v2.0)

Sistema web ligero y moderno para gestionar pedidos de clientes con sincronización directa a Google Sheets mediante Google Apps Script.

## ✨ Novedades y Características v2.0
- **Diseño Moderno & Responsivo**: Construido con Tailwind CSS y tipografía Plus Jakarta Sans. Funciona perfectamente en computadores, tablets y celulares.
- **Doble Vista**: Alterna con 1 clic entre **Vista de Tabla** detallada y **Vista de Tarjetas** visual.
- **Acceso Directo a WhatsApp**: Botón directo para iniciar chat de WhatsApp con el cliente y mensaje pre-cargado con el número de pedido.
- **Alertas de Plazos y Vencimientos**: Detección automática de fechas: *¡Entrega Hoy!*, *Vencido*, o *A tiempo*.
- **Métricas y KPIs en Tiempo Real**: Resumen de pedidos activos, en fabricación, listos para entrega y total facturado en el mes.
- **Filtros Rápidos**: Búsqueda por texto (nombre, N° pedido, notas o teléfono) + filtros por estado (*No iniciada, En proceso, Completado*) y prioridad (*Rápida, Normal, Baja*).
- **Notificaciones Toast**: Mensajes elegantes en pantalla sin molestas alertas emergentes.
- **100% Compatible con Google Sheets**: Mantiene exactamente la misma estructura de datos y endpoints con tu Google Apps Script.
- **Backup & Restauración Local**: Exportación e importación de respaldo en formato JSON.

## 🚀 Uso
1. Abre `pedidos.html` en cualquier navegador web.
2. En el botón **Ajustes**, pega la URL de tu Google Apps Script (que termina en `/exec`).
3. Haz clic en **Cargar** para sincronizar tus pedidos desde Google Sheets o **Guardar** para respaldar los cambios.
