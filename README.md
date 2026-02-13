# 📄 CvAutomatic

Generador automático de currículum en formato `.docx` usando Python.

Este proyecto permite crear un CV dinámico a partir de una plantilla Word que contiene variables (placeholders) como:

{{fullnombre}}
{{email}}
{{telefono}}
{{linkedin}}
{{github}}

yaml
Copiar código

El script solicita los datos por consola, reemplaza automáticamente los placeholders y genera un nuevo archivo listo para enviar.

---

## 🚀 Tecnologías Utilizadas

- Python 3
- python-docx

---

## 📦 Instalación

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/TecnicoD/CvAutomatic.git
cd CvAutomatic
2️⃣ (Opcional) Crear entorno virtual
bash
Copiar código
python -m venv venv
venv\Scripts\activate  # Windows
3️⃣ Instalar dependencias
bash
Copiar código
pip install -r requirements.txt
▶️ Uso
Ejecutar el script principal:

bash
Copiar código
python cv_generator.py
El programa pedirá ingresar los datos por consola y generará un nuevo archivo .docx con el CV completo.

📂 Estructura del Proyecto
Copiar código
CvAutomatic/
│
├── cv_generator.py
├── CV_template.docx
├── requirements.txt
└── README.md
🎯 Objetivo del Proyecto
Automatizar la creación de currículums

Adaptar el CV rápidamente a distintas ofertas laborales

Practicar manipulación de documentos Word con Python

Optimizar tiempo en procesos de postulación

💡 Posibles Mejoras Futuras
Generación automática en PDF

Interfaz gráfica (Tkinter / PyQt)

Versión web con Flask

Publicación como herramienta CLI instalable

👨‍💻 Autor
Dante Nicolás Rodríguez

GitHub: https://github.com/TecnicoD

LinkedIn: https://www.linkedin.com/in/dantenrodríguez/

⭐ Si te resulta útil
Podés dejar una estrella en el repositorio.
