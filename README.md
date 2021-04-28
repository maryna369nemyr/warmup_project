# warmup_project
## Miniconda
Install miniconda from this [website](https://docs.conda.io/en/latest/miniconda.html).

Update conda by
``` conda update -n base -c defaults conda```


Check the python version
```
python3 --version
```
Then once you installed miniconda, create a new environamen
```
conda create -n myenv python=3.6
```
Then install packages to the environment

```
conda activate myenv
```

Then
```pip3 install numpy```

Run pycharm 
```
 bash ~/Downloads/pycharm-community-2018.1.4/bin/pycharm.sh 
```


## Conda
To see which environamens are available
``` conda info --envs```

Activate existing environment
``` conda activate myenv```

(To deactivate this environment run)
``` conda deactivate```

List all the packages in the enironment 
``` conda list -n myenv```