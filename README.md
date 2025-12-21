## Graded Submission: RL Project
* This project submission consists of five elements. To reproduce the results simply run the code in the Jupyter notebook referenced below.

### Project Report
* BathProjectRL2025.pdf - The project write up covering the background, method and results

### Video Presentation
* This a link that has been uploaded via Echo 360

### Agent Video
* RLProject2.mov - A two-minute video of our agent's learning

### Source code and ancillary files
* README.md - This file.
* RLProject2025.ipynb - A Jupyter notebook with the source code. Uncomment the pip install commands in the first code block to install the necessary libraries. 
* batch8_pong_dqn (n steps).keras - model checkpoints that save the state of the model after n steps
* batch8_pong_episode_end_steps.npy - stored np.array for the x-axis of the learning visualisation for the model after n steps
* batch8_pong_episode_rewards.npy - stored np.array for the y-axis of the learning visualisation for the model after n steps

### Group Contribution Form.
* Group Contribution Form Template RL.pdf - completed contribution form

## We used the following libraries in this project
* OpenAI Gym/Farama Gymnasium (https://pypi.org/project/ale-py/) - for the Atari game environment, pre-processing wrappers and rendering
* TensorFlow/Keras (https://www.tensorflow.org/guide/keras) - for the DQN network, optimiser and training steps
