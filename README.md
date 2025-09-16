# Escáner de Equipajes • Flybondi (camera-only)
- Diseño tipo Zebra (fullscreen, botones grandes), **sin DataWedge**, sólo **Cámara**.
- Flujo por **Carros** con totales por carro y por vuelo.
- **Detección de duplicados** a nivel vuelo.
- **Vuelos escaneados** agrupados por sesión (ver carros y códigos).
- PWA (offline), integración a **Google Sheets** vía Apps Script.

## Configuración rápida
1. Descomprimir y abrir `index.html` con servidor local (IIS Express / Live Server).
2. Renombrar `config.example.json` -> `config.json` y poner tu `apps_script_url` (Web App de Apps Script).
3. Permitir cámara en el navegador y listo.
