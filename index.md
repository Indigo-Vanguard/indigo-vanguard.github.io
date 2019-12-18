---
layout: page
title: There is No Plan Bee Without Them
bigimg: img/bigbee.jpg
---

# There is no plan Bee without them

## Bees are dying
#### What's up with that?

For 20 years, bees have been dying all over the world at an alarming rate: **half of the colonies do not make it through the year**[^1] [^2]. Entire hives are being deserted by their worker bees, leaving behind a lonely queen and plenty of food. Those same bees are vital to our agriculture and responsible for pollinating a third of our food[^3]. Without them, the human race would last less than 5 years[^4]. This mass extinction is known as **Colony Collapse Disorder (CCD)** and threatens our entire way of life, as well as theirs.

Many factors are thought to be responsible for the bees' decline, among which pests, insecticides and other environmental stresses[^5].

In this Data Story, we explore the death of bees, observe their impact on the world economy and bring to light the dirty tricks of the honey trade.


## Can we find a single culprit of this collapse?
#### (We can't)

First of all, experts claim that those deaths can't be explained by a single cause. Are all the experts wrong? Have they overlooked an obvious correlation fully explaining the bees' death? (Spoiler: They haven't)

<div class="withSidenote" markdown="1">
We investigate here two widely agreed upon causes of CCD: pests and insecticides.

One of those pests -- the (charmingly named) **Varroa destructor** -- is a parasite a bit smaller than the bee that attaches itself on the bee's body. It spreads throughout the colonies and leads to infections, killing the bees. Hence, we also isolate the influence of the Varroa infestation on the death rate of colonies.

<figure class="sidenote">
    <img src="https://indigo-vanguard.github.io/img/varroa_annotated.png">
    <figcaption>Figure 1. The Varroa destructor in action !</figcaption>
</figure>
</div>

To do this, we gather [Varroa infestation data](https://quickstats.nass.usda.gov/results/23E6C5E2-4F53-39C6-91FA-F9878CB8F444) and [pesticide contamination data](https://quickstats.nass.usda.gov/results/E86E00EE-2910-373B-B378-B0AC78EDC0B3) from the **National Agricultural Statistics Service (USDA)**  which we compare with the colony losses accross the US, obtained through the [**Bee Informed Partnership (BIP)**](https://beeinformed.org), a US-wide collaboration of leading research labs and universities in agricultural science.

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="500" allowfullscreen="true" src="https://indigo-vanguard.github.io/plot/scatterplot_lack_of_correlation.html"></iframe>

Unfortunately, the bees' decline does not have a single answer. They are dying regardless of how infected or poisoned by insecticides they are. But what about environmental stresses? Let's observe CDD from a geospatial perspective.

## Where are the bees dying? A US Case study
#### Death, the American way

We investigate the death-rate of colonies across the US, hoping to find clues as to where colonies mostly die. 

To do this, we use the data from Bee Informed Partnership (BIP) for the years 2010-2016.

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="500" allowfullscreen="true" src="https://indigo-vanguard.github.io/plot/yearly_loss_of_colonies_percent.html"></iframe>

Clearly, in terms of the average death rate, all states are roughly equal: **Every year, roughly half of the bee population is decimated**, be it in California or Minnesota. But what about the raw counts? 

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="500" allowfullscreen="true" src="https://indigo-vanguard.github.io/plot/yearly_loss_of_colonies_unit.html"></iframe>

We notice something interesting: **California, Texas and North-Dakota experience much more collapsed colonies**. What makes those states so special?

<div class="withSidenote" markdown="1">
The fact is that beekeepers rely less and less on honey making, and more and more on **migratory beekeeping**. It represents now up to **50% of their revenue**. They pack their hives in boxes, mount them on trucks and scout the US throughout the year to pollinize fields, amongst which[^6]:

- **Almonds** in **California** (February)
- **Alfalfa**, **clover** and **sunflowers** in **North Dakota** (June / July) (Picture of the side with caption "For the uninitiated" )
- **Pumpkins** in **Texas** (October)

<figure class="sidenote">
    <img src="https://indigo-vanguard.github.io/img/alfalalafa.jpg">
    <figcaption>Figure 2. We bet you didn't know about Alfalfa, because we didn't 😋</figcaption>
</figure>
</div>
This migratory beekeeping explains the high death-count: the colonies die in _those_ places, because that's where they spend most of their life.

This way of renting out hives and transporting them across an entire continent incurs high stresses on the bees, weakening them and exposing them to environmental parameters they are not used to. Additionally, now that bees can travel throughout the entire USA, their pest can as well. This is exactly how the Varroa Destructor came to the USA/Europe in the first place, emigrating from Asia in the 70's[^7].

The main event of this migratory beekeeping is the blooming of California's almond orchards in February, gathering 31 billion honeybees within one single state[^6].

## The life of an American bee in February
#### An almond love story

Strapped on lorries, more than a million hives arrive in California around Valentine's day. Their little dwellers will work hard for the next few weeks in the hundred of thousands of hectares of almond orchard in Central Valley. Buzzing from flower to flower, they play an essential role in pollinating the almond trees, while gathering pollen to feed the colony after a harsh winter. Those orchards produce about 80% of the world almonds and it's one of the main crop grown in the state[^8]. The work of the honeybees in the field bring back the beekeepers **250 to 290 millions dollars** anually. But since the bees are dying, how does this impact the almond production ?

\Plot almond production

First, we can see that the bearing area is strictly increasing. This reinforce the idea that the industry has become more and more popular (and lucrative). Yet, 


## Bees-ness
#### World-wide honey trade

Often consumed locally, honey has become a raw material exported throughout the world.
A trend has emerged in recent years: countries that were able to produce enough honey for their own consumption can no longer do so.

The unit of measurement we use for import and export is the tonne of honey.

Let the total amount of available honey in a country (Honey Capacity) be the the sum between its honey production and its imported honey. 

To compare multiple countries, we will compute their import and their export ratios.

We observed 3 different kind of countries:
- The countries which **export** the greater part of their honey production (Argentina)
- The countries which **import** the greater part of their honey (United Kingdom, Japan)
- The countries which **use** the greater part of their honey (China)

We observe that the world is split between honey producers and consumers. Western countries seem to have had production issues in the last decades while other countries became big exporters.

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="500" allowfullscreen="true" src="https://indigo-vanguard.github.io/exportations_graph/main/html/honey_graph.html"></iframe>

Click on countries in order to see important links between them through years.

We observed the same phenomenon mentioned above, namely the emergence of major exporters (India, Ukraine) but also the ever-increasing dependence of Western countries (France, United States) on these exporters.


## Productivity of beehives
#### How do countries exploit their beehives?

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="650" src="https://indigo-vanguard.github.io/plot/scatterplot_beehives_production.html"></iframe>

Studies show that the average beehive produces from 10 to 40 kg of honey annually[^9] [^10]. The above scatter plot shows, using the [Food and Agriculture Organization](http://www.fao.org/faostat/en/)'s data sets, how the honey production behaves against the number of beehives per country. The green zone shows the aforementioned average zone of production. We see that a few countries, e.g. India, are well under the average production. Indeed, different types of honey bees exist, and they do not have the same rate of production [^10]. Most other countries, like France or the USA, seem to behave according to the average. However, we note that some countries (Ukraine, Latvia, Belarus, Rwanda, etc.) are way off, and show impossible production rates. We notice that 3 of them were in the USSR and show these counts since their independence in 1991 (they appear in 1992 in the graph). This can be explained by either dubious internal counts, non official data, or adulterated honey (with e.g. syrup). China shows another interesting behavior. It starts in 1990 by being well into the average zone, but then slowly climbs out of it. It now has an abnormal production rate. Something fishy is happening here... Is that happening in other countries?

\Heatmap world



## Conclusion
#### Support your local beekeepers!


## References

[^1]: [Greenpeace, *Bees in Decline*, 2013](http://sos-bees.org/wp-content/uploads/2014/04/BeesInDecline.pdf)

[^2]: [The Balance, _Colony Collapse Disorder and Its Impact on the Economy_, 2019](https://www.thebalance.com/bee-colony-collapse-disorder-facts-and-economic-impact-3305815)

[^3]: [YaleEnvironment360, _Declining Bee Populations Pose a Threat to Global Agriculture_, 2013](https://e360.yale.edu/features/declining_bee_populations_pose_a_threat_to_global_agriculture)

[^4]: [Vice, _What Would Happen if All the Bees Went Extinct?_, 2017](https://www.vice.com/en_us/article/d7ezaq/what-would-happen-if-all-the-bees-died-tomorrow)

[^5]: [Congressional Research Service, _Bee Health: Background and Issues for Congress_, 2015](http://www.fas.org/sgp/crs/misc/R43191.pdf)

[^6]: [Scientific American, _The Mind-Boggling Math of Migratory Beekeeping_, 2013](https://www.scientificamerican.com/article/migratory-beekeeping-mind-boggling-math/)

[^7]: [Vatorex, _Varroa? No problem – Meet the Asian honeybee_, 2019](https://www.vatorex.ch/en/varroa-no-problem-meet-the-asian-honeybee/)

[^8]: [Almond Board of California, _Almond Almanac_, 2018](http://www.almonds.com/sites/default/files/Almond_Almanac_2018_F_revised.pdf)

[^9]: [Kim Flottum, U.S. Honey Industry Report – 2017, 2018](https://www.beeculture.com/u-s-honey-industry-report-2017/)

[^10]: [TNAU Agritech, Types of Honey Bee](http://agritech.tnau.ac.in/farm_enterprises/fe_api_typesofhoneybee.html)