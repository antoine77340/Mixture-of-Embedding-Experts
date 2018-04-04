# Mixture-of-Embeddings-Experts

BlaBla

## Usage example

Creating a NetVLAD block:

```python
import loupe as lp

'''
coments
'''
code blabla

```

## Reproducing results on MPII dataset and MSRCTT dataset

Downloading the data:

```bash
wget https://www.rocq.inria.fr/cluster-willow/amiech/ECCV18/data.zip
unzip data.zip
```


Training on MSR-VTT:

```bash
python train.py --epochs=100 --batch_size=64 --lr=0.0004  --coco_sampling_rate=0.5 --MSRVTT=True
```

Training on MPII:

```bash
python train.py --epochs=50 --batch_size=512 --lr=0.0001  --coco=True
```


## References

If you use this code, please cite the following paper:

[1] Antoine Miech and Ivan Laptev and Josef Sivic, Learning a Text-Video Embedding from Incomplete and Heterogeneous Data, arXiv::
```
@article{miech18learning,
  title={Learning a {T}ext-{V}ideo {E}mbedding from {I}ncomplete and {H}eterogeneous Data},
  author={Miech, Antoine and Laptev, Ivan and Sivic, Josef},
  journal={arXiv:},
  year={2018},
}
```



Antoine Miech
