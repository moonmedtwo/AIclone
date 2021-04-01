AIclone
create venv
	python -m venv venv
	
source venv

install requirements
	pip install -r requirements.txt
	
download pretrained (checkpoints)
	move checkpoints folder in to backend/checkpoints
run inference
	cd backend
	python inference.py