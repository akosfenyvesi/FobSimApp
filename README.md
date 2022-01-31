# FobSim

This project aims to introduce a reliable Fog-enhanced Blockchain simulation environment, namely FoBSim.

This environment shall facilitate easy simulation for different Fog-Blockchain integration scenarios.

FoBSim is implemented using Python 3.8, and it is adviced to be run on Linux or Windows OS. 

This research work is a part of a paper that is published in the PeerJ-Computer Science journal. The open-access paper can be found  at:

https://peerj.com/articles/cs-431/

DOI: 10.7717/peerj-cs.431

IMPORTANT NOTE: Published code should be considered copyrighted whether or not it includes an explicit copyright notice. This means that no one can distribute, reproduce, display, or create derivative works of the software without permission of the copyright owner.

*The components implemented in FoBSim contains:

1- Fog layer implementation.

2- Blockchain network Implementation.

3- End-User layer implemetation.

4- Consensus algorithms.

5- Incentivization Mechanisms.

6- Parallel Mining.

7- Gossip Protocol.

8- Easy network topology and unique identities management.

*FoBSim allows the placement of the Blockchain network in either:

1- The Fog layer.

2- The End-User layer.

*The Blockchain in FoBSim provides the following services/immutable distributed ledgers:

1- Payment/Trading

2- Data management

3- Identity management

4- Computational Services through Smart Contracts

*The Blockchain in FoBSim allows the use of one of the following Consensus algorithms during each run:

1- Proof-of-Work (PoW)

2- Proof-of-Stake (PoS)

3- Proof-of-Authority (PoA)



# Installation:
Dependencies (you may be informed when you run the tool that other libraries need to be installed. Please do that depending on your OS):
-- Git
-- hashlib
-- json
-- random
-- time
-- multiprocessing
-- math
-- shutil
-- pandas

STEPS:
1- clone this repository to your machine. You need Python 3.X installed 
2- navigate to the new Fobsim directory just created
3- modify the json file: Sim_parameters.json according to the scenario to be simulated. Please refer to the published paper indicated above for details regarding the simulation parameterization. Make sure to save the file after modifying it.
3- run the following command: python3 main.py
4- follow the instructions
5- check the provided analysis at the end of the simulation run
6- check the temporary files created in the 'Fobsim/temporary' folder
