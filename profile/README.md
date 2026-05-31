# 🏡 Mita — Agente Inmobiliario con IA

**Mita te ayuda a encontrar tu espacio comercial, productivo y logístico en Santa Cruz.**

Mita es una plataforma inteligente desarrollada para la Hackathon **Build With AI 2026 — Santa Cruz (Mención Industria)**. Está orientada a resolver un problema crítico del mercado local: encontrar un espacio adecuado (locales comerciales, oficinas, depósitos, galpones y talleres) en Santa Cruz de la Sierra sigue siendo un proceso lento, manual e informal.

Mita usa inteligencia artificial (modelos Gemini de Google) y un enfoque RAG-lite para estructurar publicaciones fragmentadas, calcular la compatibilidad de uso del suelo, y conectar a pymes y emprendedores con agentes inmobiliarios a través de leads calificados por WhatsApp.

---

## 🔗 Enlaces Oficiales (Entregables)

*   **🎬 Video de Presentación y Demo:** [https://youtu.be/G3OXSWv7gQw](https://youtu.be/G3OXSWv7gQw)
*   **📊 Slides del Pitch (Google Slides):** [https://docs.google.com/presentation/d/18Je4QOhWFr40LIwaTisR7hjwyYEfrXxePe5Ei4NbNOI/edit?usp=sharing](https://docs.google.com/presentation/d/18Je4QOhWFr40LIwaTisR7hjwyYEfrXxePe5Ei4NbNOI/edit?usp=sharing)
*   **💻 Aplicación Frontend (Vercel):** [https://mita-frontend.vercel.app/](https://mita-frontend.vercel.app/)
*   **⚙️ Backend API (Vercel):** [https://mita-api-nu.vercel.app/](https://mita-api-nu.vercel.app/)
*   **📝 Lienzo Lean Canvas (Google Docs):** [https://docs.google.com/document/d/1CIipiuv3CtWW9dVyoqMoafpUg7sWlungbditSw9C2HM/edit?usp=sharing](https://docs.google.com/document/d/1CIipiuv3CtWW9dVyoqMoafpUg7sWlungbditSw9C2HM/edit?usp=sharing)
*   **📄 Documento de Negocio y Técnico (Google Docs):** [https://docs.google.com/document/d/16lkrffneIhbr1qJiQdBeKtB0vD8aeeJYedG9I8j9pls/edit?usp=sharing](https://docs.google.com/document/d/16lkrffneIhbr1qJiQdBeKtB0vD8aeeJYedG9I8j9pls/edit?usp=sharing)

---

## 📂 Contenido del Repositorio `.github`

Dentro de este repositorio de configuración pública se encuentran las carpetas de soporte para la entrega final:
*   [**`pitch/`**](../pitch/): Contiene los documentos en formato de Microsoft Office listos para entrega:
    - [**`Mita_pitch_deck.pptx`**](../pitch/Mita_pitch_deck.pptx): Presentación en formato widescreen 16:9 simplificada, con gráficos de reporte y notas del orador completas en español.
    - [**`Mita_documento_pitch_negocio.docx`**](../pitch/Mita_documento_pitch_negocio.docx): Documentación técnica y de negocios formal (152 párrafos, 7 tablas y 6 diagramas de flujo embebidos).
    - [**`LienzoLeanCanvas_BWAI.docx`**](../pitch/LienzoLeanCanvas_BWAI.docx): Lienzo Lean Canvas oficial de Mita.
*   [**`diagrams/`**](../diagrams/): Código fuente de los diagramas de secuencia y flujo en PlantUML (`.rb`) y sus correspondientes imágenes generadas en [**`diagrams/png/`**](../diagrams/png/).
*   [**`research/`**](../research/): Gráficos estadísticos formales y reportes de PIB del INE Santa Cruz e inferencias generadas para Mita.

---

## ✨ Características Principales

1.  **Normalización de Ofertas Inmobiliarias:** Transforma publicaciones desordenadas y lenguaje informal de redes en esquemas JSON limpios y estructurados.
2.  **Búsqueda Conversacional:** Interpreta búsquedas abiertas del usuario (ej. *"local para cafetería cerca de avenida con alto tráfico, máx $800"*) extrayendo intenciones, zonificaciones e infraestructura necesaria.
3.  **Algoritmo de Matching Explicable:** Evalúa la compatibilidad comercial y logística de las propiedades, generando una explicación en lenguaje natural con Pros, Contras y Alertas (ej. restricciones de parqueo, falta de energía trifásica).
4.  **RAG-lite (Retrieval-Augmented Generation):** Búsqueda semántica ágil y cálculo de similitud coseno de embeddings de Gemini contra el inventario.
5.  **Trust Friction Index:** Métrica propia que mide el nivel de riesgo de fraude, veracidad e incompletitud de cada publicación.
6.  **WhatsApp Leads:** Botón final para contactar al agente enviando un mensaje pre-filtrado con la justificación de compatibilidad calculada.

---

## 👥 Equipo Mita — Build With AI 2026

*   **Daniel Cueto**
*   **Ariane Somoza**
*   **Denis Lira**
