Note this implementation works with pytorch=0.4.0 and cuda8.0.
## Create a conda environment

```
conda env create -f csm.yml
source activate csm
```

## Download and install dependecies
```
pip install cupy-cuda80
```

## Download & clone the repo
```
git clone git@github.com:nileshkulkarni/csm.git csm_root
```


## Download external dependcies
```
cd csm_root/csm/external/
sh install.sh
```

## Install remaining dependencies
```
pip install -r docs/requirements.txt
```




