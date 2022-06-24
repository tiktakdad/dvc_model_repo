<div align="center">


# DVC Model Repository
</div>


<br><br>

## 🚀&nbsp;&nbsp;Quickstart

```bash
# clone project
$ git clone https://github.com/tiktakdad/dvc_model_repo.git
$ cd dvc_model_repo
$ pip install -r requirements.txt
$ dvc pull
$ cd triton_models_auto_labeling
$ tree
.
└── auto_labeling_onnx
    ├── 1
    │   └── model.onnx
    └── config.pbtxt


# [OPTIONAL] create conda environment
$ conda create -n dvc python=3.8
$ conda activate dvc