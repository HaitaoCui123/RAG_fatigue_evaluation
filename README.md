## Environmental requirements  
```
conda create -n kotaemon python=3.11
conda activate kotaemon

# clone this repo
git clone https://github.com/Cinnamon/kotaemon
cd kotaemon

pip install -e "libs/kotaemon[all]"
pip install -e "libs/ktem"
```
## Start the web server  
```
python app.py
```
## Possible Issues and Solutions
### 1.Attempted to load [93mtaggers/averaged_perceptron_tagger_eng/
``` 
pip install nltk
```
从https://www.nltk.org/nltk_data/   下载Averaged Perceptron Tagger (JSON)，解压后放在/home/cht/nltk_data/taggers

