# scanpy
test repo

# rapids-singlecell installation
1st install: conda create --solver=libmamba -n rapids-24.02 -c rapidsai -c conda-forge -c nvidia  \
                rapids=24.02 python=3.10 cuda-version=12.0 \
                jupyterlab tensorflow pytorch

2nd install: pip install rapids-singlecell