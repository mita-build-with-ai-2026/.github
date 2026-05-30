# 🏡 Mita

**Mita te ayuda a encontrar tu espacio.**

Mita es un proyecto desarrollado para la Hackathon **Build With AI 2026 — Santa Cruz**, orientado a resolver un problema real del mercado inmobiliario local: encontrar un espacio adecuado en Santa Cruz de la Sierra sigue siendo un proceso lento, manual y desordenado.

Las ofertas están dispersas entre portales, redes sociales, WhatsApp e inmobiliarias. Muchas publicaciones están incompletas, usan formatos distintos y no permiten comparar fácilmente aspectos importantes como precio, zona, tamaño, condiciones, servicios, accesibilidad o tipo de uso.

Mita usa inteligencia artificial para recopilar, entender, estructurar y recomendar espacios según lo que cada persona o negocio necesita.

---

## ✨ ¿Qué hace Mita?

Mita es un **agente inmobiliario con IA** que permite buscar espacios en lenguaje natural.

En lugar de usar filtros rígidos, el usuario puede escribir:

> “Busco un local comercial cerca de una avenida transitada, máximo 800 dólares, ideal para abrir una cafetería.”

O también:

> “Necesito un depósito de al menos 200 m² en zona norte, con acceso para camión y seguridad.”

Mita interpreta la necesidad, analiza las ofertas disponibles y muestra opciones ordenadas por compatibilidad.

---

## 🎯 Enfoque del proyecto

Para la hackathon, Mita se enfoca en la mención **Industria**, ayudando a emprendedores, pymes, comercios y operadores locales a encontrar espacios productivos, comerciales y logísticos en Santa Cruz.

Mita puede ayudar a encontrar:

* Oficinas
* Locales comerciales
* Depósitos
* Galpones
* Talleres
* Espacios logísticos
* Espacios para emprendimientos
* Viviendas y alquileres residenciales como extensión natural del producto

La idea central es simple:

> **Encontrar el espacio correcto para vivir, trabajar, vender, almacenar o emprender.**

---

## 🤖 ¿Cómo usamos IA?

Mita aplica IA en varias partes del flujo:

1. **Normalización de ofertas**
   Convierte publicaciones desordenadas en datos estructurados.

2. **Búsqueda conversacional**
   Entiende lo que el usuario necesita aunque lo escriba de forma natural.

3. **Ranking inteligente**
   Ordena propiedades según compatibilidad con la necesidad del usuario.

4. **RAG-lite / búsqueda semántica**
   Recupera espacios relevantes aunque las publicaciones no usen exactamente las mismas palabras del usuario.

5. **Explicaciones inteligentes**
   Muestra por qué una opción conviene, qué riesgos tiene y qué información falta.

6. **Comparación de opciones**
   Permite comparar 2 o 3 espacios y recibir una recomendación clara.

---

## 🧩 Flujo principal del MVP

1. Mita importa ofertas desde una fuente externa o demo.
2. La IA normaliza las publicaciones.
3. Las propiedades se guardan como datos estructurados.
4. El usuario busca en lenguaje natural.
5. Mita extrae criterios de búsqueda.
6. Mita recupera propiedades relevantes.
7. Mita calcula compatibilidad.
8. Mita explica los resultados.
9. El usuario compara opciones.
10. El usuario contacta por WhatsApp.

---

## 🏗️ Arquitectura general

```txt
React Frontend
    ↓
API Backend
    ↓
Base de datos
    ↓
Servicios de IA
```

Componentes principales:

* **Frontend web:** interfaz para búsqueda, resultados, comparación, login y panel admin.
* **Backend API:** lógica de negocio, endpoints, autenticación, propiedades, leads e importaciones.
* **IA:** extracción de criterios, normalización, explicación, comparación y búsqueda semántica.
* **Base de datos:** almacenamiento de propiedades, fuentes, importaciones, búsquedas, resultados, embeddings y leads.

---

## 📦 Repositorios

### [`mita-frontend`](https://github.com/mita-build-with-ai-2026/mita-frontend)

Aplicación frontend de Mita.

Contiene la interfaz web del proyecto:

* Landing principal
* Búsqueda conversacional
* Resultados de propiedades
* Detalle de propiedad
* Comparador
* Login admin
* Panel de importaciones
* Panel de leads
* Flujo demo

Tecnologías base:

* React
* Vite
* JavaScript
* CSS

---

### [`mita-api`](https://github.com/mita-build-with-ai-2026/mita-api)

Backend/API de Mita.

Contiene la lógica principal del sistema:

* Endpoints de propiedades
* Login admin
* Importación de ofertas
* Normalización con IA
* Búsqueda conversacional
* Ranking de resultados
* RAG-lite
* Comparación de propiedades
* Registro de leads
* Integración con servicios de IA

---

### [`.github`](https://github.com/mita-build-with-ai-2026/.github)

Repositorio de configuración pública de la organización.

Contiene el README público de la organización y archivos generales de presentación para GitHub.

---

## 🧠 Problema que resolvemos

En Santa Cruz, buscar un espacio adecuado para vivir, trabajar o emprender puede tomar demasiado tiempo.

El mercado está fragmentado:

* Portales inmobiliarios
* Redes sociales
* Grupos de WhatsApp
* Publicaciones informales
* Inmobiliarias
* Contactos directos

Además, muchas ofertas no indican información clave:

* Tamaño
* Precio real
* Moneda
* Zona exacta
* Condiciones de alquiler
* Servicios incluidos
* Expensas
* Garaje
* Seguridad
* Acceso para vehículos
* Uso permitido del espacio
* Datos de contacto

Mita busca ordenar ese caos usando IA.

---

## 🚀 Propuesta de valor

### Para usuarios

* Buscar espacios conversando.
* Ahorrar tiempo.
* Comparar opciones con criterios claros.
* Entender ventajas, riesgos e información faltante.
* Contactar rápidamente por WhatsApp.

### Para emprendedores y pymes

* Encontrar espacios adecuados para operar.
* Evaluar mejor ubicación, precio y condiciones.
* Reducir fricción para abrir o expandir un negocio.

### Para inmobiliarias

* Mejorar publicaciones.
* Recibir leads más calificados.
* Automatizar parte del proceso de atención y comparación.

---

## 🧪 Demo esperada

La demo muestra el siguiente flujo:

1. Importar ofertas.
2. Normalizar publicaciones con IA.
3. Buscar un espacio en lenguaje natural.
4. Mostrar resultados con porcentaje de coincidencia.
5. Explicar por qué cada opción encaja o no.
6. Comparar alternativas.
7. Contactar por WhatsApp.

Ejemplo de búsqueda demo:

> “Busco un local comercial cerca de una avenida transitada, máximo 800 dólares, ideal para abrir una cafetería.”

---

## 🏁 Build With AI 2026

Mita fue creado como proyecto para **Build With AI 2026 — Santa Cruz**, organizado por la comunidad de Google Developer Groups Santa Cruz y Women Techmakers Santa Cruz.

El objetivo del proyecto es demostrar cómo la inteligencia artificial puede aplicarse a un problema real y local de Santa Cruz, generando una solución viable, escalable y útil para personas, emprendedores, pymes e inmobiliarias.

---

## 👥 Equipo

Proyecto desarrollado por el equipo Mita para Build With AI 2026.

Integrantes:

* Daniel Cueto
* Ariane Somoza
* Denis Lira

---

## 📌 Estado del proyecto

MVP en desarrollo durante la hackathon.

Prioridades actuales:

* Construir el frontend funcional.
* Implementar la API.
* Integrar IA para búsqueda y normalización.
* Preparar demo funcional.
* Documentar arquitectura y flujo del proyecto.

---

## 💡 Visión

Mita quiere convertirse en una capa inteligente sobre el mercado inmobiliario de Santa Cruz.

No buscamos ser solo otro portal de propiedades.

Queremos que encontrar un espacio sea tan simple como conversar.

> **Mita: encuentra tu espacio con IA.**
