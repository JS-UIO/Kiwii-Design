# 🌸 Kiwii Design — Tienda Online

Sitio web de **Kiwii Design**, accesorios de resina artesanales. Listo para GitHub Pages.

## 📁 Estructura de carpetas

```
kiwii-design/
├── index.html
└── images/
    ├── logo.png
    ├── llaveros/        (llaveros-1.jpg … llaveros-8.jpg)
    ├── esferos/         (esferos-1.jpg … esferos-3.jpg)
    ├── separadores/     (separadores-1.jpg … separadores-8.jpg)
    ├── orquideas/       (orquideas-1.jpg … agrega más)
    ├── anillos/         (anillos-1.jpg … anillos-5.jpg)
    ├── aretes/          (aretes-1.jpg … aretes-5.jpg)
    ├── collares/        (collares-1.jpg, collares-2.jpg)
    ├── combos/          (combos-1.jpg … combos-5.jpg)
    ├── estuches/        (estuches-1.jpg … estuches-4.jpg)
    ├── mascotas/        (mascotas-2.jpg, mascotas-3.jpg)
    ├── portaretrato/    (portaretrato-1.jpg)
    └── vinchas/         (vinchas-1.jpg … vinchas-3.jpg)
```

## ➕ Cómo agregar fotos nuevas

1. Coloca el archivo en la carpeta correcta con el siguiente nombre en la secuencia (ej: `llaveros-9.jpg`)
2. Abre `index.html`, busca el producto (Ctrl+F) y agrega el nombre al array `imgs:[]`

**Ejemplo:**
```js
// Antes:
imgs:['images/llaveros/llaveros-1.jpg']
// Después:
imgs:['images/llaveros/llaveros-1.jpg','images/llaveros/llaveros-9.jpg']
```

## 🚀 Publicar en GitHub Pages

1. Sube la carpeta `kiwii-design/` a un repositorio GitHub
2. Ve a **Settings → Pages → Source → main → / (root)**
3. Tu tienda estará en `https://[usuario].github.io/[repositorio]/`

## 📱 Características

- ✅ Mobile-first, optimizado para celular
- ✅ 12 categorías de productos
- ✅ Carrusel por producto + swipe en móvil
- ✅ Lightbox al tocar la foto
- ✅ Carrito con pedido directo a WhatsApp
- ✅ Sección Orquídeas con cotización
- ✅ Instagram, WhatsApp y TikTok en footer
