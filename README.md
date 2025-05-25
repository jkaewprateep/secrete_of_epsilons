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
🐯💬 Culture-INFO, custom functions need to provide results in the same way they are mentioned, and provide the same results or patterns for the same input and output algorithms, and how you do it with the random functions, combined with  epsilon functions, and random functions, they are provided the same pattern with similar output for the same input. There are about 5 action patterns, and the snakes will explore under the effect of the epsilon function, but they will go to the  setup goal without the effects of the epsilon function.</br>
🦁💬 Random action is not a function, but machine learning and machines can run under randomized signals, with epsilon's function creates patterns for machine learning to learn, explore possibilities, and remember and repeat outside of the effects. It saved time for running machine learning for the exploration process. </br>

🦭💬 In precision calculation, it required a  small number of changes to create differences in each record, and the random function performed well because there are random scales that are too small to create effects after being estimated with sources. In example, we are calculating 4 digits or 6 digits precision for GPRS tracking system, but a small number of random living between 8 to 12 precision numbers will be neglected after the calculation step. </br>
🐐💬 Even in clear signals of communication they had capacitors and resistances they had their own signals pattern but two circuits can create harmonic signal without the effects of the different cuircuit pattern that is because of absorbtion and released effects harmonic will have a stronger result with both patterns than only one circuit that remove white noise or equipment resistance effects. </br>
```
def action_epsilon(step, rewards):
    epsilon = (step / 10000) + rewards / (step + 1)

    return epsilon > 0.00012
```

```
if not action_epsilon(step, reward) :
    action = random_action(_gamestate);
else: 
    DATA, LABEL = create_dataset( _gamestate, scores, action_tonumber(K_h) );
    action = predict_action(DATA);
```
