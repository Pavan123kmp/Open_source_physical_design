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

# List of All Open-Source Tools Used

Name of tool  | Application/Usage
------------- | -------------
yosys | Synthesis of RTL design
ABC	  | Mapping of Netlist
OpenSTA	|Static Timing Analysis
OpenROAD	| Floorplanning, Placement, CTS, Optimization, Routing
TritonRoute	|Detailed Routing
Magic VLSI	|Layout Tool
NGSPICE	| SPICE Extraction and Simulation
SPEF_EXTRACTOR	| Generation of SPEF file from DEF file

# Setting up environment
The above list of tools shows that, many different tools are required for various tasks in Physical VLSI Design. Each tool in itself have number of system requirements and require various supporting tools to be installed. Installing each tool one-by-one seems in-efficient. This is made easy by some custom scripts that setup the required tools and environment for them in just a few easy steps. To install all the required tools, one can refer to the below mentioned repositories:

* VSDFlow - Installs Yosys, Magic, OpenTimer, OpenSTA and some other supporting tools
* OpenLANE Build Scripts - Install all required OpenROAD and some supporting tools

# Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK
