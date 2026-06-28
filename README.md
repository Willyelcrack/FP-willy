# Portafolio — Willy Wilfrid Jatsa

Sitio web personal de **Willy Wilfrid Jatsa**, Técnico Superior en Informática
de Redes y Telecomunicaciones y Desarrollador Fullstack.

Landing page de una sola página, responsiva y sin dependencias de build:
HTML + CSS + JavaScript puro.

## 🗂️ Estructura

```
TECH-WEBSITE/
├── index.html              # Estructura y contenido
├── css/
│   └── styles.css          # Estilos (tema minimal blanco/negro)
├── js/
│   └── main.js             # Menú móvil, scroll activo, reveal y contadores
└── assets/
    ├── favicon.svg
    ├── profile-placeholder.svg   # Se muestra mientras no exista profile.jpg
    ├── profile.jpg               # ← Añade aquí tu foto de perfil
    └── cv-willy-wilfrid-jatsa.pdf # ← Añade aquí tu CV (botón "Descargar CV")
```

## 🖼️ Personalización

1. **Foto de perfil:** coloca tu retrato en `assets/profile.jpg`
   (recomendado vertical 4:5, p. ej. 880×1100 px). Si el archivo no existe,
   se mostrará automáticamente un marcador de posición.
2. **CV:** coloca tu currículum en `assets/cv-willy-wilfrid-jatsa.pdf`.
3. **Enlaces sociales:** edita los `href` de GitHub, LinkedIn, WhatsApp y
   correo en `index.html` (header, hero y footer).
4. **Contenido:** textos, estadísticas y proyectos están en `index.html`.

## 🚀 Cómo ver el sitio

Al ser estático, basta con abrir `index.html` en el navegador. Para una vista
con servidor local:

```bash
python3 -m http.server 8000
# luego visita http://localhost:8000
```

## ✨ Secciones

- **Inicio (Hero)** — presentación, CV y redes.
- **Estadísticas** — años de experiencia, proyectos, tecnologías, estudiantes.
- **Sobre mí** + **Habilidades** — perfil y stack tecnológico.
- **Servicios** — desarrollo web, redes, programación, ofimática y docencia.
- **Proyectos** — EGMarket, Ensema Group y Colegio Santa Isabel.
- **Contacto** — llamada a la acción para nuevos proyectos.

---

© Willy Wilfrid Jatsa
