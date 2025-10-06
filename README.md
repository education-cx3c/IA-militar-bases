# 🧠 Bases Teóricas de la Inteligencia Artificial Militar
**Repositorio de apoyo académico – Programa de Educación Militar en IA**  
📍 Organización: [education-cx3c](https://github.com/education-cx3c)  
📅 Última actualización: Octubre 2025  

---

## 🎯 Propósito del material
Este repositorio proporciona las **bases teóricas, técnicas y normativas** para comprender e integrar la **Inteligencia Artificial (IA)** dentro del entorno militar, con el objetivo de:

1. Formar pensamiento estratégico y técnico en los cursantes.  
2. Establecer un marco de referencia alineado con normas internacionales (ISO / NIST / UNESCO).  
3. Servir como base para ejercicios prácticos, artículos doctrinales y proyectos de investigación de posgrado.  

---

## 🪖 1. ¿Qué es la Inteligencia Artificial?

> “La Inteligencia Artificial es la disciplina científica y tecnológica que busca desarrollar sistemas capaces de ejecutar funciones asociadas al pensamiento humano —como el razonamiento, la percepción, la planificación o el aprendizaje— mediante modelos matemáticos y computacionales.”  
> — *Adaptado de Russell & Norvig (Artificial Intelligence: A Modern Approach, 2021)*

### Tipos de IA

| Tipo | Descripción | Ejemplo militar |
|------|--------------|----------------|
| **IA Débil (Narrow AI)** | Especializada en tareas concretas; no razona fuera de su dominio. | Clasificación de imágenes satelitales, predicción logística. |
| **IA Fuerte (General AI)** | Inteligencia equiparable a la humana; aún teórica. | No disponible (hipótesis de investigación). |
| **IA Generativa** | Produce contenido nuevo (texto, imagen, código) basado en patrones aprendidos. | Análisis doctrinal automatizado, generación de reportes ISR. |

---

## ⚙️ 2. Fundamentos técnicos

### 🔹 Aprendizaje Automático (Machine Learning)
Método mediante el cual un sistema aprende de los datos para mejorar su desempeño sin ser explícitamente programado.  
- **Supervisado:** aprende con ejemplos etiquetados.  
- **No supervisado:** encuentra patrones ocultos.  
- **Reforzado:** aprende por ensayo y error (similar a la toma de decisiones militar iterativa).

📘 *Referencia:*  
- Mitchell, T. (1997). *Machine Learning*. McGraw-Hill.  
- Géron, A. (2022). *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*. O’Reilly.

---

### 🔹 Aprendizaje Profundo (Deep Learning)
Basado en **redes neuronales artificiales** con múltiples capas que simulan la forma en que el cerebro procesa información.  
Usos militares: reconocimiento de objetivos, predicción de trayectorias, procesamiento de señales ISR.

📘 *Referencia:*  
- LeCun, Y., Bengio, Y., & Hinton, G. (2015). *Deep Learning*. Nature, 521(7553), 436–444.

---

### 🔹 Modelos de Lenguaje Extenso (LLM)
Son modelos entrenados con grandes cantidades de texto que aprenden el contexto y la estructura del lenguaje.  
Ejemplo: Llama, Gemma, Mistral, DeepSeek, GPT.  
Se utilizan como base para construir sistemas de IA generativa en entorno militar cerrado (on-premise).

📘 *Referencia:*  
- OpenAI (2023). *Technical Report: GPT-4 System Card*.  
- Meta AI (2024). *Llama 3: Open Foundation and Fine-Tuned Chat Models*.  

---

## 🧩 3. Arquitectura general de un entorno de IA militar

**Componentes clave:**

| Capa | Elemento | Función |
|------|-----------|---------|
| **Datos** | MinIO (S3), PostgreSQL | Repositorio seguro de datasets y documentos doctrinales. |
| **Vectorización** | Qdrant / Chroma | Búsqueda semántica y RAG (Retrieval-Augmented Generation). |
| **Modelos** | Ollama (Llama/Gemma) | Inferencia local sin dependencia de nube. |
| **Orquestación** | WebUI / API REST | Interacción segura y trazable. |
| **Gobernanza** | GitLab, Keycloak, Vault | Control de versiones, autenticación, gestión de secretos. |
| **Seguridad** | pfSense, HAProxy, WAF | Protección perimetral y cifrado TLS. |

📘 *Referencia:*  
- Goodfellow, I., et al. (2016). *Deep Learning*. MIT Press.  
- Zissis, D., Lekkas, D. (2011). *Addressing Cloud Computing Security Issues*. Future Generation Computer Systems.

---

## 🧭 4. Marcos normativos y éticos

| Norma / Marco | Enfoque | Aplicación militar |
|----------------|----------|--------------------|
| **ISO/IEC 42001:2023** | Gestión ética y trazable de sistemas de IA. | Implementación de control humano significativo. |
| **NIST AI RMF 1.0 (2023)** | Marco de gestión de riesgos de IA. | Evaluación de sesgos, seguridad y gobernanza. |
| **ISO/IEC 27001:2022** | Seguridad de la información. | Clasificación de datos por nivel y categoría. |
| **UNESCO AI Ethics (2021)** | Principios éticos globales. | Garantía de proporcionalidad y respeto a derechos humanos. |
| **OCDE AI Principles (2019)** | Recomendaciones de transparencia y responsabilidad. | Supervisión y auditoría de modelos de IA militar. |

📘 *Referencias oficiales:*  
- [ISO/IEC 42001 Overview](https://www.iso.org/standard/81217.html)  
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)  
- [UNESCO – Ethics of Artificial Intelligence](https://unesdoc.unesco.org/ark:/48223/pf0000379920)  
- [OECD – AI Principles](https://oecd.ai/en/ai-principles)

---

## ⚔️ 5. Aplicaciones en el ámbito militar

| Dominio | Aplicación IA | Ejemplo |
|----------|----------------|---------|
| **ISR / Inteligencia** | Análisis multifuente, priorización de PIRs. | Integración SIGINT + OSINT. |
| **Operaciones** | Generación de COAs, simulación doctrinal. | Planeamiento automatizado con control humano. |
| **Logística** | Predicción de consumos, optimización de rutas. | Soporte a unidades desplegadas. |
| **Ciberdefensa** | Correlación de TTP y respuesta a incidentes. | Apoyo a Comando Cibernético. |
| **Formación** | Tutor doctrinal, wargaming, revisión AAR. | Entrenamiento con IA adaptativa. |

---

## 🧠 6. Principios doctrinales de integración IA–militar

1. **Soberanía Cognitiva:** los modelos, datos y pesos deben residir bajo control estatal o institucional.  
2. **Control Humano Significativo:** ninguna decisión operacional sin validación humana.  
3. **Necesidad de Saber + Mínima Exposición:** segmentación por nivel y categoría.  
4. **Trazabilidad Total:** toda inferencia debe ser auditable y verificable.  
5. **Resiliencia Operacional:** capacidad de operar sin internet o en modo degradado.  

📘 *Referencia doctrinal:*  
- Doctrina OTAN AJP-3.10 (Information Operations).  
- U.S. DoD (2023). *Responsible Artificial Intelligence Strategy and Implementation Pathway*.  
- SECTEI México (2024). *Lineamientos Éticos para el Uso de IA en el Sector Público.*

---

## 🧮 7. Retos actuales y oportunidades

| Desafío | Riesgo | Oportunidad |
|----------|---------|-------------|
| Dependencia tecnológica | Fuga de datos sensibles | Desarrollo soberano de IA nacional |
| Sesgos algorítmicos | Decisiones no proporcionales | Mejora del criterio doctrinal y ético |
| Falta de doctrina específica | Uso descontrolado | Creación de doctrina IA militar nacional |
| Desconocimiento técnico | Rechazo o miedo a la IA | Capacitación híbrida: técnico–estratégica |

---

## 📚 8. Referencias bibliográficas complementarias

- Russell, S., & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach*. Pearson.  
- Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press.  
- Kaplan, J., Haenlein, M. (2020). *Rulers of the World, Unite! The Challenges and Opportunities of AI*. Business Horizons.  
- U.S. Department of Defense (2023). *DoD Data, Analytics, and Artificial Intelligence Adoption Strategy*.  
- NATO Communications and Information Agency (2024). *AI in Defence Operations: Doctrinal Overview.*  
- SECTEI CDMX (2024). *Ética e Inteligencia Artificial en la Administración Pública*.  

---

## 🧩 9. Actividad académica recomendada

> **Tarea:**  
> 1️⃣ Lee este material.  
> 2️⃣ Escribe una reflexión (máx. 1 página) sobre:  
> - ¿Qué principio del NIST o ISO consideras más relevante para el ámbito militar?  
> - ¿Qué dominio (ISR, C2, Logística o Ciber) se verá más transformado por la IA y por qué?  
>  
> 📅 *Entrega: próxima sesión (día siguiente).*  

---

## 🪙 Frase de cierre doctrinal

> “La Inteligencia Artificial no sustituirá al comandante; pero quien domine su uso, comandará el futuro.”

---

## 🔗 Enlaces complementarios

- [ISO/IEC 42001:2023 – AI Management System](https://www.iso.org/standard/81217.html)  
- [NIST AI Risk Management Framework (AI RMF)](https://www.nist.gov/itl/ai-risk-management-framework)  
- [UNESCO Ethics of AI Report (2021)](https://unesdoc.unesco.org/ark:/48223/pf0000379920)  
- [Open-Source Models – Ollama Library](https://ollama.ai/library)  
- [NATO Science & Technology – AI in Defence](https://www.nato.int/cps/en/natohq/topics_195915.htm)  

---

**Autor:** Programa de Educación e Investigación en Inteligencia Artificial Militar – [GRUPO SST / education-cx3c](https://github.com/education-cx3c)  
**Uso:** Material educativo abierto con fines académicos y doctrinales.  
**Licencia:** CC BY-NC-SA 4.0  

---
