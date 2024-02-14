<!-- h1. header sets the name of the page. Default for index is "Home". -->

### Disclaimer
The collective behind this guideline has a positive bias towards Open Source, and is moved by the conviction that, as a default option, Open Source is the preferable approach for development cooperation (DC) and international cooperation (IC) projects because: 

 - DC projects are most frequently publicly financed (see [public money public code](https://publiccode.eu/en/)). In addition, many public institutions financing such projects have politically induced preferences in favour of open source (see e.g. Principles of Digital Development) 

 - of the collaborative nature of these projects (co-financing of projects through several donors; mutualization and cross-fertilization) 

 - open source makes the involvement of local IT-companies and individuals for the development and maintenance etc. Easier, which can also trigger positive side effects for the local IT sector.  

 - developed software can become a tool and the intellectual capital for a new organization in the event of a project spin-off or transfer. 

However, we are also pragmatic and fully acknowledge that, in some situations, proprietary solutions are the way to go. This is typically the case when a partner already uses a proprietary software or there is existing and affordable proprietary software that fulfills the requirements better. In this case it often makes more sense to further build their capacities on this software than to re-invent the wheel and force new tools, processes and approaches on them. It can also make sense if the partner has no or little own IT capacities and maintenance is expensive (e.g. due to a lack of an open source community or lack of scale).


## Introduction 

This guideline is designed to help project managers to: 
 - Take a well-informed decision for or against the use, introduction or development of open source tools 
 - Avoid late failure and unexpected cost through good planning 

It is written from the perspective of practitioners working in publicly funded development cooperation projects and organizations. We wish for more successful open source endeavors, and less that lead to frustration, budget explosion and lack of sustainability. 

The goal of this guideline is therefore to equip those that are responsible for the procurement and implementation of digital solutions in different sectors in development cooperation, but are themselves not IT specialists, with an overview of aspects to consider and ask for at project planning and implementation stages.


### Essential terminology 

Open source software is software with source code that anyone can inspect, modify, and enhance (see [opensource.com](https://opensource.com/resources/what-open-source)). 

There are dozens of widely recognised free and open source types of licenses, which can accommodate the specific needs of each open source project. Many of these free open source licenses (e.g. Licenses – Open Source Initiative) have now become standards supported by millions of experts worldwide. It follows that open source solutions can theoretically be implemented anywhere in terms of innovation, knowledge transfer and transferable ownership. In the following, we distinguish between three cases:

 1. introducing and using existing open source software,  
 1. adapting existing open source software, 
 1. building completely new open source software.  

In practical terms, this distinction means that for case **1.** the main reasons that differentiate open source from closed source software are either normative (e.g. political) or on vendor lock-in and adaptability (case 2). Other factors like cost and fit for the purpose should not differentiate specifically between open source and other software, although e.g. cost structures may differ between different types of software. 

A typical example for case **2.** is one, where an open source solution to the problem generally exists, but needs to be adapted slightly to fit the exact case.  

Case **3.** should only be relevant if a project or problem is "generic" enough that it can be interesting and relevant for others. Only then, it makes sense to develop a new open source solution, considering the effort and dedication it takes to build and maintain a community of users and developers. 

If project teams want to be co-responsible for innovation, security, transparency, flexibility and a sustainable project future, open source is the choice. And, even small inventive digital solutions, designed only for specific tasks can be implemented efficiently with open source. The lifespan of a project supported by open source software depends on its management, impact and funding, not on the level of availability, flexibility and support of licensed software.

 - **Open source licenses:** An open source license is a legal agreement or copyright license allowing developers to use, modify, and distribute a software's source code freely. It sets the terms and conditions for using, sharing, and modifying software. There are different types of open source licences. Generally, "Open source licenses are licenses that [...] allow software to be freely used, modified, and shared." Open Source Initative, 2023 (Licenses – Open Source Initiative) 
 - **Open source tools:** An open-source tool is a software application or program that serves a specific purpose and whose source code is made available to the public under an open-source license. 
 - **Open -source libraries:** An open-source library is a collection of pre-written, reusable code modules or functions that developers can incorporate into their software projects.

The following is an outline of the development phases of an open source project and what project teams should pay attention to. It gives a proposal for an ideal project development, starting with the clearness of the strategic goals, comprehensive conceptual work, a well documented technical implementation, adoption and communication activities.


## Checklists at Pre-Project Stage 

The project design phase can set the stage for a possible preference for open source technology.  In line with the definitions above, we focus here on projects that want to use or adapt open source software. For a discussion on case 3, open source development, see the exchange here.  

When translating possible open source preferences into project requirements, consider the following points.

### 📋 Preproject IT selection

At this point of project design there often already exists a good  general sense of the underlying need or problem, but the range of possible solutions needs to be better understood. This checklist seeks to guide this process and help determine whether or not an (existing) open source solution is suitable for the project.  Many of the questions are open-ended, and while it is not necessary to answer all of them in order to proceed, this analysis will lay the groundwork for the subsequent creation of clear Terms of Reference (ToR) and successful project implementation.

 1. **Are the needs of the user(s) well understood?**
    1. Is there a precise definition of the problem? 
    1. Who is the client and who are the different user groups?
    1. What are (the) current user workflows?
    1. How high is the digital literacy of the users?
    1. What data is needed to answer the user need? Is it already available?  If not, how can it be obtained? 
    1. What is the current stage of the solution identification process? Does a requirements list for a potential solution already exist? Do the client or the users maybe already have solution in mind?

1. **Is the existing IT environment and policies well understood?**
    1. Is there already a digital architecture  in place that a solution should integrate with? If so, how close does this integration need to be?
    1. Is there an existing tool in the existing architecture that can easily be upgraded/ extended to address this need?
    1. Who will host and maintain the solution after the end of the project?
    1. What is the existing tech stack of the client and the users? What are existing standards that are being followed?
    1. Is there are an overarching IT strategy that can guide the choice of solution (e.g. cloud vs on-premise)? What are the usual decision making processes like? Who needs to be involved? Are there other departments and institutions that we can align with or learn from? Are other departments facing similar challenges? How and by whom are projects implemented there?

1. **Are the capacities of the client/partner well understood?**
    1. How high are the digital capacities of this future host? Is there a strong internal IT department? How were previous IT projects implemented?
    1. What is the level of digital skills at the host organisation? Are there any gaps that need to be addressed?
    1. What (financial and human) resources are available during the project (project management, development / deployment, training,...) and after the project (hosting / maintenance / continuous development / continued training)?

1. **Are digital options well understood?**
    1. Based on the problem definition, what software (open and closed) is used to address similar needs? How are these usually provided? 
    1. Are there off-the-shelf, fully-serviced  tools (open source or proprietary) that can cover all or part of the needs? How are they priced?
    1. What is the landscape of IT companies to provide support in development, hosting, maintenance? Are there local options?
    1. What is the level of maturity and sustainability of the open source software options (whether a specific solution is well developed and maintained: [redhat](https://www.redhat.com/en/resources/open-source-project-health-checklist) and [tinycloud](https://www.tiny.cloud/software-evaluation-criteria-checklist/))?
    1. What are options to integrate into the broader solution environment in this field? Are there data or software standards, that ensure interoperability?


### 📋 Writing ToRs

We recommend those unfamiliar with open source software procurement to seek expert guidance on formulating tenders, as they differ significantly from standard international development tenders (technical advice and infrastructure). As general best practice, consider involving partners and future users early in the conception of the ToR, to ensure alignment with their needs and expectations. In line with this, clearly agree with them their expected level of involvement during the project and transparently communicate this in the ToR. Similarly, be transparent in the reasoning on the technical requirements and have resources available to answer technical questions during the tendering process.

1. **Background**
    1. Provide a clear description of the problem and user group, addressing the dimensions of 1.
    1. Provide a detailed description of the status quo, including 2., 3. and 4.
    1. Clearly describe the vision and highlight which parts are not predetermined
    1. Transparently share the reasoning for the open source preference.

1. **Define clear technical requirements for the project**
    1. Make the requirements as flexible as possible to meet with different technological solutions. Consider only sharing the needs analysis, leaving the choice of technology to the contractor. When listing technological options, be mindful of omissions.   
    1. Be specific on interoperability requirements and standards to follow 
    1. Describe the service requirements across the entire software life-cycle (Software-Lebenszyklus – Wikipedia), in particular those aspects that concern roll-out, maintenance and later adaptations that may be needed 
    1. Differentiate nice to have and must have criteria. Avoid long wish-lists focus on criteria that are relevant for the core problem only.
    1. Be aware of potentially exclusive criteria that may seem small side-aspects, but can be prohibitively expensive for (small) suppliers (e.g. specific hosting requirements, certain cybersecurity standards, …)

1. **Work packages**
    1. Clearly describe and differentiate the required development stages (discovery, pilot, implementation/roll-out, maintenance)
    1. Describe the involvement of user groups
    1. Describe desired implementation approach - consider prioritising agile modes of work where possible
    1. Plan the project timeline accordingly. Take into account that design and user engagement can take significant amounts of time.

1. **Budget preparation**
    1. Carefully match the project requirements to the budget. Adapting, rather simply adopting, a piece of software can imply significant increases in effortConsider at minimum the following aspects for human capacity: analysis/requirements engineering, design, programming, user engagement and testing, domain expertise 
    1. Consider costs for training and change management
    1. The less clear the choice of technology, the more flexibility is also required in the budget. If no solution has been identified, budget for decision making process. If instead the choice is clear, draw on a standard framework for software budgets.
    1. User engagement is key but costly. At minimum, budget explicitly for design workshops and user testing.
    1. Calculate costs for maintenance and hosting both for the project period and for afterwards
    1. Consider agile-compatible remuneration and project steering strategies 
