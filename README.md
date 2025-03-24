# overview of the Mass-GT project
In order to get access to the code pleasae send your GitHub account name or e-mail adress to thoen@significance.nl or m.a.debok@tudelft.nl to get full access to the repository. External users are invited to make use of existing subversions of the model, and to contribute to the further development of the simulation approach (GPL 2.0 license). 

<p align="left">
  <img src="https://user-images.githubusercontent.com/81620383/186445600-255ebfc9-bc95-4d09-9bbb-600c4fa82638.png" width="150" height="155">
  <img src="https://user-images.githubusercontent.com/81620383/186445620-0eea8abf-66d1-4cc9-91be-b73295bc125d.png" width="125" height="125">
  <img src="https://user-images.githubusercontent.com/81620383/186445650-85d43d7c-c68c-4c28-9f9b-589508066932.jpg" width="180" height="70">
  <img src="https://user-images.githubusercontent.com/81620383/186445682-0bc6ec78-ac03-4680-be8e-c802a34cbfe2.png" width="180" height="70">
  <img src="https://user-images.githubusercontent.com/81620383/186445701-7d7720df-76f3-4680-8e8a-378d24b79092.png" width="100" height="100">
</p>

## Introduction

The MASS-GT model is a multi-agent simulation models for urban freight transport. Main motivators were the absence of strategic simulation tool for impact assessment of city logistic developments and policies, and the emergence of new sources of large data collections on freight transport.
It is being developed at Delft University of Technology. In different research projects the system is further developed with the help Significance as a technical partner, or public authorities (such as the City of Rotterdam of the Road Transport Authorities RWS) as important stakeholders in the use and application of the models.
The acronym MASS-GT stands for Multi-Agent Simulation System for Goods Transport and expresses the general specifications of the approach. First of all, the multi-agent approach is adopted to explicitly address the heterogeneity of stakeholders that are involved in urban freight transport (e.g. producers, customers, carriers, local administrators). Second, an extensive dense dataset with freight vehicle trip diary data is used to develop data-based simulation solutions and calibrate logistical choice models. Demand is simulated at the unit of shipments (instead of vehicles) to complement the more behavioural approach we are aiming at. Some shipments are transported directly from producer to consumer but many goods are transported via distribution channels with one or more ‘logistical nodes’. Therefore distribution centers and transshipment terminals are represented as logistic nodes, to distinguish transportation flows that are part of a multi-tier distribution channel. Figure 1 illustrates how the goods are transported as shipments between producer and consumer, and where which logistical choices are made. It illustrates strategic choices, such as distribution channel choice, shipment size, and tactical choices such as vehicle type and tour formation. 
 
<img src="https://user-images.githubusercontent.com/81620383/186440192-8ab2b276-8fb5-4a2a-8815-5dbf92aeed1a.png" width="648" height="280">

*Conceptual model for logistic choices in MASS-GT*

The evolutionary development of the approach is published in a number of publications, and is still further evolving. In several research projects different components, or improved release of the system are being developed. These incremental progression takes place in diverse parallel projects: a H2020 innovation projects, PhD projects, or MSc projects.
The next figure gives an indication of the scope of the simulation and (intermediate) results.

<img src="https://user-images.githubusercontent.com/81620383/186440052-6348882d-7eb2-4897-a229-f78d031e220b.jpg" width="648" height="420">

*MASS-GT in 6 illustrative figures*


## Development path and collaborations
As explained, ‘the’ MASS-GT model, is developed in an evolutionary approach. This means different releases of the simulator have been developed, and many are expected to follow as this line of research still hosts so many challenges. 
Contributions are in research innovation projects funded by the European Commission such as the HARMONY (http://harmony-h2020.eu/) , LEAD (https://www.leadproject.eu/) or URBANE (https://www.urbane-horizoneurope.eu/) projects. Through these H2020 projects, there is an intense collaboration with technical partner Significance (www.significance.nl), or public authorities such as the City of Rotterdam (https://www.rotterdam.nl/english/).
The model is also used as a donor model for the Dutch Strategic Freight transport demand model BasGoed for Rijkswaterstaat. The implemented module is also available as an open-source module that can be run wit a full set-up of the BasGoed model.
In addition, most of the academic exploration and development steps are taken with the help of PhD, Master or Bachelor students.

## Publications
- de Bok, M, S Giasoumi, L Tavasszy, A Nadi, S Thoen, J Streng (2024) “A simulation study of the impacts of micro-hub scenarios for city logistics in Rotterdam”. Research in Transportation Business & Management. Vol 56. pp. xx-xx
- de Bok, M, L Tavasszy, A Nadi, S Thoen, S Giasoumi, J Streng (2024) “Learnings from the simulation of use cases in city logistics in the HARMONY project”. Transportation Research Procedia. Vol 79, pp. 249–256
- Tapia, R., I Kourounioti, S Thoen, M de Bok, L Tavasszy (2023). "A disaggregate model of passenger-freight matching in crowdshipping services." Transportation Research Part A: Policy and Practice. Vol 169, pp. xx-xx 
- Mohammed, A R, A Nadi, L Tavasszy, M de Bok (2023) “A data fusion approach to identify distribution chain segments in freight shipment databases”, Transportation Research Records, Vol 2677, pp. 310-323.
- de Bok, M, L Tavasszy, I Kourounioti, S Thoen, L Eggers, V Mayland Nielsen, J Streng (2021) “Impacts of a low-emission zone on freight delivery patterns in Rotterdam: a case study with the HARMONY tactical freight simulator”, Transportation Research Records, Vol 2675(10), pp. 776-785 (https://doi.org/10.1177/03611981211012694)
- de Bok, M, L Tavasszy, S Thoen (2022) Application of an empirical multi-agent model for urban goods transport to analyze impacts of zero emission zones in The Netherlands, Transport Policy, Volume 124, Pages 117 – 127
- Thoen, S, L Tavasszy, M de Bok, G Correia, R van Duin (2020) Descriptive modeling of freight tour formation: A shipment-based approach, Transportation Research Part E, Volume 140, Pages XX – XX (https://doi.org/10.1016/j.tre.2020.101989)
- de Bok, M, I Bal, L Tavasszy, T Tillema (2020) Exploring the impacts of an emission based truck charge in the Netherlands, Case Studies on Transport Policy, Volume 8, Pages 887 – 894. (https://doi.org/10.1016/j.cstp.2020.05.013)
- Thoen, S, M de Bok and L Tavasszy (2020) Shipment-based urban freight emission calculation. 2020 Forum on Integrated and Sustainable Transportation Systems (FISTS) in Delft. (DOI: 10.1109/FISTS46898.2020.9264858)
- de Bok, M, L Tavasszy (2018) "An empirical agent-based simulation system for urban goods transport (MASS-GT)." Procedia Computer Science, 130: 8. (https://doi.org/10.1016/j.procs.2018.04.021)


