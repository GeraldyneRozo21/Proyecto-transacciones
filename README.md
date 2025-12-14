# Proyecto de Procesamiento de Transacciones
Canalización de procesamiento de datos de transacciones con Python y Pandas

📌 Objetivo
Este proyecto implementa un script en Python para procesar un archivo de transacciones en formato JSON Lines (.jsonl), aplicar transformaciones y generar un archivo de salida en formato Parquet, optimizado para análisis y almacenamiento eficiente.

El objetivo principal es demostrar habilidades prácticas en procesamiento de datos, manejo de archivos y buenas prácticas de estructuración de proyectos para ingeniería de datos.

🧠 ¿Qué hace el script?

Lee un archivo de transacciones en formato .jsonl
Valida y normaliza la información
Aplica transformaciones básicas sobre los datos
Genera un archivo de salida en formato Parquet

📂 Estructura del proyecto
Proyecto-transacciones/
│
├── proyecto_transacciones.py # Script principal
├── requirements.txt # Dependencias del proyecto
├── output.parquet # Archivo de salida generado
└── README.md # Documentación del proyecto

▶️ Cómo ejecutar el proyecto

1️⃣ Clonar el repositorio
git clone https://github.com/GeraldyneRozo21/Proyecto-transacciones.git
cd Proyecto-transacciones

2️⃣ Instalar dependencias
pip install -r requirements.txt

3️⃣ Ejecutar el script
python proyecto_transacciones.py

📥 Datos de entrada
Formato: JSON Lines (.jsonl)
Cada línea representa una transacción independiente

📤 Salida
Archivo generado: output.parquet
Formato optimizado para análisis y procesamiento posterior

🛠️ Tecnologías utilizadas
Python 3
Pandas
pyarrow 

📊 Decisiones técnicas
Uso de Parquet por su eficiencia en almacenamiento y lectura
Procesamiento en Python para claridad y mantenibilidad
Dependencias mínimas para facilitar la ejecución

👩‍💻 Autora
Geraldyne Rozo Arias
