# Set up conda environment 
## From environment.yml file
```bash
conda env create -f environment.yml
conda activate redi2019
python -m ipykernel install --user --name redi2019 --display-name "redi2019"
```

## Manual setup
```bash
conda create --name redi2019 python=3.6
conda install pandas
conda install seaborn
conda install jinja2
conda install -c conda-forge scikit-learn
conda install -c conda-forge azure-storage-blob
conda install -c conda-forge python-avro
conda install -c conda-forge tqdm
conda install ipykernel
conda activate redi2019
python -m ipykernel install --user --name redi2019 --display-name "redi2019"
```