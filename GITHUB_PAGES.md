# 📚 GUÍA: Publicar el Blog en GitHub Pages

## Paso 1: Preparar el Repositorio Git

Si aún no has inicializado Git en la carpeta `blog-grafos`, ejecuta:

```bash
cd blog-grafos
git init
git add .
git commit -m "Initial commit: Blog técnico de grafos"
```

## Paso 2: Crear el Repositorio en GitHub

1. Ve a [GitHub.com](https://github.com) e inicia sesión
2. Haz clic en el **"+"** en la esquina superior derecha
3. Selecciona **"New repository"**
4. Nombre del repositorio: `blog-grafos` (o el que prefieras)
5. **IMPORTANTE:** El repositorio debe ser **público** (Public)
6. Haz clic en **"Create repository"**

## Paso 3: Conectar el Repositorio Local con GitHub

Después de crear el repositorio en GitHub, verás instrucciones. Ejecuta:

```bash
git remote add origin https://github.com/TU_USUARIO/blog-grafos.git
git branch -M main
git push -u origin main
```

Reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub.

## Paso 4: Habilitar GitHub Pages

1. Ve al repositorio en GitHub
2. Haz clic en **Settings** (Configuración)
3. En el menú lateral, busca **"Pages"** (Páginas)
4. Bajo **"Source"**, selecciona:
   - Branch: `main`
   - Folder: `/ (root)` o `/docs` si la carpeta blog está dentro de docs
5. Haz clic en **"Save"**

## Paso 5: Esperaar la Publicación

GitHub Pages tardará entre 1-2 minutos en procesar tu sitio. Verás un banner azul que dice:

> "Your site is published at: https://TU_USUARIO.github.io/blog-grafos"

¡Eso es! Tu blog estará disponible en esa URL.

---

## 🔗 Nota sobre Rutas

Si el repositorio es `blog-grafos`, la URL será:
```
https://TU_USUARIO.github.io/blog-grafos/
```

Si tienes un repositorio llamado `TU_USUARIO.github.io`, la URL será:
```
https://TU_USUARIO.github.io/
```

En ese caso, coloca todo el contenido (index.html, css/, js/, etc.) en la raíz.

---

## 🧪 Verificar que Todo Funciona

Una vez publicado:

1. Visita tu URL de GitHub Pages
2. Verifica que todos los archivos se carguen correctamente
3. Haz clic en los artículos para confirmar la navegación
4. Abre la consola del navegador (F12) para ver si hay errores

---

## 📤 Actualizar el Blog

Para hacer cambios y actualizar el blog:

```bash
git add .
git commit -m "Descripción de cambios"
git push origin main
```

GitHub Pages se actualizará automáticamente en 1-2 minutos.

---

## 📝 Alternativa: Usar GitHub Desktop

Si prefieres una interfaz gráfica:

1. Instala [GitHub Desktop](https://desktop.github.com/)
2. Abre la carpeta `blog-grafos` con GitHub Desktop
3. Haz cambios en los archivos
4. En GitHub Desktop, añade un "Summary" de los cambios
5. Haz clic en "Commit to main"
6. Haz clic en "Push origin"

---

## ✅ Checklist Final

- [ ] Repositorio creado en GitHub
- [ ] `git remote add origin` ejecutado
- [ ] Primer push realizado (`git push`)
- [ ] GitHub Pages habilitado en Settings
- [ ] URL de publicación recibida
- [ ] Blog accesible y funcionando
- [ ] Diagramas interactivos mostrando correctamente
- [ ] Enlaces de navegación funcionando

---

**Una vez completado todo esto, tu blog estará disponible públicamente en GitHub Pages.**

Para la tarea, copia el link final: `https://TU_USUARIO.github.io/blog-grafos/`