# Monorepo NX con Angular y NodeJS

Este repositorio corresponde a un curso de **Monorepo NX con Angular y NodeJS** de **PLATZI** dictado por **Sergie Code**.

## 📚 Temas del Curso

Los temas tocados en este curso son los siguientes:

- ¿Qué es NX y Monorepo?
- Instalaciones necesarias
- Inicializar proyecto NX
- Estructura proyecto NX y agregar Angular
- Crear apps Angular
- Creación de librerías comunes
- Node.js
- UI Utils Common - Componentes, Modelos y Servicios
- Agregar Servidor Node.js
- Agregar App1 - Inscripciones de Estudiantes
- Agregar App2 - Cursos y Profesores
- Agregar Tests Unitarios
- Lint - Errores y Soluciones
- Conectar a NX Cloud
- NX Tags - Organización con Tags
- Beneficios de Monorepo con NX: Caché y Rendimiento
- Github Actions con NX

## 🏗️ Estructura del Proyecto

Este monorepo contiene:

- **packages/app1**: Aplicación Angular para inscripciones de estudiantes
- **packages/app2**: Aplicación Angular para gestión de cursos y profesores
- **packages/server**: Servidor Node.js
- **packages/ui-shared**: Librería de componentes UI compartidos
- **packages/utils-common**: Librería de utilidades, modelos y servicios comunes

## 🎓 Sobre Platzi

Platzi es una plataforma de educación en línea enfocada en el desarrollo profesional, especialmente en áreas como tecnología, negocios, marketing y diseño. Ofrece cursos, rutas de aprendizaje y programas en vivo dictados por expertos de la industria, con un modelo de suscripción que permite acceso ilimitado a su catálogo. Su comunidad activa y su enfoque en el aprendizaje constante la convierten en una de las principales opciones de formación digital en Latinoamérica y el mercado hispanohablante.

## 👨‍💻 Sobre Sergie Code

Sergie Code es un Software Engineer especializado en Frontend y actualmente se desempeña como Tech Lead liderando dos equipos de desarrolladores en una reconocida empresa americana de seguros. Además, es creador de contenido tecnológico y educativo, ofreciendo cursos gratuitos de programación en su canal de YouTube y compartiendo a diario en Instagram, TikTok y otras redes sociales tips, recomendaciones y novedades del mundo del desarrollo y la inteligencia artificial.

Ha dictado clases en la UTN, en los programas Codo a Codo y Argentina Programa 4.0, y también ha desarrollado e impartido cursos de HTML, CSS, JavaScript y ReactJs en la carrera Certified Tech Developer de Digital House.

En el marco de su colaboración con Platzi, recientemente filmó en Bogotá, Colombia, tres cursos para la nueva etapa de contenidos 2025/2026: **Fundamentos de Python**, **Firebase con Angular y Gemini** y **Monorepo NX con Angular y NodeJS**. Asimismo, lanzó cursos propios en el área de Data, como Introducción a Python y Programación en Python, donde enseña esta tecnología desde cero.

Su formación incluye estudios en Ingeniería Electrónica en la UNC, la certificación como Java Developer Engineer en Educación IT y una extensa capacitación en frameworks y tecnologías a través de cursos online. Además de su perfil técnico, se ha desarrollado como músico independiente, lo que potenció su creatividad y habilidades comunicacionales. Gracias a su experiencia, posee destacadas soft skills, comodidad al hablar en público y ha participado como orador en eventos multitudinarios como ADA13, Fingurú y SAIA en la UTN.

### 🌐 Redes Sociales de Sergie Code

- 📸 **Instagram**: https://www.instagram.com/sergiecode
- 🧑🏼‍💻 **LinkedIn**: https://www.linkedin.com/in/sergiecode/
- 📽️ **YouTube**: https://www.youtube.com/@SergieCode
- 😺 **GitHub**: https://github.com/sergiecode
- 👤 **Facebook**: https://www.facebook.com/sergiecodeok
- 🎞️ **TikTok**: https://www.tiktok.com/@sergiecode
- 🕊️ **Twitter**: https://twitter.com/sergiecode
- 🧵 **Threads**: https://www.threads.net/@sergiecode

## 🚀 Comandos de NX

Para trabajar con este monorepo, puedes usar los siguientes comandos de NX:

```bash
# Instalar dependencias
npm install

# Servir una aplicación
npx nx serve app1
npx nx serve app2

# Ejecutar el servidor
npx nx serve server

# Ejecutar tests
npx nx test

# Ejecutar lint
npx nx lint

# Construir aplicaciones
npx nx build app1
npx nx build app2

# Ver el grafo de dependencias
npx nx graph
```

## 📝 Instalaciones Necesarias

Consulta el archivo `instalaciones-necesarias.md` para ver los requisitos del sistema y las herramientas necesarias para trabajar con este proyecto.