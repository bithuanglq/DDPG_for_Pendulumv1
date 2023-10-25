This repository has been modified based on [RLcode](https://github.com/louisnino/RLcode), where we upgraded Pendulum from v0 to v1. It's also ensured that it now runs smoothly with no bugs, allowing for quick execution.


# My Setup
Ubuntu 20.04 LTS, tensorflow 2.14.0, python 3.10

# Step 1
Clone this repo, create environments:
```
git clone _this_repo_
conda create -n tf_RLcode python=3.10
pip install -r requirements.txt
```
Then replace tensorlayer package file 

*/path/to/your/anaconda3/envs/tf_RLcode/lib/python3.10/site-packages/tensorlayer/files/utils.py* 

with *replace_tensorlayer_utils.py*


# Step 2
Run in your terminal:
```
python tutorial_DDPG.py --train_or_test 1
```

Or Test with visualized result:
```
Python tutorial_DDPG.py --train_or_test 0
```

# Visualized Result
One temp image in test phase:
</div align="cente">
  <img src="temp_result.png" width="50%" alt="One screenshot in the test phase">
</div>


