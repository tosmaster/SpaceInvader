# SpaceInvader

This project is based on https://github.com/dgriff777/a3c_continuous

## How to train SpaceInvader
python main.py --env SpaceInvaders-v0 --gpu-id 0 --workers 15

## How to evaluate
python gym_eval.py --env SpaceInvaders-v0 --gpu-id 0 --new-gym-eval tos --num-episodes 100
