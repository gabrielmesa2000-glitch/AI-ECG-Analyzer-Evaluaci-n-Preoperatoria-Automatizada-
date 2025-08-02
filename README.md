# AI ECG Analyzer – Evaluación Preoperatoria Automatizada 🫀⚡

Este proyecto integra inteligencia artificial y visualización médica para apoyar decisiones clínicas en cardiología:

- Generación de trazado electrocardiográfico simulado 📊
- Cálculo automatizado de EuroSCORE II 🧠
- Presentación web accesible para demostraciones clínicas 🌐

## 💻 Componentes

- `EuroSCOREII_calculator.py`: Calcula riesgo quirúrgico según variables clínicas.
- `ecg_tracer.py`: Simula un trazado de ECG y lo guarda como imagen.
- `app.py`: Interfaz Flask que une todos los módulos.
- `assets/`: Carpeta con recursos gráficos como ECG generado.
- `requirements.txt`: Dependencias para el entorno Python.

## 🚀 Cómo usar

```bash
pip install -r requirements.txt
python app.py
