# Reinforcement learning

# 1. Concepts du RL
Concepts fondamentaux en RL : l'environnement, l'état, l'agent, l'action et la récompense (reward). Le cadre du RL est séquentiel. L'agent est le modèle. Il va apprendre à effectuer des actions optimales, face à chaque état donné de l'environnement. Pour cela, à chaque action qu'effectue l'agent, l'environnement lui renvoie une récompense négative ou positive. Si la récompense est positve, l'agent apprend à choisir cette action. Si la récompense est négative, il apprend à ne pas la reproduire. <br>
## Exemple
L'environnement est un labyrinthe avec des pièges. L'agent doit apprendre à choisir la bonne direction pour atteindre l'arrivée, sans tomber dans les pièges.



| ![content_mouse] |   |   |  ![content_cheese] |   |  ![content_cheese]  |
|---|---|---|---|---|---|
|   |   |  ![content_poison] |   |   |    |
|   |   |   |   |  ![content_poison] |  ![content_cheese_double]  |
|   |   |   |   | ![content_poison]  |  ![content_poison]  |
|   |  ![content_cheese] |   |   |   |
|   |   |   |   |![content_goal] ![content_cheese_double] |








On part d'une étape initiale.



L'environnement est dans un état initial. L'agent va effectuer une action


L'agent effectue des actions, qu'il envoie à l'environnement. L'environnement renvoie alors comme output un état et une récompense.

# 2. Concepts du module Gym
- L'instance fondamentale est __env__. C'est une instance d'environnement.
- Ses méthodes principales sont :
  - __.reset
- Il n'y a pas d'instance d'agent.




### Sources :
- https://github.com/openai/gym
- OpenAI Gym, Greg Brockman and Vicki Cheung and Ludwig Pettersson and Jonas Schneider and John Schulman and Jie Tang and Wojciech Zaremba
- <div>Icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>


[content_mouse]: contents/mouse.png
[content_cheese]: contents/cheese.png
[content_cheese_double]: contents/cheese_double.png
[content_goal]: contents/goal.png
[content_poison]: contents/poison.png
