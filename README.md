# AMONG
Agent based Modeling Of Negative Gearing

The current debate regarding Australia’s housing tax system is fraught. Despite the best efforts of many, public understanding of outcomes associated with changes to negative gearing and capital gains tax regimes remains obscured by conflicting ‘analyses’ generated by parties from either side of the debate. 
This need not be the case.

Given the known structure of the housing market and actors contained within it (e.g., buyers, sellers, renters), this project builds a transparent, dynamic agent-based model that re-creates the Australian housing market from the ‘bottom-up’.


## Project Pipeline

The project creates a fine-grained representation of the housing market including all relevant actors, (e.g., buyers, sellers, investors, builders, lenders and policy-makers) relevant to the Australian housing industry. The agent-based model will be built to reflect raw figures contained within existing ‘top-down’ models constructed by existing independent analyses to ensure consistency with ‘baseline’ assumptions.
Workshops between investigators will take place following the 10-step format of van Dam, Nikolic, and Lukszo (2012). The results of the pilot project will generated within 12 month.
1. Problem formulation and identification
1.1. Defining the scope and aims of the model and project as described in this application
2. System identification and decomposition
2.1. Workshops held with investigators and other interested / invited parties (e.g., industry groups and
government) to identify the breadth and scope of actors and influences included in the model. 3. Concept formalisation
3.1. Defining relationships, behaviours and interactions of the model actors. Here, the broad policy settings and underlying behavioural assumptions of buyers and sellers (for example) will be made transparent.
4. Model formalisation
4.1. Here, the ‘story’ of the model will be built, detailing which actors do what and when. This aspect of
the model build will be written in ‘pseudo-code’ so that people unfamiliar with reading computer
code can gain an understanding of how the model ‘works’. 5. Software implementation
5.1. Transcribing the pseudo-code into an existing agent-based modelling platform such as Netlogo or RePast Symphony to ensure model transparency and enable iterations and update of future models.
6. Model verification
6.1. Once built, the model will be iterated and run under various baseline and experimental conditions to
determine whether the actors and relationships we intended to model are operating as expected.
7. Experimentation
7.1. When satisfied with the operation of the model, we will then experiment with the policy settings contained within it, testing assumptions made by previous ‘top-down’ models and creating various future policy scenarios.
8. Data analysis
8.1. Data produced by the model will be analysed to identify trends and insights as well as policy settings
that produce optimal system performance. Pattern exploration will also take place based on the
macro-level visualisation outputs of the model.
9. Model validation
9.1. To validate the model we will compare results produced from the ‘baseline’ settings against those created by previous top-down models from The Grattan Institute as well as ‘replay’ historic policy- change events (e.g., previous efforts to limit negative gearing) in attempt to replicate observed patterns
10. Modeluseanddissemination
10.1. Finally, the model will be published in a formal academic publication and in Pursuit. Results will be
made available to policy-makers and planners, with opportunity for individual to input their own assumptions and policy-scenarios
The project aims to conclude the first 4 steps within 2 months. The software implementation and verification (steps 5 and 6) will take up to 4 months during which most of the costs occur. Running multiple experiments, generating results and evaluating them (Steps 7 – 9) is anticipated to take 3 months.

![alt text](https://github.com/gaschwanden/AMONG/blob/master/stuff/class_diagram.png)


## Project Goal

This project aims to produce a transparent evaluation methodology to estimate the impact of policy changes associated with changes to the Australian negative gearing and capital gains tax regime. The research question is: How can we most effectively model the impact of policy changes to the housing market.
Access to safe and secure housing is a basic human right. Unfortunately, however, the current political debate around affordable housing and how it may best be achieved is fraught, with opinionated conversations around negative gearing and capital gains tax at the centre of this debate.
The public domain is replete with economic models both requested and generated by industry sectors with vested interests in their outcomes. Often designed to produce ‘nightmare scenarios’ of falling house prices and unaffordable rents, such modelling does little to inform public debate or make explicit the competing forces at play within this complex policy environment. For example, a recently released report by consultancy firm BIS Schrapnel predicted that reductions in negative gearing would produce a $19billion hit to Australia’s GDP, while pushing rents up by as much as 10%. The Housing Industry Association likewise warned of falling living standards and higher tax burden for all Australians should negative gearing be restricted.
The assumptions and dire predictions contained within such reports have been rejected by independent institutions such as the McKell and Grattan Institutes, who provide a more temperate estimates of policy changes in their respective 2015 and 2016 reports. Still, the complex nature of debate and the inability of the public to effectively ‘get inside’ the numbers, assumptions and combined scenarios contained even in more balanced analyses, means that true understanding remains limited. Required is a new, transparent method for the public to interact with this heated and complex policy arena; one where the multitude of available policy options can be generated, viewed and understood by all.
The housing market contains a large number of actors, including builders, agents, banks, renters and owners with a relatively stable number of objects (houses and apartments). Each of these actors also has motivations to buy, sell, rent, invest or otherwise act in their best interests. Rather than a traditional ‘top-down’ method as has been traditionally used in the models described above, this structure lends itself to be modelled in a bottom up manner using computational social science methods; Agent-Based Modelling (ABM).
ABM has been successfully used in many complex policy environments to understand the effect that various policy-levers have on individual actor and population-level outcomes. Unlike more static, deterministic models used above, ABMs are also extremely flexible, enabling an almost infinite set of policy scenarios to be studied or for systems to seek optimisation based on desired macro-level outcomes. Developing this model will enable us to investigate the behaviour of the market as a whole over time but also to see how these changes are impacting individual population or market segments (e.g. Older vs younger investors, 2 room apartments vs detached homes, etc.). This unprecedented granularity of evidence may help guide policy and how they should be implemented to support affordability or mitigate erratic changes due to sudden policy adaptation.
