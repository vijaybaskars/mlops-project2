# mlops-project2
```
git clone git@github.com:vijaybaskars/mlops-project2.git
cd mlops-project2
conda create -n "mlops-project2_env" python=3.9
conda activate mlops-project2_env
conda install "numpy<2" statsmodels
conda activate mlops-project2_env
python regression.py
git add .
git commit -m "Running Version" -a
git push origin main
conda list
git add .
git commit -m "Added requirements.txt" 
git push origin main
conda list -e > requirements.txt
```