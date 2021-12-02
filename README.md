## Using Deep Deterministic Policy Gradient to play TORCS for overtaking maneuvers

![](fast.gif)

# Installation Dependencies:

* Python 2.7
* Keras 1.1.0
* Tensorflow r0.10
* [gym_torcs](https://github.com/ugo-nama-kun/gym_torcs)

# How to Run?

```
git clone https://github.com/WetRavioli22/rl_project.git
cd rl_project
cp *.* ~/gym_torcs
cd ~/gym_torcs
python ddpg.py 
```

(Change the flag **train_indicator**=1 in ddpg.py if you want to train the network)
