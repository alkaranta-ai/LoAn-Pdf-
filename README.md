# LoAn Estética — Generador de Documentos

PWA para generar PDFs con identidad LoAn: presupuestos, fichas de clientes, informes, consentimientos y más.

## Instalación en GitHub Pages

1. Creá un repositorio nuevo en `alkaranta-ai/LoAn-Docs` (o el nombre que prefieras)
2. Subí estos 4 archivos:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icono-192.png` ← usá el mismo que ya tenés en LoAn-Turnos
   - `icono-512.png` ← ídem
3. Activá GitHub Pages desde Settings → Pages → Branch: `main`
4. La app queda en `https://alkaranta-ai.github.io/LoAn-Docs/`

## Instalar en el celular

### Android (Chrome)
1. Abrí la URL en Chrome
2. Aparece el banner "Agregar a pantalla de inicio" — aceptá
3. O tocá el menú ⋮ → "Instalar app"

### iPhone / iPad (Safari)
1. Abrí la URL en Safari (obligatorio, no Chrome)
2. Tocá el botón Compartir (cuadrado con flecha)
3. → "Agregar a pantalla de inicio"
4. Confirmá — queda como ícono en el home

## Funciones

- **6 tipos de documento**: presupuesto, ficha, informe, consentimiento, turno, libre
- **IA integrada**: describís con tus palabras → la IA redacta el documento
- **Fotos**: adjuntás imágenes que se incluyen en el PDF
- **Historial**: todos los documentos se guardan en el dispositivo
- **Reusar**: podés reutilizar documentos previos como base
- **Descarga + Compartir**: PDF listo en segundos

## Configuración de IA (obligatorio para usar "Generar con IA")

La app usa la IA de Google Gemini (plan gratuito). Cada persona necesita SU PROPIA clave —
si varias personas comparten la misma clave, se agota el límite diario de uso y aparece
el error "llegaste al límite de usos por hoy".

Para activar la IA:
1. Entrá a https://aistudio.google.com/apikey con tu cuenta de Google
2. Creá una API Key (es gratis)
3. En la app, tab ⚙️ Config → pegá la clave en "🔑 Clave de IA (Gemini)" → Guardar

La clave se guarda solo en tu dispositivo (localStorage), nunca sale a ningún servidor.

## Paleta LoAn

| Token | Valor |
|-------|-------|
| Rosa principal | `#C9527A` |
| Rosa claro | `#F2C4D4` |
| Rosa pálido (fondo) | `#FDF0F4` |
| Rosa oscuro | `#9E3A5C` |
| Negro | `#1A1014` |
