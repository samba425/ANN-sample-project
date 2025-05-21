
IMPORTANT TIPS(## siva)

-> install Anaconda
-> conda insatll pydotplus (to visulaize decision tree)
-> conda install tensorflow / pip install tensorflow (deep network)



basic of python
-> ...../MLCourse/Python101.ipynb (can see basic of python)

basic of Pandas
-> ...../MLCourse/PandasTutorial.ipynb (can see basic of Pandas)

<!-- to install python  -->
bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" 
brew install python 
python3 --version
echo "alias python=python3" >> ~/.zshrc
source ~/.zshrc


<!-- install conda  -->

curl -LO https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
bash Miniconda3-latest-MacOSX-x86_64.sh


<!-- creating env -->
conda create -p venv python==3.11

=> create requirements.txt for install packages

<!-- to activeate env -->
conda activate venv/
 
 
 <!-- install packages -->
pip install -r requirements.txt
 
 <!-- for execute jupiter notebook -->
pip install ipykernel (for execute jupiter notebook)

// setup env 
conda setup -p venv python==3.11 -y ()


conda activate path



python -m venv myenv(any name)# ANN-sample-project
