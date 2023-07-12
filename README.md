```
Create a new conda environment from the provided env.yaml file:
conda env create -f env.yaml
````

```
ML Workflow Scripts
The project includes the following ML workflow scripts:

ingest_data.py: A script to download and create training and validation datasets
python ingest_data.py

train.py: A script to train the model(s)
python train.py

score.py: A script to score the model(s)
python score.py

```

```
Logging
The scripts use logging to generate logs during execution.
```