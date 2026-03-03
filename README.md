### This is a repository for PROL : Rehearsal Free Continual Learning in Streaming Data via Prompt Online Learning (ICCV 2025) 
## Paper link:  https://openaccess.thecvf.com/content/ICCV2025/papers/Masum_PROL__Rehearsal_Free_Continual_Learning_in_Streaming_Data_via_ICCV_2025_paper.pdf
## Arxiv paper : https://arxiv.org/abs/2507.12305

## Example of running script

## CIFAR100 dataset
python main_prol.py cifar100_prol --batch-size 10 --num_tasks 10 --data-path ./local_datasets/ --seed 1993 --lr 0.05 --epochs 1 --length 5

python main_prol.py cifar100_prol --batch-size 10 --num_tasks 10 --data-path ./local_datasets/ --seed 1993 --lr 0.01 --epochs 1 --length 5

## ImageNet-R dataset
python main_prol.py imr_prol --batch-size 10 --num_tasks 10 --data-path ./local_datasets/ --seed 1993 --lr 0.05 --epochs 1 --length 5

python main_prol.py imr_prol --batch-size 10 --num_tasks 10 --data-path ./local_datasets/ --seed 1993 --lr 0.01 --epochs 1 --length 5

## ImageNet-A dataset
python main_prol.py ima_prol --batch-size 10 --num_tasks 10 --data-path ./local_datasets/ --seed 1993 --lr 0.05 --epochs 1 --length 5

python main_prol.py ima_prol --batch-size 10 --num_tasks 10 --data-path ./local_datasets/ --seed 1993 --lr 0.01 --epochs 1 --length 5

## CUB dataset
python main_prol.py cub_prol --batch-size 10 --num_tasks 10 --data-path ./local_datasets/ --seed 1993 --lr 0.05 --epochs 1 --length 5

python main_prol.py cub_prol --batch-size 10 --num_tasks 10 --data-path ./local_datasets/ --seed 1993 --lr 0.01 --epochs 1 --length 5
