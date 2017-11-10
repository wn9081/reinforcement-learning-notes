A constantly evolving list of notes and summaries of the Reinforcement Learning papers.

[atari]: ./icons/atari.png "Atari 2600 games"
[doom]: ./icons/doom.png "Doom game"
[sc]: ./icons/sc.png "Starcraft game"
[go]: ./icons/go.png "Go game"
[table]: ./icons/table.png "Table games"
[nn]: ./icons/nn.png "Neural Networks & Optimizers"
[robot]: ./icons/robot.png "Real Robot Experiments"
[loco]: ./icons/loco.png "Locomotion tasks"
[maze]: ./icons/maze.png "Mazes & Labyrinths"

**Glossary:**

  - :rocket: - state-of-the-art method in current domain at the moment of paper publication.

  - :star: - valuable paper.
  
  
**Domain Tags**:
  
  - ![atari] - Atari game (Atari).
  
  - ![doom] - Doom game (Doom).
  
  - ![sc] - Starcraft game (SC).
  
  - ![nn] - Neural Networks & Optimizers (NN).
  
  - ![robot] - Real Robot Experiments (Robot).
  
  - ![go] - Go game.
  
  - ![table] - Table games.
  
  - ![loco] - Simulated robotic locomotion: MuJoCo, Roboschool etc (Locomotion).
  
  - ![maze] - Mazes and Labyrinths (Maze).
  
  - **Multi** - Multi-agent learning.
  
  - **Continious** - Methods that can be applied to continious action space problems.
  
  - **Planning** - Complex planning problems.
  
  - **Transfer** - Transfer Learning.
  
  - **RTS** - Real-Time Strategy video game.
  
  - **FPS** - First-Person Shooter video game.


# Deep Reinforcement Learning
## Year 2017
:star: **Mastering the Game of Go without Human Knowledge** (AlphaGo Zero)
  - [[pdf](https://deepmind.com/documents/119/agz_unformatted_nature.pdf)], [[official blog post](https://deepmind.com/blog/alphago-zero-learning-scratch/)]
  - Silver et al.; Google Deepmind
  - ![go] ![table] Go, Table

:star: **Learning Transferable Architectures for Scalable Image Recognition**
  - [[arXiv](https://arxiv.org/abs/1707.07012)], [[pdf](https://arxiv.org/pdf/1707.07012.pdf)]
  - Zoph et al.; Google Brain
  - ![nn] NN

**Neural Optimizer Search with Reinforcement Learning**
  - [[pdf](http://proceedings.mlr.press/v70/bello17a/bello17a.pdf)]
  - Bello et al.; Google Brain
  - ![nn] NN

**Neural Architecture Search with Reinforcement Learning**
  - [[arXiv](https://arxiv.org/abs/1611.01578)], [[pdf](https://arxiv.org/pdf/1611.01578.pdf)]
  - B. Zoph and Quoc V. Le; Google Brain; ICLR.
  - ![nn] NN

:star: **Meta Learning Shared Hierarchies**
  - [[arXiv](https://arxiv.org/abs/1710.09767)], [[pdf](https://arxiv.org/pdf/1710.09767.pdf)], [[official blog post](https://blog.openai.com/learning-a-hierarchy/)]
  - Frans et al.; OpenAI, UC Berkeley
  - ![loco] Locomotion, Continous

**Asymmetric Actor Critic for Image-Based Robot Learning**
  - [[arXiv](https://arxiv.org/abs/1710.06542)], [[pdf](https://arxiv.org/pdf/1710.06542.pdf)], [[official blog post](https://blog.openai.com/generalizing-from-simulation/)]
  - Pinto et al.; OpenAI, CMU
  - ![robot] Robot, Continous

**Sim-to-Real Transfer of Robotic Control with Dynamics Randomization**
  - [[arXiv](https://arxiv.org/abs/1710.06537)], [[pdf](https://arxiv.org/pdf/1710.06537.pdf)], [[official blog post](https://blog.openai.com/generalizing-from-simulation/)]
  - Peng et al.; OpenAI, UC Berkeley
  - ![robot] Robot, Continous

:star: **Learning with Opponent-Learning Awareness** (LOLA)
  - [[arXiv](https://arxiv.org/abs/1709.04326)], [[pdf](https://arxiv.org/pdf/1709.04326.pdf)], [[official blog post](https://blog.openai.com/learning-to-model-other-minds/)]
  - Foerster et al.; OpenAI, University of Oxford, UC Berkeley, Carnegie Mellon University
  - Multi

**One-Shot Visual Imitation Learning via Meta-Learning**
  - [[arXiv](https://arxiv.org/abs/1709.04905)], [[pdf](https://arxiv.org/pdf/1709.04905.pdf)]
  - Finn et al.; UC Berkeley, OpenAI
  - ![robot] Robot, Continious

**A Deep Reinforcement Learning Chatbot**
  - [[arXiv](https://arxiv.org/abs/1709.02349)], [[pdf](https://arxiv.org/pdf/1709.02349.pdf)]
  - Serban et al.; MILA

:rocket: **Scalable trust-region method for deep reinforcement learning using Kronecker-factored approximation** (ACKTR, A2C)
  - [[arXiv](https://arxiv.org/abs/1708.05144)], [[pdf](https://arxiv.org/pdf/1708.05144.pdf)]
  - Wu et al.; University of Toronto, New York University
  - ![atari] ![loco] Atari, Locomotion, Continious

**Parameter Space Noise for Exploration**
  - [[arXiv](https://arxiv.org/abs/1706.01905)], [[pdf](https://arxiv.org/pdf/1706.01905)]
  - Plappert et al.; OpenAI, Karlsruhe Institute of Technology
  - ![atari] ![loco] Atari, Locomotion, Continious
  
:rocket: **Proximal Policy Optimization Algorithms** (PPO)
  - [[arXiv](https://arxiv.org/abs/1707.06347)], [[pdf](https://arxiv.org/pdf/1707.06347.pdf)], [[official blog post](https://blog.openai.com/openai-baselines-ppo/)]
  - Schulman et al.; OpenAI
  - ![atari] ![loco] Atari, Locomotion, Continious

**Learning model-based planning from scratch**
  - [[arXiv](https://arxiv.org/abs/1707.06170)], [[pdf](https://arxiv.org/pdf/1707.06170.pdf)], [[official blog post](https://deepmind.com/blog/agents-imagine-and-plan/)]
  - Pascanu et al.; Google DeepMind
  - ![loco] Locomotion, Continious
  
:star: **Imagination-Augmented Agents for Deep Reinforcement Learning** (I2As)
  - [[arXiv](https://arxiv.org/abs/1707.06203)], [[pdf](https://arxiv.org/pdf/1707.06203.pdf)], [[official blog post](https://deepmind.com/blog/agents-imagine-and-plan/)]
  - Weber et al.; Google DeepMind
  - ![atari] Planning, Atari, Transfer
  
**Distral: Robust Multitask Reinforcement Learning**
  - [[arXiv](https://arxiv.org/abs/1707.04175)], [[pdf](https://arxiv.org/pdf/1707.04175.pdf)]
  - Teh et al.; Google DeepMind
  - ![maze] Maze, Transfer

**Emergence of Locomotion Behaviours in Rich Environments**
  - [[arXiv](https://arxiv.org/abs/1707.02286)], [[pdf](https://arxiv.org/pdf/1707.02286.pdf)], [[official blog post](https://deepmind.com/blog/producing-flexible-behaviours-simulated-environments/)]
  - Heess et al.; Google DeepMind
  - ![loco] Locomotion, Continious

[RTS:SC] **Multiagent Bidirectionally-Coordinated Nets for Learning to Play StarCraft Combat Games**
  - [[arXiv](https://arxiv.org/abs/1609.02993)], [[pdf](https://arxiv.org/pdf/1703.10069.pdf)]
  - Peng et al.; Alibaba Group, University College London
  - ![sc] Starcraft, Multi

**Programmable Agents**
  - [[arXiv](https://arxiv.org/abs/1706.06383v1)], [[pdf](https://arxiv.org/pdf/1706.06383v1.pdf)]
  - Denil et al.; Google DeepMind
  - ![loco] Locomotion, Continious

:star: **Hybrid Reward Architecture for Reinforcement Learning** (HRA)
  - [[arXiv](https://arxiv.org/abs/1706.04208v1)], [[pdf](https://arxiv.org/pdf/1706.04208v1.pdf)]
  - van Seijen et al.; Microsoft Maluuba, McGill University
  - ![atari] Atari

:star: **Evolution Strategies as a Scalable Alternative to Reinforcement Learning**
  - [[arXiv](https://arxiv.org/abs/1703.03864v1)], [[pdf](https://arxiv.org/pdf/1703.03864v1.pdf)]
  - Salimans et al.; OpenAI
  - ![atari] Atari

**Neural Episodic Control**
  - [[arXiv](https://arxiv.org/abs/1703.01988v1)], [[pdf](https://arxiv.org/pdf/1703.01988v1.pdf)]
  - Pritzel et al.; Google DeepMind
  - **Brief Summary.** NEC agent is extremely data efficient. It's performance at 5 millions of frames can be reached by DQN with Prior. Replay only after 40 millions of frames. However, the final perfomance is still worse than the other state-of-the-art agents can obtain.
  - ![atari] Atari

## Year 2016
[RTS:SC] **Episodic Exploration for Deep Deterministic Policies: An Application to StarCraft Micromanagement Tasks**
  - [[arXiv](https://arxiv.org/abs/1609.02993)], [[pdf](https://arxiv.org/pdf/1609.02993.pdf)]
  - Usunier et al.; Facebook AI Research
  - ![sc] Starcraft

**Reinforcement Learning with unsupervised auxiliary tasks** (UNREAL)
  - [[arXiv](https://arxiv.org/abs/1611.05397)], [[pdf](https://arxiv.org/pdf/1611.05397.pdf)]
  - Jaderberg et al.; Google DeepMind
  - :pencil: [**Notes**](./notes/unreal-agent.md)
  - ![atari] ![maze] ![loco] Atari, Maze, Locomotion, Continious
  
:rocket: **Asynchronous Methods for Deep Reinforcement Learning** (A3C)
  - [[arXiv](https://arxiv.org/abs/1602.01783v2)], [[pdf](https://arxiv.org/pdf/1602.01783v2.pdf)]
  - Mnih et al.; Google DeepMind
  - :pencil: [**Notes**](./notes/a3c-agent.md)
  - ![atari] ![maze] ![loco] Atari, Maze, Locomotion, Continious
  
:rocket: **VizDoom 2016 (Full DM) Winner: Learning to act by predicting the future**
  - [[arXiv](https://arxiv.org/abs/1611.01779)], [[pdf](https://arxiv.org/pdf/1611.01779.pdf)]
  - Dosovitskiy, Koltun; Intel Labs
  - ![doom] ![maze] Doom, Maze, FPS
  
**VizDoom 2016 (Limited DM) 2nd place: Playing FPS Games with Deep Reinforcement Learning**
  - [[arXiv](https://arxiv.org/abs/1609.05521)], [[pdf](https://arxiv.org/pdf/1609.05521.pdf)]
  - Lample, Chaplot; Carnegie Mellon University
  - ![doom] ![maze] Doom, Maze, FPS

**The Predictron: End-To-End Learning and Planning**
  - [[arXiv](https://arxiv.org/abs/1612.08810v2)], [[pdf](https://arxiv.org/pdf/1612.08810v2.pdf)]
  - Silver et al.; Google DeepMind
  - ![maze] Maze, Planning

## Year 2015
:star: **Trust Region Policy Optimization** (TRPO)
  - [[arXiv](https://arxiv.org/abs/1502.05477)], [[pdf](https://arxiv.org/pdf/1502.05477.pdf)]
  - Schulman et al.; UC Berkeley
  - ![atari] ![maze] ![loco] Atari, Maze, Locomotion, Continious

:star: **Dueling Network Architectures for Deep Reinforcement Learning** (Dueling DQN)
  - [[arXiv](https://arxiv.org/abs/1511.06581)], [[pdf](https://arxiv.org/pdf/1511.06581.pdf)]
  - Wang et al.; Google DeepMind
  - ![atari] Atari

:star: **Deep Reinforcement Learning with Double Q-learning** (Double DQN)
  - [[arXiv](https://arxiv.org/abs/1509.06461)], [[pdf](https://arxiv.org/pdf/1509.06461.pdf)]
  - Hasselt et al.; Google DeepMind
  - ![atari] Atari

**Prioritized Experience Replay**
  - [[arXiv](https://arxiv.org/abs/1511.05952v4)], [[pdf](https://arxiv.org/pdf/1511.05952v4.pdf)]
  - Schaul et al.; Google DeepMind
  - :pencil: [**Notes**](./notes/prioritized-exp-replay.md)
  - ![atari] Atari
  
:rocket: **Human-level control through deep reinforcement learning** (DQN)
  - [[Nature](http://www.nature.com/nature/journal/v518/n7540/full/nature14236.html)], [[reddit](https://www.reddit.com/r/MachineLearning/comments/2x4yy1/google_deepmind_nature_paper_humanlevel_control/)]
  - Mnih et al.; Google Deepmind
  - :pencil: [**Notes**](./notes/dqn-agent.md)
  - ![atari] Atari
 
**Mastering the game of Go with deep neural networks and tree search** (AlphaGo Master)
  - [[Nature](https://www.nature.com/nature/journal/v529/n7587/full/nature16961.html)], [[reddit](https://www.reddit.com/r/MachineLearning/comments/42ytdx/pdf_mastering_the_game_of_go_with_deep_neural/)]
  - Silver et al.; Google Deepmind, Google
  - ![go] ![table] Go, Table

## Year 2013
:rocket: **Playing Atari with Deep Reinforcement Learning** (DQN)
  - [[arXiv](https://arxiv.org/abs/1312.5602)], [[pdf](https://arxiv.org/pdf/1312.5602.pdf)]
  - Mnih et al.; DeepMind Technologies
  - ![atari] Atari

**Evolving Large-Scale Neural Networks for Vision-Based Reinforcement Learning**
  - [[pdf](http://people.idsia.ch/~juergen/gecco2013torcs.pdf)]
  - Koutnik et al.; IDSIA, USI-SUPSI

## 2012 and earlier
**Horde: A Scalable Real-time Architecture for Learning Knowledge from Unsupervised Sensorimotor Interaction**
  - [[pdf](https://www.cs.swarthmore.edu/~meeden/DevelopmentalRobotics/horde1.pdf)]
  - Sutton et al. (2011);  University of Alberta, McGill University
  - ![robot] ![loco] Robot, Locomotion
  
:star: **Temporal Difference Learning and TD-Gammon**
  - [[pdf](http://cling.csd.uwo.ca/cs346a/extra/tdgammon.pdf)]
  - Gerald Tesauro (1995)
  - ![table] Table
  
:star: **Simple Statistical Gradient-Following Algorithms for Connectionist Reinforcement Learning** (REINFORCE)
  - [[pdf](http://www-anw.cs.umass.edu/~barto/courses/cs687/williams92simple.pdf)]
  - Ronald J. Williams (1992); Northeastern University

## Books
:star: **Reinforcement Learning: An Introduction** (Complete Draft)
  - [[pdf](http://incompleteideas.net/sutton/book/bookdraft2017nov5.pdf)]
  - Richard S. Sutton and Andrew G. Barto (2017)
  
## Miscellaneous
**How to Read a Paper**
  - [[pdf](http://ccr.sigcomm.org/online/files/p83-keshavA.pdf)]
  - S. Keshav (2007); University of Waterloo
