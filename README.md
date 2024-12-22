# 📄 App de IA para Resúmenes y Preguntas

### **Descripción del Proyecto**
Esta aplicación web utiliza inteligencia artificial para resumir documentos complejos y generar preguntas clave basadas en el contenido. Diseñada para demostrar capacidades innovadoras de IA generativa, está enfocada en atraer la atención en LinkedIn como herramienta de marketing y automatización.

---

## **Características Principales**
- **Carga de Documentos:** Subida de archivos en formatos PDF y texto plano.
- **Resúmenes Automáticos:** Simplifica textos largos en resúmenes concisos.
- **Generación de Preguntas:** Crea preguntas relevantes para facilitar el análisis del contenido.
- **Interfaz Intuitiva:** Diseño amigable y simple para el usuario.

---

## **Tecnologías Utilizadas**
- **Backend:** FastAPI
- **Frontend:** React
- **IA:** LangChain con modelos OpenAI GPT
- **Base de Datos:** SQLite
- **Gestón del Proyecto:** Notion y WhatsApp

---

## **Instalación y Configuración**

### **Requisitos Previos**
- Python 3.9 o superior.
- Node.js 14 o superior.

### **Pasos de Instalación**
1. Clona este repositorio:
   ```bash
   git clone https://github.com/usuario/nombre-repo.git
   ```
2. Entra al directorio del proyecto:
   ```bash
   cd nombre-repo
   ```
3. Crea un entorno virtual e instala las dependencias:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows usa venv\Scripts\activate
   pip install -r requirements.txt
   ```
4. Configura la API Key para OpenAI:
   - Crea un archivo `.env` en la carpeta raíz:
     ```env
     OPENAI_API_KEY=tu_clave_api
     ```
5. Inicia el servidor backend:
   ```bash
   uvicorn main:app --reload
   ```
6. Levanta el frontend en desarrollo:
   ```bash
   npm start
   ```

---

## **Uso de la Aplicación**
1. Sube un documento en formato PDF o texto.
2. Espera el procesamiento por la IA.
3. Recibe un resumen automático y preguntas clave generadas.

---

## **Contribuciones**
Este proyecto es colaborativo y está abierto a contribuciones.
- **Autores:** Nahuel Perdomo, Guillermo Torres.
- **Contribuciones:** Se aceptan pull requests. Para sugerencias o ideas, abre un issue en el repositorio.

---

## **Estado del Proyecto**
- **Fase Actual:** Desarrollo del Producto Mínimo Viable (PMV).
- **Fecha esperada para lanzamiento:** Febrero de 2025.

---

## **Licencia**
Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

