# RelaHash

### Official PyTorch implementation of the paper: "RelaHash: Deep Hashing with Relative Position"

## How to run

### Training

```bash
python main.py --ds cifar10 --nbit 64 --device cuda:0 
```

You can run `python main.py --help` to see the full list of arguments.

### Dataset

We closely follow the dataset format of [HashNet](https://github.com/thuml/HashNet). You can follow the instructions as in [this link](https://github.com/swuxyj/DeepHash-pytorch) to download the datasets.
