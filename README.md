# Open_source_physical_design
This repository contains all the information studied and created during the Advanced Physical Design Using OpenLANE / SKY130 workshop. It is primarily foucused on a complete RTL2GDS flow using the open-soucre flow named OpenLANE.

# Table of Contents

# Introduction to RTL to GDSll Flow
RTL to GDSII Flow refers to the all the steps involved in converting a logical Register Transfer Level(RTL) Design to a fabrication ready GDSII format. GDSII is a database file format which is an industry standard for data exchange of IC layout artwork. The RTL to GSDII flow consists of following steps:

* RTL Synthesis
* Static Timing Analysis(STA)
* Design for Testability(DFT)
* Floorplanning
* Placement
* Clock Tree Synthesis(CTS)
* Routing
* GDSII Streaming

All the steps are further discussed in details in the repository.

# About Google SkyWater PDK
Google and SkyWater Technology Foundry in collaboration have released a completely open-source Process Design Kit(PDK) in May, 2020. The current release target to a SKY130 (i.e. 130 nm) process node is available as SkyWater Open Source PDK. The PDK provides Physical VLSI Designer with a wide range of flexibility in design choices. All the designs and simulations listed in this repository are carried out using the same SkyWater Open Source PDK.
