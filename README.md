## Blue Cross Blue Shield Association
- Blue Cross Blue Shield is a franchise made up of member companies that license the Blue Cross, Blue Shield name. This TigerGraph database contains all the Blue Cross Blue Shield Association member comapnies and states that they operate in. Currently there are 34 companies that operate in all 50 states, District of Columbia, and Puerto Rico.
## Example of Global_Types Integration
- This repository has a dependency on the [**Global_Types**](https://github.com/custom-discoveries/Global_Types) repository and uses the *state* Vertex. Please make sure to clone Global_Types repository and load it into your TigerGraph database as part of deploying this application.
## Install and Run
### Install
To install this TigerGraph demo, clone this repository at a terminal command prompt: 
- \>git clone https://github.com/custom-discoveries/BCBSA.git
### Run Cheetah in Cloned Directory:
-  cd BCBSA
-  BCBSA\> Cheetah [^1]
    - Select -b option to load both the schema & data
    - Select -q (sub option -b) to Define and Install the queries
[^1]: See Cheetah [README.md](https://github.com/custom-discoveries/Cheetah/blob/main/README.md) for installation and setup of Cheetah
### In TigerGraph GraphStudio:
Run the query scripts in TigerGraph GraphStudio Write Queries:
- findCompany.gsql
- findState.gsql
