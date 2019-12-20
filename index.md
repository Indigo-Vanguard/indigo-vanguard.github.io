---
layout: page
title: There is No Plan Bee Without Them
bigimg: img/bigbee.jpg
---
## Bees are dying
#### What's up with that?

For 20 years, bees have been dying all over the world at an alarming rate: **half of the colonies do not make it through the year**[^1] [^2]. Entire hives are being deserted by their worker bees, leaving behind a lonely queen and plenty of food. Those same bees are vital to our agriculture and responsible for pollinating a third of our food[^3]. Without them, the human race would last less than 5 years[^4]. This mass extinction is known as **Colony Collapse Disorder (CCD)** and threatens our entire way of life, as well as theirs. Many factors are thought to be responsible for the bees' decline, among which pests, insecticides and other environmental stresses[^5].

In this data story, we explore the death of bees, observe their impact on the world economy and bring to light the dirty tricks of the honey trade.


## Can we find a single culprit for this collapse?
#### (We can't)

First of all, experts claim that those deaths can't be explained by a single cause. Are all the experts wrong? Have they overlooked an obvious correlation fully explaining the bees' death? <span class="spoiler">(Spoiler: They haven't)</span>

<div class="withSidenote" markdown="1">

We investigate here two widely agreed upon causes of CCD: pests and insecticides.

One of those pests -- the (charmingly named) **Varroa destructor** -- is a parasite smaller than the bee that attaches itself on the bee's body. It spreads throughout the colonies and leads to infections, killing the bees. Hence, we also isolate the influence of the Varroa infestation on the death rate of colonies.

<figure class="sidenote">
    <img src="img/varroa_annotated.png">
    <figcaption><em>Figure 1.</em> The Varroa destructor in action.</figcaption>
</figure>
</div>

To do this, we gather [Varroa infestation data](https://quickstats.nass.usda.gov/results/23E6C5E2-4F53-39C6-91FA-F9878CB8F444) and [pesticide contamination data](https://quickstats.nass.usda.gov/results/E86E00EE-2910-373B-B378-B0AC78EDC0B3) from the **National Agricultural Statistics Service (USDA)**  which we compare with the colony losses across the US, obtained through the [**Bee Informed Partnership (BIP)**](https://beeinformed.org), a US-wide collaboration of leading research labs and universities in agricultural science.

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="550" src="plot/scatterplot_lack_of_correlation.html"></iframe>

Unfortunately, the lack of correlation shows that the bees' decline does not have a single answer. Even a combination of those factors doesn't suffice at explaining some catastrophical cases of CCD. They are dying regardless of how infected or poisoned by insecticides they are. But what about environmental stresses? Let's observe CCD from a geospatial perspective to explore this last important factor.

## Where are the bees dying? A US Case study
#### Death, the American way

We investigate the death-rate of colonies across the US, hoping to find clues as to where colonies mostly die. To do this, we use the data from Bee Informed Partnership (BIP) for the years 2010-2016.

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="500" src="plot/yearly_loss_of_colonies_percent.html"></iframe>

Clearly, in terms of the average death rate, all states are roughly equal: it's a nation-wide problem. **Every year, roughly half of the bee population is decimated**, be it in California or Minnesota. But each state doesn't have the same bee population so what about the raw counts?

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="500" allowfullscreen="true" src="plot/yearly_loss_of_colonies_unit.html"></iframe>

We notice something interesting: **California, Texas and North-Dakota experience much more collapsed colonies**. What makes those states so special?

<div class="withSidenote" markdown="1">

The fact is that beekeepers rely less on honey making, and more on **migratory beekeeping**. It represents now up to **50% of their revenue**. They pack their hives, mount them on trucks and scout the US throughout the year to pollinize fields, among which[^6]:

- **Almonds** in **California** (February)
- **Alfalfa**, **clover** and **sunflowers** in **North Dakota** (June / July)
- **Pumpkins** in **Texas** (October)

<figure class="sidenote">
    <img src="img/alfalalafa.jpg">
    <figcaption><em>Figure 2.</em> For the uninitiated: we bet you didn't know about Alfalfa, because we didn't.</figcaption>
</figure>
</div>

This migratory beekeeping explains the high death-count: the colonies die in _those_ places, because that's where they spend most of their life.

This way of renting out hives and transporting them across an entire continent incurs high stresses on the bees, weakening them and exposing them to environmental parameters they are not used to. Additionally, now that bees can travel throughout the entire USA, their pest can as well. This is exactly how the Varroa Destructor came to the USA/Europe in the first place, emigrating from Asia in the 70's[^7].

The main event of this migratory beekeeping is the blooming of California's almond orchards in February, gathering 31 billion honeybees within one single state[^6].

## The life of an American bee in February
#### An almond love story

Strapped on lorries, more than a million hives arrive in California around Valentine's day. Their little dwellers will work hard for the next few weeks in the hundred of thousands of hectares of almond orchards in Central Valley. Buzzing from flower to flower, they play an essential role in pollinating the almond trees. Those orchards produce about 80% of the world almonds and it's one of the main crop grown in the state[^almond_almanac]. The work of the honeybees in the field bring back the beekeepers **250 to 290 millions dollars** annually. But since we have shown that bees are dying *en masse*, how does this impact the almond production using [data](https://quickstats.nass.usda.gov/results/2373C039-2CFF-3744-A554-328E6A79BD39) from the USDA?

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="500" src="plot/california_almond.html"></iframe>

First, we can see that the bearing area is strictly increasing. This reinforces the idea that the industry has become more and more popular (and lucrative). Yet, the almond production doesn't always follow the trend. What's happening in those years? Are almond trees suddenly extremely unproductive or does this show environmental problems?

>California almond growers are once again being stung by a shortage of honeybees[^lack_bee]. _Los Angeles Times_, 2005

The first **plateau from 2002-2005** is then due mostly to a lack of pollinators. The beekeeping community was overwhelmed and not all almond growers could find bees to work in their fields. As the demand was high, this made the price of pollinators skyrocket. Many unconvinced beekeepers jumped on the migratory beekeeping train and new honeybee management practices were introduced[^bee_practice].

Problem solved, right? Not really, the production **dropped again in 2009** and has not been faring so well between **2011-2015**. Are the bees to blame _again_?! It turns out that weather is the main culprit this time. California was especially exposed to drought and there are many report of almond growers not being able to irrigate their orchards[^drought].

As the state will surely experience more frequent and severe droughts, there will be an impact on the almond agriculture. Almond growers need to continue working hand-in-hand with the beekeeping community and run experiments on new varieties of more resistant, less water-consuming trees to ensure its perennity[^almond_almanac].

## Bees-ness
#### World-wide honey trade

Let's now focus on the other main revenue of a beekeeper: **honey**. Often consumed locally, honey has become a raw material exported throughout the world. But how is this precious resource exported and imported around the globe? We give a look at honey trade using [data](http://www.fao.org/faostat/en/#data/TM) from the **Food and Agriculture organization of the United Nations (FAO)**.

<figure>
    <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="550" allowfullscreen="true" src="exportations_graph/main/html/honey_graph.html"></iframe>
    <figcaption>Click on countries in order to see important links between them through years.</figcaption>
</figure>

By toggling between the imports and exports we can identify a first trend. There are countries that **export a lot**: China, Argentina, Ukraine and India and those that **import a lot**: USA, Germany, Japan. Can we find a way to cluster the countries? To do so we devise a new value called the **Honey Capacity** by letting it be the total amount of available honey in a country. For each nation, the capacity is computed as the _sum between its honey production and its imported honey_. In order to compare the countries, we also compute their **import** and **export ratios with respect to their capacity**.

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="620" src="plot/beezness_plot.html"></iframe>

At the end of the animation, we can actually observe not 2 but 3 different clusters of countries:
- The countries which **export** the greater part of their honey production (such as Argentina and Ukraine)
- The countries which **import** the greater part of their honey (such as the United Kingdom, the USA and Japan)
- The countries which **use** the greater part of their honey (such as China)

This leads us to observe that the world is split between honey producers and consumers. Western countries seem to have production issues in the last decades while other countries became big exporters. This clear trend has emerged during the animation: developed countries that were able to **produce enough honey** for their own consumption **can no longer do so** and have to rely on other nations to satisfy their local demand.

## Shedding the light on dirty honey tricks
#### On the (hyper-)productivity of beehives

With such a juicy market at hand, are all countries playing fair and square or are some squeezing more out of their beehives and trading partners than they should? In order to check that we look at the production of honey using [data](http://www.fao.org/faostat/en/) from the FAO. As studies show, the **average beehive produces from 10 to 40 kg of honey annually**[^9] and this plausible range is represented in green.

<figure>
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="650" src="plot/scatterplot_beehives_production.html"></iframe>
    <figcaption>Some data points are bigger to highlight their behavior: China, India, the USA, France and Switzerland.</figcaption>
</figure>

<div class="withSidenote" markdown="1">

We see that a few countries, e.g. India, are well under the average production. Indeed, India has its own kind of honeybee (the _Apis Cerana Indica_), and they do not have the same rate of production[^10]. Most other countries, like France, Switzerland or the USA, seem to have a plausible honey production. However, we note that some countries (Ukraine, Latvia, Belarus, Rwanda, etc.) are way off, and show impossible production rates. We notice that three of them were in the USSR and show these counts since their independence in 1991 (they appear in 1992 in the graph). This behavior can be explained by either dubious internal counts or non-official/missing data, especially for African countries[^africa_no_data].

<figure class="sidenote">
    <img src="img/apiscerana.jpg">
    <figcaption><em>Figure 3.</em> A less fluffy and smaller version of the European honneybee, the <em>Apis Cerana Indica</em> lives in colonies of a few thousands workers compared to the average fifty thousand for <em>Apis Mellifera</em></figcaption>
</figure>
</div>

But we are still missing the elephant in the room. **China shows a strange behavior**. It starts in 1990 by being well into the plausible zone, but then slowly climbs out of it. From 2005 to 2017, the number of **beehives only increased by 10%**, whereas its **honey production jumped by more than 80%**. Something fishy is happening here... Is this _hyper_-productivity phenomenon happening in other countries as well?

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="650" src="plot/honey_productivity.html"></iframe>

<div class="withSidenote" markdown="1">

Two bright red dots appear since the beginning of the animation, in Canada and Australia. At first, we were wondering if beekeepers were feeding Maple syrup and Vegemite, respectively, to their bees to increase their productivity. It turns out that the wide meadows and longer days allow for more productive foraging and a higher yield[^beekeeping_canada].

<figure class="sidenote">
    <img src="img/vegemite.jpg">
    <figcaption><em>Figure 4.</em> Vegemite is an Australian delicacy comparable to our Cenovis. If you haven't had one of them yet, give it a try.</figcaption>
</figure>
</div>

So let's focus on what is going on in Asia. As we mentioned, their productivity boomed in the recent years to fill in the gap left by other bees around the developed world. But is it really possible to increase the productivity to this extent or did we uncover something? **Honey adulteration** is an old tale finding its root in the 70's. During the 21<sup>st</sup> century, this is has become a main concern as more than a quarter of the world honey is of questionable authenticity, rising up to 50% for Asian honey[^adulterated_honey]. The main practice consists of **cutting honey with cheap high-fructose syrup**. It is a constant struggle for food administrations as it is not only hard but expensive to detect. This lead to recent temporary bans and tariffs from the EU and the USA[^fake_honey]. But Chinese honey smugglers always found ways to flood the market with cheap, adulterated honey **using neighboring countries as proxies**.

## Don't support Winnie the Pooh[^winnie_pooh]
#### Help your local beekeepers!

As greedy industrials with no concerns for the economy keep dumping adulterated honey on the market, local beekeepers struggle to keep up[^honeygate]. Juggling with **dying bees**, **mite infections**, **unfair competition** and **migratory beekeeping** to survive, we think a way to help is to **support your local beekepers**. By buying local, you provide them the means to face those adversities and anyway you eat enough adulterated honey in processed food products.

<figure>
    <img src="img/Bee-hiding.jpg">
    <figcaption>My people need you: support me <a href="https://freethebees.ch/en/">@FREETHEBEES</a>, a Swiss charity fighting for sustainable honey culture.<br />Thank you for your engagement!</figcaption>
</figure>

## References

[^1]: [Greenpeace, *Bees in Decline*, 2013](http://sos-bees.org/wp-content/uploads/2014/04/BeesInDecline.pdf)

[^2]: [The Balance, _Colony Collapse Disorder and Its Impact on the Economy_, 2019](https://www.thebalance.com/bee-colony-collapse-disorder-facts-and-economic-impact-3305815)

[^3]: [YaleEnvironment360, _Declining Bee Populations Pose a Threat to Global Agriculture_, 2013](https://e360.yale.edu/features/declining_bee_populations_pose_a_threat_to_global_agriculture)

[^4]: [Vice, _What Would Happen if All the Bees Went Extinct?_, 2017](https://www.vice.com/en_us/article/d7ezaq/what-would-happen-if-all-the-bees-died-tomorrow)

[^5]: [Congressional Research Service, _Bee Health: Background and Issues for Congress_, 2015](http://www.fas.org/sgp/crs/misc/R43191.pdf)

[^6]: [Scientific American, _The Mind-Boggling Math of Migratory Beekeeping_, 2013](https://www.scientificamerican.com/article/migratory-beekeeping-mind-boggling-math/)

[^7]: [Vatorex, _Varroa? No problem – Meet the Asian honeybee_, 2019](https://www.vatorex.ch/en/varroa-no-problem-meet-the-asian-honeybee/)

[^almond_almanac]: [Almond Board of California, _Almond Almanac_, 2018](http://www.almonds.com/sites/default/files/Almond_Almanac_2018_F_revised.pdf)

[^9]: [Kim Flottum, _U.S. Honey Industry Report 2017_, 2018](https://www.beeculture.com/u-s-honey-industry-report-2017/)

[^10]: [TNAU Agritech, _Types of Honey Bee_, 2014](http://agritech.tnau.ac.in/farm_enterprises/fe_api_typesofhoneybee.html)

[^lack_bee]: [Los Angeles Time, _For Almond Growers, Honeybee Shortage Is a Hard Nut to Crack_, 2005](https://www.latimes.com/archives/la-xpm-2005-may-07-fi-almonds7-story.html)

[^bee_practice]: [California Almond Board, _Honey Bee best Management Practices_, 2014](http://www.almonds.com/pollination)

[^drought]: [Growing Produce, _Impacts Of Drought On Almond Production_, 2014](https://www.growingproduce.com/fruits/impacts-of-drought-on-almond-production/)

[^beekeeping_canada]: [Apimondia, _beekeeping in Canada_, 2019](https://www.apimondia2019.com/beekeeping-in-canada/)

[^fake_honey]: [Forbes, _Honey Is World's Third Most Faked Food_, 2016](https://www.forbes.com/sites/larryolmsted/2016/07/15/exclusive-book-excerpt-honey-is-worlds-third-most-faked-food/#432d1244f095)

[^adulterated_honey]: [Nature, _Authenticity and geographic origin of global honeys determined using carbon isotope ratios and trace elements_, 2018](https://www.nature.com/articles/s41598-018-32764-w)

[^winnie_pooh]: [CSB News, _Winnie the Pooh censored in China after President Xi Jinping comparisons_, 2017](https://www.cbsnews.com/news/winnie-the-pooh-censored-china-president-xi-jinping-comparisons/)

[^africa_no_data]: [FAO, _Methodology of Crops data_, 2019](http://fenixservices.fao.org/faostat/static/documents/QA/QL_methodology_e.pdf)

[^honeygate]: [Reuters, _U.S. charges five in 'Honeygate' anti-dumping probe_, 2013](https://www.reuters.com/article/usa-china-honey/u-s-charges-five-in-honeygate-anti-dumping-probe-idUSL1N0BKCRX20130220)
