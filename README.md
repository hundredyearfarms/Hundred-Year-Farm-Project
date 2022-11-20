Includes: agribusiness, agroforestry, habitat, buildings, FreeCAD, Blender, BIM, IFC, Ethereum

---

**SUMMARY**

We are transitioning a small portion of our agribusiness farmland to agroforestry with habitat restoration.  

Agroforestry has the potential, over the next hundred years, to transition land that is no longer suitable for agribusiness back to natural habitat while still being a source of local energy, food, materials, and water. 

Such transitions could become a generally preferred solution in the future, but they are not  economically feasible today and the necessary technology is probably decades away.  This project is working towards the long-term development of that technology so it could some day allow agroforestry with habitat restoration to scale in a meaningful way.  

**OVERVIEW**

A 42 acre parcel of land that is being treated in two ways.

1) Most of the land will continue to be farmed through conventional agribusiness and most of the wooded area (a former clear-cut) will be maintained for the selective harvesting of softwood (spruce) for lumber.  This continues the generally accepted practices of today without change.

2) A small portion (about 2.5 acres) will transition to carbon-negative agroforestry with habitat restoration.  This may eventually lead to the manufacture of hardware components for agroforestry systems along with sales of the higher-value hardwoods (oak, walnut, maple, beech) as well as fruit, nut, and hardwood tree saplings.   
  

**MILESTONES**

***Past***

2010: Concept development.

2013: Purchased farmland.

2016: Made early investments in relevant technologies. In particular, water technologies and technologies that could automate project work for equipment manufacturing and buildings.

2019: Initial design of a carbon-negative co-generation system for agroforestry.

2021: Started work on the co-generation prototype (for energy, water, nutrient capture), buildings, trails, and computer models.

***Present***

Current project plans are to use a [cogeneration system](https://www.energy.gov/eere/amo/combined-heat-and-power-basics) supplemented with solar photovoltaics to provide the agroforestry buildings and  greenhouse with space heating, hot water, electricity, and water purification. Since on-site wood waste from pruning and trimming is plentiful, it will be used as biofuel with nutrients, and especially the nitrogen that the system generates being captured for use. When also producing char for soil improvement, that co-generation system can become carbon negative.  The technology to do this is not new, but it, and the business processes organizing it, still require significant automation and cost reduction before they will be economically viable.  

***Future***

**2023-2033**: Construction of supporting infrastructure for carbon-negative agroforestry through three stages:

- A utility building (pumphouse with drip irrigation mixing equipment, computer controls, sensors, and lights for plant germination).  The drip irrigation system itself.
- An equiped workshop with office space (2 people 8 hours per day).
- A three season working cabin (2 people, 24 hours, spring, summer, and fall).

**OWNERS**

Nancy and Brenon both grew up on small farms. Brenon worked in the development and manufacture of distributed co-generation power systems and later in the engineering of public utilities. Nancy managed projects for new technology product development and hardware prototyping. Both have developed a keen interest in the relationship between secure communities, energy, and biodiversity in this time of changing climate and technology.

You can email the project at hund---yearfar-s @ protonmail.com.

---

**SUPPLEMENTARY REFERENCE MATERIAL**

***Agroforestry***

Agroforestry is the practice of planting crops among trees. The trees protect the crops from wind, heat, and water extremes such as those predicted by climate models. In general, total food productivity from agroforestry is about the same per acre as agribusiness, but it can be more reliable, support habitat, and is better suited to small scale operations with a single household. 

One hectare of agroforestry was chosen for this project since that is roughly how much land it takes, in principle, to supply a small carbon-negative household with its food, water, and energy needs.  One hectare is 2.5 acres, or about half a residential city block.  For reference, there is roughly two hectares (5 acres) of productive arable land available for every household on earth.  

- [What is agroforestry?](https://www.aftaweb.org/)

- [Agroforestry - UK](https://www.agforward.eu/index.php/en/silvoarable-agroforestry-in-the-uk.html)

- [Agroforestry - US](https://www.fs.usda.gov/nac/about/why-agroforestry.php)

***Cogeneration***

In climates with a winter season, cogeneration can supply buildings with space heating and hot water as well as electrical power during the night and cloudy winter days.  Critically, they can help process water for re-use, produce solid carbon for soil amendment, and they can generate nitrogen rich fertilizers.  These systems can be supplemented with photovoltaics which can produce useful amounts of electricity during the summer when there are long hours of daylight and less need for heat.  Co-generation is a well-known and proven technology, but is not yet cost effective at small scale.  We think it could someday become cost-effective in this specific application where the fuel (wood waste) is available at no, or a negative cost.  

- [Cogeneration - US Department of Energy](https://www.energy.gov/eere/amo/combined-heat-and-power-basics)

- [Micropower Connect - NRCAN](https://www.nrcan.gc.ca/sites/www.nrcan.gc.ca/files/canmetenergy/files/pubs/2006-073_%2528TR%2529_411-INTERC_Connecting_MicroPower_to_the_Grid_2nd_Edition.pdf)

- [Biomass Gassification - Energy and Environmental Science](https://pubs.rsc.org/en/content/articlepdf/2016/ee/c6ee00935b)

- [Cogen example - heat and electricity at Scotston Farm](https://www.youtube.com/watch?v=i9xmWJ4hAGs)

- [Cogen example - heat and char at Burt's Greenhouse](https://biochar-international.org/burtsgreenhouse/)

- [Cogen example - heat and char by the City of Stockholm](https://www.stockholmvattenochavfall.se/en/current-projects/development/biochar/#!/about-the-biochar-project)

- [Cogen biomass generator](https://www.allpowerlabs.com/products/product-overview)

***Design and Coordination (Blender, FreeCAD, IFC, and Ethereum)***

The effectivce design and coordination of a project of this type is a difficult problem.  Below is a description of the software we are using to build a digital twin (model) of the property that has automated business processes.

**Blender:**  We use Blender [BIM and IFC](https://blenderbim.org/search-ifc-class.html) to model the overall property, site layout, crops, and trees.   This allows us to manage data using a 3D file system rather than 2D file/folder structure.  This approach allows, for example, the history of building, equipment, and trees to be obtained by selecting them from the 3D model.  That history may include a given tree's supplier, year planted, species, cost, tax depreciation, maintenance, yield, and height over time, among other parameters.  

**FreeCAD:**  This is a 3D modelling tool typically used by trades and engineers.   In our project it is used to design metal parts for the co-gen system and we use it to detail building construction (e.g. wall framing).  FreeCAD is generally used when more precision and design computation (e.g. heat flow) is needed than Blender is designed for.  FreeCAD, like Blender, can use IFC for data exchange. 

**IFC** or [Industry Foundation Class](https://www.buildingsmart.org/standards/bsi-standards/industry-foundation-classes/)  is an open standard for exchanging information about the physical world.  It is used to describe the built environment (buildings, equipment, roads, and infrastructure) as both a 3D geometry and a language which helps machines reason about the model.  The next edition of IFC will include landscapes which we will use to model the crop and forestry aspect of our project.  IFC is commonly used by regional and municipal governments which aids in compatibility and helps ensure the data format will persist for many decades.    

**Ethereum** is a coordinating smart-contract platform that has the long-term potential to automate business processes and, in doing so, reduce the cost of delivering low-carbon technologies.  It could, for example, make manufacturing co-ops cost effective once again (e.g. DAOs for co-gen systems and kit buildings).  Distributed and automated KYC/AML/ATF, accounting, finance, tax payments, and especially voluntary standards and certification programs for consumer protection, among others, are still needed for this technology to mature and be adopted over the coming decade.  Ethereum integration with IFC's semantics should allow smart contracts to better reason about the physical asset being represented and its transactions.   The [Ernst & Young Global Blockchain Summit](https://pub.ey.com/public/2021/2112/2112-3933703/blockchain-summit-2022/index.html#events)) describes some of the future ways we see Ethereum being used in our project.  While this technology remains unproven, it is probably not realistic for most product development in our region to be successful without it. 


- [DAO cooperatives](https://medium.com/nexus-mutual/digital-cooperatives-are-the-future-2b0772c1e03a)

- [US Federal Reserve - Smart Contract Research Report](https://research.stlouisfed.org/publications/review/2021/02/05/decentralized-finance-on-blockchain-and-smart-contract-based-financial-markets)

- [UNICEF's Innovation Fund for Blockchain Technologies](https://www.unicef.org/innovation/stories/Fundblockchain6months)

- [OASIS Standards Body - Baseline Protocol for Smart Contracts](https://docs.baseline-protocol.org/baseline-protocol/architecture)

- [Microsoft using Ethereum Technology in their Supply Chain](https://cloudblogs.microsoft.com/industry-blog/manufacturing/2020/12/17/improve-supply-chain-resiliency-traceability-and-predictability-with-blockchain/)

- [DAO Legislation](https://www.wyoleg.gov/Legislation/2021/SF0038#-408)

- [Gitcoin Grants](https://gitcoin.co/blog/gitcoin-grants/)


