Includes: agroforestry, farmland, habitat, buildings, Ethereum, FreeCAD, Blender, BIM, IFC

---

**SUMMARY**

An experiment in transitioning a portion of our agribusiness farm to agroforestry.  Agroforestry has the potential to be carbon-negative while improving access to energy, food, water, and habitat as the climate changes over the next 100 years.

The project is funded through to the year 2035.

**OVERVIEW**

The project is located on a 42 acre parcel of land.  Much of the property will be at-risk of increased fire, erosion, and habitat loss if the climate continues to warm over the next few decades.  Agroforestry practices should be able to mitigate that risk, however, there is still a great deal of technology development that will be required before such systems are practical enough to scale in a meaningful way.

In our case, the land will be treated in two ways.

1) Most of the land will continued to be farmed through conventional agribusess and most of the wooded area (a former clear-cut) will be maintained for the selective harvesting of wood.  This continues the generally accepted practices of today without change.

2) A small portion (about 2.5 acres) will transition to carbon-negative agroforestry.  

Assuming the agroforestry venture is successful, the manufacture of components for such agroforestry systems is a possibility.    

**PROJECT MILESTONES**

***Past***

2010: Developed the concept for a carbon-negative agroforesty.

2013: Purchased farmland.

2016: Made early investments in technologies that would be needed in a climate changing world.   In particular, water technologies and technologies that automate project work in equipment manufacturing and buildings.

2019: Initial design of the carbon-negative co-generation system.

2021: Started work on the co-generation prototype, buildings, food trails, and computer models.

***Present***

Covid set the project back a couple of years, however, some progress was made in 2021/2022 as illustrated below.   

<p align="center">
<img src="Update2022.svg" alt="Project Update" width="1000">
</p>

Current project plans are to use a [cogeneration system](https://www.energy.gov/eere/amo/combined-heat-and-power-basics) supplemented with solar photovoltaics to provide the buildings with space heating, hot water, electricity, and water purification. Yard and wood waste will be used as biofuel with nutrients, and especially the nitrogen that the system generates being captured for use onsite. When also producing char for soil improvement, that co-generation system can become carbon negative.  The technology to do this is not new, but it  requires significant development for cost reduction before it will be economically viable in general use.  

***Future***

**2023-2033**: Construction of supporting infrastructure for carbon-negative agroforestry through three stages:

- A utility building (pumphouse with drip irrigation mixing equipment).
- A workshop and office building (1 person 8 hours per day).
- A three season building (2 people, 24 hours, spring, summer, and fall).

**OWNERS**

Nancy and Brenon both grew up on small farms. Brenon worked in the development and manufacture of distributed co-generation power systems and later in the engineering of large public utilities. Nancy managed projects for new technology product development and hardware prototyping. Both have developed a keen interest in the relationship between secure communities, housing, and biodiversity in this time of changing climate and technology.

You can email the project at hund---yearfar-s @ protonmail.com.

---

**SUPPLEMENTARY REFERENCE MATERIAL**

***Agroforestry***

Agroforestry is the practice of planting crops among trees. The trees protect the crops from wind, heat, and water extremes such as those predicted by climate models. In general, total food productivity from agroforestry is about the same per acre as agribusiness, but it can be more reliable, support habitat, and is better suited to small scale farms with a single household. 

One hectare of agroforestry was chosen for this project since that is roughly how much land it takes, in principle, to supply a small carbon-negative household with its food, water, and energy needs.  One hectare is 2.5 acres, or about half a residential city block.  For reference, there is about two hectares (5 acres) of productive arable land available to every household on earth.  

- [What is agroforestry?](https://www.aftaweb.org/)

- [Agroforestry - UK](https://www.agforward.eu/index.php/en/silvoarable-agroforestry-in-the-uk.html)

- [Agroforestry - US](https://www.fs.usda.gov/nac/about/why-agroforestry.php)

***Cogeneration***

In climates with a winter season, cogeneration can supply homes with space heating and hot water as well as electrical power during the night and cloudy winter days.  Critically, they can help process water for re-use, produce solid carbon for soil amendment, and they can generate nitrogen rich fertilizers.  These systems complement photovoltaics which are most effective when producing electricity during the summer with its long hours of daylight.  Co-generation is a well-known and proven technology, but is not yet cost effective at small scale.  We think it could become cost-effective in our application within the next decade or so.

- [Cogeneration - US Department of Energy](https://www.energy.gov/eere/amo/combined-heat-and-power-basics)

- [Micropower Connect - NRCAN](https://www.nrcan.gc.ca/sites/www.nrcan.gc.ca/files/canmetenergy/files/pubs/2006-073_%2528TR%2529_411-INTERC_Connecting_MicroPower_to_the_Grid_2nd_Edition.pdf)

- [Biomass Gassification - Energy and Environmental Science](https://pubs.rsc.org/en/content/articlepdf/2016/ee/c6ee00935b)

- [Cogen example - heat and electricity at Scotston Farm](https://www.youtube.com/watch?v=i9xmWJ4hAGs)

- [Cogen example - heat and char at Burt's Greenhouse](https://biochar-international.org/burtsgreenhouse/)

- [Cogen example - heat and char by the City of Stockholm](https://www.stockholmvattenochavfall.se/en/current-projects/development/biochar/#!/about-the-biochar-project)

- [Cogen biomass generator](https://www.allpowerlabs.com/products/product-overview)

***Design and Coordination (Blender, FreeCAD, IFC, and Ethereum)***

The design and then tracking of buildings,  equipment, crops, and habitat over time is a difficult problem.  That is especially true if the data is to be used for long-term research and scientific purposes.  To manage data we will be using a 3D file system rather than 2D file/folder structure.  In addition to buildings and equipment, this approach allows, for example, the history of a fruit tree to be obtained by selecting it from the 3D model.  That history may include a given tree's supplier, year planted, species, cost, tax depreciation, maintenance, yield, and height over time, among other parameters.  Below is a description of the software we are using to build such a digital twin of the project (see also the above illustration under the Milestones heading).

**Blender**, often used by artists, is a 3D modelling tool for visualizing and communicating project information. We use Blender to model the overall property, site layout, crops, and trees. With Blender's use of GIS and [BIM and IFC](https://blenderbim.org/search-ifc-class.html) it should prove useful when working with planners, landscape architects, biologists, agronomists, among others.  

**FreeCAD**  is a 3D modelling tool typically used by skilled trades and engineers.   In our project it is used to design metal parts for the co-gen system and we use it to detail building construction (e.g. wall framing).  FreeCAD is generally used when more precision and design computation (e.g. heat flow) is needed than Blender is designed for.  FreeCAD, like Blender, can use IFC for data exchange.  The project will use this software when working with house builders, machinists, welders, and others.

**IFC** or [Industry Foundation Class](https://www.buildingsmart.org/standards/bsi-standards/industry-foundation-classes/)  is an open standard for exchanging information about the physical world.  It is used to describe the built environment (buildings, equipment, roads, and infrastructure) as both a 3D geometry and a semantic language which helps machines reason about the model.  The next edition of IFC will include landscapes which we will use to model the crop and forestry aspect of our project.  IFC is commonly used by regional and municipal governments in BIM projects which means our project data is likely to be compatible with agencies we work with.  And since IFC is used for public infrastructure, it is a file format that is likely to remain relevant for many decades.   

**Ethereum** is a coordinating smart-contract platform that has the long-term potential to automate business processes and, in doing so, reduce the cost of delivering low-carbon technologies and homes.  It could, for example, make manufacturing co-ops cost effective once again (e.g. DAOs for co-gen systems and kit houses) and it could automate much of the administrative costs of housing developments.  Distributed and automated KYC/AML/ATF, accounting, finance, tax payments, and especially voluntary standards and certification programs for ethics and consumer protection, among others, are still needed for this technology to mature over the coming decade.  Ethereum integration with IFC's semantics should allow smart contracts to better reason about the physical asset being represented and its transactions.   The [Ernst & Young Global Blockchain Summit](https://pub.ey.com/public/2021/2112/2112-3933703/blockchain-summit-2022/index.html#events)) describes some of the future ways we see Ethereum being used in our project.

The image below illustrates how the above software (Blender, FreeCAD, and Ethereum), as part of a larger set of distributed technologies, may help to offer cost effective and low-carbon alternatives to  climate, food, energy, habitat, and housing challenges.  

<img title="" src="DistTechnologies.svg" alt="Distributed Technologies" width="1000">

- [DAO cooperatives](https://medium.com/nexus-mutual/digital-cooperatives-are-the-future-2b0772c1e03a)

- [US Federal Reserve - Smart Contract Research Report](https://research.stlouisfed.org/publications/review/2021/02/05/decentralized-finance-on-blockchain-and-smart-contract-based-financial-markets)

- [UNICEF's Innovation Fund for Blockchain Technologies](https://www.unicef.org/innovation/stories/Fundblockchain6months)

- [OASIS Standards Body - Baseline Protocol for Smart Contracts](https://docs.baseline-protocol.org/baseline-protocol/architecture)

- [Microsoft using Ethereum Technology in their Supply Chain](https://cloudblogs.microsoft.com/industry-blog/manufacturing/2020/12/17/improve-supply-chain-resiliency-traceability-and-predictability-with-blockchain/)

- [DAO Legislation](https://www.wyoleg.gov/Legislation/2021/SF0038#-408)

- [Gitcoin Grants](https://gitcoin.co/blog/gitcoin-grants/)

**[Image Credits]([Openverse &#124; WordPress.org](https://wordpress.org/openverse/search/?q=farm))**

[Toronto Healthy House - Rolf Paloheimo](http://www3.sympatico.ca/rolf/index.html)  

[Agribusiness](https://www.flickr.com/photos/48631399@N07/16145919580) by [ukagriculture](https://www.flickr.com/photos/48631399@N07) is licensed under [CC BY-NC-ND 2.0](https://creativecommons.org/licenses/by-nd-nc/2.0/jp/?ref=openverse).

[Metra Electric Line, Chicago Illinois](https://www.flickr.com/photos/75683070@N00/9179520017) by [Ken Lund](https://www.flickr.com/photos/kenlund/) is licenced under [CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0/)

[Preventing desertification](https://www.flickr.com/photos/75478114@N00/3861819575) by [Bert van Dijk](https://www.flickr.com/photos/75478114@N00) is licensed under [CC BY-NC-SA 2.0](https://creativecommons.org/licenses/by-nc-sa/2.0/?ref=openverse).

[Agforward](https://www.flickr.com/photos/120950867@N08) is licensed under [CC BY-NC-SA 2.0](https://creativecommons.org/licenses/by-nc-sa/2.0/?ref=openverse).
