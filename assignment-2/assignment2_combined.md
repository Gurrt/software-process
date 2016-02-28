% Group Assignment 2
% Team Blue Mondays
%  Alex van Manen (Lead), Pim Tegelaar (Vice Lead), Job Witteman, Erik Verhoofstad, Alberto Martinez de Murga, Ger Krijnen, Carla Alvarado & Joel James Bartholomew \hfill \break \break \centering{\today} 


\newpage

# Abstract

In software engineering, it is important to understand organizational level factors and their influence on development projects. This is necessary to be able to organize for successful software projects. In this report we cover the following topics: CMMi, Lean, 7S and Power. 

In the CMMi section, we examine Scrum, RUP and the HealthCare.gov project to determine what the maturity is of their project organization. The Lean section provides insight into the varying forms of waste present in Scrum and RUP. The next section examines KLM, Spotify and the HealthCare.gov project. This is done using the 7S model and is concluded by showing what can be learned from Scrum and RUP in regards to the KLM and Spotify organizations. The last section covers Power in organizations by examining the effects of control, balance of power and the presence of learning environments in RUP, Scrum and the HealthCare.gov case.

# 1.0 CMMi analysis

In this section, we examine to which extent the various CMMi Development process areas are covered in Scrum, RUP and the HealthCare.gov project. For this, we used the CMMi for Development report. The analysis of Scrum is based on the content in the Scrum Guide [4]. Likewise, the analysis of RUP is based on the RUP book [5].

## 1.1 Analysis Overview

| CMMi Process Area | Scrum | RUP | HealtCare.gov |
| ------------------| ----- | --- | ------------- |
| **Maturity Level 2 - Managed**                |
| CM - Configuration Management                | Not at all | Fully      | Unknown    |
| MA - Measurement and Analysis                | Partially  | Partially  | Not at all |
| PMC - Project Monitoring and Control         | Partially  | Fully      | Not at all |
| PP - Project Planning                        | Fully      | Partially  | Not at all |
| PPQA - Process and Product Quality Assurance | Partially  | Fully      | Partially  |
| REQM - Requirements Management               | Fully      | Fully      | Not at all |
| SAM - Supplier Agreement Management          | Not at all | Not at all | Partially  |
| **Maturity Level 3 - Defined**                                                      |
| DAR - Decision Analysis and Resolution       | Not at all | Not at all | Unknown    |
| IPM - Integrated Project Management          | Partially  | Fully      | Partially  |
| OPD - Organizational Process Definition      | Not at all | Not at all | Not at all |
| OPF - Organizational Process Focus           | Partially  | Partially  | Not at all |
| OT - Organizational Training                 | Not at all | Not at all | Unknown    |
| PI - Product Integration                     | Partially  | Fully      | Not at all |
| RD - Requirements Development                | Partially  | Fully      | Unknown    |
| RSKM - Risk Management                       | Not at all | Fully      | Not at all |
| TS - Technical Solution                      | Partially  | Partially  | Partially  |
| VAL -  Validation                            | Partially  | Fully      | Partially  |
| VER -  Verification                          | Partially  | Fully      | Partially  |
| **Maturity Level 4 - Quantitatively Managed**                                       |
| OPP - Organizational Process Performance     | Partially  | Not at all | Unknown    |
| QPM - Quantitative Project Management        | Not at all | Not at all | Unknown    |
| **Maturity Level 5 - Optimizing**                                                   |
| CAR - Causal Analysis and Resolution         | Not at all | Partially  | Unknown    |
| OPM - Organizational Performance Management  | Partially  | Not at all | Not at all |

## 1.2 Scrum

| CMMi Process Area | Covered | Rationale  |
| ------------------| ------- | ---------  |
| **Level 2**           |
| CM                | Not at all | There is no explicit mention of this in Scrum. CM is important to software development thus this leads to it becoming the task of the Scrum team having to figure out how to perform it. However, CM can become bigger than just one project and then it is subsequently an organization level concern which can put it out of the scope of Scrum.             |
| MA                | Partially | Scrum specifies some possible measurements like team velocity but not for all of its process areas such as direct insight into the quality of the work produced by a product owner.             |
| PMC               | Partially | Scrum has the notion of sprint goals but not reaching them indicates that the goals are not realistic. There is also velocity which can be used to plan and determine if any form of attempted process improvement is adding any value. Scrum specifies that the Scrum master is responsible for making sure that the team performs optimally but does not formally state everything they should do and how it should be done.           |
| PP                | Fully     | This corresponds with sprint planning meetings where backlog items are selected and broken down into tasks for the upcoming sprint backlog which are then assigned to team members.             |
| PPQA              | Partially | Scrum prescribes some for measures for process quality. These can for example be used by the Scrum master to know when they should aid the team but it says nothing about how to assure the quality of products produced. Most Scrum teams have to incorporate quality assurance into their definition of done for sprint tasks.            |
| REQM              | Fully | The requirements are in user stories in the backlog and are the responsibility of the product owner to determine and formulate.            |
| SAM               | Not at all | Scrum only prescribes some practices on how a team should develop software and does not have information on dealing with a supplier. An organization would need to supplement Scrum with processes for contract management but this is really only relevant for organizations that do subcontracting.              |
| **Level 3**                                 |
| DAR               | Not at all | Scrum does not have any formal evaluation methods which can be used to analyze possible decisions or alternatives. An organization would have to organize meetings specifically to deal with the evaluation of alternative decisions.             |
| IPM               | Partially | There are guidelines in place to manage when stakeholders can interact with their team but for the most part this is up to the product owner.            |
| OPD               | Not at all | This is left entirely up to the wishes of the development team. This means that any processes that are created during projects are not shared with the rest of the organization which can lead to the wheel often being reinvented.              |
| OPF               | Partially | Scrum's retrospective allows for teams to come up with improvements to the process. An organization would need to come up with a process to spread these improvements.             |
| OT   | Not at all | Identifying training needs of an organization and assessing their effectiveness is not covered in Scrum. |
| PI   | Partially | Scrum states that at the end of each sprint a product should be developed, tested and ready for production. It does not cover how this integration should be achieved. |
| RD   | Partially | Scrum addresses this through the use of user stories in the Product Backlog and Sprint Backlog. The responsibility of creating these user stories is entirely delegated to the Product Owner. Scrum does not offer guidelines in how to collect and coördinate stakleholder needs and translate them into requirements.           |
| RSKM | Not at all | Identifying potential risks and how to deal with them is not covered in Scrum.      |
| TS   | Partially | Scrum does not address the consideration and selection of alternative solutions. The design of solutions is left to the development team and takes place during sprints. Scrum offers no guidance in how to create these designs. Implementation and testing of components is covered in the sprint phase of Scrum. |
| VAL  | Partially | A form of validation is done through the Sprint Review in which the product is demonstrated to the stakeholders. Other aspects of validation such as training, manufacturing and maintenance are not covered by Scrum. |
| VER  | Partially | Verification is done in-sprint in the form of testing activities and during the Sprint Review in which the product is demonstrated to its stakeholders. Scrum does not state what kind of methods, such as peer reviews, test methods, etc. should be applied.            |
| **Level 4**                              |
| OPP               | Partially | Organizational process performance is covered in a Sprint Retrospective. However, the retrospective has little quantitive properties. It is based soley on subjective input of inidividual team members and does not deal with objective measurements. |
| QPM               | Not at all | Quantitive management of the project's quality and process performance objectives is not covered in Scrum.           |
| **Level 5**                              |
| CAR               | Not at all | Scrum does not provide a formal process to prevent defects and problems by means of root cause analysis. |
| OPM               | Partially | The responsibilty of this process is delegated to the Scrum Master who optimizes team performance by removing impediments thus enabling the team to meet its business objectives. There are however, no quantitive properties prescribed. |

## 1.3 RUP

| CMMi Process Area | Covered | Rationale  |
| ------------------| ------- | ---------  |
| **Level 2**           |
| CM                | Fully | RUP's configuration and change management workflow covers configuration identification, configuration control, configuration status accounting, and configuration audits.             |
| MA                | Partially | RUP's project management workflow involves an activity for creating a measurement plan. Although, RUP does not exactly specify how this should be communicated to all relevant parties.            |
| PMC               | Fully | The workflow pertaining to project management covers all aspects of monitoring a project against the plan and taking necessary corrective actions.              |
| PP                | Partially | The project management and environment workflows provide adequate support to the project planning. However, they do not determine non-software related project attributes such as labor requirements.                 |
| PPQA              | Fully | The review record in each of RUP's workflows addresses the issue of quality assurance and the creation of the problem resolution plan insures that all quality issues are dealt with.            |
| REQM              | Fully | The requirements workflow integrates change management with the capturing and analyzing of requirements.            |
| SAM               | Not at all | RUP has no elements which dictate interactions with external suppliers, its use is purely centered around development. This may not be an issue as it only applies to organizations that engage in subcontracting.            |
| **Level 3**           |
| DAR               | Not at all | This process area does not seems to be covered in any workflow of RUP. An organization would have to come up with a process that allows for the formal evaluation of alternatives.             |
| IPM               | Fully | The project management and environment workflows encourages the creation of integrated product plans but are lacking when it comes to the management of dependencies.            |
| OPD               | Not at all | RUP is a project methodology and does not prescribe any method for dealing with organizational process assets. RUP must be supplemented with a methodology specifically towards process management otherwise it will be difficult to spread process knowledge from the project to the rest of the organization.             |
| OPF               | Partially | RUP is a project methodology so organizations would need to supplement it with other processes for this area. However, RUP's environment workflow does have an activity which handles the assessment of the development-organization. Another process would be required to ensure this information reaches the rest of the organization.            |
| OT                | Not at all | Identifying training needs of an organization and assessing its effectiveness is not covered in RUP.          |
| PI                | Fully | RUP addresses product integration through its implementation, test and deployment workflows.            |
| RD                | Fully | Mainly through its requirements workflow, RUP provides good support for understanding stakeholder needs, to produce and refine requirements and manage change requests. |
| RSKM              | Fully | RUP itself is a risk-driven development process. It aims to identify as many risks as possible and to tackle them in an early phase (elaboration) of the project.            |
| TS   | Partially | RUP offers good support in this area. The development, design and implementation of solutions are covered in the Analysis & Design workflow. Product components and their documentation are implemented through the Implementation and Deployment workflows. However, RUP does not explicitly cover the consideration and selection criteria for alternative solutions.
| VAL  | Fully | In RUP, validation is covered by a product acceptance plan in the Project Management workflow and through beta testing during Deployment.             |
| VER  | Fully | Verification is covered in RUP by means of planning and conducting system and integration tests. Through its *work guideline* Review it also prescribes the practice of peer reviews.        |
| **Level 4**|
| OPP  | Not at all | This is not in the scope of RUP.           |
| QPM  | Not at all | This is not in the scope of RUP.          |
| **Level 5**        |
| CAR  | Partially | This can be done in an Iteration Assessment. However, RUP does not prescribe any analysis techniques for it.           |
| OPM  | Not at all | This is not in the scope of RUP.             |

## 1.4 HealthCare.gov

| CMMi Process Area | Covered | Rationale  |
| ------------------| ------- | ---------  |
| **Level 2**           |
| CM                | Unknown | There could be no information found on how configuration management was dealt with during the HealthCare.gov project.           |
| MA                | Not at all | Obama claimed to not be well notified about the status of the project and an audit by the Inspector General office showed that CMS did not keep adequate track of records [6]. This indicates that there were no processes defined on how to measure aspects of the project and report them to the relevant parties.             |
| PMC               | Not at all | There were a number of the issues found early in the project's lifecycle during audits, such as how there was not enough time allotted to test the system. The fact that these issues persisted even after the launch of the site indicated that there was little to no control methods in place [9]. Scheduling timely internal audits would have likely aided the project.            |
| PP                | Partially | CMS established a clear plan with deadlines but the organization did not actively maintain these plans throughout the project [2].        |
| PPQA              | Not at all | There were a number of external audits on the project but its clear from the events on the launch date that CMS did not properly deal with this internally [3].            |
| REQM              | Not at all | There was a complete lack of adequate requirements tracking and management, as contractors reported requirements changing up until several weeks before the launch of the website [7].             |
| SAM               | Partially | Formal agreements were in place to manage contractors, but these lacked quality control measures. Furthermore, the employees responsible for awarding the contracts were inexperienced. CMS did not comply with a federal rule requiring employees to receive 96 hours of training if they oversaw contracts worth more than $10 million [6]. |
| **Level 3**           |
| DAR               | Unknown | No information could be found on how this was performed during the project.           |
| IPM               | Partially | CMS was responsible for the project but it was clear that the organization lacked the necessary experience to have standard processes in place for stakeholder involvement and project management.              |
| OPD               | Not at all | The large amount of parties associated with the development of HealthCare.gov made this close to impossible to achieve and there were no explicit processes in place to deal with this.            |
| OPF               | Not at all | The project had a clear lack of leadership and no clear decision-maker [8].            |
| OT                | Unknown | CMS does offer trainings for the Affordable Care Act & the Marketplace, however, these are not targeted for people working in the project organization of HealthCare.gov [11].              |
| PI                | Not at all | CMS did not plan for a lead systems integrator to coordinate all contractors' efforts and integrate their delivered components [12].    |
| RD                | Unknown | The requirements for HealthCare.gov were developed by CMS staff with contractor support. It is not clear how formal this process was [2].     |
| RSKM              | Not at all | CMS did not develop a required acquisition strategy to identify risks and document mitigation strategies [2].          |
| TS                | Partially | While the site had its issues, it was launched on October 1st and did provide a lot of the intended functionality but inadequately.           |
| VAL               | Partially | CMS defined a testing framework that was to establish a consistent, repeatable CMS testing life-cycle process for validation of product components [12].  It is not clear how this framework maps on CMMi. |
| VER               | Partially | Testing was done but up until the last weeks. End-to-end testing was insufficient according to a report from McKinsey & Co. Also the test documentation was missing key elements [12].            |
| **Level 4**                              |
| OPP               | Unknown | There could be no information found on how this process area was dealt with during the HealthCare.gov project.           |
| QPM               | Unknown | There could be no information found on how this process area was dealt with during the HealthCare.gov project.           |
| **Level 5**                              |
| CAR               | Unknown | There could be no information found on how this process area was dealt with during the HealthCare.gov project.  |
| OPM               | Not at all | CMS was responsible for overseeing the performance of subcontractors but did this inadequately according to Office of Inspector General [10].  |

## 1.5 Conclusion Analysis

Scrum and RUP are primarily designed to be software methodologies so they are lacking when they are being measured in terms of the CMMi maturity levels.
This is understandable because CMMi is intended to measure the maturity of organizations. 
This means that any organizations which base their processes on Scrum or RUP would need to supplement the them with more supporting processes. Furthermore, we find that RUP has a better coverage of CMMi than Scrum and that for both methodologies the coverage is spread among the different CMMi levels. Since both Scrum and RUP miss some process areas in level 2, (e.g. Supplier Agreement Management) this means that both are only CMMi level 1 compliant.

|              | Scrum | RUP | HealthCare.gov |
| -------------|-------| --- | -------------- |
| # Not at all | 8     | 7   | 9              |
| # Partially  | 12    | 5   | 6              |
| # Fully      | 2     | 10  | 0              |
| # Unknown    | 0     | 0   | 7              |

It was difficult to obtain knowledge about the implementation of the CMMi process areas within HealthCare.gov. For that, most of the analysis of the different areas was based on outcome and results. From that we can not conclude whether the lack of a defined process or the failure to follow that process was the cause of the problems at HealthCare.gov.

# 2.0 Lean argumentation

The LEAN methodology, also known as a *Toyota Production System*, is an
engineering methodology which has its origin in the production method
that Toyota used to produce its cars. Later, the book *The Goal* from
Elia Goldratt extended the base of the methodology into a more
generalist one. The methodology has spread to other areas, like medicine
or software engineering, and many companies tried to replicate the
process but so far none has been as successful as Toyota applying the
methodology [14, p. 280].

The methodology aims to eliminate everything which is not necessary or
does not have any value for the client, usually referred in general as
“wastes”: overburden (*muri*), inconsistency (*mura*) and over waste
(*muda*) in the process. Eliminating wastes is an effective way to
increase efficiency. To achieve that, they use a system to produce the
**exact** component, in the **exact** moment and the **exact** amount.

The waste is classified in three different types:

- *Muri* is the process overburden, doing things in a sub-optimal way,
  executing processes that take more resources or time than the
  optimal one. It is solved by standardizing the workflow optimally.
- *Mura* is the inconsistency of the stock of products available. It
  is solved by a JIT (Just In Time) inventory: there is only a little
  or no inventory of products or components and when there is a
  request of a product, the components are requested through a pull
  system in which all the components are recursively requested until
  they reach the external supplier.
- *Muda* is the over waste in its more general meaning: all those
  added processes or goods that are not request or have any value for
  the customer. *Muda* can be divided into two types: *muda* type I,
  which has no value for the customer but it is necessary for the
  manufacturing of the product; and *muda* type 2, which has no value
  for the customer and it is not necessary either. It aims to
  eliminate the *muda* type 2 but there is no straightforward way of
  doing it because of the variety of things that can be
  considered waste.

The concept of waste is a traversal concept in other software
development methodologies. *RUP* (Rational Unified Process) focuses on
reducing risks and scrum focuses on delivering product. Both of them do
not pay special attention to waste. Although scrum might look like aims
to reduce waste as they only focus on delivering a product, their focus
is to deliver whichever is the cost. This may lead to sub-optimal
practices.

On one hand, RUP can be more wasteful than scrum. The early stages of
RUP (business modeling, requirements and analysis & design) take a long
period and effort and, although they produce deliverables and artifacts,
they are not the requested one by the client. This qualifies as *muda*
type I, as it is a waste, but it is necessary. This waste does not exist
in scrum. In scrum, the documentation is almost not existing or it is
very reduced based in the Agile Manifesto directives [15]. This means
that the team does not produce any other deliverables but the product
that the client requests.

RUP also has more phases besides development. The early phases focus on
having clear requirements and late ones focus on deployment and testing.
These phases are also present in scrum but they happen in a different
way. In scrum, part of the requirements are gathered by the product
owner from the clients and the other part is done by the developers
during the sprints. The testing and deployment are also integrated
during the sprint instead in a separate phase. In RUP, the division of
the phases aims to reduce the risks in the project by specifying the
details of the project ahead and making sure that the product has been
properly deployed and tested. Although necessary, these phases add extra
waste in terms of processes and management, instead of being integrated
within the development. In scrum, this waste does not exist because it
is considered part of the development and it does not carry extra
overhead due to being integrated into the development phase.

In RUP, the construction phase is done by a requirements team which is
composed by requirement engineers who are not the developers who will
implement the software during the implementation phase. This practice is
sub-optimal because it leads to a situation in which there are
intermediaries and artifacts between the clients and the team that will
implement the product. In scrum, although the requirements are gathered
by the *product owner*, the development team which will implement the
product is involved in the creation of the backlog.

On the other hand, scrum can be more wasteful than RUP. Scrum works with
smalls teams and big projects require more than one scrum team working
on it. This means that those teams would have each one their own *scrum
master* who will act as facilitator and a *product owner* who will talk
with the clients. This situation will lead to role duplicity which is
not optimal at all. It is true that given the case, the scrum master and
the product owner can be shared between different teams but if teams
belong to different organizations or divisions will not happen. RUP only
has one management team which is an improvement in terms of waste over
scrum.

Scrum also focuses on small iterations of the product: features are
added iteration after iteration. The client then will not receive the
final product requested during the first iterations, which is a waste
because it is not what was requested. We understand as an *incomplete
product*, a product which does not have all the features requested
originally by the client. Depending on the definition of done, a
complete product may include the testing and deployment. In addition,
those iterations may lead to having to re-implement features due to
changes in the architecture. This problem, which is inherited from the
agile development philosophy, does not exist in RUP as it has only one
implementation phase. Scrum also requires to perform testing every
iteration for the existing code base, which RUP does only once the whole
project is finished as part of their quality assurance..

Iterative development has the problem also that requires to deliver
products constantly. This leads to a situation in which some operations
need to be repeated every sprint when in RUP they only need to be
performed once when the product is delivered. The backlog needs to be
reviewed after every week, full testing and deployment, retrospectives…
A constant waste that accumulates iteration after iteration of the
partial product.

Scrum might deliver a product which is not the exact one requested. The
*product owner* discusses the details with the clients and
*stakeholders* but during development, the discussions with the
developers during the sprint planning can lead to some features staying
in the backlog and never make it into development, suffer changes or be
directly taken off from it. RUP states that the final product delivered
will be the one discussed during the design phases.

In conclusion, both scrum and RUP are wasteful from the LEAN
perspective. The wastes in scrum are related with the overhead that
having different iterations of the product have attached to it and with
the delivery of incomplete products from the client point of view which
still require testing and finalizing. At certain point, depending of the
definition of done for the product, the amount of waste can vary: an
extensive definition of done would include also testing and deployment,
while other more relaxed could only include the coding. The wastes in
RUP are related to extended design phases and creation of deliverables
(design documents, requirements…) which are not the product requested by
the client. Both scrum and RUP have different objectives in their
methodologies which they are optimized for and the over waste is not a
priority for them.

# 3.0 Looking through the eyes of the 7S model

## 3.1 Introduction

In this chapter we'll take a look at several successful companies. We use the 7S model as a guidance, to understand the different aspects of these organizations. The first company that we've analyzed is Spotify, a company that became very popular over the last years with their music streaming services. Next, we take a look at KLM, that is in a completely other line of business.

Next, we discuss what practices the companies behind HealthCare.gov, a failed software development case, could have learned from the practices of Spotify and KLM. Also we take a small sidestep and look at Heerema Marine Contractors, a successful offshore company. Although they deal with a completely different business, they've found a way to tackle their complex projects. Their practices may be of interest for companies that need to work together with a lot of subcontractors.

Finally, we discuss whether we can learn something about RUP and Scrum, based on our analysis of Spotify and KLM.

## 3.2 Software industry - Spotify

Spotify is a commercial music streaming, podcast and video service, founded in April 2006 by Daniel Ek and Martin Lorentzon. Spotify was launched in September 2008 and by June 2015 Spotify had more than 75 million active users, including about 20 million paid users. 

### 3.2.1 Strategy

Two music streaming tiers: Spotify Free ( a lot advertisements) and Spotify Premium ( paid, remove advertisements, improve audio quality, download available), this is called 'freemium pricing strategy'.
Spotify pays artists based on their 'market share' (the number of streams for their songs as a proportion of total songs streamed on the service). They distribute approximately 70% to rights-holders.
Other competitors in the market like Grooveshark have been shut down as part of legal settlements, because strategies that did not compensate the music production, Spotify even having some artist criticism, has manage to hold some balance between their activities and the music production industry.
Spotify build open and active coalitions among business partners, creating structured channels aiming to ease the use of playlist on many business branches like media, festivals, not-for-profit organizations, audio hardware companies. They also facilitate partnerships at strategic openings for example fitness partners and gift card retailers. 

### 3.2.2 Structure

Spotify headquarters resides in London and its handles, research and development departments are in Stockholm.
Like many other matrix management organizations, Spotify subdivides the work among people with similar skills, and they are pooled for work assignments, resulting in more than one manager with their own responsibilities and competencies. All this managers are from that point, reporting hierarchical button up to the CTO and finally to the CEO.
Further literature does not specify aspect like functional elements (e.g., sales, service, R&D), and how they interact with each other.

### 3.2.3 Systems

How things get done? 
according to [18], Spotify has a culture based on agile principles, that went down to Scum at early years, but some of the scrum practices were getting on the way so they decided to make them optional. Perhaps because they value agile principles more than scrum practices.
All engineering happens in squads (preferably less than 8 members), they try to keep those squads loosely coupled and tightly aligned. I could not find the reasons why they use squads, but perhaps they do it to attempt to minimizing dependencies.
They like cross-pollination instead of 'standardization', in order to spread knowledge, trends and tools between squads. It does not break the principle of 'isolated missions' because cross-pollination is used to spread the uses of tools like github for example. When there is no standard for the use of tools they can lose consistency. Despite this literature indicates that Spotify culture stands for flexibility and they found a happy balance.
Their code is shared on an internal open source model. Again this can be an attempt to avoid dependencies.
Squads make small and frequent releases as a routine, which is enabled due to decoupling their services.
They use release trains and feature toggles aiming get things into production early and often.
They claim that their culture is based on the people, therefore the focus on motivation, community and trust rather than structure and control.
Product development is based on Lean. They release their new features to a small group of customers limiting the 'blast radius' of a possible fail and it allows them to conduct a lot of small experiments. They report that it produces a lot of waste but this can be seen from a Lean perspective. 
They have something called 'core metrics data'. The data is fed dynamically due to constant experimentation.

### 3.2.4 Staffing

Spotify claims to have a very clear definition of what and how employees careers should develop in order to achieve the most important organization goals.[17]"Everyone in *Spotify tech* should have a way to grow their careers and expand the impact of their -work no matter what role they play".
The Spotify technology career framework, consist on letting the employee transfer itself on as many roles and domain expertise as possible in order to gain experience and later evaluate their impact into the organization.
*On recognition and promotions* Spotify observes constantly the impact someone has at a wider scope, and they have a formal ways to promote their employees.
*On setting the step for a new employee* Spotify gives 6 months to all new employees to get involved with their role and the organization.
*On compensation* A formal promotion should lead to higher pay in a straightforward and transparent way.

### 3.2.5 Skills

What is the organization good at?
According to [20]:
Spotify has better social features than its rivals, with the ability to add friends and see their playlists and listening, as well as a built-in messaging system to ping music back and forth. Creating and sharing your own playlists is easy too.
Another strength is the system for following musicians' profiles and getting notifications when they have new music out. A recently introduced concerts feed shows you upcoming, nearby gigs by artists you have listened to, which is useful.
It has good support for devices beyond the desktop and mobile: it is available on Sony’s PlayStation 4, Sonos hi-fis and through Google’s Chromecast and Amazon’s Fire TV, while its mobile app plays nicely with Apple TV too.
Spotify’s free tier has audio advertising, but is missing offline listening and – on mobile – the ability to pick tracks on-demand, although you can play an artist’s catalog on shuffle mode. Pay €9.99 a month, and you get full access (including offline), no ads, and a higher-quality streams option.
Where Spotify falls down is its family plan, which is more expensive than rivals. You can add up to four extra accounts for €4.99 each, but that means you’ll pay €29.95 a month for a family of five compared to Apple Music and Google Play’s €14.99 for six.
Besides all of these, there actually are a couple of easy things to say where Spotify is very good at, like Spotify seems to be good at keeping their organization dynamic, focusing on their community rather to an hierarchical structure.

### 3.2.6 Style

How do the leaders interact with subordinates and others in the organization?
According with [18] Spotify have an Agile engineering culture, which means they like servant leaders rather than process masters.
Autonomy that every member team has over their work has evolve to a high rate percentage of team members satisfaction and they keep investing in it. 
Autonomy also seems to keep high motivation levels [18] [19], teams are fast, and their minimize their dependency from and to, other teams.
 
### 3.2.7 Shared Values

The vision of Spotify is to give people access to all the music they want all the time, in a completely legal manner. 
It is their mission to ensure a fair digital deal for artists.
Spotify's vision is providing music moments everywhere, launching in more markets globally so that any music fan can access that music wherever they are.
Spotify's mission is also keeping the organization a very nice place to work in.

### 3.2.8 External Environment

Despite the evident growing of Spotify, and their alignment with the music industry on matters as fair trades and artist compensations, at the begin of 2015, according to [21] "The financial results reveal that the 25% of Spotify users who pay for the service account for 91% of its income: the company made €982.9m from subscriptions in 2014 and €98.8m  from advertising. Of that overall €1.08bn of revenues, €882.5m was spent on royalties and distribution costs. Spotify’s average headcount increased from 958 in 2013 to 1,354 in 2014, with its personnel costs rising from €114m to €180.9m in that period." Which means Spotify struggles with keeping their business profitable.

## 3.3 Non-Software industry - KLM

Note: Most of the information about the leadership comes from talks with my (Ger) father, who is a copilot for KLM. Therefore there are no official sources to cite and the leadership style is largely from a pilot's point of view. So different departments will likely have other styles of internal management.

### 3.3.1 Strategy

KLM's main strategy is to position itself as a luxury brand. In their advertisement they position flying as something
unique and beautiful, instead of focusing on the price of the tickets. Instead of nickle-and-diming their customers for drinks and food like many other airlines, they prefer to just include it in the ticket price. This gives a more luxurious and relaxed feeling during flights. Together with this they also aim for a very user friendly
atmosphere by focusing a great deal of attention to twitter and Facebook customer service.

In order to establish a better market position, KLM is a member of an airline alliance: Skyteam. Through these alliances airlines expand their global network of destinations. Through this network the airlines can offer a better service to their customers, they can integrate the flights of their allied airlines (this is called code sharing). This helps customers in making it easier to book multi-legged trips, thereby creating a one-stop-shop for virtually any destination in the world. Furthermore, it is customary for alliances to share frequent flyer miles. Which makes customers more likely to choose for an ally of their regular airline when needing to select a different airline, as such creating a stronger binding to their customer.
It has to be noted that this is not a very uncommon strategy. According to the Skytrax (http://www.airlinequality.com/) rating (which is most likely not a very scientific measurement, but it is still a recognized industry benchmark) there is only one five-star airline not participating in an alliance: Hainan Airlines. Likewise, a majority (21 of 38) of the airlines that are rated with four stars are participating in an alliance.

### 3.3.2 Structure

As to be expected of a company with 32.000 employees, the structure is very classical and hierarchical.
The executive committee consists of 13 people [22], each responsible for their subdivision of KLM. This kind of structure is not the best for quick decision making, but it is good at managing very large companies. The main division is done by function. Every occupation is in their own subdivision. Within these divisions there can be further subdivisions as well, for example the pilots have subdivisions based on the type of aircraft that they are flying. For such a global company you would expect that there is a more geographical structure. But pretty much every flight is either from or to Amsterdam or a layover of one of those flights. This means that most of the employees are living in the Netherlands. Of course there are always some exceptions, for example KLM has Asia based flight attendants to help reduce the language barrier on all of their flights to and from Asian destinations.

### 3.3.3 Systems

The advantage of hierarchical systems is that it is usually very easy to identify the chain of command. Within the airplane everyone answers to the Captain and after that to the second in command. Who again answer to the chief of staff for the type of airplane they are flying. Due to the large amount of pilots (2.600) they rarely see the chief of staff though.  The advantage of this is, that it is easy to get things done, when on a trip the Captain is in charge of all decisions and only when something goes seriously wrong, they have to answer to their manager.

As for the actual performance of the job, airlines are surrounded by rules and regulations so most of what they do is done according to strict rulebooks and guidelines. For the customer, this means that they usually have a very consistent experience when flying aboard airplanes.

### 3.3.4 Staffing

A main pro of being a company this big and well known, with a prestigious brand name is that it is not very hard to get the right staff. People know how to find KLM, and this shows. They usually have no open vacancies for aircraft crew. Most open vacancies are usually in the IT field.

### 3.3.5 Skills

As noted before, a main skill of KLM is customer engagement through Twitter and Facebook, this helps in creating a very friendly brand name. Other skills of note are the international networking and cooperation through the Skyteam network, ensuring that you can reach virtually any destination of the world while flying with KLM or one of their partners.

### 3.3.6 Style

KLM's leadership style is very detached from the 'workfloor'. Captains all have their own style of leadership in their airplane. The main way of influence from higher management is through flight plans and regulations. But as stated earlier, pilots really only see their supervisor once something goes really wrong. So if a captain flies slightly faster than planned, which burns more fuel, to be on their destination earlier that will likely not attract any attention at all.  This means that the area in which leadership has the most influence is in all the supporting activities: routes, staff planning, catering, hotels, management, cargo and training.

### 3.3.7 Shared Values

The two Shared Values that KLM hold closest to its heart are: the experience of flying and customer service. In their commercials KLM emphasize the first shared value. In their actions on social media and training of flight crew they pay a great deal of attention to the second shared value`

### 3.3.8 External Environment

Since the economical crisis, airlines have had to deal with a smaller market for their services. A lot of companies chose the budget airline approach. In this approach airline travel is reduced to the bare minimum in order to reduce operating costs and ticket prices. For every extra that you need (food, luggage, etc.) you need to pay a premium. Due to this, companies that didn't change their approach are now the more luxurious companies. KLM is one of these. As stated before, KLM differentiates itself from other airlines by offering great customer service through social media. As such KLM hopes to be ahead of its competitors by creating a better customer engagement.

## 3.4 Failed Case - HealthCare.gov

### 3.4.1 Background

In the previous sections we've analyzed two successful companies, through the eyes of the 7S model. Both very different organizations with very different perspectives and very different visions and missions. During our previous research we've analyzed the case of HealthCare.gov. This website is an integral part of the health care system of the United States. President Obama introduced the 'Obamacare'. The HealthCare.gov website must make sure that all American individuals can find and compare health insurance policies via one website. The system was launched on 01 October 2013. It is still live and in that sense it is not a failed case. However, based on our previous study and our analysis we can conclude that the development and organization of the system has been a failure. The original estimation for the costs of the project was $292 million. Before the launch the costs were already $500 million. According to figures from February 2014 the costs exceeded $1.7 billion by then [26]. Besides the tremendous costs, the launch of the system was surrounded by technical problems. In this section we analyze the case of HealthCare.gov further, by taking a careful look at the practices from successful companies. Despite the big differences between the industry and political organizations, there are organizational practices that can be shared. We want to know what the contractors behind HealthCare.gov could have learned from the practices of Spotify and KLM.

Comparing different companies is always a big challenge. Especially when they are in entirely different industries, this is difficult. It *seems* easier to talk about differences between companies, as companies have different products, a different vision and so on. This also is not the case when we look further then the superficial parts. We then have to take a deeper look at their processes and somehow make a rational comparison. It is required to take a step, or multiple steps, back and look very carefully at the business processes. Are they really that different from each other? Most of the time different outcomes are produced, but from an abstract perspective, similar tasks and procedures are followed. In this section we'll try to make this abstraction. We try to make a comparison and elaborate on whether we think HealthCare.gov could have succeeded when certain practices were applied.

Trying to compare processes between a company like Spotify with the processes within an initiative like HealthCare.gov seems like a futile task at first. Spotify is one company, producing a popular, but limited range of products. What would be the company with whom we compare? Should it be the client, thus the US government? Should it be CGI Federal Inc, one of the 55 (sub)contractors that were responsible for building HealthCare.gov? As our goal is to compare specific (sub)processes, we've decided not to compare at a company level. This would result in skewed findings, due to the very different worlds they live in. In order to make a more useful analysis, we focus on a couple of very specific aspects that we can compare. The 7S model provides us with some guidelines to start our comparison. Based on the lessons from the successful companies, we form some hypotheses how this could have worked for HealthCare.gov.

### 3.4.2 Dealing with knowledge creation & sharing

One of the many challenges for CGI at HealthCare.gov, was managing the amount of (sub)contractors. In total 55 contractors were involved. One of the biggest problems we see when multiple companies are involved, is that there are differences between companies in their perception of quality, success and many other factors. The project was already a challenge from a technical perspective (but not impossible according to our analysis), the real problems are in the project management area. Especially in the area of knowledge creation and sharing. From CMS, the designated systems integrator, we may expect that it is able to work in large collaborations. For other companies this is not a standard operation. These companies are working, more or less, in isolated bubbles and are not (or less) aware of what happens in the outside world. Because of the enormous scale, the biggest challenge was the project management organization. How was knowledge shared between the contractors? More precisely, how did project management make sure that the correct amount of specific knowledge was shared between contractors?

### 3.4.3 Knowledge creation & sharing at Spotify

Spotify is an interesting organization. It grew from 0 to 1800 employees in a period of approximately 10 years. From the total workforce there are approximately 700 employees with a technical profession. This increase of the workforce causes 'growing pains'. In a very small organization communication is still easy, the communication lines are short and everybody knows what everybody is doing. The bigger the company becomes, the more difficult it is to keep an overview. Dividing the work becomes a challenge, sharing knowledge with *everybody* becomes almost impossible. With hundreds of developers, how is it possible to communicate throughout the organization, without overloading the employees with information? How to keep learning from the experiences of the separate teams? And what is the important lesson here for HealthCare.gov?

One thing that Spotify kept in mind, was that they wanted to keep an agile mindset. With their growth, new working structures needed to be developed [16, p.1]. As explained before, the *Squad* is the basic unit. This unit can be compared to a Scrum team. The benefit of this, is that they are self-organizing. It has all the competencies on board that is necessary to fulfill a certain task. The Squad has a Product Owner (PO). The PO is responsible for prioritizing tasks. Furthermore we have an Agile Coach (AC). The AC is responsible to improve the way of working. Next, we have a *Tribe*. A Tribe exists out of a collection of Squads. These work together on particular system functionality. The Tribe has a Tribe Lead (TL), which is responsible for creating a good habitat for the Squads. By keeping the Tribes relatively small (less then 100 employees), it is still possible to limit the amount of *waste*. It is the intention of Spotify, to keep Squads as autonomous as possible. This is a problem when multiple Squads are involved in a certain feature. Thus, dependencies occur. Via surveys and meetings Spotify tries to identify these dependencies in an early stage. This way, they can find better ways to prioritize and deal with activities that compass multiple Squads or even Tribes.

The problem with this working structure is scale. Because of the (relative) autonomous Squads and Tribes, it can happen that reusable knowledge is not shared. One of the structures to prevent this, is a *Chapter*. People with similar skills, that work in similar competence areas, are part of a Chapter. A Chapter has a Chapter Lead (CL), that is responsible for people development. The final structure is a *Guild* and it is referred to as a 'community of interest'. They can best be seen as alliances of groups of employees with similar interests. It cuts through the organization and can encompass more than the other structures. It is a way to share knowledge throughout the organization.

The way how Spotify shares their knowledge within the organization is very interesting. On the lowest level the Squads have quite some freedom to experiment and create new functionality. The different larger structures try to make sure that the knowledge is shared in the organization.

Now, the problem with HealthCare.gov, is that it was not created by one organization. It was created by 55 organizations. Companies with their own culture, vision and ways of working. These are things that are not easily changed. Enforcing one work methodology over these 55 organizations would not have worked. We do think that some of the structures could have been used. Especially the high-level structures are interesting. For example, the concepts behind Chapters and Guilds could have been used for HealthCare.gov. It would be unrealistic to say that all employees with similar competences should discuss this with each other. But perhaps in smaller settings, the different contractors could have shared certain knowledge.

### 3.4.4 Knowledge sharing at KLM

What we've learned from KLM, is that they work together with other airlines in an alliance, the so called 'Skyteam'. The purpose of this setup is to improve their market position, by providing the customer with a better flying experience. The problem that airlines were facing, was that certain knowledge about customers was not shared. Also, services were not shared. This was problematic for the customers, because they've suffered from the problems of coordination between airlines. As explained earlier, these allied airlines solved this by sharing for example flight information. Better, this information is integrated, to help customers with transparently arranging their flights. Also other pieces of customer information are shared. The big benefit for the connected airlines is that they enforce a stronger customer binding.

This 'alliance' and 'sharing' culture, could have been a key factor in making this project work. Of course this situation is not completely comparable with HealthCare.gov. After all, the airlines are seeking a structural solution, where HealthCare.gov was one assignment. The many separate investigations of HealthCare.gov all indicated that none of the involved companies had an overview of what was going on. Although this is a management issue in the end, knowledge creation/sharing is a very important aspect. The complexity of the project can't be used as an excuse for this failure. It would have been a good thing, if the contractors approached this project as one entity. 

### 3.4.5 Dealing with complex projects at Heerema Marine Contractors

Another example, of how these alliances can work, is Heerema Marine Contractors (HMC), a Dutch offshore company that performs complicated projects for the oil & gas industry. Examples are transporting, installation and removing offshore facilities. But also installing subsea pipelines and infrastructures in ultra deep water. The market has forced HMC to think about how they work. Years ago, it was common that all these contractors worked separately at very specific tasks. In the present, the big oil companies tender for much larger projects. This concerns highly complex projects, for example EPCI (Engineering, Procurement, Construction, Installation) projects. The stakes and risks of these projects are incredibly high. HMC realized that they could not do projects on this scale alone. In order to cope with the changing market, HMC decided to join forces with Technip, a large French company with a big engineering capacity. Together they've formed a consortium and they offer their skills on specific projects as one entity. In this alliance, both companies profit from a stronger position in the market. The awarded Kaombo Project by Total E&P Angola, the largest subsea contract ever, is a direct result from this strategy.

### 3.4.6 What can we learn from the successful companies

The interesting question is, whether such a strategy would have made a difference for HealthCare.gov. In an earlier stage of the project, McKinsey already identified risks and root cause drivers [25]. One of these drivers was that there were no clear roles, responsibilities and processes for making change. The fact is, that HealthCare.gov was the most complex website for the government, ever. This was known upfront. What is not clear from the reports, is what the strategy concerning working together was. PMBOK was used as an indicative standard [23, p.5]. But 'indicative' provides too much freedom for a project of this scale. If we take back a step from all the separate findings, we can conclude one thing with certainty. Information was not (properly) shared between contractors and stakeholders. Interviewed employees pointed their finger at other contractors (which is a common action, when things go wrong), for not delivering in time. According to a report contractors were writing a lot of code themselves, where existing code should have been reused [24, p.11]. 

These are only a few of the alarming signals. If the government and CGI knew that this project was of this magnitude of complexity, they've should have taken action in their general strategy. It is very strange for a project like this, that it suffered from 'unclear responsibilities'. This kind of issue could have been prevented by working together as an alliance. In this form, it is not a matter of 'us' and 'they'. The purpose of an alliance, is that it becomes 'we'. That is a subtle, but fundamental difference in perception. It is not realistic that all 55 companies worked in 1 alliance for this case. What *could* have worked, was an alliance of the top-5 companies. There was already a huge, complex organization in the form of the government. At the other side of the table, there were all kinds of loosely connected managing boards of the contractors. The complexity of the organizational structure could have been lowered by having one board of directors at the contractor side. This should have been one entity, with very clear responsibilities. By forming an alliance, the companies could have improved their mutual communication lines a lot, although there is no guarantee that the total performance would have improved. Most alliances are formed with value creation and improvement of long term performance in mind. 

### 3.4.7 Developing shared knowledge processes and shared responsibility

The knowledge creation and sharing is not automatically enforced by forming an alliance. A problem with the amount of contractors was that the responsibility for the end product was not shared among all companies. An alliance would have forced the affiliated companies to create a shared vision. This alone could already make the development of a 'we' mentality possible. If the boards are forced to strategically collaborate and share their information, it is more likely that the work forces do the same. The shared responsibility also would have forced the companies to develop knowledge sharing systems. For example, HMC does this by sharing information via Microsoft Sharepoint systems. Numerous lessons from the project management and Document Control practices have been adopted in these systems.
The way how knowledge is shared between multiple parties is really valued by contractors and clients (BP referred to a 'world class' system). The main message is not that CGI should have used a Sharepoint system, but that the knowledge 'culture' should have been better. We've provided one example of how they could have done that (by forming one or more logical alliances). In the end, the project relied too heavily on contractors and third parties [23, p.6]. We believe that this problem could have been less if a shared vision was in place and if responsibilities were shared. Due to the magnitude of this project, it would have been necessary to do this in a more formal form. Otherwise contractors would have had an easy way out again.

### 3.4.8 Evalution

[TODO...]

## 3.5 RUP - What can we learn?

### 3.5.1 Spotify

Spotify find as a challenge to handle big projects, they consider it a big source of waste since big projects demands a lot of squad to work tightly coordinated. They handle it until recently, visualizing progress with boards, daily sync meetings and weekly demos in order to interact fast with stakeholders. For all cases they acknowledge that there is a lot to discover on that field. Perhaps a RUP approach which promote first risk management would **learn** Spotify to estimate the risk and the cost benefit of incurring in such big projects.

### 3.5.2 KLM

Our insights on KLM do not help in dealing with RUP. RUP is focused on products in changing environments. For example, one of the key components in RUP is requirement management, since these are often changed during the project. KLM does not have this problem, customers buy a ticket and get their transportation to their destination. Every part of the job is done according to strict guidelines and rulebooks, software development is more of a creative job where you do not know how things will go at the start of the project.

## 3.6 Scrum - What can we learn?

### 3.6.1 Spotify

At the beginning Spotify was a scrum company. As we know scrum is a well established Agile development approach, scrum gave the foundations to the team-oriented culture. After some years, some of the scrum practices were getting on the way, for example 'spring planning meetings', 'burndown charts', 'estimation', so they decided to make it optional or "on demand" or even mix with other development approaches.

**We can learn that rules can be a good start, but breaking a rule when is needed can be also a good practice.**

### 3.6.2 KLM

Since scrum is more focused on the team than on the product, a comparison with the KLM flight crew can be made.
The crew aboard an aircraft is not that different from a scrum team. Both teams are self sufficient in the sense that they have everything that they need to get the job done. One of the lessons that could be taken from KLM is that it is perhaps not needed to have a scrum team consist only out of peers. It could perhaps relieve some pressure if there was one 'captain' in a scrum team. Someone who gets the final say over anything the team does, in case there is a dispute about something. This could mean that there is less time spent in meetings, and more doing actual programming. Note that this is different from a product owner. The product owner gets to decide what the team does, and the captain would have the final say in how to do it. A  drawback would be the loss of control for individuals. This may reduce motivation and as such could also lead to a drop in productivity instead of increasing it. 

# 4.0 Power

## 4.1 HealthCare.gov out of control

### 4.1.1 Context

On 23 March 2010, president Obama signed the Patient Protection and Affordable Care Act, better known as Obamacare. One of the consequences of this law was that everyone in the USA would require access to a health insurance marketplace. Therefore the federal government started the HealthCare.gov project. The implementation of the law depended crucially on this website. It was therefore imperative for the Democratic party to make this project a success. On the other hand the Republican party opposed and still opposes the Patient Protection and Affordable Care Act (Obamacare). 

### 4.1.2 Federal shutdown

One of the biggest clashes of this conflict was the United States federal government shutdown that came into effect on the 1st of October 2013. The shutdown was into effect because the U.S. debt-ceiling was reached and the Republican-controlled House of Representatives did not want to raise this ceiling. The main reason according to the American political newspaper Hill [32] and news magazine Time [33] was to delay or defend Obamacare. On the 17th of October 2013 the shutdown ended when the Republicans agreed to raising the debt-ceiling.

### 4.1.3 Parties

The number of parties that are involved in the HealthCare.gov project are enormous. Because of time constraints for this assignment and non disclosed information it is unfeasible to get a complete picture whether all people got the right amount of power. The main focus will be on CMS and CGI federal because there are a lot of disclosed reports [Levinson] from the Office of Inspector General (OIG) who report on these two parties. 

### 4.1.4 CMS

The construction of HealthCare.gov was overseen by Centers for Medicare and Medicaid Services (CMS)  which is a part of the US Department of Health and Human Services (HHS). The primary contractor was CGI Federal who had a contract of around 250 million dollars. Next to that there were 16 official subcontractors, but the total number of subcontractors was actually 55. All under the supervision of CMS. There were also 300 private insurers. All in all there were around 4000 plans. [Levinson]

### 4.1.5 CGI

CGI Federal was the main contractor of the HealthCare.gov project who was awarded with the Federally Facilitated Marketplace (FFM) contract on September 30, 2011 [Levinson]. The FFM supports according to CMS [34] the following functions: Eligibility & Enrollment, Plan Management, Small Business Health Options Program (SHOP) Application, Financial Management and Consumer Support. 

### 4.1.6 Office of Inspector General 

Office of Inspector General (OIG) is an office that is part of Cabinet departments and independent agencies of the Federal government of the United States as well as some state and local governments. Each office includes an Inspector General and employees charged with identifying, auditing, and investigating fraud, waste, abuse, and mismanagement within the parent agency. [35]

## 4.2 Control & Power

### 4.2.1 Failure of CMS

As already was stated CMS was responsible for the overall coordination and planning of the HealthCare.gov project. But it did fail according to reports [27] [28] [36] of the office of inspector general.

When looking at the budget we see that it grew continuously. According to the OIG report [36] the original budget for CGI was $93.7 million, however this grew to $292 million prior to launch of the website. While estimates that the overall cost for building the website had reached over $500 million prior to launch, the Office of Inspector General released a report finding that the total cost of the HealthCare.gov website had reached $1.7 billion. 

According to one report [27] there were inadequacies in contract planning and procurement. The report states: <i>“When awarding the Federal Marketplace contracts, CMS did not always meet contracting requirements. For example, CMS did not develop an overarching acquisition strategy for the Federal Marketplace or perform all required oversight activities. Moreover, for a project of this size and importance, CMS missed opportunities to leverage all available acquisition planning tools and contracting approaches to identify and mitigate risks. Specifically, CMS did not exercise the option to plan for a lead systems integrator to coordinate all contractors’ efforts prior to the launch of the Federal Marketplace. The complexity of the Federal Marketplace underscored the need for CMS to select the most qualified contractors. However, CMS did not perform thorough reviews of contractor past performance when awarding two key contracts. CMS also made contracting decisions that may have limited the number of acceptable proposals for much of the key Federal Marketplace work. In addition, CMS selected contract types that placed the risk of cost increases for this work solely on the Government.“ </i>. 

The office of inspector general Daniel Levinson states in another report [28] that CMS did not always manage and oversee the contractor performance. The main problem according to this report is the lack of control on the contract deliverables.

For example the CMS did not always provide adequate contract management and oversight for Federal marketplace contracts. For example a report of the OIG states [3, p.4]:

<i>“The FFM contract awarded to CGI Federal on September 30, 2011, required the contractor to provide a quality assurance surveillance plan within 45 days of contract award. The plan provides a systematic and structured process for the Government to evaluate the services the contractor will provide, including but not limited to processes, methods, metrics, customer satisfaction surveys, service-level agreements, and operational level agreements. The contractor’s January 2012 status reports showed that the contractor provided its plan on January 19, 2012, more than 2 months after it was required. CMS officials were unable to show us the plan and said that they never received it. The contracting officer’s representative had not questioned the accuracy of the January 2012 status report. " </i>

Not only the IOG states that CMS did not handle the project well. Journalists David Perera and Sean Gallagher speculated that CMS was ill-suited to the task of coordinating all the contractors. Social activist and technologist Clay Johnson later said that the federal government had issues come up given that it "leans towards a write-down-all-the-requirements-then-build-to-those-requirements type of methodology" not well suited to current IT [38].

### 4.2.2 Culture: Alienative, Calculative vs. Moral involvement

Etzioni [29] [30] developed the compliance theory. He classifies organizations by the type of power they use to direct the behavior of their members and the type of involvement of the participants. He identified three types of organizational power: coercive, utilitarian, and normative, and relates these respectively to three types of involvement: alienative, calculative, and moral.  

Robert Kennedy states [31] that people working for the HealthCare.gov project were afraid of being fired because of a mistake this seems to match with a coercive use of power described by Etzioni. According to Etzioni this means that the employees usually react to the organization with hostility, which is alienative involvement.

According to Robert Kennedy [31] a Google employee that worked in is free time in Washington DC at the HealthCare.gov project, people were afraid of making mistakes because they could be fired for it. This way people did not raise any mistakes that they made and therefore the problems that resulted from these mistakes couldn’t be easily resolved.

It seems that this culture of fear resulted that on vital reports were not reacted on the right way. For example on April 4, 2013 a 15-page document by McKinsey & Co. warns among others the CMS administrator that there was insufficient end-to-end testing and advises that a limited initial launch of the website would be ideal. This reports surfaced only half November 2013. One and a half month after the launch. The advise in this report was not followed, because there were only two weeks of end-to-end testing before the launch took place for all the users and there was no limited initial launch. Also other reports and warnings were discarded like that the website as of September 30 could handle only about 1100 users at a time, even though officials have said it should have been able to accommodate perhaps as many as 60,000 users. It seems that people were afraid to be fired or were afraid that the Republicans would use such reports to try to delay or cancel the whole project and with that the whole Obamacare bill.

Robert Kennedy [31] also stated that he met with an employee of one of the site contractors who was in charge of software “security.” When he asked her which penetration threats she had prepared for, she responded that she did not think about such things: she was in charge of “risk assessment.”. In contractor terms, that meant the risk of government contract non-fulfillment. She saw that her job was to ensure that a software audit confirmed that the software was “secure” as defined in the contract. So the overall security objective was not to make sure that the system was difficult to hack, but that the contractual terms were met.

### 4.2.3 Intervention

The question that you could ask after reading the previous part is: why does someone not intervene and end the project or replaces contractors? This is not a question that I can answer, but I can speculate about this with the information we have.

### 4.2.4 So who is really in control?

My speculation is that there was a political will and power to make Obamacare a success. Therefore everything was put into place to get the HealthCare.gov system up and running as soon as possible. The costs were not a priority and issues about for example performance were neglected. The Democrats wanted to get system to work on 1 October 2013. I think it is an achievement that there was some kind of a workable system created in two years time with so many parties involved. Because after the Obamacare was signed it took one and a half year before CGI Federal got the FFM contract. To get a project of this magnitude finished in two years is very challenging if not impossible. 

In 2014 the contract of CGI Federal was not extended and they were replaced by Accenture Federal on February 28th 2014 [37]. But why did Accenture replaced CGI? “Marilyn Tavenner, the CMS administrator, and Kathleen Sebelius, the U.S. health secretary, each told Congress in hearings late last year that CGI had failed to meet expectations under its contract.” [40]. But is it a good choice replacing one big consultancy company with another? Accenture did led construction of California’s better-performing state system [40]. According to a blog of Luke Chung [39] big government contractors like CGI and Accenture are to big to be fired. Also the have no accountability according to Chung. ”The large companies can deflect the blame and legally challenge any attempt to hold them accountable”. Chung also states: “What happened with Healthcare.gov is exactly what our system encourages contractors to do. Had the contractors finished on time and properly, they would have made less money than delivering a flawed system.”. This kind of situations also occur in the Netherlands. A documentary called “the spaghetticode” [41] is about failed IT-projects. One case that is mentioned in this documentary is about a big consultancy company called Cap Gemini. The assignment was to modernize a system for one of the agencies of the department of Social Affairs called the SVB. The system that needed to be modernized is responsible for payment of allowances and retirement. The conclusion is that the government finally pulls the plug out of the system without it functioned one day. Curiously, the Capgemini bills are simply paid. The damage: tens of millions of euros of taxpayers' money seem to have disappeared. 

### 4.2.5 Is the power in balance?

My point of view is that it is not. CMS has to do what the Obama administration tells them to do and follow their political agenda. Even despite all warnings [27] [28] and even if it is impossible to get it done. Should not it be possible for the CMS to say to politician: “no, we can’t”? 

### 4.2.6 Knowledge is power

From all the sources in read (see references below) I get the idea that CMS and politicians are experts in legislation, but know little about IT. On the other hand, the contractors are experts in IT (or you expect them to be). If you take the maxim “knowledge is power”, then you could argue that the contractors have a big advantage towards the government. 

### 4.2.7 Did the government learn from his failure? 

I can not tell, because I do not have enough information. But here are my thoughts. Robert Kennedy [31] noted that there was a culture of fear. According to the compliance theory of Etzoini [30] this will create a hostile environment. My thought is that in a hostile environment people can not work optimal, because they're busy first feeling them safe and cover up the mistakes the made. This is also what Robert Kennedy noticed [31]. I do not know if the culture is changing within the U.S. government, but I argue that the use of more calculative and normative power as Etzoini calls it [30] will be beneficial. 

Next to that I think that the risks of projects needs to be put more at the contractor side. I don’t know if this is the case for FFM contract with Accenture.

From my experience in the past as an employee of Accenture and reading all the HealthCare.gov reports, I see a certain pattern. The pattern is that at the end of a tender of a big IT government project always the usual suspects pop up as the winners like Accenture, CGI, Atos, Capgemini [42]. There seems to be little competition. I think it will benefit the government if it changes the tender process so that there will be more competitors. Especially if these contractors focus on delivering software that works(functional, performance, etcetera wise) instead of just delivering what the requirements tell to do and charging extra money for everything extra you did not think of. Another way is that the government is stating there requirements better, but I think this does not happen because the don’t have IT-experience to know which security risk are out there.

## 4.3 Scrum

### 4.3.1 Power in Scrum

Scrum evangelizes empowerment.
The Scrum team is self-organizing and structured and empowered by the organization to manage their  own work.
The development team decides how to do the work.
In Scrum, accountability lies within the whole team.
The team creates a definition of done, which controls the level of quality of the product.
This also leads to a lack of control, that the management can exert.

Dan Ariely experimented with motivation and found out, that people are more productive when they receive feedback on their work.
In his experiment, he let people write down the double letters on a sheet of random letters. They tracked how many sheets the subjects would finish. They experimented with three conditions for receiving the paper from the subject:
- In the first condition, the experimenter would receive the paper, look at it and nod and add it to the stack of finished papers.
- In the second condition, the experimenter would not look at the paper and simply add it to the stack of finished papers.
- In the third condition, the experimenter would shred the paper in front of the subjects eyes.

The result of this experiment is, that the subjects in the first condition finished a lot more papers than the subjects in the third.
The people in the second condition did better than the ones in the third, but not by much[43].
At the end of each sprint in Scrum, there is a sprint review, in which stakeholders give feedback. 
Considering the results of the experiments of Ariely, this should increase the motivation of the team.
However, there is no conclusive evidence that Scrum and agile practices increase productivity [44][45][46][47].
One thing to be considered, is that in this experiment, motivation lead to more productivity, but they only looked at when the subjects gave up, not at the amount of time spent.
This leaves open the question whether a high motivation makes you more productive given a fixed time frame.
The impact of motivation on performance is a complex matter. Recognition of ones work is proven to impact performance [48]

The development team within the Scrum team decides *how* to do their work.
The product owner decides what is on the backlog and in which order.
The individual members of the development team actually have no say in which priority the items on the backlog get.
They can advise the product owner, but the final decision lies only with the product owner.
If the product owner has a different vision for the product than the development team, this can also lead to friction and lack of motivation.

### 4.3.2 Control in Scrum

Robert Simons describes four levers for harnessing control:
- Beliefs systems
- Diagnostic control systems
- Boundary systems
- Interactive control systems

He argues that a combination of these levers is required to ensure effective control (with examples of what can happen when you do not) [49].
Scrum provides a some forms of diagnostic control.
By having a sprint review each sprint, the stakeholders can have an overview of the results of the previous sprint and have the chance to influence the coming sprint(s).
Scrum puts a lot of emphasis on leaving the control to the development team.
Since Scrum does not ensure that a combination of the four levers of control is utilized properly, a project done with Scrum can still fail, due to a lack of, or the wrong application of control (the same examples given by Simons apply [49]).

### 4.3.3 Learning organizations and Scrum

Peter Senge defines five disciplines of a learning organization [51].
- Systems thinking
- Personal mastery
- Mental models
- Shared vision
- Team learning

All these characteristics contribute to a learning organization (with systems thinking integrating the other four).
Scrum supports a shared vision, to a certain degree, by having a definition of done shared by all teams, working on the same product.
Teams also reflect on their own performance and mental models during the retrospective in each sprint.
When applying scrum at a larger scale, there is no inherent mechanism in Scrum to ensure a shared vision throughout the whole company.
Other than the composition of Scrum teams, Scrum does not define how an organization should be structured and how changing company goals can be related back to the teams.

## 4.4 RUP

### 4.4.1 Power in RUP

Because RUP has six specific engineering disciplines, it limits the power of the individual, you only have power to make decisions concerning the discipline you are in.
Because of this specialization, you can exert increased influence using expertise, as described in French and Raven's five bases of power [50].

# 5.0 Conclusion

[TODO...]

[This is important. In the last report there were not any final lessons or takeaways. Please think about this and update]

# References

## CMMi

[1] CMMI Product Team (2010), "CMMI for Development" Version 1.3" 

[2] United States Government Accountability Office, "HEALTHCARE.GOV Ineffective Planning and Oversight Practices Underscore the Need for Improved Contract Management", July 2014. http://www.gao.gov/assets/670/665179.pdf  

[3] Ballotpedia.org, "Healthcare.gov website rollout - Ballotpedia", 2016. https://ballotpedia.org/Healthcare.gov_website_rollout.

[4] Ken Schwaber, Jeff Sutherland, “The Scrum Guide”, Scrum Alliance, 2013.

[5] P. Kruchten, The rational unified process. Reading, Mass: Addison-Wesley, 1999.

[6] Ihealthbeat.org, "Audit Details Lapses in CMS Oversight Prior to HealthCare.gov Launch - iHealthBeat", 2015. http://www.ihealthbeat.org/articles/2015/9/15/audit-details-lapses-in-cms-oversight-prior-to-healthcaregov-launch.

[7] The New York Times, “From the Start, Signs of Trouble at Health Portal”, 2013.

[8] HotAir.com, "A lack of leadership, not technological prowess, doomed the healthcare.gov launch - Hot Air", 2016. http://hotair.com/archives/2016/02/24/a-lack-of-leadership-not-technological-prowess-doomed-the-healthcare-gov-launch/. 

[9] Allen,J.(2013). Report warned of HealthCare.gov laws last spring. http:// www.politico.com/story/2013/11/report-warned-of-healthcaregov-flaws-last-spring-100037.html

[10] Levinson, Daniel. “CMS Did Not Always Manage and Oversee Contractor Performance for the Federal Marketplace as Required by Federal Requirements and Contract Terms”, Office of Inspector General, September 2015.

[11] CMS, "Affordable Care Act & the Marketplace", Webpage. 
https://www.cms.gov/Outreach-and-Education/Look-Up-Topics/ACA-and-Marketplace/Affordable-Care-Act-and-the-Marketplace-page.html

[12] United States Government Accountability Office, "CMS Has Taken Steps to Address Problems, but Needs to Further Implement Systems Development Best Practices", March 2015. http://www.gao.gov/assets/670/668834.pdf

## Lean

[14] Jayanth Jayaram, Ajay Das, Mariana Nicolae, Looking beyond the obvious: Unraveling the Toyota production system, International Journal of Production Economics, Volume 128, Issue 1, November 2010, Pages 280-291.

[15] "Principles behind the Agile Manifesto." Principles behind the Agile Manifesto. Accessed February 28, 2016. http://www.agilemanifesto.org/principles.html

## 7S

[16] Kniberg, H., & Ivarsson, A. (2012). [Scaling Agile@Spotify](https://creativeheldstab.com/wp-content/uploads/2014/09/scaling-agile-spotify-11.pdf). *UCVOF*.

[17] Spotify, [Spotify labs](https://labs.spotify.com/2016/02/15/spotify-technology-career-steps/).

[18] Spotify, [Spotify Engineering Culture - part 1](https://vimeo.com/user14023874/spotify-engineering-culture-part1).

[19] Dan Pink, [The science of human motivation](https://youtu.be/rrkrvAUbU9Y?list=PLjzx_gymL6dPiP6c9YlA96dT8beeAehXe).

[20] The guardian[Which is the best music streaming service?](http://www.theguardian.com/technology/2016/feb/16/which-is-the-best-music-streaming-service-spotify-apple-music).

[21] The guardian [Spotify financial results show struggle to make streaming music profitable](http://www.theguardian.com/technology/2015/may/11/spotify-financial-results-streaming-music-profitable).

[22] Web, ["KLM Management"](http://www.klm.com/corporate/nl/about-klm/management/).

[23] Anthopoulos, L., Reddick, C. G., Giannakidou, I., & Mavridis, N. (2015). [Why e-government projects fail? An analysis of the Healthcare. gov website](http://www.sciencedirect.com/science/article/pii/S0740624X15000799). Government Information Quarterly.

[24] Chambers & Associates Pty Ltd (2014, April), [Case Study Analysis Saving Obamacare](http://www.chambers.com.au/public_resources/case_study/obamacare/saving-obamacare-case-study-analysis.pdf).

[25] LaFraniere, S., & Lipton, E. (2013). [Officials were warned about health site woes](http://www.nytimes.com/2013/11/19/us/politics/administration-open-to-direct-insurance-company-signups.html?pagewanted=all&_r=1).

[26] Levinson D.R. (2014, August). [An overview of 60 contracts that contributed to the development and operation of the federal marketplace](http://oig.hhs.gov/oei/reports/oei-03-14-00231.asp). Office of inspector general.

## Power

[27] [Federal Marketplace: inadequacies in contract planning and procurement]  (http://oig.hhs.gov/oei/reports/oei-03-14-00230.pdf)

[28] [Levinson, Daniel. “CMS Did Not Always Manage and Oversee Contractor Performance for the Federal Marketplace as Required by Federal Requirements and Contract Terms”, Office of Inspector General, September 2015, Report.] (http://oig.hhs.gov/oas/reports/region3/31403001.pdf)

[29] Etzioni, A. (1975). A comprehensive analysis of complex organizations (rev. ed.). New York, NY: Free Press.
 
[30] Etzioni, A. (1997). Modern organizations. Englewood Cliffs, NJ: Prentice Hall.

[31] [The Failure of HealthCare.gov Exposes Silicon Valley Secrets, Charles Petrie, (August 30, 2014)] (https://pdfs.semanticscholar.org/4b50/4337ca7cee8f5e6916e46832550f1f60088d.pdf)

[32] [Joseph, Cameron (October 9, 2013). "Heritage Action leader: Paul Ryan's shutdown offer off-target". The Hill.](http://thehill.com/blogs/ballot-box/house-races/327469-conservative-leader-paul-ryans-shutdown-offer-off-target) 

[33] [Miller, Zeke J (September 30, 2013). "Hidden Hand: How Heritage Action Drove DC To Shut Down". Time.] (http://swampland.time.com/2013/09/30/hidden-hand-how-heritage-action-drove-dc-to-shut-down/)

[34] [CMS, “Federal Marketplace Progress Fact Sheet”] (https://www.cms.gov/CCIIO/Resources/Fact-Sheets-and-FAQs/ffe.html)

[35] [Inspector General, “IG_Authorities_Paper”, (July 14, 2014)] (https://www.ignet.gov/sites/default/files/files/IG_Authorities_Paper_-_Final_6-11-14.pdf)

[36] [Levinson, Daniel. “An Overview of 60 Contracts That Contributed to the Development and Operation of the Federal Marketplace”. Office of Inspector General, August 2014, Report.] (http://oig.hhs.gov/oei/reports/oei-03-14-00231.pdf)

[37] [Yahoo News “Accenture named lead contractor for Obamacare website: government”] (http://finance.yahoo.com/news/accenture-chosen-lead-contractor-obamacare-website-government-220550193--sector.html)

[38] ["How Healthcare.gov Went Wrong". dobt.co.] (http://blog.dobt.co/2013/10/10/how-healthcare-gov-went-wrong/)

[39] [Luke Chung (7 December 2013). "Too Big to Fire: How Government Contractors on Healthcare.gov Maximize Profits"] (http://blog.fmsinc.com/too-big-to-fire-healthcare-gov-government-contractors//)

[40] [Bloomberg, “CGI to Be Replaced by Accenture on Obamacare Contract”] (http://www.bloomberg.com/news/articles/2014-01-10/cgi-to-be-replaced-by-accenture-on-obamaacre-contract)

[41] [Zembla, “Spaghetticode”] (http://zembla.vara.nl/seizoenen/2015/afleveringen/02-09-2015)

[42] [Consultancy.uk, “Consultancy Fees & Rates"](http://www.consultancy.uk/consulting-industry/fees-rates)

[43] Dan Ariely, Emir Kamenica, Drazen Prelec [Man’s search for meaning: The case of Legos](http://faculty.chicagobooth.edu/emir.kamenica/documents/meaning.pdf) Journal of Economic Behavior & Organization 67 (2008) 671–677.

[44] Eliza S. F. Cardozo et al. [SCRUM and productivity in software projects: a systematic literature review](http://dl.acm.org/citation.cfm?id=2227073) EASE'10 Proceedings of the 14th international conference on Evaluation and Assessment in Software Engineering (2010) 131-134

[45] Philipp Diebold, Marc Dahlem[Agile Practices in Practice: A Mapping Study](http://dl.acm.org/citation.cfm?id=2601254)EASE '14 Proceedings of the 18th International Conference on Evaluation and Assessment in Software Engineering (2014)

[46] Gabriela Robiolo, Daniel Grane [Do agile methods increase productivity and quality?])(http://article.sciencepublishinggroup.com/pdf/10.11648.j.ajsea.20140301.11.pdf)Published online April 20, 2014 (http://www.sciencepublishinggroup.com/j/ajsea)

[47] Cleviton V. F. Monteiro et al.[A qualitative study of the determinants of self-managing team effectiveness in a scrum team](http://dl.acm.org/citation.cfm?id=1984646) CHASE '11 Proceedings of the 4th International Workshop on Cooperative and Human Aspects of Software Engineering (2011)

[48] Ukaejiofo Rex Uzonna [Impact of motivation on employees' performance: A case study of CreditWest Bank Cyprus](http://www.academicjournals.org/article/article1380794547_Ukaejiofo.pdf) Journal of Economics and International Finance Vol 5 August 2013 199-211

[49] Robert Simons [Control in an age of empowerment](https://hbr.org/1995/03/control-in-an-age-of-empowerment)Harvard Business Review (1995)

[50] John R. P. French, Bertram Raven [The Bases of Social Power](http://web.mit.edu/curhan/www/docs/Articles/15341_Readings/Power/French_&_Raven_Studies_Social_Power_ch9_pp150-167.pdf)

[51] Peter Senge [Learning Organization](https://en.wikipedia.org/wiki/Learning_organization)

# Appendix A - Process Area Descriptions

The following is a list of the CMMI process areas for Development along with a description of their purpose. All information was acquired from the official CMMI for Development report [1].

### Maturity Level 2 - Managed

#### Configuration Management 

The purpose of Configuration Management (CM) is to establish and maintain the integrity of work products using configuration identification, configuration control, configuration status accounting, and configuration audits.

#### Measurement and Analysis

The purpose of Measurement and Analysis (MA) is to develop and sustain a measurement capability used to support management information needs.

#### Project Monitoring and Control

The purpose of Project Monitoring and Control (PMC) is to provide an understanding of the project's progress so that appropriate corrective actions can be taken when the project's performance deviates significantly from the plan.

#### Project Planning

The purpose of Project Planning (PP) is to establish and maintain plans that define project activities

#### Process and Product Quality Assurance

The purpose of Process and Product Quality Assurance (PPQA) is to provide staff and management with objective insight into processes and associated work products.

#### Requirements Management

The purpose of Requirements Management (REQM) is to manage the requirements of the project's products and product components and to identify inconsistencies between those requirements and the project's plans and work products.

#### Supplier Agreement Management

The purpose of Supplier Agreement Management (SAM) is to manage the acquisition of products from suppliers for which there exists a formal agreement.

### Maturity Level 3 - Defined

#### Decision Analysis and Resolution

The purpose of Decision Analysis and Resolution (DAR) is to analyze possible decisions using a formal evaluation process that evaluates identified alternatives against established criteria.

#### Integrated Project Management

The purpose of Integrated Project Management (IPM) is to establish and manage the project and the involvement of the relevant stakeholders according to an integrated and defined process that is tailored from the organization's set of standard processes.

#### Organizational Process Definition

The purpose of Organizational Process Definition (OPD) is to establish and maintain a usable set of organizational process assets.

#### Organizational Process Focus

The purpose of Organizational Process Focus (OPF) is to plan and implement organizational process improvement based on a thorough understanding of the current strengths and weaknesses of the organization's processes and process assets.

#### Organizational Training

The purpose of Organizational Training (OT) is to develop the skills and knowledge of people so they can perform their roles effectively and efficiently.

#### Product Integration

The purpose of Product Integration (PI) is to assemble the product from the product components, ensure that the product, as integrated, functions properly, and deliver the product.

#### Requirements Development

The purpose of Requirements Development (RD) is to produce and analyze customer, product, and product-component requirements.

#### Risk Management 

The purpose of Risk Management (RSKM) is to identify potential problems before they occur so that risk-handling activities can be planned and invoked as needed across the life of the product or project to mitigate adverse impacts on achieving objectives.

#### Technical Solution

The purpose of Technical Solution (TS) is to select design and implement solutions to requirements. Solutions, designs, and implementations encompass products, product components, and product related lifecycle processes either singly or in combination as appropriate.

#### Validation

The purpose of Validation (VAL) is to demonstrate that a product or product component fulfills its intended use when placed in its intended environment.

#### Verification

The purpose of Verification (VER) is to ensure that selected work products meet their specified requirements.

### Maturity Level 4 - Quantitatively Managed

#### Organizational Process Performance

The purpose of Organizational Process Performance (OPP) is to establish and maintain a quantitative understanding of the performance of the organization's set of standard processes in support of quality and process-performance objectives, and to provide the process performance data, baselines, and models to quantitatively manage the organization's projects.

#### Quantitative Project Management

The purpose of the Quantitative Project Management (QPM) process area is to quantitatively manage the project's defined process to achieve the project's established quality and process-performance objectives.

### Maturity Level 5 - Optimizing

#### Causal Analysis and Resolution

The purpose of Causal Analysis and Resolution (CAR) is to identify causes of defects and other problems and take action to prevent them from occurring in the future.

#### Organizational Performance Management

The purpose of Organizational Performance Management (OPM) is to proactively manage the organization’s performance to meet its business objectives.
