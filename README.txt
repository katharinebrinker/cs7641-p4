Requirements:
- python > 3.5
- OpenAI Gym
- PythonMDPToolbox

I installed OpenAI Gym through PyCharm by adding it to the project interpreter; it can also be installed via pip (pip install gym). For installation via PyCharm, a current version of PyCharm is required to avoid errors.

The pymdptoolbox library was downloaded and modified, so it's necessary to use this local version, rather than installing it via pip.

Running the experiments:

Frozen Lake
- policy and value iteration:
-- I ran via PyCharm, by selecting the "run" option for mdp_frozen_lake.py
- Q-learning
-- Run via terminal: rl_frozen_lake.py
-- Run options can be found here: https://gym.openai.com/evaluations/eval_xSOlwrBsQDqUW7y6lJOevQ/

Forest Management:
- Run via terminal: py mdp_forest.py