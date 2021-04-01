create venv
	python -m venv venv
	
source venv

install requirements
	pip install -r requirements.txt
	
download pretrained (checkpoints)

run forward_flow
	python forward_flow.py