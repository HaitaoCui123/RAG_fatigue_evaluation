## Environmental requirements  
```
conda create -n kotaemon python=3.10
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
