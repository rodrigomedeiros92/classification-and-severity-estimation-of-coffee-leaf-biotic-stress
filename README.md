# Projeto com pesos e resultados da arquitetura Resnet 18 e 34, como há limite de armazenamento é necessário retreinar e retestar os modelos automaticamente com o arquivo script.py


Deep Learning for Classification and Severity Estimation of Coffee Leaf Biotic Stress
This repository is intended to develop the work supported by the Latin America Research Awards 2018.

Requirements
Install anaconda.

Create conda environment with python 3:

conda create -n <your_env_name> python=3.7
conda activate <your_env_name>
Then install the requirements:

conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
conda install Pillow==6.1 pandas matplotlib bokeh opencv
pip install -r requirements.txt
Dataset
All images collected to build the datasets used in this work are public available at the following link:

Coffee datasets.

Our experiments using the symptom datasets combine our images with those available at https://www.digipathos-rep.cnptia.embrapa.br/. However, the public dataset above contain only the images we collect, but here on github you will find exactly what was used in the experiments.
Research
The development of this work led to the publication of an paper in Computers and Electronics in Agriculture journal.
