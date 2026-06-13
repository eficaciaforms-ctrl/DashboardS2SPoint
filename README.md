# Dashboard S2S · Kenvue Perú

Dashboard ejecutivo conectado al Google Sheets del app S2S Point.

## 🚀 Acceso al dashboard

Una vez activado GitHub Pages, accede en:

```
https://eficaciaforms-ctrl.github.io/<NOMBRE-DEL-REPO>/
```

## 🔑 Usuarios

| Usuario | Contraseña | Rol |
|---|---|---|
| `JEFECANAL` | `JEFE123$` | Jefe de Canal · Vista nacional |
| `SUPLIMA` | `SUPER123$` | Supervisor Lima · ALBERTO SILVA |
| `SUPAREQUIPA` | `SUPER123$` | Supervisor Sur · CARLOS MAMANI |
| `SUPCHICLAYO` | `SUPER123$` | Supervisor Norte · MIGUEL BAZAN |
| `SUPPIURA` | `SUPER123$` | Supervisor Piura · ROBERTO ARICA |
| `SUPHUANCAYO` | `SUPER123$` | Supervisor Centro · GABRIELA YMAÑA |

## ⚙ Configuración inicial

1. **Subir archivos al repo:** solo `index.html`
2. **Activar GitHub Pages:**
   - Ve a **Settings** → **Pages**
   - En **Source**, selecciona **Deploy from a branch**
   - En **Branch**, selecciona `main` y carpeta `/ (root)`
   - Clic en **Save**
3. **Esperar 1-2 minutos** y recargar la página de Pages hasta ver "Your site is live at..."

## 🔌 URL del Google Apps Script

La URL del GAS ya viene pre-cargada en `index.html`. Si la cambias en el GAS:
- Edita `index.html` línea ~717
- O usa el botón **⚙** del topbar del dashboard para actualizarla sin tocar el código

## 📊 Funcionalidades

- **Resumen ejecutivo** con storytelling automático del día
- **Equipo de promotoras** con detalle expandible de visitas (clic en cada promotora → ver cada cliente y SKUs)
- **Análisis profundo de causales** de no-venta con drill-down ejecutivo
- **Ranking de SKUs** vendidos en el día
- **Mapa de calor** con polígonos reales del Perú (departamentos, provincias, distritos)
- **Conclusiones automáticas** + comentarios ejecutivos editables
- **Filtros encadenados:** Supervisor → Promotora → Departamento → Provincia → Distrito

## 📱 Compatible con

- PC (Chrome, Firefox, Safari, Edge)
- Móvil (Android e iOS, layout responsive)

---

Eficacia/SPG · Kenvue Perú · 2026
