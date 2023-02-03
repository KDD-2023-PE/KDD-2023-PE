## Running the Code
- Create the virtual environment
```
virtualenv pevenv --python=python3.8
. pevenv/bin/activate
```
- Install required packages
```
cd pseudo_edge
pip install -r requirements.txt
```
- Create following folders:
```
mkdir best_model
mkdir best_pl_model
```
- To reproduce *Pseudo-Edge w/GCN* performance on OGBL-COLLAB, run the following script:
```
bash run.sh
```
