# planet_cubicus_species
An artificially generated dataset of species with various attributes depending on the climate zone. Goal: Provide a data set for data mining. The model is very simple. It's meaningfulness in the biological sense is rather limited, but the data set provides an excellent playground for data analysis. 

## Abstract
This population generator is a small piece of python software which aims to generate a big set of population data. It generates a flat file comprising records of species that live on the imaginary model planet Cubicus. The species have some model attributes like length and furr colour. They depend on the country they live in. Their abundance per country depends on the local climate. 

To keep things simple, the features of the model are as trivial as possible, yet, meaningful enough to experiment with proceeding and analysing big data. Thus, Planet Cubicus is a model planet where continents and countries are cubic and climate zones depend on the longitude only. However, it is by far not good enough to simulate a proper exoplanet or reproduce realistic features of populations, biological or evolutionary laws. As mentioned, the only aim is to deliver a big data set for data analysis.

## Planet Cubicus Map

Have a look at the model map. Planet Cubicus consists of 14 countries distributed over three continents. The continents are separated by oceans. The climate zones in the far north and the far south are the coldest, getting ever warmer along the longitude towards theequator. So some features are much like that of the earth, however, much simpler. For example, there are no alpine regions.

However, there's a lot of work to be done, yet, for example a species occurs only in one single country, which is not particulary realistic.
​
## The Features of the Species
​
The species on planet Cubicus are similar to animals, plants, fungi and bacteria, their size depends on their kingom belonging. Their attributes in this model are:
​
* __Name and subname__: Just like on earth, species are named using a species and a subspecies name. However, their names are randomly generated using a crude computer algorithm, so they don't follow any linguistic rule set.
* __Country__: The cubical country they live in.
* __Climate__: The climate zone of their abundance: Polar, subpolar, tundra, temperate, subtropical, arid, and tropical
* __Kingdom__: Four kindoms of species exist on planet Cubicus: Animalia, Plantae, Fungi, and Bacteria.  
* __Abundance per country__: An animal with a high abundance in temperate Penalae is likely to be found in temperate amura, but rather not in ice cold, antarctic Anorna.
* __Size__: The body production of heat depending on the volume increases by the cube, while the loss of heat depending on the skin area increases only by the square. Thus, animals in cold areas are bigger than those in arid ones. The size is provided in relative units.
* __Fur color__: Naturally, the colour becomes darker the hotter it gets in order to protect the skin from radiation, while it becomes lighter the colder it gets to disguise the animal where white snow falls. The colour can be black, brown, grey and white. The color is a nominal value.
* __Behaviour__: In our model world, the animals in hot areas are likely to become aggressive, while those in cold areas tend to become shy. In between, their behavoir is rather balanced: this makes the behaviour an ordinal value: shy < normal < aggressive.
