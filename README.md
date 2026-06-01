# 🐾 AXIOM_PET_TRANSLATE // Analizador Biométrico y Conductual

Plataforma SaaS de uso diario diseñada en un entorno de arquitectura monolítica y distribución de alto rendimiento para el análisis conductual y salud visual de mascotas (perros y gatos). 

El sistema implementa un modelo de acceso híbrido: una zona de procesamiento de imágenes de uso libre mediante infraestructura local descentralizada y un ecosistema de monitorización avanzada protegido bajo pasarelas criptográficas en la nube.

---

## 🛠️ Especificaciones Tecnológicas (Pila Core)

La aplicación ha sido construida bajo la filosofía de **cero dependencias pesadas** y un peso crítico de red optimizado, consolidando toda la interfaz en un único archivo autónomo (`index.html`):

* **HTML5 Semántico:** Estructura nativa optimizada para la carga de canvas multimedia y manipulación de captura de streams.
* **CSS3 Ultra-Glass:** Diseño de cristal líquido blanco puro con saturación avanzada (`backdrop-filter: blur(24px) saturate(190%)`) y aceleración por GPU garantizada a 120Hz para eliminar el retraso de refresco táctil.
* **Vanilla JavaScript (ES6+):** Gestión asíncrona de tokens de sesión, llamadas perimetrales fetch y control estructural del DOM.
* **Integración de Componentes vía CDN:**
    * `Supabase Client`: Orquestador de persistencia de bases de datos y seguridad en el cliente.
    * `GSAP`: Motor físico para microinteracciones elásticas y estados mutables del avatar.
    * `Lenis`: Desplazamiento táctil y scroll suavizado continuo.
    * `Canvas-Confetti`: Animación matemática procedural de partículas para hitos de conversión.

---

## 🏎️ Arquitectura de Seguridad y Flujos Lógicos

### 1. Motor de IA Abierta Descentralizado (Cero Baneos)
Para mitigar el riesgo de bloqueos automatizados por parte de los bots de escaneo de GitHub, el sistema elimina las API Keys fijas del backend.
* **Persistencia Local:** Los usuarios inyectan su propia clave gratuita desde el HUD superior. El script la almacena de manera persistente en el navegador usando `localStorage`.
* **Guardia de Control:** Si la clave está ausente, el pipeline asíncrono mitiga la ejecución, detiene el avatar físico y despliega un aviso estético solicitando la clave. De estar activa, despacha un prompt biométrico al modelo `llama-3.1-8b-instant` de Groq.

### 2. Muro de Pago Premium y Login Social (OAuth Gate)
Al intentar conmutar hacia las pestañas avanzadas ("Escucha Real de Ladridos" o "Historial Clínico"), un interceptor lógico evalúa el estado del token de usuario.
* **Bloqueo Reactivo:** Si no hay sesión válida, el chasis se difumina y despliega un formulario *Ultra-Glass* con efectos de refracción óptica (`::before`).
* **Proveedores OAuth Integrados:** El sistema se comunica nativamente con las APIs de **Google** y **X (Twitter)** configuradas en tu instancia perimetral de Supabase. El inicializador cuenta con la función `checkActiveSessionEngine()` encargada de capturar los callbacks de retorno síncronos en la URL y desbloquear la interfaz en microsegundos sin recargas manuales.

---
<sub>AXIOM SYSTEMS // PET TRANSLATE PIPELINE // OAUTH & LOCAL IA INTEGRATION COMPLETE</sub>
</p>
