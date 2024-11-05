1. Crear el virtual enviromment

python -m venv .venv

2. Activar el virtual enviromment

.venv\Scripts\Activate.psl

3. Instalar pip

python -m pip install --upgrade pip

4. Instalar fastapi

pip install "fastapi[standard]"

5. Crear archivo requeriments

python -m pip freeze > requirement.txt

6. Crear el main.py

7. Correr el servidor

fastapi dev .\main.py

8. Instalar TestClient

pip install httpx

9. Instalar PyTest

pip install pytest

10. Iniciar la app

uvicorn main:app --reload

11. Ingresar a los métodos

http://127.0.0.1:8000/docs
