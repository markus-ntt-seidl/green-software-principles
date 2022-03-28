# Understanding corporate commitments

## Learning Objectives

* What are neutralizations? [Knowledge]
* How would you compare neutralizations with reductions [Comprehension]
* What approach would you take to neutralize carbon emissions from energy consumption? [Application]
* What approaches can you take to neutralize embodied carbon emissions? [Application]
* What are the differences between carbon avoidance and carbon removal offsets [Analysis]
* What is durability with respect to carbon removal offsets? [Knowledge]
* Can you order these carbon removal offsets from least durable to most durable? [Analysis]
* How can you judge the quality of a neutralization? [Evaluation]
* What are the minimum criteria for being carbon neutral? [Knowledge]
* What are the criteria as per the SBTi for being net-zero? [Knowledge]
* If an organization has set this XXXX target, does it meet the criteria of being net-zero? [Evaluation]

## How to measure carbon emissions?

The [Greenhouse Gas Protocol](https://ghgprotocol.org) is the most widely used and internationally recognized greenhouse gas accounting standard. In fact, [92%](https://ghgprotocol.org/about-us) of all Fortune 500 companies use the GHG protocol when calculating and disclosing their carbon emissions. 

The GHG Protocol divides emissions into 3 scopes:

* Scope 1: Direct emissions related to on-site fuel combustion or fleet vehicles;
* Scope 2: Indirect emissions related to emission generation of purchased energy, such as heat and electricity;
* Scope 3: Other indirect emissions from all the other activities you are engaged in. Including all emissions from an organization's supply chain, business travel for employees, and the electricity customers may consume when using your product.

For many organizations Scope 3 is their most significant source of emissions and the most complex to calculate.

When it comes to software energy consumption, it might not be obvious which bucket the emissions for energy fall into. For example, if you are a mobile application developer, the energy usage of your application will fall under scope 3 since it's the end-user that actually consumes the electricity. On the other hand, if you are a cloud provider, the energy use of your virtual machines will fall under scope 2 since you are purchasing the energy.

### Nesting Scopes

Your scope 3 emissions are the aggregate of your supplier's scope 1 and 2, and 3 emissions. If you supply another organization, your scope 1, 2 + 3 emissions form part of their scope 3 emissions.

Through this approach, it's at least theoretically possible to sum up all the GHG emissions from every organization and person in the world and reach a global total.

**!Image Idea!** https://capture.dropbox.com/olhu7yVc5J7wOrVr

### Value Chain Emissions

A value chain is a business model that describes the full range of activities needed to create a product or service. For companies that produce, say a laptop, this includes all the steps that bring a product from conception to distribution, such as procuring raw materials, manufacturing functions, and marketing activities.

Every step in this process emits carbon emissions. For example, every raw material used in the production of the laptop emitted carbon in its extraction and processing. Value chain emissions also include emissions from the use of the laptop, so the emissions from the energy used to power the laptop after it has been sold to a customer.

### Attributional vs. Consequential

The GHG Protocol is an accounting methodology. For some organizations, the Chief Financial Officer calculates their carbon emissions.

To be an accounting methodology, everything needs to _sum up_ to a total. 

An attributional model estimates what share of the global carbon emissions belongs to a single entity. To work, the sum total of all entities needs to equal the total. There can be no double counting. Every carbon molecule is mapped 1-to-1 to a single entity in an attributional model. An accounting methodology, therefore, needs to be attributional.

A consequential model estimates the total amount of carbon reduction associated with an entity. It doesn't matter if all the potential carbon reductions add up to more carbon than the total, as there will inevitably be double counting. In a consequential model, every molecule of carbon is linked to every entity that has the capability of taking actions to remove or reduce it.

You could argue that the attributional model is more accurate, but a consequential model is more impactful. One is not better than the other; both are fit for different purposes.

[This whitepaper](https://www.watttime.org/app/uploads/2021/08/GHG-Frameworks-WhitePaper-Tomorrow-WattTime-202108.pdf) has more information regarding Attributional vs Consequential.

## How to reduce carbon emissions?

There are many ways to reduce emissions, so it's essential when discussing reducing emissions to achieve targets to understand the exact *mechanism* of the reduction.

### Abatement / Carbon Elimination

The [Science Based Targets Initiative](https://sciencebasedtargets.org/) refers to a mechanism called **abatement**. It means eliminating sources of CO2 emissions associated with a company's operations and its value chain so those emissions do not enter the atmosphere. This includes increasing energy efficiency to eliminate some of the emissions associated with energy generation.

It will be impossible to eliminate all emissions. There will always be some areas that can't be eliminated due to technological or economic constraints. To balance those residual emissions, we need to look at other mechanisms such as compensating and neutralizing emissions.

### Compensating / Carbon Avoidance

Compensations are actions that companies take to help society avoid or reduce emissions outside of their value chain. This includes direct investment in emission reduction projects by purchasing carbon credits on the Voluntary Carbon Market.

This is essentially investing in other organizations' abatement projects.

### Neutralizing / Carbon Removal

Neutralizations are actions that companies take to remove carbon from the atmosphere within or beyond their value chain. Neutralizations refer to the removal and **permanent storage** of atmospheric carbon to counterbalance the effect of releasing CO2 into the atmosphere. This includes actions such as restoring natural carbon sinks via actions like soil sequestration or engineered solutions like direct air capture.

#### Durability

When it comes to carbon removal projects, durability is a critical consideration. The durability of a project describes how long the carbon dioxide will be kept from the atmosphere.

Short-term durability is up to 100 years, medium-term is 100 to 1,000 years, and long term is more than 1,000 years.

Solutions that rely on Earth's natural carbon cycle have short-term durability, measured in decades. For example, forestry projects have a durability of 40 to 100 years.

Engineered solutions such as direct air capture often have long-term durability measured in millennia. For example, direct air capture has a durability of 10,000 years.

Long-term projects are typically orders of magnitude more expensive than short-term projects.

Once emitted carbon remains in the atmosphere for 5000 years, to be net-zero, carbon that has been emitted needs to be permanently removed.

A short-term carbon removal project will only remove carbon for 100 years, after which it's back in the atmosphere warming up our planet.

This is one of the reasons why abatement is preferred. Never releasing carbon is far better than releasing carbon and then trying to keep it out of the atmosphere for 5000 years.

## Corporate Commitments

### Carbon Neutral

Carbon-neutrality is defined by an internationally recognized standard: [PAS 2060](https://info.eco-act.com/hubfs/0%20-%20Downloads/PAS%202060/PAS%202060%20factsheet%20EN.pdf).

To achieve carbon neutrality, an organization must measure its emissions. The sum total must be matched by the sum total of its emissions offsets through carbon reduction projects that reduce the amount of CO2 released into the atmosphere. This can include carbon removal projects (neutralizations) and carbon avoidance projects (compensations).

Although it does recommend an organization sets abatement targets, it doesn't demand any level of ambition. So to be considered carbon-neutral, an organization can just measure and offset without investing any resources in eliminating their carbon emissions.

To be carbon neutral, you must cover direct emissions (scope 1 and 2). The general rule of thumb is that organizations measure and offset their scope 1, 2, and business travel from scope 3. However, there is no solid requirement to include that.

Carbon neutral is a great first step for any organization since it encourages measurement, but there are not enough carbon offsets in the world to offset the emissions of all the organizations, so any strategy which doesn't include abatement will not scale or help the world to achieve the 1.5 degree target set out in the Paris Climate Agreement. This is where Net-zero comes into play.

### Net Zero

The [standard for net-zero](https://sciencebasedtargets.org/resources/files/foundations-for-net-zero-full-paper.pdf) is being developed by the [Science Based Targets Initiative](https://sciencebasedtargets.org/).

Net-zero means reducing emissions according to the latest climate science and balancing remaining residual emissions through carbon removals (neutralizations). Net-zero, by definition, requires emissions reductions in line with a 1.5°C pathway. All businesses must do this to achieve net-zero global emissions by 2050. 

The critical differentiator between net-zero and carbon-neutral is net-zero's focus on abatement rather than neutralizations and compensations. A net-zero target aims to eliminate emissions and only offset the residual emissions that you cannot eliminate.

According to the Science Based Targets Initiative, scenarios with a 66% probability of limiting warming to 1.5°C reach a level of abatement of about 90% of all GHG emissions by midcentury. **So for a corporation to meet a net-zero target, it needs to eliminate 90% of its emissions by 2050**. The remaining emissions can only be offset using neutralizations, permanent carbon removals. Through a net-zero strategy, the actual amount of carbon in the atmosphere remains constant.

Also, to be a net-zero target, you must cover direct and indirect, i.e. supply chain emissions (scopes 1,2, and 3). Therefore, your entire value chain needs to be included in the scope of your net-zero target. This is significant since scope 3 is often the majority of emissions for most organizations.

### 100% Renewable

When an organization sets a target of 100% renewable power, they **might** distinguish between being matched-by vs. powered-by renewables.

Powered-by means you are directly powered by a renewable power source, say a hydro dam. In that scenario, the electrons flowing into your device can only come from that source, so you can confidently say that you are 100% powered by renewables.

For most people, we live on an interconnected grid, with many producers pumping electricity in and many consumers taking electricity out. This means the electrons coming into your device are a mixture of all the electrons going into the grid. For example, suppose the grid only has 5% of wind supply. You are getting 5% of wind-generated electrons and 95% fossil fuel-generated electrons.

You can't track individual electrons. Once the electrons from a wind farm are on a grid, they all get mixed with the electrons from a fossil fuel plant. So there is no way for a consumer to insist the electrons that it uses only come from renewable sources.

To solve this problem, a renewable plant sells two things. The first is its electricity, which it sells into a grid. The second is a REC, a Renewable Energy Credit. 1 REC equals 1kWh of energy.

If you want to be 100% matched by renewable energy and are on the grid, the solution is to buy enough RECs to cover the amount of electricity you consume. For instance, if you consume 100 kWh of electricity every day, then to be 100% matched by renewables, you buy 100 RECs.

When organizations set 100%, renewable targets purchasing RECs on the market is the solution they often employ to meet their commitments.

#### PPAs

You might also hear the term PPA. A PPA is a power purchase agreement, and in this context, it's another way to purchase RECs.

If we estimate for a particular data center, we need 500MWh of electricity per year; you may sign a PPA to purchase 500MWh per year from a renewables plant. You would then get all the RECs associated with this power plant.

PPAs are typically very long-term contracts. A renewables plant can find financing with one of these agreements since it already has a buyer for its electricity for many years.

PPAs encourage something called additionality. Purchasing a PPA drives the creation of new renewable plants. PPAs are a solution that gets us towards a future where everyone has access to 100% renewable energy.

### 24/7 Hourly Matching

When it comes to 100% renewable claims, the critical question is what is the granularity of matching? Do you sum up and net off yearly, monthly, weekly, daily, hourly? That question is important because to truly transition across to renewable energy, we need 100% of the power, 100% of the time to come from low-carbon energy sources like renewables. This fine granual matching is often called *24/7 Hourly Matching*.

24/7 hourly matching is one of the many strategies we need to employ to help accelerate the transition to a 100% renewable-powered grid. [Google](https://sustainability.google/progress/energy/) and [Microsoft](https://blogs.microsoft.com/blog/2021/07/14/made-to-measure-sustainability-commitment-progress-and-updates/) have both committed to 24/7 hourly matching by 2030.

#### The difference between daily matching and hourly matching

Imagine an organization has a demand curve like this, each blue square represents 1kWh:

**!Sample Image!** https://capture.dropbox.com/olhu7yVc5J7wOrVr

They have purchased RECs from a wind farm that generated electricity with a curve, so each green square represents 1 REC.

**!Sample Image!** https://capture.dropbox.com/MEr7jbaszBPddEhn

Matching by day means the organization consumed 18 kWh and bought 18 RECs. As a result, they netted off to zero. So they can say they are **100% matched by renewable energy daily.**

However, if we looked at it in hourly buckets (each square here is 2 hrs in length), then it seems a bit different: 

**!Sample Image!** https://capture.dropbox.com/xj05k9wpV88zZOq3

The total amount of energy consumed is still 18kWh. However, there are only a few hours in the day where we are 100% matched by renewable energy for that hour. So for some hours, we have way more renewable energy than we need. Conversely, we have way less renewable energy than we require for most hours. 

In the above example, they are **100% matched by renewable energy on an hourly basis for only 6 hrs of the day.**

The number we use to describe how successful we are at 24/7 hourly matching is the carbon-free energy percentage. 

#### Carbon Free Energy

Carbon-Free Energy is defined as [the average percentage of carbon-free energy consumed in a particular location on an hourly basis](https://cloud.google.com/sustainability/region-carbon#understanding)

So for the previous example, if measured using daily matching, we are 100% matched with renewable energy. However, we are only 33.1% matched if measured using hourly matching. **The CFE percentage is, therefore, 33.1%**.  

[Google](https://sustainability.google/progress/energy/) and now [Microsoft](https://blogs.microsoft.com/blog/2021/07/14/made-to-measure-sustainability-commitment-progress-and-updates/) have both set a goal to reach 100% CFE for all their operations by 2030. So for every hour of every day, be 100% matched with renewable energy. This is the essence of a 24/7 Hourly Matching Target.
