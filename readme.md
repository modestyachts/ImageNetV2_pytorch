# Pytorch Dataloader for ImageNet V2

First Install

```
pip install git+https://github.com/modestyachts/ImageNetV2_pytorch
```

Usage:

```
    from ImageNetV2_dataset import ImageNetV2Dataset
    from torch.utils.data import DataLoader

    dataset = ImageNetV2Dataset("matched-frequency") # supports matched-frequency, threshold-0.7, top-images variants
    dataloader = torch.DataLoader(dataset, batch_size=32) # use whatever batch size you wish
    # feed into pytorch code
```
