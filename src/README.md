# Introduction

Book i wish i had when learning everything about how the engineering simulation software works under the hood as well as making my own simulators.

Book is heavy on the examples side and combining the material without necessarily going to full depth. FOr the theoretical side will provide links to books, and ChatGPT keyword and question prompts that will give a good start for digging deeper into the topic.


Foundation topics:
- Graphs / networks and their algorithms
- State machines
- Algorithms from numerical methods
- Actors
- time stepping simulation
    - numerical integration
- discrete simulation
    - event schedulers

Useful design patterns:
- Builder - for simulation assemblies
- Obverver - for pub / sub subscribing to events
to follow a specific model

Computation for the entire systems:
- blocking / waiting
- polling (repeatedly checking)
- callbacks & events

Physical model representations:
- meshes 
- grids
- assemblies / graphs

Individual model definitions:
- some models should be able to interact with the schedulers
to schedule an action for later

Model assemblies:
- How models communicate?
- How models get intputs and create outputs?

Representation of "physical" part of CPS
- physical system (mechanical, thermal, electrical)

Representation of "cyber" part of CPS
- communication models






