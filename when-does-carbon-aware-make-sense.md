# When does carbon-aware software make sense?

Let’s be absolutely clear on the answer to the question “is carbon-aware computing just bad?” No. We don’t intend to bash the core concepts of carbon-aware software. 

The core concept that shifting compute jobs to respond to the electricity available is sound.

**The criticism, however, is that current approaches never mention that "terms and conditions apply".**

There is no real acknowledgement of the nuances of how balancing electricity supply and demand works in practice. We fail to mention that the current patterns are only helpful in certain circumstances, futile in most, and seriously harmful in others. It seems the uncomfortable outcome is all this effort hampes tech’s sustainability efforts as we try to help them. 

Most crucially we see don’t carbon-aware software meaningfully addressing the elephant in the room. **It is simply not possible to optimise our way to the reductions needed in the tech sector, whilst tech’s overall energy and resource demands grow rampantly.**
The damage of runaway climate change to populations around the world demands that we do better, and we believe the tech sector is <a href="https://rtl.chrisadams.me.uk/2023/07/comparing-what-is-spent-on-share-buybacks-vs-the-cost-of-decarbonising-the-grid/">well resourced enough to tackle this in a meaningful way</a>.


## What are the “terms and conditions” that need to be applied?

There are two ways in which we think the logic of the carbon-aware approach holds true.

**Way 1:** Time-shifting or location-shifting compute to when demand is naturally low and then using electricity that would otherwise be curtailed.

**Way 2:** When jobs run on electricity that is additive to the grid.

Don't just take our word for these two. The shortest, clearest authoritative summary on this is from a <a href="https://www.whitehouse.gov/wp-content/uploads/2022/09/09-2022-Crypto-Assets-and-Climate-Report.pdf">White House investigation into crypto mining</a> (see page 24). The useful part says:

> "There are two primary ways.... using grid electricity would result in zero direct GHG emissions:
>
> 1) constructing or contracting for new clean electricity sources or
> 
> 2) using existing renewable electricity that would otherwise be curtailed by the grid.
>
> When... electricity [comes] from existing renewable sources, it displaces the GHG emissions in the near-term, shifting users of renewable sources to fossil fuel sources. This is because coal and natural gas often supply electricity generation for each additional unit of electricity demanded in the United States. As the amount of renewable sources is held constant, but electricity demand increases, additional fossil power will likely be dispatched. This displacement results in no net change or in increases in total global emissions through a process called leakage.”

We get into these two ways in the sections below, before discussing the elephant in the room - the net increases in resources demanded by the tech sector - which leads us to conclude with way three.

### Way 1: Run compute when demand is low, using curtailed electricity in stable grids

> **TL;DR:** The refinement to current carbon-aware time-shifting or location-shifting approaches we propose is to prioritise demand intensity first and carbon intensity second. We need to do this in collaboration with one another and local grid systems.

Scheduling compute to run at already predicted low demand times contrasts to the current approach of dynamically time-shifting to periods of high renewables/low carbon intensity, which fluctuates day-to-day and is hard to forecast. If we time-shift compute within our own grids based on grid demand in a highly predictable, stable fashion we don’t create unpredictable daily spikes.

This sounds simple for routine jobs. As a concept perhaps it is. But that doesn’t mean it isn’t a valuable contribution.

And for compute that’s more spontaneous? There’s some good demand-focused tweaks available here too.

Our beneficial impact can be even greater if running compute can play a part in helping the grid to avoid ramp-ups/downs. Going up or down can inflate carbon emissions, as we explored earlier. Ramping down also typically involves curtailing electricity, which is essentially wasting electricity. Getting compute to make use of that, regardless of the carbon intensity at the time, is an approach worth working on.

We think an alternative version of location-shifting, that factors in demand, could also be helpful. What if we first looked for grids that currently have low demand AND then sought those with a period of naturally high renewable electricity production? This contrasts to the current carbon-aware location-shifting approach that just looks at electricity carbon intensity.

In our proposed way we might look for places with low demand, let’s say between 2am and 4am, with high winds in a grid that does a solid job of harnessing wind energy. If that grid were unable to make use of all that wind and had to curtail it, our compute could use it for something productive.

The above has merit when happening at a relatively small scale. But if everyone does this at the same time? Then we *still* have the problem of creating demand spikes, one our core worries about the current approaches. 

So, let’s take the approach even further. Let’s get our compute jobs to interface with grids that need to use some electricity that would otherwise be curtailed, and get a handshake saying we can use it. If that grid can’t handle our needs we look for another that can.

And if no grid meets our criteria? *We wait*. We wait until we find one that does.

This implies a shift in mindset for those wanting the results of the compute, be it in a corporate or domestic setting. Waiting patiently until the conditions are right, rather than expecting results immediately. There’s a lot of compute that needs immediate response, like visiting a web page. But there’s also plenty that is not time sensitive, like complex algorithmic analysis for research.

By interacting with grid management systems, ideally in an automated, collaborative, and democratic way, we can identify times that assist with managing the grid, rather than placing additional burdens on it.
Democratic here is key as well.

This can’t just be the realm of the Big Tech players. We all need a chance to participate through open source standards and protocols. By doing so, we can actually prevent fossil fuels from being used, further reducing net emissions – a win/win across the board. We discuss these ideas further in way 3.

### Way 2: Run compute on additive renewable energy

> *TL;DR:* To be in any way effective, computing must target green energy sources that are in fact additive, and transparently address and mitigate the risks of perverse effects.

> ## Quick reference – Additive renewable energy 
>
> “Additive” or “additional” renewable electricity means your purchase is financing new renewable electricity that would otherwise not exist. Related is applying the principle of "<a href="https://www.electricitymaps.com/blog/what-is-additionality-and-emissionality">additionality</a>" to renewable energy generation, particularly in <a href="https://en.wikipedia.org/wiki/Carbon_emission_trading">carbon markets</a>. 
>
> If your compute consume 50 terawatts of electricity and you pay for new solar panels that generate 50 terawatts of electricity, you achieve additionality. You can claim, in theory, that your compute is emissions neutral. In practice <a href="https://kvenkatm.medium.com/we-need-a-better-way-of-purchasing-and-accounting-for-renewable-electricity-34c0ee66070e">it’s less clear-cut</a>, but this is the general idea.
>
> Traditional carbon markets often sell ‘carbon credits’ based on already existing renewable electricity. In this scenario there is no additionality. You are merely claiming the existing renewable energy production as yours and giving responsibility for the existing dirty energy production to someone else. This is not reducing emissions at all. 
 
There are two common ways running compute on additive renewable energy can be achieved. 

#### Power Purchase Agreements (PPAs) and Renewable Energy Certificates (RECs)

The primary way that many organisations tackle this is through <a href="https://en.wikipedia.org/wiki/Carbon_emission_trading">carbon markets</a>. These in turn sell two main instruments:  <a href="https://en.wikipedia.org/wiki/Renewable_Energy_Certificate_(United_States)">Renewable Energy Certificates</a> (RECs) and <a href="https://en.wikipedia.org/wiki/Power_purchase_agreement">Power Purchase Agreements</a> (PPAs). 

This remains a highly problematic approach. Why? Because <a href="https://www.spglobal.com/esg/insights/problematic-corporate-purchases-of-clean-energy-credits-threaten-net-zero-goals">the vast majority of RECs are non-additive</a>. 

They enable you to buy into the existing green energy mix, and simply take credit for their contribution. But you have zero effect on what’s called ‘**emissionality**’, which has similarities to the **displacement effect**. 

> ## Quick reference – Emissionality
>
> New renewable energy projects don’t always pull emissions out of the atmosphere. The reason they help is because they **displace fossil fuel power plants** that would otherwise keep polluting.
>
> But which projects are effective? That can vary greatly from project-to-project as well as the fuel-mix of the grid to which the project will be connected. For example, adding one more solar power purchase agreement (PPA) in California increasingly reduces output from a mix of natural gas plants and existing solar farms. But adding a new wind PPA in Wyoming nearly always reduces output at a coal plant, avoiding more emissions. This practice of comparing and acting on the avoided emissions of different renewable energy projects is called “emissionality.”
> 
> You can <a href="https://www.watttime.org/solutions/renewable-energy-siting-emissionality/">read more on this by WattTime</a>, who popularised the emissionality term.

PPAs are commonly employed throughout the business world, especially by <a href="https://www.datacenterdynamics.com/en/opinions/ppa-evolution-in-the-data-center-industry/">data centres</a>. Corporate purchasers make agreements with energy companies promising to purchase the power and RECs generated by the renewable project for a specific time period, often the next 10-15 years. 

While PPAs are often touted as a critical mechanism responsible for a company’s green credentials and central to its <a href="https://en.wikipedia.org/wiki/Environmental,_social,_and_corporate_governance">ESG strategy</a>, they can be misleading. Even if PPAs are attributed to particular renewable projects, <a href="https://www.datacenterdynamics.com/en/analysis/everything-data-center-operators-need-to-know-about-power-purchase-agreements-ppas/">they do not generally directly power data centres</a>. In other words, just because green electrons are being produced, does not mean those electrons are directly powering the compute within a data centre – despite often being <a href="https://www.electricitymaps.com/blog/green-electricity-contracts">touted as so</a>. There is also the risk of <a href="https://www.epa.gov/green-power-markets/double-counting">double counting</a>.

Therefore the best implementation of carbon markets involves ensuring that the renewable energy you purchase is *additive*.

### Your own renewable sources

A second, much rarer version of additionality - yet far more effective. 

Instead of purchasing some remote renewable infrastructure and “accounting” your claim to being powered by renewables, **actually** power your compute directly from your own renewable sources.

If your compute is being directly powered by your own solar panels or wind turbines etc., there is no sleight of hand or complex statistical projections. Your compute is effectively off grid to the extent that it is directly powered by your own renewable sources.

While preferable in terms of emissions, this approach is challenging to scale and risks perverse effects as get into below. 

### Innovation with distributed alternatives
As a complement to this section, it’s worth mentioning there’s room to innovate with distributed alternatives. Distributed compute and renewable electricity generation.

Hyperscale computing today is highly centralised in massive data centres. To power such enormous compute directly requires renewable generation facilities taking up massive amounts of land and water, around already huge data centre land occupation. While this can genuinely reduce compute emissions from hyperscalers, there are usually wider environmental, social and economic impacts, aside from the logistics involved. 

As an example, one such project is <a href="https://www.datacenterdynamics.com/en/news/230-million-solar-powered-data-center-planned-in-aragon-spain/">underway in Zaragoza, Spain</a>. A 40,000 square metres data centre will be supplied by two solar farms. Just one of these two solar farms, accounting for 90MW,  will span <a href="https://www.boe.es/diario_boe/txt.php?id=BOE-A-2023-1169">232 gross hectares</a> (2.3m square metres). This is roughly the size of Central Park in New York. It will take up land rich in biodiversity, which, provisions notwithstanding, it seems set to damage, including endangered species of both animals and trees.

And one more, the recent data centre built by Google in Chile is double the size, <a href="https://www.ciperchile.cl/2020/05/25/las-zonas-oscuras-de-la-evaluacion-ambiental-que-autorizo-a-ciegas-el-megaproyecto-de-google-en-cerrillos/">extracting 169 litres of water/second in the local area</a> and would thus require close to 10 million square metres to be powered directly by solar.

Local populations are already feeling the impact from the huge expansion of data centres. There’s a movement forming calling for a <a href="https://techmonitor.ai/technology/cloud/inside-the-data-centre-moratorium-movement">moratorium on data centre construction</a>. It’s happening globally – in <a href="https://www.rte.ie/news/dublin/2022/0110/1272869-eirgrid-datacentres-dublin/">Ireland</a>, <A href="https://www.washingtonpost.com/climate-environment/2022/05/28/meta-data-center-zeewolde-netherlands/">The Netherlands</a>, and <a href="https://www.itpro.com/server-storage/data-centres/367441/why-singapore-stopped-building-data-centres">Singapore</a>. The resistance is not just around electricity consumption. <a href="https://blogs.lse.ac.uk/medialse/2022/11/02/big-techs-new-headache-data-centre-activism-flourishes-across-the-world/">Water use is a huge issue too</a>. Local populations in <a href="https://www.abqjournal.com/news/local/facebook-data-center-water-use-scrutinized/article_521c48ac-c971-577c-bed2-3b0c7df4b0cc.html">New Mexico, USA</a>, <a href="https://www.theguardian.com/world/2023/jul/11/uruguay-drought-water-google-data-center">Uruguay</a>, and <a href="https://www.ciperchile.cl/2020/05/25/las-zonas-oscuras-de-la-evaluacion-ambiental-que-autorizo-a-ciegas-el-megaproyecto-de-google-en-cerrillos/">Chile</a> continue to be at the forefront of the struggle over resource use.

**However, hyperscale is not the only model, and it doesn’t have to be the inevitable future**. Most computing today is highly distributed or distributable. There are <a href="http://arxiv.org/abs/2207.02428">experiments with co-location of compute</a> (crypto-currency specifically) where renewable generation already exists. This ensures direct power for compute using renewable energy, and plays a role in renewable electricity demand management. This too has the risk for perverse incentives effects. But with the right guardrails could be a significant paradigm to expand and explore.

Finally mainstream electricity generation tends to be concentrated in massive power plants. Renewable electricity infrastructure makes distributed energy generation possible. Instead of electricity being generated in a few massive central nodes, significant amounts could be generated in a large number of widely distributed, smaller nodes and <a href="https://www.sciencedirect.com/science/article/pii/S136403211830128X#bbib113">microgrids</a>. 

The idea of <a href="https://www.researchgate.net/profile/Anaza-Sikiru-2/publication/368472105_Potential_of_Renewable_Energy_Sources_for_Distributed_Generations_An_Overview/links/63efa2f919130a1a4a896a9c/Potential-of-Renewable-Energy-Sources-for-Distributed-Generations-An-Overview.pdf">matching distributed renewable energy generation</a> with distributed computing <a href="https://doi.org/10.1093/jcde/qwac087">has been floated</a> and holds promise. This not only allows the off-grid powering of compute, but also expands the possibilities of dual use. For example distributed data centre servers can be used <a href="https://energycentral.com/system/files/ece/nodes/418708/200424_sdia_report_utility_full-final.pdf">simultaneously for compute and for heating</a>, reducing the energy currently spent for indoor heating.

## Addressing the elephant in the room

And lastly, the above two ways don’t stand to gain us much if we are not also tackling the big question: **how much of the world’s resources is it acceptable for tech to use?**

There is a danger that the key takeaway from scenarios 1 and 2, is that if we build and use electricity and data centres more innovatively, we can safely continue with business as usual. We can build massive AI products, keep growing our data centres and enjoy the benefits of limitless personal compute potential.

It cannot be understated that one of the biggest shifts required to reduce carbon emissions in line with the <a href="https://en.wikipedia.org/wiki/Paris_Agreement">Paris Agreement</a> is to accept that we cannot continue to grow everything without some limitations. At least not in the short-term whilst we wildly exceed the world’s carbon budgets and need to drastically reduce our emissions. 

### Way 3: Demand shaping computing electricity use so it stays within agreed resource use boundaries

> **TL;DR:** The core question that should be on all responsible technologists’ minds: is my compute’s net electricity demand reducing?  Data centres should interact with grids and seek assent to use electricity or other resources in a dynamic way, against a specific resource budget. 

#### The global emissions picture

As a digital tech industry level, we need to accept there should be limits to the amount of resources consumed. To achieve this we have to look at and restrict the growth of computing. Many would argue this is where the real, impactful work lies.

> “The current emissions from computing are about 2% of the world total but are projected to rise steeply over the next two decades. By 2040 emissions from computing alone will be more than half the emissions level acceptable to keep global warming below 1.5°C. This growth in computing emissions is unsustainable: it would make it virtually impossible to meet the emissions warming limit. Plus, the emissions from the production of computing devices far exceed the emissions from operating them. So, even if software is more energy efficient, producing more of them will make the emissions problem worse.” 
>
> <a href="https://www.dcs.gla.ac.uk/~wim//low-carbon-computing/index.html">Low carbon and sustainable computing</a>, by Professor Wim Vanderbauwhede

<a href="https://docs.google.com/spreadsheets/d/e/2PACX-1vSd8nYugza3UjPaG8Y6DP8Fufq4JxWDDn8cdSQXq7KyfeXkbLvc3XC9uDxyXr5dkA/pubhtml">Two models created for this article by Professor Vanderbauwhede</a> show that the real problem our planet faces is not how we optimise our compute via patterns like carbon-aware compute, but how we change the alarming growth trend in computing driven electricity demand. 

The first model shows that because carbon-aware computing does not assume energy demand reduction, only greener compute whatever the demand, it will hardly slow down our race to <a href="https://en.wikipedia.org/wiki/Tipping_points_in_the_climate_system">planetary tipping points</a>.

Business as usual results in a 3 times increase in emissions by 2040 - most of the planet's carbon budget. With the adjustments to carbon-aware computing in scenarios 1 and 2, it will be 2.8 times. That 0.2 factor does matter. Every single reduction counts and buys us days, months, years before irreversible milestones. But it is hardly the solution. 

The second model shows that specifically the reductions from location shifting are very modest. Even if there were no issues with demand, capacity and curtailment, realistic scenarios give around 3% reductions in emissions generated by computing electricity use. This is because of the overhead in location shifting and the embodied carbon of the required excess capacity.

In contrast, if we achieved a 50% reduction in computing related electricity demand, the increase in emissions by 2050 would be 0.2 times; and combined with grid-aware computing, 0.18 times. In this scenario, grid-aware computing might be not a bandaid, but a small but definite element in some form of homeostasis: true sustainability. 

One course of action is to prioritise where our resource usage goes and make sure it happens in a fair and equitable way across all nations. The concept of improved carbon-aware computing could be hugely helpful. Especially so if data centres interact with grids and seek assent to use electricity or other resources in a dynamic way, as we described above, but against a specific budget. We touched on this in scenario 1 as well.
What those budgets should be, and for what types of compute activity will require some thought. Nevertheless, this is a vital step to put checks and balances in place to shape computing’s demand and ensure the basic human needs of a local population are met before the profits of Big Tech.


#### Data centres are considered "critical infrastructure"

A hurdle we have to overcome when implementing something like this is that right now, data centres are considered "critical infrastructure", whatever type of compute they're running. This means they automatically get preferential access to the grid. When grid operators are deciding who to provide power to at times of strain, they often receive priority the same way hospitals might as well.

This is also partly why in West London in 2022, <a href="https://www.datacenterdynamics.com/en/news/report-home-building-to-halt-in-west-london-due-to-data-center-power-demands/">datacentres were able to get grid access ahead of the construction of new houses</a>.

It's possible to flip it around so the default is that data centres only pull power from the grid when there is excess green energy that needs to be used. In this scenario, it's likely big operators would just source their own local off-grid power, which is almost universally more co2 emitting because year round onsite power usually relies on fossil fuels.



## Next section
Continue the journey: [Where do we take carbon-aware from here? Introducing grid-aware computing](grid-aware-computing.md)