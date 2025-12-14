# Proyecto-transacciones
Canalización de procesamiento de datos de transacciones con Python y Pandas

## 📌 Objetivo
Crear un script de Python que procese un archivo de transacción y genere una vista de resumen agregada por:
- BIN (Número de Identificación Bancaria)
- Día de la transacción
- Número de transacciones aprobadas
- Importe total aprobado

La salida se almacena en **formato Parquet**.

---

## 🛠️ Tecnologías utilizadas
- Python 
- pandas
- pyarrow

---

## 📂 Datos de entrada
El archivo de entrada debe ser un archivo de líneas JSON (`.jsonl`) que contenga los registros de las transacciones.
