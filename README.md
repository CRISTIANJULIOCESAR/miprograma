# Create cisTarget databases


## MIPROGRAMA


### Clone `create_cisTarget_databases` source code

```bash
# Clone git repo.
git clone https://github.com/aertslab/create_cisTarget_databases

cd create_cisTarget_databases

# Display to which value ${create_cistarget_databases_dir} variable should be set.
echo "create_cistarget_databases_dir='""${PWD}""'"
```


### Create conda environment

```bash
# Create conda environment.
conda create -n create_cistarget_databases \
    'python=3.10' \
    'numpy=1.21' \
    'pandas>=1.4.1' \
    'pyarrow>=7.0.0' \
    'numba>=0.55.1' \
    'python-flatbuffers'
```

### Install Cluster-Buster

Install [Cluster-Buster](https://github.com/ghuls/cluster-buster/) for scoring regulatory regions with motifs.

#### Install precompiled binary
