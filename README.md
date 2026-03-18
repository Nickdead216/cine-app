# 🎬 CineApp — Cartelera de Películas

Aplicación web de cartelera de cine que consume la API de TMDB en tiempo real. Muestra películas populares, en cartelera, mejor valoradas y próximos estrenos. Permite buscar cualquier película y ver sus detalles completos.

![Status](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![TMDB](https://img.shields.io/badge/API-TMDB-01b4e4)

---

## ✨ Funcionalidades

- **4 categorías** — Populares, En cartelera, Mejor valoradas, Próximamente
- **Búsqueda en tiempo real** — busca cualquier película por título
- **Detalle de película** — modal con póster, sinopsis, géneros, duración y puntuación
- **Paginación** — cargar más películas con un clic
- **Skeleton loading** — indicadores visuales mientras cargan los datos
- **Datos en español** — la API responde con contenido localizado

## 🔗 Demo

**[Ver app en vivo →](https://nickdead216.github.io/cine-app)**

## 🚀 Cómo usar localmente

```bash
git clone https://github.com/Nickdead216/cine-app.git
cd cine-app
```

Abre `index.html` en tu navegador — no requiere servidor ni instalación.

> Para usar tu propia API key: reemplaza el valor de `API_KEY` en el archivo `index.html` con tu clave de [TMDB](https://www.themoviedb.org/settings/api).

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 + CSS3 | Estructura y estilos |
| JavaScript (Vanilla) | Lógica, fetch API, DOM |
| TMDB API | Datos de películas en tiempo real |
| Google Fonts | Tipografía (Playfair Display + Outfit) |

## 📡 Endpoints de TMDB usados

```
GET /movie/popular       → Películas populares
GET /movie/now_playing   → En cartelera
GET /movie/top_rated     → Mejor valoradas
GET /movie/upcoming      → Próximamente
GET /search/movie        → Búsqueda por título
GET /movie/{id}          → Detalle de película
```

## 📁 Estructura

```
cine-app/
└── index.html    # App completa
```

## 🔮 Próximas mejoras

- [ ] Sección de series (TV shows)
- [ ] Trailer de YouTube integrado
- [ ] Favoritos guardados en localStorage
- [ ] Filtro por género y año

## 👨‍💻 Autor

**Nicolás Vicentelo Ortiz** — [@Nickdead216](https://github.com/Nickdead216)  
Ingeniero Civil en Computación e Informática — UCN, Coquimbo

---
*Datos proporcionados por [The Movie Database (TMDB)](https://www.themoviedb.org/).*
