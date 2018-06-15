# Transferable Trial-Minimizing Progressive Peg-in-hole Model

## grid sampling to collect inserting trials

1.run `python3 UR5_ReceiveData.py`

## train sequential relative pose estimator

2.run `python3 train.py --gpu True`

## meta training of the dynamics model

3.run `python3 meta_train.py --gpu True`
