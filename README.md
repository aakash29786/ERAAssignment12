#CIFAR10 Dataset training using ResNet18 (Lightning module)# 

This notebook contains the ResNet18 model training using Pytorch Lightning module

Please find the training statistics below:

INFO:pytorch_lightning.callbacks.model_summary:
  | Name  | Type   | Params
---------------------------------
0 | model | ResNet | 11.2 M
---------------------------------
11.2 M    Trainable params
0         Non-trainable params
11.2 M    Total params
44.696    Total estimated model params size (MB)
Epoch 9: 100%
197/197 [00:36<00:00, 5.38it/s, loss=0.289, v_num=0, val_loss=0.350, val_acc=0.879]
INFO:pytorch_lightning.utilities.rank_zero:`Trainer.fit` stopped: `max_epochs=10` reached.
Files already downloaded and verified
Files already downloaded and verified
INFO:pytorch_lightning.accelerators.cuda:LOCAL_RANK: 0 - CUDA_VISIBLE_DEVICES: [0]
Testing DataLoader 0: 100%
40/40 [00:02<00:00, 13.69it/s]
────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
       Test metric             DataLoader 0
────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
        test_acc            0.8733999729156494
        test_loss           0.3723158836364746
────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
[{'test_loss': 0.3723158836364746, 'test_acc': 0.8733999729156494}]
