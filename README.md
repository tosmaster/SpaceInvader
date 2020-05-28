# SpaceInvader

This project is based on https://github.com/dgriff777/a3c_continuous

## How to train SpaceInvader
python main.py --env SpaceInvaders-v0 --gpu-id 0 --workers 15

## How to evaluate
python gym_eval.py --env SpaceInvaders-v0 --gpu-id 0 --new-gym-eval tos --num-episodes 100

# Best score
reward mean 107965.4000
2020-04-30 22:26:34,516 : Time 01h 09m 22s, episode reward 3200.0, episode length 3151, reward mean 36376.0500
2020-05-19 23:24:10,313 : Time 03h 11m 27s, episode reward 153790.0, episode length 92445, reward mean 107965.4000
