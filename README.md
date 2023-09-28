# Open Source Checklist

## Collaboration rules and notes
<em>Feel free to edit the text as you like. If you want to propose a completely new structure or delete major parts, please use the pull request function

If you want to start a discussion on a specific word or aspect in the main text, please create an issue and link the issue to the main text (see interoperability as an example)

General note: As you will see below, we are back to the question on general digital projects versus specifically open source. Maybe we could have a very brief general point and below each of them something like: specific to consider for open source choices....? Or kick out all the general stuff</em>


## Aim and objective

* Context: projects with a digital component, in the broad field of international development cooperation
* Objective of this checklist: provide a list of points / questions / topics that need to be discussed / brainstormed / resolved / challenged when deciding to go for Open Source

## Disclaimer

The collective behind this checklist has a positive bias towards Open Source, and is moved by the conviction that, as a default option, Open Source is the preferable approach for development cooperation projects because they are publicly financed (public money public code) and because of the collaborative nature of these projects (co-financing of projects through several donors; mutualization and cross-fertilization) and because open source makes the nvolvement of local IT companies for the development and maintenance; etc. easier. 
lack of resources from the partners to pay for licenses on the long-term?

However, we are also pragmatic and fully acknowledge that, in some situations, proprietary solutions are the way to go. This is typically the case when 1) a partner already uses a proprietary software, it often makes more sense to further build their capacities on this software than to re-invent the wheel and force new tools, processes and approaches on them, or it may make sense if the partner has no own IT capacities and maintenance is expensive (e.g. due to a lack of a community, lack of scale).

## Introduction
* An open source tool is generally associated to a software whose code is freely available. 
* There are different types of open source licences. The most common ones are to be found on https://opensource.org/licenses/
* We need to distinguish between open source libraries and open source tools.
* We need to distinguish between "using existing OpenSource software" (typically in our context: QGIS, NextCloud, etc.) vs. "developing OpenSource tools" (incl. code and community management, choice of license, long-term ownership, etc.)
* Digital Public Goods: define whether this is relevant (as a quality label?)
* Public money - public code - no blackbox


## Open Source checklist by project stage

### Preparatory stages (e.g. prefeasibility and feasibility stage)
The (pre)feasibility stage can set the stage for a possible preference on open source. This choice should be based on:
- beneficiary/host institution internal aspects:
  - a precise problem definition
  - a definition of the use case(s) including users, contributers (e.g. data providers), decisiontakers (those who decide whether the tool is being used and at which scale)
  - existing software in use
  - digital capacities at hosting institution (partner or project team):
  - digital skills in team: if low, then propose STE that understands the technical language to accompany tendering and initial stages of implementation > prepare the team for having to be deeply involved in the design and implementation (giving frequent feedback, testing, reviewing)
  - dedicated IT department responsible for hosting and maintenance
    
- local context
  - digital capacities in the country / region (landscape of IT companies able to provide support, development, hosting, maintenance locally)
  - digital capacities and expertise in the networks of the partner (e.g. in other Ministries), who *might* become involved in the process (as users, as data partners, etc.)
- general context
  -  availability of existing open source tools that match the problem definition with their level of maturity
    - how to assess the maturity of an Open Source digital tool?
      - timeline of existence
      - size and activity level of community > vendor lock-in
      - existing number of service providers offering hosting, setup, adaptations...
      - transparency of the development processes (e.g. are all changes, commits, feature requests visible on an open repository? or is the work actually conducted in a closed way, and "just uploaded to GitHub from time to time"?)
      - _iteratively apply the same questions / criteria on the main libraries upon which the tool relies_

- Cost considerations
  - Even though it may not be possible to estimate the cost precisely at this stage, there should be a general review of the of the cost categories to consider for different scenarios ( incl. open source and non-open source)
     - approximate total cost of ownership is a nice way to structure the discussions around pros and cons for different software stacks. you can use it to roughly estimate:

        Cost of licences
        Cost of internal devs / external devs
        Cost of internal administration
        Cost of hardware /maintenance

      This allows you then to compare different scenarios in a way that also speaks to non-tech people...contribution to an open source community or trying to build up a new one?
  - consider vendor lockin
  - interperability above open source?
  
### Tendering stage: What to consider when writing ToR (goal: ensuring that those responding to the tenders have all the necessary information to submit an offer of good quality)
General points:
- Be fully honest and transparent with the partners, and involve them early in the conception of the ToR. Very often, the partners only receive a final version of the ToR, "for comments", at a stage where it is too late for questioning the ToR's rationale and main directions
   - Typical situation: the development partner (GIZ, KfW) wants to develop an open source GIS tool. The partner, however, has already some experience with ArcGIS (proprietary), has built up a simple ArcGIS-based spatial data infrastructure, and has some licenses available. Explicitly forcing the ToR towards Open Source will only bring confusion and frustration from all sides, requiring sketchy adjustments ("It must be Open Source, but also fully compatible with ArcGIS")
   
Possible structure:
- problem description
- status quo description incl. existing software, existing skills and roles / capacities
  - make clear which aspects about the software, its implementation or use are still unclear > derive from that: requirement to use a specific open source tool or to find an appropriate solution
- broad product vision / description of the ideal state
  - including an explanation why open source is the preferred option 
- User groups: who will be the users and stakeholders in the software?
- development stages: often 1) discovery, 2) pilot, 3) implementation/roll out, 4) maintenance for existing open source tools, for "developing OpenSource tools", the following: ....
- methods may not be needed, but if: the more unknown the more agile is needed. Therefore, avoid to be too precise and details in the description of the wished features (the "how"). Rather spend energy on identifying, understanding and re-formulating the user needs and use cases (the "why")
- budget
  - assess the code of each stage
  - Assess the running costs of the software - hosting, maintenance, support, further development - for different options
  - Consider whether only user training is needed, or also training for contributers, IT departments, etc.


### What to consider in the discovery phase
- identify detailed problem description (description of use cases and personas AND highlight the need for agility, because we know already that the users will come with new needs during the development phase)
- be careful with user needs (Usually the users don't know what they need until they have something in their hands)
- prioritize on the core problem
- be careful with assigning roles to other critical user types without talking to them and analyzing their "problem" (e.g. those that enter data, those that supposed to benefit from increased transparency, ...)

- translate them into technical requirements
- develop a clear product vision
- re-assess the running costs of the software - hosting, maintenance, support, further development - for different options
- Accept the fact that, no matter how good your discovery phase has been, there will be massive changes during implementation and the users will discover later that they have new needs and requirements. Therefore, need to embed processes supporting agility (e.g. drop a feature envisioned by the ToR, and replace it by another one, deemed more important / relevant by the users), and ensure that the quality / completedness of the tool will not be only assessed against the requirements specified in the ToR
> [!WARNING]
> [Comment Fred] The value of the prefeasibility or the feasibility is not always ensured for complex IT projects given their fast lifecycle. We even observe quite often that an IT project never delivers because it remains stuck in discovery and feasbility. How can we make clear how to overcome this (the whole agile toolkit...?)
> [Comment Linda] Ah I seem to remember something with LODA in Rwanda which was canceled after two years. My first thought would be that we change the feasibility section into saying: concentrate on the problem description only (and maybe a description of the ideal state), as that lifecycle is slower. But that means that budget estimates would be near to impossible and budget would have to be decided on other information.
> [Comment Clarisse] just an idea to go beyong the problem description only: it could be useful to use the BMC toolkit for this: start by discribing the custumer PAINS (problems you want to overcome for the user) and costumer GAINS (what could help the user in their task/job)

Project complexity

    The FC cycle (maybe to a lesser degree for TC) is really meant to implement complicated projects.
    IT projects easily get complicated (a la Cynefin) with many stakeholders, fast technology cycles, complex technology.
    So does Open Source make the project too complicated or is able to handle this?
    How is the complexity integrated into the implementation phase ?
    This is most likely part of the discovery phase ?

### What to consider for the implementation phase
- [Interoperability](https://github.com/GFA-DIU/GFA-DIU.github.io/issues/1)
- the clearer the more to think about priorization of features (narrow vs broad use cases)
- timeline for user uptake
- training
- several feedback loops and/or continuous further development?
- handover
- close collaboration with the partner and repeated meetings (whatever your preferred time interval ).
- Retros and reviews for the pain points and delivered successes ? Make sure that repriorization is constantly possible.

### What to consider for the maintenance and support phase
- clarify costs/staff responsibilities for hosting and maintenance, if there is no one then get a contract with a provider for that
- clarify....

