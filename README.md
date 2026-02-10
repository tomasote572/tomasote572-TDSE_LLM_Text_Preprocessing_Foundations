# TDSE_LLM_Text_Preprocessing_Foundations

## Embeddings y Preprocesamiento de Texto para LLMs

Este repositorio contiene un notebook Jupyter educativo basado en el Capítulo 2 del libro "Build a Large Language Model (From Scratch)" de Sebastian Raschka.

### Contenido

#### 📓 `embeddings.ipynb`
Notebook completo que cubre los fundamentos del preprocesamiento de texto para Large Language Models:

1. **Tokenización básica y Byte Pair Encoding (BPE)**
   - Conversión de texto a tokens
   - Implementación con tiktoken (GPT-2)
   
2. **Data sampling con sliding window**
   - Creación de ventanas de entrenamiento
   - Parámetros `max_length` y `stride`
   
3. **Token embeddings**
   - Representaciones vectoriales de tokens
   - Matrices de embeddings aprendibles
   
4. **Positional encodings**
   - Incorporación de información de posición
   - Encodings absolutos y relativos

5. **Experimento: Efecto de max_length y stride**
   - Análisis práctico de parámetros
   - Visualización de resultados

#### 📄 `the-verdict.txt`
Archivo de texto de ejemplo usado en el notebook para demostración.

### Características especiales

- ✅ **4 explicaciones en español** que responden preguntas fundamentales:
  - ¿Por qué necesitamos tokenización?
  - ¿Por qué usar sliding window para crear muestras?
  - ¿Por qué los embeddings codifican significado?
  - ¿Por qué necesitamos positional encodings?

- ✅ **Experimento práctico** con análisis de parámetros de data sampling

- ✅ **148 celdas totales** (94 markdown, 54 código)

- ✅ **Código ejecutable** de principio a fin

### Requisitos

```bash
pip install torch tiktoken pandas jupyter
```

### Uso

```bash
jupyter notebook embeddings.ipynb
```

### Estructura del notebook

```
Introducción
├── Explicación 1: Tokenización (con código)
├── Explicación 2: Sliding Window (con código)
├── Explicación 3: Embeddings (con código)
├── Explicación 4: Positional Encodings (con código)
└── Experimento: max_length y stride (con análisis)
```

### Referencias

- Libro: "Build a Large Language Model (From Scratch)" - Sebastian Raschka
- Repositorio original: https://github.com/rasbt/LLMs-from-scratch
- Capítulo 2: https://github.com/rasbt/LLMs-from-scratch/tree/main/ch02

### Licencia

Este material educativo está basado en código de fuente abierta del repositorio LLMs-from-scratch.