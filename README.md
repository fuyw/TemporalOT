# TemporalOT

## Environment Setup

We use Python3.9 and Cuda12.

```shell
conda create --name TemporalOT python==3.9
conda activate TemporalOT
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
pip install -r requirements.txt
```

## Run Experiments

We need to first generate the expert demo data using `collect_expert_traj.py`.

We can then run the TemporalOT agent using `python main.py`.