# 🥟 La Carbonada - Empanadas Artesanales

App web ligera y responsive para la gestión de pedidos de empanadas artesanalas. Diseñada para funcionar como un catálogo interactivo que envía el pedido final directamente al **WhatsApp** del negocio.

---

## ✨ Funcionalidades Principales

* **Interfaz Mobile-First:** Diseñada específicamente para ser usada desde smartphones.
* **Cálculo Automático:** Suma el total del pedido en tiempo real a medida que el usuario agrega unidades.
* **Feedback Visual:** Los ítems seleccionados resaltan para evitar confusiones.
* **Mensaje Estructurado:** Genera un texto profesional para WhatsApp con negritas y bullets.
* **Validación de Datos:** Evita envíos sin nombre, dirección o productos seleccionados.

---

## 🛠️ Configuración del Proyecto

Para poner la app en funcionamiento con tus propios datos, solo debés editar las constantes al inicio del bloque `<script>` en el archivo `index.html`:

### 1. Cambiar el Teléfono
Localizá la constante y poné tu número (formato internacional, sin espacios ni símbolos):
```javascript
const TELEFONO_WHATSAPP = "5493517485182";
