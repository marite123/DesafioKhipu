# DesafioKhipu
Desafio CSM
Integración Khipu API v3 – DemoBank (Python)

Este proyecto es un ejercicio de prueba que demuestra cómo crear un cobro usando la API v3 de Khipu y abrir el flujo de DemoBank (para simular pagos de hasta $5.000 CLP).

🚀 Requisitos

Python 3.10+ instalado

Librería requests

⚙️ Instalación

Clonar el repositorio

git clone https://github.com/marite123/DesafioKhipu.git
cd DesafioKhipu


Crear entorno virtual e instalar dependencias

python -m venv .venv
source .venv/bin/activate      # macOS / Linux
# .venv\Scripts\activate       # Windows PowerShell

pip install -r requirements.txt

🔑 Configurar credenciales

Copiar el archivo de ejemplo:

cp .env.example .env


Editar el archivo .env y agregar tu API Key de Khipu:

KHIPU_API_KEY=TU_API_KEY_AQUI



▶️ Ejecución
python TestKhipu.py


Resultado esperado:

Código de respuesta: 201 Created

JSON con un payment_url

Apertura automática del flujo DemoBank en el navegador

📂 Estructura del proyecto
DesafioKhipu/
├─ TestKhipu.py        # Script principal de integración
├─ requirements.txt    # Dependencias
├─ .env.example        # Plantilla para credenciales (sin tu API Key real)
├─ .gitignore          # Archivos ignorados (incluye .env y .venv)
└─ README.md           # Este documento

🔒 Seguridad

La API Key no debe compartirse.

El archivo .env está en .gitignore → no se sube al repo.

Solo compartir .env.example como guía.

📜 Licencia

Este proyecto se distribuye bajo la licencia MIT.
Uso únicamente con fines demostrativos para el desafío técnico


