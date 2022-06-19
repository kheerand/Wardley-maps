# Tooling landscape 2022

>DRAFT DRAFT DRAFT DRAFT DRAFT DRAFT DRAFT DRAFT DRAFT DRAFT  
> Note that this document is still in draft and I'm still forming my narrative here.
>-

During the Down Under Dagsthul workshop held in 2021, a brainstorm was done of all the tools that
were available for creating, publishing and maintaining vocabularies.  In 2022 I took this list
and mapped them on to Simon Wardley's evolution map to see where things are in the landscape.

During the workshop, each of the tools were tagged with the function they performed,

* Authoring
* Discovery
* Display
* API services
* Governance
* Validation

Each of these are mapped as a pipeline in the map as the expectation is that there will be tools
at different stages of the evolution.

Below is the resulting map.

<img src="./Controlled Vocabulary Tooling Landscape.png" width ="100%">

There were a few general tools like Excel, Github, Google Sheets in the list of tools identified, but these
were not mapped as they are general purpose tools that are not specifically for management of vocabularies.

>**NOTE 1 on bias**: Another bias that probably exists in here is that the tools found on Github were 
classified as _Custom Built_.  However it is entirely feasible that at least some of these could be considered _Products_.  
>
>The reasoning behind this choice is an assumption that these were built for
bespoke needs, then generalised and made available for broader use.  Therefore, it is assumed that
anyone implementing these tools will also use these as the foundation to craft their own bespoke
solution.

> **NOTE 2 on bias**: The placement of tooling is at this stage based only on my opinion of them, which is in
turn is based on a quick scan of the tools on the web.  I've got no first hand experience in using or
implementing any of these tools.  Therefore it is highly likely that it contains considerable biases of
mine in there.

## Explanation of landscape

### Observation 1

Noting the bias expressed above the map shows that mostly the tooling for vocabulary management is in its
early stages of evolution.  However, there are a few tools that are in the untility model.

Of the three that are in utility, two are commercial products and one is a 
government funded service.  

PoolParty is the only commercial product here with a direct focus on 
vocabularies.  It is a software suite that is also offered as a managed
service.

TopBraid is at its core a RDF linked data
management product suite that is offered as a service.  It provides the
building blocks to develop RDF data solutions, one aspect being vocabularies.

RVA or Research Vocabiliaries Australia is an Australian government funded
initiative providing the services around vocabularies.

While all of these fit the utility model, they do not compete with each
other, but provide complementary capability.  As a result there is no
evolutionary presure for any of them.

This comes from the set of tools that are in the *custom built* zone of
evolution.  It is very likely that tools are too bespoke to currently
be considered as a threat to the three services providing *utility* style
services.

> Conclusion: There is limited climatic presures to the three products
in the *utility* space to force them to evolve.


### Observation 2

Looking at the products in the *Custom built* space, most of them are
developed or maintained by academic groups.

> TODO: Confirm if this observation is accurate.  Some certainly are, but
confirm if most are stemming from academia.

Academic groups tend to consist mostly of *pioneers*.  Therefore it is not
surprising that many of these tools are in the bespoke, custom built stages
of its evolution.  This is where this group of people are good at,
developing new prototypes, and evolving them to useful bespoke solutions.

>Conclusion: What is probably missing in the landscape are the *settler* type people within the right institutional mechanisms that enable them to be able
to take the custom-built, bespoke solutions and produce good products and
evolve them into stable tools that can lower the barriers for a broader 
number of people utilising these tools to develop, publish and maintain
their vocabularies.
>
> Introduction of this would pave the way for the existing tools to be
evolved as well as create competition for the three products within the
*utility* zone, which in turn can lead to accelerated enhancement of
features, price and service.  All of these serve to accelerate the
use and adoption of vocabularies in daly work of people.
