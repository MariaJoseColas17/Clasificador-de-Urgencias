# 🇩🇴 Dominican Emergency Message Analyzer

**Clasificador inteligente de mensajes en jerga dominicana**, diseñado para identificar la intención (emergencia, consulta o informal), el nivel de urgencia y extraer palabras clave relevantes para su uso en sistemas automatizados de respuesta.

---

## 📌 Descripción

Este proyecto demuestra cómo aplicar técnicas de NLP (procesamiento de lenguaje natural) y machine learning para analizar mensajes escritos en lenguaje coloquial dominicano. Está orientado a:

- Clasificar la **intención del mensaje**
- Estimar la **urgencia** (alta, media o baja)
- Detectar **palabras clave críticas** relacionadas a emergencias

Ideal como MVP para soluciones locales de asistencia basada en IA.

---

## 🛠 Tecnologías y librerías

- Python
- Pandas
- Scikit-learn
- TfidfVectorizer
- RandomForestClassifier
- Matplotlib / Seaborn

---

## 🧠 Estructura del proyecto

- `dataset`: Frases en jerga dominicana etiquetadas por intención y urgencia.
- `modelo`: Clasificadores entrenados para intención y urgencia.
- `predicción`: Entrada de nuevos mensajes y retorno de clasificaciones.
- `visualización`: Gráficas para analizar distribución de datos y resultados.

---

## 🧪 Ejemplo de uso

```python
Texto: "¡Se prendió fuego en la cocina!" → Clasificación: "emergencia", Urgencia: "alta"
Texto: "¿Dónde hay un colmado?" → Clasificación: "consulta", Urgencia: "media"
Texto: "Tamo en teteo manito" → Clasificación: "informal", Urgencia: "baja"
