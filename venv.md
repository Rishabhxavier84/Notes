# Python Virtual Environment:


### VirtualEnv:
```bash
pip install virtualenv
virtualenv $envname
source .venv/bin/activate
```

### UV:

```bash
#install uv
pip install uv

#Creates set of default files
uv init $projectname
cd $projectname

#install dependencies and create the virtual environment
uv add numpy    

#remove dependencies
uv remove numpy


#create venv and install dependencies from the project
uv sync

#install dependencies from requirements.txt
uv pip install -r requirements.txt

#run python files
uv run hello.py
```