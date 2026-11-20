# Sheep herding behaviour
### Collective Behaviour, Group A, 2026/2027 Winter Semester

* * *

## Team

| Name               | GitHub account                                           |
|--------------------|----------------------------------------------------------|
| *Daurian Garnier* | [@Daurian-Garnier](https://github.com/daurian-garnier) |
| *Kenny Weidemann*  | [@jawe456d](https://github.com/jawe456d)                         |

* * * 

## Project Description

This project aims to simulate the collective behavior of sheep (*Ovis aries*) as they dynamically balance two primary behavioral instincts: grazing and escaping threats. When undisturbed, the herd disperses into smaller subgroups to maximize the available grazing area per individual. However, when a threat—such as a predator or a herding dog—approaches, an individual's startle response triggers a rapid "fast packing event" ([Ginelli et al., 2015](https://www.pnas.org/doi/10.1073/pnas.1503749112)), causing the sheep to tightly aggregate to reduce individual predation risk and flee together as a cohesive unit. During this evasion phase, the flock follows an oscillating, zig-zag trajectory while the herding dog continuously adapts its movement to steer and contain the group, as described in recent empirical modeling of sheep–border collie interactions ([*Communications Biology*, 2024](https://www.nature.com/articles/s42003-024-07245-8)). Once the perceived threat recedes and the herd settles down, this defensive flocking subsides and individuals gradually transition back to dispersed grazing. Grounded in these two foundational studies, our agent-based simulation is implemented in **Java**, leveraging its object-oriented architecture to encapsulate distinct behavioral states (grazing, startle/packing, and fleeing), local neighbor interactions, and adaptive predator–prey dynamics.

* * *

## Starting Papers

The order reflects the importance of each paper to our project:

1. **Jadhav, Vivek, et al.** "[Collective Responses of Flocking Sheep to a Herding Dog](https://doi.org/10.1038/s42003-024-07232-9)." *Communications Biology*, vol. 7, no. 1, 2024, p. 1543.\
Uses Ultra-Wideband tracking to analyze how a flock of sheep coordinates its escape when driven by a herding dog. The study demonstrates that directional information propagates counter-intuitively from the front of the flock to the rear, with the dog continuously adapting its trajectory to the flock's movement. Finally, a discrete-time shepherding model confirms that simple local attraction, alignment, and repulsion rules replicate these hierarchical escape dynamics.

2. **Gómez-Nava, Luis, Richard Bon, and Fernando Peruani.** "[Intermittent Collective Motion in Sheep Results from Alternating the Role of Leader and Follower](https://doi.org/10.1038/s41567-022-01769-8)." *Nature Physics*, vol. 18, no. 12, 2022, pp. 1494–1501.\
Investigates spontaneous movement in small sheep flocks, revealing an alternation between stationary grazing phases and cohesive, single-file collective motion episodes. During each motion phase, information flows strictly from a temporary leader at the front down a directed, hierarchical network. Because individuals randomly rotate leadership roles across episodes, the flock achieves democratic information pooling while retaining hierarchical control.

3. **Ginelli, Francesco, et al.** "[Intermittent Collective Dynamics Emerge from Conflicting Imperatives in Sheep Herds](https://doi.org/10.1073/pnas.1503749112)." *Proceedings of the National Academy of Sciences*, vol. 112, no. 41, 2015, pp. 12729–12734.\
Quantifies how large herds of grazing Merino sheep alternate between slow spatial dispersion and sudden, avalanche-like regrouping events. Using an agent-based model with strong allelomimetic (imitative) behavior, the authors show that these intermittent density oscillations emerge without external threats. This self-organized dynamic balances two competing biological needs: maximizing individual grazing space while maintaining rapid, cohesive protection against predators.

4. **King, Andrew J., et al.** "[Selfish-Herd Behaviour of Sheep under Threat](https://doi.org/10.1016/j.cub.2012.05.008)." *Current Biology*, vol. 22, no. 14, 2012, pp. R561–R562.\
Provides empirical GPS tracking evidence supporting Hamilton's selfish-herd theory by analyzing a flock of 46 sheep approached by a herding dog. When the dog comes within roughly 70 meters, individual sheep move rapidly toward the geometric center (centroid) of the flock to reduce their personal predation risk. A simple differential equation model confirms that sheep approximate the position of multiple neighbors to coalesce into a tight, protective cluster.

5. **Ortiz-Plata, Carmen, José De Lucas-Tron, and Genaro C. Miranda-de la Lama.** "[Breed Identity and Leadership in a Mixed Flock of Sheep](https://doi.org/10.1016/j.jveb.2011.07.002)." *Journal of Veterinary Behavior*, vol. 7, no. 2, 2012, pp. 94–98.\
Examines social segregation and movement leadership over 120 days in a mixed-breed flock of Suffolk and Columbia sheep. The observations reveal strong breed identity, with both breeds remaining spatially separated during daily grazing and resting routines. Furthermore, the less gregarious Suffolk sheep consistently acted as flock leaders when exiting pens and moving to pastures.

6. **Dwyer, Cathy M.** "[How Has the Risk of Predation Shaped the Behavioural Responses of Sheep to Fear and Distress?](https://doi.org/10.1017/S0962728600028384)" *Animal Welfare*, vol. 13, no. 3, 2004, pp. 269–281.\
Reviews how evolved anti-predator strategies—such as vigilance, tight flocking, flight to cover, and inhibited vocalization—govern the stress responses of domestic sheep. While domestication has raised the response threshold for these behaviors, they persist along a continuum influenced by breed, age, sex, and prior experience. Consequently, measuring flight distances and vigilance offers a reliable framework for assessing sheep fear and welfare.

7. **Sendra, Sandra, et al.** "[Smart Wireless Sensor Network to Detect and Protect Sheep and Goats to Wolf Attacks](https://doi.org/10.2174/22117407112016660012)." *Recent Advances in Communications and Networking Technology*, vol. 3, no. 1, 2014, pp. 18–28.\
   Proposes an IEEE 802.15.4/ZigBee wireless sensor network mounted on livestock collars to monitor sheep and goat heart rates and body temperatures overnight. When five or more animals exhibit simultaneous spikes in vital signs within five minutes, an intelligent tagging algorithm classifies the event as a collective stress episode. Upon detecting a likely wolf attack or theft, the system triggers audible and visual deterrents while alerting the farmer via SMS and phone call.

* * *

## Milestones

1. **First report - 13/11/26**
_Goal:_ Provide an overview of existing literature regarding the collective behaviors in sheep flocks
_State:_ You can check our report in [pdf](<./Collective_behaviour_Seminar_Paper_1.pdf>) or
[overleaf](https://www.overleaf.com/project/6ae9ad2bda054dfc3f24fa3d/share#f4f74537224b2ce89bc3a88d6da158175baf27b9137c41c3)

2. **Second report - 11/12/26**
_Goal:_ Model basic behavior (spreading out to graze when relaxed, basic startle response)

3. **Final report - 08/01/26**
_Goal:_ Model the more complex fleeing behaviors and the movement of the herding dog

5. **Final presentation - 08/01/26**

* * *







