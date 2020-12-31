# IIT BOMBAY TECHFEST 2020 Project Submission For Computational Agriculture Challenge

**Project Name :** AgriSpect

**Tagline :** Food is the key element required for life. What if we tell you that you can make the food invulnerable!

**Case Study :** In modern Agriculture and Forestry purposes Plant Pathological Research is very much essential for the crop improvement. In every year, huge crop is damaged by pathogen attack. In most of the cases, Farmers and lay men suffers huge loss due to severe pathogenic infestation. For crop improvement, the first and foremost essential key point is diseases identification. After proper identification of diseases we will be able to treat the diseases. Most of the cases lab oriented research is time taking and very much expendable but instant identification of plant diseases with its causal organism by using modern technology is most suitable and cost effective and also authentic. This type identifying methodology will help us to identify the diseases with its proper control measures. Above 95 % accuracy and authentic identification is possible by using this methodology.

As per Wikipedia The impact of pesticides consists of the effects of pesticides on non-target species. Pesticides are chemical preparations used to kill fungal or animal pests. Over 98% of sprayed insecticides and 95% of herbicides reach a destination other than their target species, because they are sprayed or spread across entire agricultural fields.Runoff can carry pesticides into aquatic environments while wind can carry them to other fields, grazing areas, human settlements and undeveloped areas, potentially affecting other species. Other problems emerge from poor production, transport and storage practices.Over time, repeated application increases pest resistance, while its effects on other species can facilitate the pest's resurgence.

Each pesticide or pesticide class comes with a specific set of environmental concerns. Such undesirable effects have led many pesticides to be banned, while regulations have limited and/or reduced the use of others. The global spread of pesticide use, including the use of older/obsolete pesticides that have been banned in some jurisdictions, has increased overall.

Thus we can conclude that even though pesticides and insecticides are pretty useful but now a days the reverse of it i.e. harmfulness is getting increased in a rapid rate.

More information can be easily expressed through this video below -
https://youtu.be/bz0ZoQuCa4w

Check out the video from Ted-Ed below to know more about the problem -
https://youtu.be/GLllZ-qiXJA

**Idea :** So the point arises - " What can we do to control usage of pesticides ? ".

Over here we should keep one thing in mind is that we need to make a system which can lower down or even maybe track down the usage of pesticides cause we can't pull it down for some obvious reasons to maintain the agriculture industry.

**Theory :** In our project we will be using the feature and characteristics of being warm-blooded mammal called thermoregulation. Here is a image showing the presence of thermoregulation and being scanned by a IR scanner camera -

So basically we will scan up using the AMG8833 Sensor Camera breakout using the OpenMV Cam H7+ and it will show up whether the pest is present there or isn't. And it will then tell us where to exactly spray the insecticide or pesticide and where shouldn't.

**Hardwares :**

OpenMV Cam H7+ (https://openmv.io/products/openmv-cam-h7-plus)

Adafruit AMG8833 IR Thermal Camera Breakout Board (https://www.adafruit.com/product/3538)

Some Jumper Wires/Cables

**Software :** 

Edge Impulse (https://edgeimpulse.com/)

OpenMV Studio (https://openmv.io/)

**Evaluation** 

If a large heat source like a nest isn’t obvious, sensitive thermal cameras may be able to detect irregular heat patterns, moisture, and other signs of damage that indicate the presence of a pest, like missing insulation or holes in walls that indicates an entry point. Understanding what patterns to look for requires training and practice, as it’s easy to incorrectly interpret an image.

Here’s some indicators to look for when trying to locate the following common intruders:

**Termites**

![image](https://user-images.githubusercontent.com/64097541/103419738-45ae8e80-4bba-11eb-9c7e-a84a44e824c3.png)


Termites nests may be visible as hotspots (left), and termite tunnels have high moisture content that can be detected with thermal imaging (right).

Termites can be found by looking for nests, moisture sources, and evidence of damage in walls. When termites enter a home, they release heat from their digestive system in the form of carbon dioxide and construct mud tubes that have high moisture content, creating irregular heat patterns on the surface of walls, ceilings, and floors.

**Rodents**

![image](https://user-images.githubusercontent.com/64097541/103419658-e6507e80-4bb9-11eb-9fd3-20a467152449.png)

Rodents (like the possum on the left) or their nests may be visible, or wildlife activity may leave clues like missing insulation (right).

Rodents and other wildlife might create nests that can be detected, or might have damaged walls or moved insulation and created cold spots that can be seen in thermal. Nocturnal animals that emerge at night can also be tracked with thermal imaging, which works in complete darkness.

**Hornets and Other Social Insects**

![image](https://user-images.githubusercontent.com/64097541/103419700-2283df00-4bba-11eb-95d4-afb4e133dc50.png)


Hornet nests show up as hotspots in thermal.

Insects are cold-blooded, but they do generate heat. The heat of a wasp nest, beehive, or other large cluster of social insects will usually generate enough heat to be detected by a thermal camera.

**Features**
1. Low in cost and can be used very easily.

2. No need of a technical background to use this device

3. Will enable correct usage of chemicals in farming.

4. Prevent harmful diseases cause by spraying unwanted chemicals.

**Future Work** 

For further development we are thinking of using some high power cameras which will be able to even track up and classify pests even if they are flying. We are thinking of reducing the cost and even trying to make our model run on cheap Android phones with a cheap Thermal Camera connected with it which will help the poor farmers to easily buy and use this technology to enhance the human life.
