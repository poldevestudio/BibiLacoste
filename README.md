# Bibi Lacoste — Artista Visual | Portfolio & Catálogo de Obras

Sitio web oficial y catálogo curatorial de la artista visual contemporánea **Bibi Lacoste** (Buenos Aires, Argentina). Diseñado bajo un enfoque editorial, sobrio y cálido, combinando la presencia de un portfolio de arte con una plataforma discreta de adquisición directa de piezas originales para coleccionistas particulares, galerías e interiorismo.

---

## 🎨 Dirección de Arte y Estilo Visual

Inspirado en la sutileza de publicaciones de arte contemporáneo (referencia *Lola Donoghue*):

* **Lienzo Cálido:** Fondo en tono papel de algodón natural (`#FBF9F5`) con textura de grano orgánico, evitando el blanco óptico para resaltar los empastes y recortes de las obras.
* **Tipografía Dual:**
  * **Titulares & Marca:** *Cormorant Garamond* (serif clásica de alta elegancia editorial).
  * **Datos Técnicos & UI:** *Plus Jakarta Sans* (lectura moderna y limpia para medidas, técnicas y años).
* **Acento Cromático:** Arcilla / Siena quemado (`#A75D43`), derivado de la propia paleta de técnicas mixtas de la artista.

---

## ✨ Funcionalidades y Experiencia de Usuario

1. **Catálogo Serie 2025:** 15 obras originales documentadas y optimizadas en formato moderno WebP de alto rendimiento.
2. **Filtros Dinámicos:** Clasificación instantánea entre *Todas las obras*, *Disponibles para adquisición*, *Técnica Mixta & Collage* y *Acrílicos*.
3. **Inspector de Obra (Modal Interactivo):**
   * **Pestaña Obra:** Vista general en alta fidelidad y proporción real.
   * **Pestaña Textura / Zoom:** Aumento focalizado para apreciar los detalles de espátula, collage de papeles impresos y grafismos gestuales.
   * **Pestaña En el Espacio:** Simulación a escala real en pared de sala contemporánea para que el coleccionista perciba la dimensión física antes de adquirir.
4. **Flujo de Adquisición:**
   * Botón *"Consultar Adquisición de esta Obra"* que traslada al usuario al formulario y pre-carga la obra elegida.
   * Botón directo para iniciar consulta por WhatsApp.
5. **Envíos Internacionales:** Sección informativa sobre embalaje de protección museológica y envíos con seguro.

---

## 📁 Estructura del Proyecto

```text
BibiLacoste/
├── index.html                   # Punto de entrada principal (autocontenido)
├── bibi-lacoste-preview.html    # Copia de previsualización
├── assets/
│   └── artworks/                # 15+ obras originales en formato .webp optimizado
│       ├── solapado_1.webp
│       ├── araucaria_8.webp
│       ├── verano_4.webp
│       ├── aquiles_11.webp
│       └── ...
├── .gitignore                   # Exclusión de temporales y configuraciones de IDE
└── README.md                    # Documentación del proyecto
```

---

## 🚀 Despliegue (Deploy)

El proyecto está listo para desplegarse como sitio estático sin dependencias de backend:

### Opción 1: GitHub Pages
1. Subí esta carpeta a tu repositorio en GitHub.
2. Andá a **Settings > Pages**.
3. En **Branch**, seleccioná `main` (o `master`) y directorio `/ (root)`. Guardá y el sitio quedará publicado en `https://<usuario>.github.io/<repo>/`.

### Opción 2: Vercel / Netlify
1. Conectá el repositorio en el panel de Vercel o Netlify.
2. Framework preset: **Other** (HTML estático).
3. Root directory: `./`
4. ¡Listo! Despliegue automático en segundos.

---

## 📄 Créditos & Derechos
© 2026 Bibi Lacoste. Todas las imágenes y derechos sobre las obras pertenecen a la artista.
