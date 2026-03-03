# EliteStaff — Sitio Web Corporativo

Sitio web estático para empresa de alquiler de staff profesional para eventos. Desarrollado en HTML, CSS y JavaScript vanilla, listo para desplegar en **GitHub Pages**.

---

## 🚀 Demo

> Una vez publicado en GitHub Pages, tu sitio estará disponible en:
> `https://<tu-usuario>.github.io/<nombre-del-repo>/`

---

## 📁 Estructura del proyecto

```
/
└── index.html       # Sitio completo (HTML + CSS + JS en un solo archivo)
└── README.md        # Este archivo
```

---

## 📄 Secciones del sitio

| Sección | Descripción |
|---|---|
| **Navbar** | Fija con efecto blur, links de navegación y botón CTA |
| **Hero** | Portada con título, descripción, estadísticas y llamadas a la acción |
| **Servicios** | Cards con los 4 tipos de staff ofrecidos |
| **Galería** | Grid asimétrico con overlay al hacer hover |
| **Contacto** | Formulario de cotización + acceso directo por WhatsApp |
| **Footer** | Información legal y links secundarios |

---

## ⚙️ Despliegue en GitHub Pages

### Paso 1 — Clonar o crear el repositorio

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com//.git
git push -u origin main
```

### Paso 2 — Activar GitHub Pages

1. Ir a **Settings** del repositorio
2. En el menú lateral, hacer clic en **Pages**
3. En *Branch*, seleccionar `main` y carpeta `/ (root)`
4. Hacer clic en **Save**
5. Esperar unos minutos — GitHub te mostrará la URL del sitio

---

## 🛠️ Personalización

### Nombre de la empresa
Buscar y reemplazar `EliteStaff` en el `index.html` por el nombre real.

### Número de WhatsApp
Buscar el siguiente fragmento y reemplazar el número:

```html
href="https://wa.me/5491100000000?text=..."
```

Reemplazar `5491100000000` por el número en formato internacional (sin `+`, sin espacios).  
Ejemplo para Argentina: `5491155556666`

### Datos de contacto
Buscar y actualizar los siguientes campos en la sección `#contacto`:

```html
Buenos Aires, Argentina — cobertura nacional
+54 11 0000-0000
contacto@elitestaff.com.ar
```

### Año en el footer
```html
© 2025 EliteStaff. Todos los derechos reservados.
```

### Estadísticas del Hero
Actualizar los valores en la sección `.hero-stat-bar`:

```html
+500   
+120   
10+    
98%    
```

### Galería de fotos
Reemplazar los bloques `.galeria-placeholder` por etiquetas `<img>` reales:

```html

```

---

## 🎨 Tecnologías utilizadas

- HTML5 semántico
- CSS3 (variables, Grid, Flexbox, animaciones)
- JavaScript vanilla (Intersection Observer, scroll events)
- Google Fonts: [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) + [DM Sans](https://fonts.google.com/specimen/DM+Sans)

---

## 📬 Formulario de contacto

El formulario incluido es **estático** (no envía datos por defecto). Para activar el envío real, se recomienda integrarlo con alguno de estos servicios gratuitos:

- [Formspree](https://formspree.io) — agregar `action="https://formspree.io/f/XXXXXX"` al formulario
- [Web3Forms](https://web3forms.com)
- [EmailJS](https://www.emailjs.com)

---

## 📝 Licencia

Uso interno / comercial para el cliente. No se permite redistribución sin autorización.
