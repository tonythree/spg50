# spg50
Hackathon #hackingtocuremichael

Using google colab:
1. Copy spg50.ipynb file in your drive.
2. Copy xls file inside data directory in your drive.
3. Open spg50.ipynb file using colab.
4. Change the first line of the notebook to True (Colab = True); this will mount your google drive.
5. Click on the path that will appear, copy the code and paste in notebook (this step is to let google mount your google drive).

1. Create a virtual environment using pipenv or venv and install requirements.txt:
Using venv:
cd spg50 
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt

Using pipenv:
cd spg50
pipenv shell
pipenv install -r requirements.txt

2. Open jupyter notebook:
jupyter notebook

3. Change the first line of the notebook to False (Colab = False).
