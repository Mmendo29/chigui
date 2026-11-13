# Chigüi 🐹

App personal para registrar comidas por foto (con Google Gemini), agua, peso, ejercicio y pasos.

- **Android:** cada vez que se sube un cambio a `main`, GitHub Actions compila `chigui.apk` y lo publica en *Releases*.
  Descarga directa: `https://github.com/<usuario>/chigui/releases/latest/download/chigui.apk`
  Los pasos se leen solos desde Health Connect.
- **iPhone:** la misma app se publica en GitHub Pages: `https://<usuario>.github.io/chigui/`.
  En Safari: Compartir → *Agregar a pantalla de inicio*. Los pasos se escriben a mano.

Los datos de cada persona viven solo en su celular. La clave de Gemini se escribe dentro de la app (Metas) y nunca va en el código.

Activar la app web una sola vez: *Settings → Pages → Source: GitHub Actions*.
