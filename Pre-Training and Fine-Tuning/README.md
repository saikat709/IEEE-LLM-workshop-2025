with conda env:
conda create -n "llm_workshop_env" python==3.10 -y
conda activate llm_workshop_env
pip install -r requirements.txt


with venv:
python3 -m venv llm_workshop_env
source llm_workshop_env/bin/activate
pip install -r requirements.txt
