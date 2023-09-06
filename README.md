# Open Source Checklist

## Aim and objective

* Context: projects with a digital component, in the broad field of international development cooperation
* Objective of this checklist: provide a list of points / questions / topics that need to be discussed / brainstormed / resolved / challenged when deciding to go for Open Source

## Disclaimer

The collective behind this checklist has a positive bias towards Open Source, and is moved by the conviction that, in most cases, Open Source is the best approach for development cooperation projects (lack of resources from the partners to pay for licenses on the long-term; co-financing of projects through several donors; mutualization and cross-fertilization; make a more transparent use of public money; involvement of local IT companies for the development and maintenance; etc.). 

However, we are also pragmatic and fully acknowledge that, in some situations, proprietary solutions are the way to go (typically: when a partner already uses a proprietary software, it often makes more sense to further build their capacities on this software than to re-invent the wheel and force new tools, processes and approaches on them).

## Introduction
* An open source tool is generally associated to a software whose code is freely available. 
* There are different types of open source licences. The most common ones are to be found on https://opensource.org/licenses/
* We need to distinguish between open source libraries and open source tools.
* We need to distinguish between "using existing OpenSource software" (typically in our context: QGIS, NextCloud, etc.) vs. "developping OpenSource tools" (incl. code and community management, choice of license, long-term ownership, etc.)
* Digital Public Goods: define whether this is relevant (as a quality label?)
* Public money - public code - no blackbox


## Open Source checklist by project stage
<em>As you will see below, we are back to the question on general digital projects versus specifically open source. Maybe we could have a very brief general point and below each of them something like: specific to consider for open source choices....? Or kick out all the general stuff</em>


### Prefeasibility and feasibility stage
The (pre)feasibility stage can set the stage for a possible preference on open source. This choice should be based on:
- a precise problem definition
- a definition of the use case(s) including users, contributers (e.g. data providers), decisiontakers (those who decide whether the tool is being used and at which scale)
- existing software in use
- digital capacities at hosting institution (partner or project team):
  - digital skills in team: if low, then propose STE that understands the technical language to accompany tendering and initial stages of implementation > prepare the team for having to be deeply involved in the design and implementation (giving frequent feedback, testing, reviewing)
  - dedicated IT department responsible for hosting and maintenance
- digital capacities in the country / region (landscape of IT companies able to provide support, development, hosting, maintenance locally)
- digital capacities and expertise in the networks of the partner (e.g. in other Ministries), who *might* become involved in the process (as users, as data partners, etc.)
- availability of existing open source tools that match the problem definition with their level of maturity
  - how to assess the maturity of an Open Source digital tool?
      - timeline of existence
      - size and activity level of community > vendor lock-in
      - existing number of service providers offering hosting, setup, adaptations...
      - transparency of the development processes (e.g. are all changes, commits, feature requests visible on an open repository? or is the work actually conducted in a closed way, and "just uploaded to GitHub from time to time"?)
      - _iteratively apply the same questions / criteria on the main libraries upon which the tool relies_
- contribution to an open source community or trying to build up a new one?
- better small and feasible, than too large and complex
- review overall cost for different options (open source and non-open source)
- consider vendor lockin
- interperability above open source?
  
### What to consider when writing ToR

- develop a product vision
- make clear which aspects about the software, its implementation or use are still unclear > derive from that: requirement to use a specific open source tool or to find an appropriate solution
- methods: the more unknown the more agile is needed. Therefore, avoid to be too precise and details in the description of the wished features (the "how"). Rather spend energy on identifying, understanding and re-formulating the user needs and use cases (the "why")
- Assess the running costs of the software - hosting, maintenance, support, further development - for different options
- Consider whether only user training is needed, or also training for contributers, IT departments, etc.
- Be fully honest and transparent with the partners, and involve them early in the conception of the ToR. Very often, the partners only receive a final version of the ToR, "for comments", at a stage where it is too late for questioning the ToR's rationale and main directions
   - Typical situation: the development partner (GIZ, KfW) wants to develop an open source GIS tool. The partner, however, has already some experience with ArcGIS (proprietary), has built up a simple ArcGIS-based spatial data infrastructure, and has some licenses available. Explicitly forcing the ToR towards Open Source will only bring confusion and frustration from all sides, requiring sketchy adjustments ("It must be Open Source, but also fully compatible with ArcGIS")

### What to consider in the discovery phase
- identify detailed user needs 
> [!WARNING]
> [Comment Stéphane] Usually the users don't know what they need until they have something in their hands. I would therefore not put so much emphasis on the "detailed user needs", but more on the description of use cases and personas AND highlight the need for agility, because we know already that the users will come with new needs during the development phase

- translate them into technical requirements
- develop a clear product vision
- re-assess the running costs of the software - hosting, maintenance, support, further development - for different options
- Accept the fact that, no matter how good your discovery phase has been, there will be massive changes during implementation and the users will discover later that they have new needs and requirements. Therefore, need to embed processes supporting agility (e.g. drop a feature envisioned by the ToR, and replace it by another one, deemed more important / relevant by the users), and ensure that the quality / completedness of the tool will not be only assessed against the requirements specified in the ToR
> [!WARNING]
> [Comment Fred] The value of the prefeasibility or the feasibility is not always ensured for complex IT projects given their fast lifecycle. We even observe quite often that an IT project never delivers becomes it remains stuck in discovery and feasbility. How can we make clear how to overcome this (the whole agile toolkit...?) 

### What to consider for the implementation phase
- Interoperability
- the clearer the more to think about priorization of features (narrow vs broad use cases)
- timeline for user uptake
- handover
- close collaboration with the partner and repeated meetings (whatever your preferred time interval ).
- Retros and reviews for the pain points and delivered successes ? Make sure that repriorization is constantly possible.

### What to consider for the maintenance and support phase
- clarify costs/staff responsibilities for hosting and maintenance, if there is no one then get a contract with a provider for that
- clarify....

### Project complexity
- The FC cycle (maybe to a lesser degree for TC) is really meant to implement complicated projects.
- IT projects easily get complicated (a la Cynefin) with many stakeholders, fast technology cycles, complex technology.
- So does Open Source make the project too complicated or is able to handle this? 
- How is the complexity integrated into the implementation phase ?
- This is most likely part of the discovery phase ?
