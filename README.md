# # 🍽️ Generador Inteligente de Recetas Saludables
## informacion de el Proyecto 
<table>
<tr>
<td><strong>Universidad</strong></td>
<td>San Francisco Xavier de Chuquisaca</td>
</tr>
<tr>
<td><strong>Carrera</strong></td>
<td>Ingeniería en Ciencias de la Computación</td>
</tr>
<tr>
<td><strong>Materia</strong></td>
<td>Desarrollo de Aplicaciones Inteligentes - IA3</td>
</tr>
<tr>
<td><strong>Autor</strong></td>
<td><strong>Alfaro Ayzama José Fernando</strong></td>
</tr>
<tr>
<td><strong>👨‍🏫 Docente</strong></td>
<td>Ing. Carlos Walter Pacheco Lora</td>
</tr>
<tr>
<td><strong>Curso</strong></td>
<td>2025 - 7mo Semestre</td>
</tr>
</table>

## 📌 Descripción Breve

> 📷imgen tomada ➜ 🧠procesada ➜ 📝lsita de ingredientes
> 📝porsion para una persona➜🥗 Receta saludable + 🍳 Receta tradicional

Con solo tomar una foto,la appidentifica los alimentos, calcula las porciones y calorías, y te sugiere 2 tipos de recetas personalizadas en cuestión de segundos. Ideal para usuarios preocupados por su nutrición, estudiantes, y aplicaciones educativas o médicas.

---

## ⚙️ ¿Cómo Funciona?

1. **Captura de Imagen**: El usuario toma una fotografía desde la app móvil (Flutter).
2. **Reconocimiento de Alimentos**: El servidor usa el modelo YOLOv8n para identificar y segmentar los alimentos.
3. **Estimación de Volumen y Calorías**: Se utiliza Depth Anything para estimar volumen y convertirlo en calorías usando tablas nutricionales.
4. **Generación de Recetas**: GPT-3 (OpenAI) genera dos recetas por imagen: una saludable y una tradicional.
5. **Visualización en App**: Todo se muestra al usuario en la aplicación móvil.

es un software basado en inteligencia artificial que reconoce alimentos mediante imágenes capturadas por un dispositivo móvil, estima su volumen y contenido calórico, y genera automáticamente dos tipos de recetas: una saludable y una tradicional. Este proyecto combina visión por computadora, estimación volumétrica y procesamiento de lenguaje natural para ofrecer una herramienta innovadora en el ámbito de la nutrición personalizada.

## 🧠 Tecnologías y Modelos Utilizados

- **YOLOv8n-seg** – Detección y segmentación de alimentos.
- **Depth Anything** – Estimación monocular de profundidad para cálculo de volumen.
- **GPT-3 (OpenAI)** – Generación automática de recetas personalizadas.
- **Flutter** – Desarrollo de la aplicación móvil.
- **Flask** – Backend para procesamiento de imágenes e inferencias.

## ⚙️ Funcionalidades

- Captura de imagen desde la app móvil.
- Identificación de alimentos en tiempo real.
- Estimación de volumen y calorías por ingrediente.
- Generación de dos recetas: saludable y tradicional.
- Visualización inmediata de resultados en la app.



