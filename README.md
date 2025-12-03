# 🕸️ Blog Técnico de Grafos

Un blog interactivo dedicado a la estructura de datos **Grafos**, con artículos detallados, visualizaciones interactivas y diagramas.

## 📋 Contenido

El blog contiene **3 artículos principales** sobre conceptos fundamentales de grafos:

### 📚 Post #1: Introducción a los Grafos
**Tema:** Nodos, Aristas y Tipos de Grafos

Contenido:
- ✓ Definición de un Grafo
- ✓ Conceptos clave (Vértices/Nodos, Aristas/Ejes)
- ✓ Tipos de grafos (Dirigidos, No Dirigidos, Ponderados)
- ✓ Ejemplo visual interactivo: Grafo de 5 nodos
- ✓ Aplicaciones reales en el mundo moderno

[📖 Leer Post #1](post1.html)

### 💾 Post #2: Representación de Grafos
**Tema:** Lista de Adyacencia vs Matriz de Adyacencia

Contenido:
- ✓ Explicación de Lista de Adyacencia
- ✓ Explicación de Matriz de Adyacencia
- ✓ Comparación de eficiencia (espacio y tiempo)
- ✓ Visualización interactiva de ambas representaciones
- ✓ Guía práctica: cuándo usar cada una

[📖 Leer Post #2](post2.html)

### 🔍 Post #3: Algoritmos Fundamentales de Recorrido
**Tema:** BFS y DFS

Contenido:
- ✓ Búsqueda en Amplitud (BFS)
- ✓ Búsqueda en Profundidad (DFS)
- ✓ Pseudocódigo de ambos algoritmos
- ✓ Visualizaciones interactivas
- ✓ Comparación y aplicaciones prácticas
- ✓ Casos de uso reales

[📖 Leer Post #3](post3.html)

## 🎨 Características

- ✨ **Diseño Responsivo:** Optimizado para desktop, tablet y móvil
- 📊 **Diagramas Interactivos:** Canvas HTML5 con visualizaciones de grafos
- 🎯 **Contenido Estructurado:** Tabla de contenidos, boxes informativos
- 🔗 **Navegación Fluida:** Enlaces suave (smooth scroll) entre secciones
- 💅 **Estilo Moderno:** Gradientes, sombras y animaciones CSS
- 📱 **Mobile First:** Responsive design en todas las páginas

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Estructura semántica
- **CSS3:** Estilos modernos, grid, flexbox, gradientes
- **JavaScript Vanilla:** Interactividad y diagramas
- **Canvas API:** Visualización de grafos
- **Git/GitHub:** Control de versiones

## 📁 Estructura del Proyecto

```
blog-grafos/
├── index.html           # Página principal
├── post1.html           # Post #1: Introducción a Grafos
├── post2.html           # Post #2: Representación de Grafos
├── post3.html           # Post #3: Algoritmos BFS y DFS
├── css/
│   └── style.css        # Estilos principales
├── js/
│   └── main.js          # Lógica y diagramas interactivos
├── img/                 # Imágenes (futuras)
├── posts/               # Archivos de posts (organización)
├── README.md            # Este archivo
└── .gitignore           # Archivos a ignorar en Git
```

## 🚀 Cómo Usar

### Opción 1: Abrir Localmente
1. Descarga o clona el repositorio
2. Abre `index.html` en tu navegador
3. Navega a través de los artículos

### Opción 2: GitHub Pages
El blog está disponible en GitHub Pages. Accede a través del link del repositorio.

### Opción 3: Servidor Local
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (instalar http-server)
npx http-server
```

Luego accede a `http://localhost:8000`

## 📖 Guía de Lectura Recomendada

**Para principiantes:**
1. Comienza con Post #1 para entender conceptos básicos
2. Continúa con Post #2 para aprender representaciones
3. Finaliza con Post #3 para dominar algoritmos

**Para avanzados:**
- Accede directamente al tema de interés
- Consulta las visualizaciones interactivas
- Revisa las tablas comparativas

## 🎓 Objetivos de Aprendizaje

Después de leer este blog, serás capaz de:

- [ ] Explicar qué es un grafo y sus componentes principales
- [ ] Diferenciar entre grafos dirigidos y no dirigidos
- [ ] Elegir la representación óptima (lista vs matriz)
- [ ] Implementar BFS y DFS
- [ ] Aplicar grafos a problemas reales
- [ ] Analizar la complejidad de algoritmos de grafos

## 💻 Desarrollo

### Agregar Nuevos Posts
1. Crea un archivo `postN.html` en la raíz
2. Copia la estructura de un post existente
3. Personaliza el contenido
4. Actualiza `index.html` con el nuevo link

### Agregar Diagramas
- Edita `js/main.js` para agregar funciones Canvas
- Implementa con Canvas API o SVG
- Prueba en diferentes navegadores

### Mejorar Estilos
- Modifica `css/style.css`
- Usa las variables CSS definidas (`:root`)
- Mantén consistencia con el diseño actual

## 🐛 Problemas y Soluciones

### Los diagramas no se muestran
- Verifica que el navegador soporte Canvas HTML5
- Abre la consola (F12) para ver errores JavaScript

### Estilos no se aplican correctamente
- Limpia el caché del navegador (Ctrl+Shift+R)
- Verifica la ruta de `css/style.css`

### Enlaces internos no funcionan
- Asegúrate de que los archivos HTML están en la misma carpeta
- Verifica la sintaxis de los links

## 📚 Recursos Adicionales

- [MDN Web Docs - Grafos](https://developer.mozilla.org/en-US/)
- [GeeksforGeeks - Grafo Algorithms](https://www.geeksforgeeks.org/)
- [Visualgo - Visualización de Algoritmos](https://visualgo.net/)

## 👨‍💻 Autor

**Leidy Mary Rodriguez**
- GitHub: [leidymaryuri25-svg](https://github.com/leidymaryuri25-svg)
- Proyecto: Estructura de Datos - Grafos
- Universidad: [Tu Universidad]

## 📄 Licencia

Este proyecto está bajo licencia **MIT**. Ver archivo LICENSE para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## ✨ Mejoras Futuras

- [ ] Agregar más algoritmos (Dijkstra, Floyd-Warshall, etc.)
- [ ] Implementar editor interactivo de grafos
- [ ] Agregar ejercicios prácticos con soluciones
- [ ] Crear sección de preguntas frecuentes
- [ ] Traducir a otros idiomas
- [ ] Agregar animaciones de algoritmos paso a paso
- [ ] Integrar un playground de código

## 📞 Contacto

¿Preguntas o sugerencias? Contacta a través de:
- Issues de GitHub
- Email: [tu-email]
- LinkedIn: [tu-linkedin]

---

**Última actualización:** Diciembre 2025

Hecho con ❤️ para aprender y compartir conocimiento sobre estructuras de datos.