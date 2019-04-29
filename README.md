# Cassie_Robot_Resources
list of papers, videos and codes about the bipedal robot Cassie developed by Agility Robotics

## Labs working on Cassie
- Dynamic Robotics Laboratory at Oregon State University: https://mime.oregonstate.edu/research/drl/
- Dynamic Legged Locomotion Lab at University of Michigan: https://www.biped.solutions/.
- ROAHM Lab at University of Michigan: http://www.roahmlab.com/.
- AMBER Lab at Caltech: http://www.bipedalrobotics.com/.
- Agile Robotics Laboratory at Harvard: https://agile.seas.harvard.edu/.
- Dynamic Autonomy and Intelligent Robotics (DAIR) Lab at University of Pennsylvania: https://dair.seas.upenn.edu/.
- The Laboratory for Intelligent Decision and Autonomous Robots (LIDAR) at Georgia Tech: https://sites.google.com/site/yezhaout/home.
- Optimal Robotics Lab at Florida State University: http://www.christianhubicki.com/.
- MOCCA Lab at University of British Columbia: https://www.cs.ubc.ca/~van/papers/index.html.

## Cassie Simulators
- Mujoco: https://github.com/osudrl/cassie-mujoco-sim.
- Gazebo: https://github.com/agilityrobotics/cassie-gazebo-sim.
- Simulink: https://github.com/UMich-BipedLab/Cassie_FlatGround_Controller.
- Drake: https://github.com/kuindersma/cassie-model.
- Bullet: https://github.com/bulletphysics/pybullet_robots.

## State Estimation
- P. Varin and S. Kuindersma, “A Constrained Kalman Filter for Rigid Body Systems with Frictional Contact,” in International Workshop on the Algorithmic Foundations of Robotics (WAFR), 2018. 
  - paper: https://agile.seas.harvard.edu/files/agile/files/contact-filter.pdf.
- Ross Hartley, Maani Ghaffari Jadidi, Lu Gan, Jiunn-Kai Huang, Jessy W Grizzle, and Ryan M Eustice, Hybrid Contact Preintegration for Visual-Inertial-Contact State Estimation within Factor Graphs, IROS 2018. 
  - paper: https://arxiv.org/abs/1803.07531.
- Ross Hartley, Maani Ghaffari Jadidi, Jessy W. Grizzle, and Ryan M. Eustice, Contact-Aided Invariant Extended Kalman Filtering for Legged Robot State Estimation , RSS 2018. 
  - paper: https://arxiv.org/abs/1805.10410, extended journal version: https://arxiv.org/abs/1904.09251
  - code: https://github.com/UMich-BipedLab/Cassie_StateEstimation.
  - video: https://youtu.be/pNyXsZ5zVZk.
- Ross Hartley, Josh Mangelson, Lu Gan, Maani Ghaffari Jadidi, Jeffrey M. Walls, Ryan M. Eustice, and Jessy W. Grizzle, Legged Robot State-Estimation Through Combined Forward Kinematic and Preintegrated Contact Factors, ICRA 2018.
  - paper: https://arxiv.org/abs/1712.05873.
  - video: https://youtu.be/QnFoMR47OBI
  
## Control
### Reinforcement Learning
- Zhaoming Xie, Patrick Clary, Jeremy Dao, Pedro Morais, Jonathan Hurst, Michiel van de Panne, Iterative Reinforcement Learning Based Design of Dynamic Locomotion Skills for Cassie.
  - paper: https://arxiv.org/abs/1903.09537.
  - video: https://youtu.be/TgFrcrARao0.
- Zhaoming Xie, Glen Berseth, Patrick Clary, Jonathan Hurst, Michiel van de Panne, Feedback Control For Cassie With Deep Reinforcement Learning, IROS 2018.
  - paper: https://www.cs.ubc.ca/~van/papers/2018-IROS-cassie/2018-IROS-cassie.pdf.
  - video: https://youtu.be/z3DMKQwt68Y. 
  - code: https://github.com/p-morais/gym-cassie.
### Using Full Order Model
- Jacob Reher, Wen-Loong Ma, Aaron D. Ames, Dynamic Walking with Compliance on a Cassie Bipedal Robot.
  - paper: https://arxiv.org/abs/1904.11104.
  - video: https://youtu.be/NYooAyAC0kA.
- Yukai Gong, Ross Hartley, Xingye Da, Ayonga Hereid, Omar Harib, Jiunn-Kai Huang, and Jessy Grizzle, Feedback Control of a Cassie Bipedal Robot: Walking, Standing, and Riding a Segway American Control Conference, June 2019.
  - paper: http://web.eecs.umich.edu/faculty/grizzle/papers/Feedback_Control_of_a_Cassie_Bipedal_Robot__Standing_and_Walking_Final.pdf.
  - video: https://www.youtube.com/playlist?list=PLFe0SMV3hBCBPg0dDG9FbqOy_x7H9kEDJ.
  - code: https://github.com/UMich-BipedLab/Cassie_FlatGround_Controller.
- Ayonga Hereid*, Omar Harib*, Ross Hartley, Yukai Gong, and Jessy W Grizzle, Rapid Bipedal Gait Design Using C-FROST with Illustration on a Cassie-series Robot.
  - paper: https://arxiv.org/abs/1807.06614.
  - video: https://youtu.be/pweV7NLr6JY.
  - code: https://github.com/UMich-BipedLab/C-Frost.
### Using Reduced Order Model
- Xiong, X.; and Ames, A. D., Coupling Reduced Order Models Via Feedback Control for 3D Underactuated Bipedal Robotic Walking. IEEE-RAS 18th International Conference on Humanoid Robots (Humanoids). 2018. 
  - paper: http://ames.caltech.edu/xiong2018coupling.pdf.
  - video: https://youtu.be/c7sKjTNS2zg.
- Xiong, X.; and Ames, A. D., Bipedal Hopping: Reduced-order Model Embedding via Optimization-based Control. Intelligent Robots and Systems (IROS), IEEE/RSJ International Conference on. 2018. 
  - paper: http://ames.caltech.edu/xiong2018bipedal.pdf.
  - video: https://youtu.be/5s19IWqN4-c.
- Taylor Apgar, Patrick Clary, Kevin Green, Alan Fern, and Jonathan Hurst, Fast Online Trajectory Optimization for the Bipedal Robot Cassie, Robotics Science and Systems (RSS), June 2018.
  - paper: https://mime.oregonstate.edu/research/drl/publications/_documents/apgar_2018.pdf.
  - video: https://youtu.be/av8xjJYQsvE.
