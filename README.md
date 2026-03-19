https://fjgkep4yftnftvdanrtzgw.streamlit.app/

📄 Convertidor PDF a Word con Streamlit

Aplicación web sencilla desarrollada con Streamlit que permite convertir archivos PDF a formato Word (.docx) directamente desde el navegador.

🚀 Características

Subida de archivos PDF

Conversión automática a Word

Descarga inmediata del archivo convertido

Limpieza automática de archivos temporales

🛠️ Requisitos

Antes de ejecutar la aplicación, asegúrate de tener instalado:

Python 3.8 o superior

pip

Instala las dependencias con:

pip install streamlit pdf2docx
▶️ Uso

Guarda el archivo como app.py (o el nombre que prefieras)

Ejecuta la aplicación:

streamlit run app.py

Se abrirá automáticamente en tu navegador

Sube un archivo PDF

Descarga el archivo convertido en Word

📂 Estructura del código
Función principal
def pdf_to_word(pdf_path, docx_path):

Usa pdf2docx.Converter

Convierte todas las páginas (start=0, end=None)

Flujo de la app

El usuario sube un PDF

Se guarda temporalmente en el servidor

Se convierte a .docx

Se genera botón de descarga

Se eliminan archivos temporales

⚠️ Notas importantes

Los archivos se guardan temporalmente en el servidor

Se eliminan automáticamente después de la conversión

La calidad de conversión depende del PDF original

PDFs escaneados pueden no convertirse correctamente (requieren OCR)

💡 Posibles mejoras

Soporte para OCR (ej: pytesseract)

Barra de progreso

Manejo de errores

Previsualización del documento

Soporte para múltiples archivos

👨‍💻 Autor

Cortesía Carpio
