# Learning_to_diversify
This is the official code repository for ICCV2021 'Learning to Diversify for Single Domain Generalization'. 

Paper Link: http://arxiv.org/abs/2108.11726


## Quick start: (Generalizing from art, cartoon, sketch to photo domain with ResNet-18)
1. Install the required packages.
2. Download PACS dataset.
3. Execute the following code.
```
bash run_main_PACS.sh
```

## Change dataset
In line 266-300 of train.py, we provide 3 different datasets settings (PACS, VLCS, OFFICE-HOME).
You can simply uncomment it to start your own experiment. It may require hyper-parameter fine tuning for some of the tasks.


