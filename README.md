# Mi proyecto con GPT-OSS 20B

Este repositorio contiene código para ejecutar el modelo GPT-OSS 20B de OpenAI usando Hugging Face Transformers.

---

## Requisitos

- Python 3.10+
- GPU NVIDIA recomendada con al menos 16 GB VRAM
- Espacio libre > 20 GB para pesos del modelo

---

## Cómo usar

1. Clona este repositorio:
bash
git clone https://github.com/tu_usuario/mi-gpt-oss-proyecto.git
cd mi-gpt-oss-proyecto

2. Instala dependencias:

pip install -r requirements.txt

3. Descarga los pesos del modelo:

./download_model.sh

4. Ejecuta el script:

python run_gpt_oss.py


---

### 2. `requirements.txt`

```txt
torch
transformers
accelerate
safetensors
