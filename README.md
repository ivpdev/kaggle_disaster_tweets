!! apparently steps from setup.sh should be executed manually
# kaggle_disaster_tweets

# Setup Env
python -m venv venv_bert_rf
source bert10l/bin/activate
pip install ipykernel
ipython kernel install --user --name=venv_bert_rf

# Start Jupyter
start_jupyter.sh