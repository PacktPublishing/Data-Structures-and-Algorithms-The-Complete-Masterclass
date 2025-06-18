


# Data-Structures-and-Algorithms-The-Complete-Masterclass
Data Structures and Algorithms: The Complete Masterclass, by Packt Publishing 

# PytorchUltimate
This repo holds material for the Udemy course PyTorch Ultimate: From Basics to Cutting-Edge. You can find the course under this link.

# Environment Installation
There are two ways to install the environment:

Using venv
Using conda

# 1. venv Environment Installation
Mac, Linux
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install -r requirements_py3.txt
Windows
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements_py3.txt

# 2. Conda Environment Installation
We work with Anaconda and use conda environments. You can replicate my environment by running:

C:\...> conda env create -f pytorch.yml

## Environment Installation from scratch
If the installation from yml file fails, you can install the environment manually by running these commands:

C:\...> conda create -n pytorch python=3.10
C:\...> conda activate pytorch
(pytorch) C:\...> conda install pytorch torchvision torchaudio cpuonly -c pytorch
(pytorch) C:\...> conda install ipykernel
(pytorch) C:\...> conda install -c anaconda seaborn
(pytorch) C:\...> conda install scikit-learn
(pytorch) C:\...> $ conda install -c conda-forge detecto
