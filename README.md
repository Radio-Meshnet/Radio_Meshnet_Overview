# Overview of the project
## Scope of the project Radio Meshnet
The aim of the project is the development of an autonomous mesh network under real conditions with the aim of emergency communication independent of electricity and the Internet. Here, the theoretical planning of such networks is to be transferred to reality. Function and reliability is to be tested and optimized with a large number of participants over long distances. In the first step, a messenger app must be developed (Communicator) and the necessary wireless hardware Loradio/ WLAN mesh/ CB radio for the selected network stack Reticulum from Mark Quist. In step two, the actual project goal is sought. With a large number of willing users and provided hardware/software, a mesh network is created under the umbrella of a foundation and the runtimes as well as the message loss recorded by the users and statistically evaluated by the project management. As a result, an assessment of the feasibility of real autonomous networks is to be carried out which should lead to the subsequent successful implementation of an extensive emergency communication network, possibly EU-wide.  In this network user will be self identified (DID) but can save encrypted communicate and maybe exchange goods and information to make it possible to survive in disaster situations with mutual help.  For this purpose, part of the project is the possible integration of a low bandwidth tolerant blockchain into the network. This has never really been implemented at the moment. Suitable blockchains such as beam, mina etc. are to be examined for this purpose.
## Roadmap and Milestones
### Step 1: Planning phase
    • 1.1 Create requirements document + threat modeling, project plan with tasks            
    • 1.2 Create technical design, diagram as technical overview of all components            
    • 1.3 First alpha release of the Communicator app as central component                   
    • 1.4 Design of the radioMesh hardware Loradio for the Communicator app                  
    • 1.5 Design of the radioMesh based on ESP32 WLAN for the Communicator app for high speed Mesh 
    • 1.6 Implementing decentralized, anonymous user identification DID with database structure 
    • 1.7 development/implantation of decentral, digital blockchain with resilience against power/internet blackout  Mina, Hydra, beam for DID, registration           , identification etc??? External help.   
    • 1.8 planing of external security audit of encryption used in the network core
    
### Step 2: Pretest with small group   
    • 2.1 New Beta release of Loradio for Communicator with optimized outline/case for use on   smartphones
    • 2.2 New beta release of Communicator with group function  and payment option
    • 2.3 Real test with bigger test group

### Step 3: Real mass test after app launch and recruiting user      
    • 3.1 Process issues from external security review and results from beta test
    • 3.2 Publish developer and user documentation
    • 3.3 Optional: porting the app to new , faster programming language with external help
    • 3.4 public launch of 1.0 release of Communicator app with new LoRadio for mobile handy use (maybe before speed porting so save time)
    • 3.5 Wide area test of the capability's of real world mesh networks. With min 200 users over large distances in urban and open landscape and result               analyzing
