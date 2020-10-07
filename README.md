# ENMODEL

## Installation

```bash
pip install -r requirements.txt
```
Move transformer_file to transformers


## Train

```bash
python train.py --dataset_path DATAPATH/Name
python train_key.py --dataset_path DATAPATH/Name --keyword_module new
```

## Test

```bash
python interact.py --dataset_path DATAPATH/Name --model_checkpoint MODELPATH/
python interact_key.py --dataset_path DATAPATH/Name --model_checkpoint MODELPATH/
```

## Data format

Source|Target

Below files is in same directory
DataName_train.txt  / DataName_train_keyword.txt  
DataName_valid.txt  / DataName_valid_keyword.txt  
DataName_test.txt   / DataName_test_keyword.txt  
