# robotic
final project of robotic course
# Installation
`pip install -r requirements.txt`
# Training from scratch
Set `load_checkpoint` and `is_countinue_train` be False and run:
`python main.py`
# Using checkpoint
-Set the id of checkpoint by using `global_counter` in file `main.py`
## Training with checkpoint
-Set `load_checkpoint` and `is_countinue_train` be True and run:
`python main.py`
## Playing with checkpoint
-Set `load_checkpoint` be True and `is_countinue_train` be False and run:
`python main.py`
