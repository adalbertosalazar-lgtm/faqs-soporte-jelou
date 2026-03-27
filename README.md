# Jelou Soporte — Documentación y FAQs

Página web de documentación y soporte para Jelou.AI con chatbot de Claude integrado.

## 🚀 Publicar en GitHub Pages (5 pasos)

### Paso 1 — Crea el repositorio en GitHub
1. Ve a [github.com/new](https://github.com/new)
2. Nombre del repositorio: `faqs-soporte-jelou`
3. Visibilidad: **Public** (necesario para GitHub Pages gratuito)
4. Haz clic en **"Create repository"**

### Paso 2 — Abre GitHub Desktop
1. Abre GitHub Desktop en tu computadora
2. Haz clic en **File → Clone Repository**
3. Busca `faqs-soporte-jelou` en la lista y clónalo en tu computadora

### Paso 3 — Copia los archivos
1. Copia el archivo `index.html` y este `README.md` a la carpeta del repositorio que se acaba de clonar
2. Asegúrate de que `index.html` esté en la **raíz** del repositorio (no en subcarpetas)

### Paso 4 — Sube los cambios
1. En GitHub Desktop verás los archivos nuevos listados
2. En el campo **"Summary"** escribe: `Publicar documentación Jelou`
3. Haz clic en **"Commit to main"**
4. Haz clic en **"Push origin"**

### Paso 5 — Activa GitHub Pages
1. Ve a tu repositorio en GitHub.com
2. Haz clic en **Settings** (⚙️)
3. En el menú izquierdo, haz clic en **Pages**
4. En "Source" selecciona: **Deploy from a branch**
5. Branch: **main** · Folder: **/ (root)**
6. Haz clic en **Save**

⏳ Espera 2-3 minutos y tu página estará en:
**`https://TU-USUARIO.github.io/faqs-soporte-jelou`**

---

## 🤖 Activar el Chatbot de Claude

El chatbot usa la API de Anthropic directamente desde el navegador.

1. Haz clic en el botón verde 🤖 (esquina inferior derecha)
2. Obtén tu API Key en: [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)
3. Ingresa la key en el campo (comienza con `sk-ant-`)
4. ¡Listo! El asistente puede responder preguntas sobre toda la documentación

> **Nota de seguridad:** La API Key se guarda solo en el navegador del usuario (localStorage). Nunca se envía al servidor del repositorio.

---

## 📁 Estructura del Proyecto

```
faqs-soporte-jelou/
├── index.html    ← Página principal (todo en un archivo)
└── README.md     ← Este archivo
```

---

## 🎨 Características

- ✅ Diseño hero con tarjetas por módulo
- ✅ Búsqueda en tiempo real en toda la documentación
- ✅ 6 secciones documentadas: Connect, Brain Studio, Datum, Marketplace, Logs & Debugger, Glosario
- ✅ FAQs en acordeón interactivo
- ✅ Guías paso a paso
- ✅ Chatbot de Claude integrado (API key del usuario)
- ✅ Responsive (mobile-friendly)
- ✅ Sin dependencias de servidor

---

## 🔄 Actualizar la documentación

1. Edita el archivo `index.html` en tu editor de texto
2. Guarda los cambios
3. En GitHub Desktop: Commit + Push
4. GitHub Pages publica automáticamente en ~30 segundos

---

**Mantenido por:** Jelou.AI — Equipo de Soporte
**Contacto:** adalberto.salazar@jelou.ai
