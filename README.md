# secrete_of_epsilons
Secrete of epsilons

<p align="center" width="100%">
    <img width="25%" src="https://github.com/jkaewprateep/secrete_of_epsilons/blob/main/Python.jpg">
    <img width="24%" src="https://github.com/jkaewprateep/secrete_of_epsilons/blob/main/pygame.jpg">
    <img width="18%" src="https://github.com/jkaewprateep/secrete_of_epsilons/blob/main/image10.jpg">
    <img width="12%" src="https://github.com/jkaewprateep/secrete_of_epsilons/blob/main/image6.jpg"> </br>
    <b> Pygame and Tensorflow AI machine learning </b> </br>
    <b> ( Picture from Internet ) </b> </br>
</p>
[Flappybird games]( https://pygame-learning-environment.readthedocs.io/en/latest/user/games/flappybird.html#rewards )

🧸💬 A secret of machine learning model training is the epsilon function, which is used to determine how much information should training machine learning and how much machine learning should provide when it is still in the learning process. Most people skip this process when it is a shortcut to reduce the amount of information to be trained on a machine learning model. </br>
```
def action_epsilon(step, rewards):
    epsilon = (step / 10000) + rewards / (step + 1)

    return epsilon > 0.00012
```
