# CMMI

In this section we examine to which extent the various CMMi Development process areas are covered in Scrum, RUP and HealthCare.gov. For this we used the CMMi for Development report. The analysis of Scrum is based the content in the Scrum Guide [SGUIDE]. Likewise the analysis of RUP is based on the RUP book [RUPBOOK]. 

> Note to document integrators: The Process Area Descriptions may be moved to an appendix.

## Process Area Descriptions

The following is a list of the CMMI process areas for Development along with a description of their purpose. All information was acquired from the official CMMI for Development report [CMMIREP].

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

## Analysis Overview

| Cmmi Process Area | Scrum | RUP | HealtCare.gov |
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

## Scrum

| Cmmi Process Area | Covered | Rationale  |
| ------------------| ------- | ---------  |
| **Level 2**           |
| CM                | Not at all | There is no explicit mention of this in Scrum. CM is important to software development thus this leads to it becoming the task of Scrum team having to figure out how to perform it.             |
| MA                | Partially | Scrum specifies some possible measurements such as team velocity but not for all of its process areas such direct insight into the quality of the work produced by a product owner.             |
| PMC               | Partially | Scrum has the notion of sprint goals but not reaching them indicates that the goals are not realistic. There is also velocity which can be used to plan and determine if any form of attempted process improvement is adding any value. Scrum specifies that the Scrum master is responsible for making sure that the team performs optimally but does not formally state everything they should do and how it should be done.           |
| PP                | Fully     | This is corresponds with sprint planning meetings where backlog items are selected and broken down into tasks for the upcoming sprint backlog which are then assigned to team members.             |
| PPQA              | Partially | Scrum prescribes some for measures for process quality. These can for example be used to by the Scrum master to know when they should aid the team but it says nothing about how about to assure the quality of products produced using it. Most Scrum teams have to incorporate quality assurance into their definition of done for sprint tasks            |
| REQM              | Fully | The requirements are in user stories in the backlog and are the responsibility of the product owner to determine and formulate.            |
| SAM               | Not at all | Scrum only prescribes some practices on how a team should develop software and does not have information on dealing with a supplier. An organization would need to supplement Scrum with processes for contract management but this is really only relevant for organizations that do subcontracting.              |
| **Level 3**                                 |
| DAR               | Not at all | Scrum does not have any formal evaluation method which can be used analyze possible decisions or alternatives. An organization would have to organize meetings specifically to deal evaluation alternative decisions.             |
| IPM               | Partially | There are guidelines in place to manage when stakeholders can interact with their team but for the most part this up to the product owner            |
| OPD               | Not at all | This is left entirely up to the wishes of the development team. This means that any processes that are created during projects are not shared with the rest of the organization which can lead to the wheel often being reinvented.              |
| OPF               | Partially | Scrum's retrospective allows for teams to come up with improvements to the process. An organization would need to come up with a process to spread these improvements.             |
| OT   | Not at all | Identifying training needs of an organization and assessing their effectiveness is not covered in Scrum. |
| PI   | Partially | Scrum states that at the end of each sprint a product should be developed, tested and ready for production. It does not cover how this integration should be achieved. |
| RD   | Partially | Scrum addresses this through the use of user stories in the Product Backlog and Sprint Backlog. The responsibility of creating these user stories is entirely delegated to the Product Owner. Scrum does not offer guidelines in how to collect and coördinate stakleholder needs and translate them in requirements.           |
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

## RUP

| Cmmi Process Area | Covered | Rationale  |
| ------------------| ------- | ---------  |
| **Level 2**           |
| CM                | Fully | RUP's configuration and change management workflow covers configuration identification, configuration control, configuration status accounting, and configuration audits.             |
| MA                | Partially | RUP's project management work flow involves an activity for creating a measurement plan. Although, RUP does not exactly specify how this should be communicated to all relevant parties.            |
| PMC               | Fully | The work flow pertaining to project management covers all aspects of monitoring a project against the plan and taking necessary corrective actions.              |
| PP                | Partially | The project management and environment work flows provide adequate support to the project planning. However, they do not determine non-software related project attributes such as labor requirements.                 |
| PPQA              | Fully | The review record in each of RUP's work flows addresses the issue of quality assurance and the creation of the problem resolution plan insures that all quality issues are dealt with.            |
| REQM              | Fully | The requirements work flow integrates change management with the capturing and analyzing of requirements.            |
| SAM               | Not at all | RUP has no elements which dictate interactions with external suppliers, its use is purely centered around development. This may not be an issue as it only applies to organizations that engage in subcontracting.            |
| **Level 3**           |
| DAR               | Not at all | This process area seems to not be covered in RUP in any work flow. An organization would have to come up with process that allows for the formal evaluation alternatives.             |
| IPM               | Fully | The project management and environment work flows encourages the creation of integrated product plans but are lacking when it comes to the management of dependencies.            |
| OPD               | Not at all | RUP is a project methodology and does not prescribe any method for dealing with organizational process assets. RUP must be supplemented with a methodology specifically towards process management otherwise it will be difficult to spread process knowledge from the project to the rest of the organization.             |
| OPF               | Partially | RUP is a project methodology so organizations would need to supplement it with other processes for this area. However, RUP's environment work flow does have an activity which handles the assessment of the development-organization. Another process would required to ensure this information reaches the rest of the organization.            |
| OT                | Not at all | Identifying training needs of an organization and assessing its effectiveness is not covered in RUP.          |
| PI                | Fully | RUP addresses product integration through its implementation, test and deployment workflows.            |
| RD                | Fully | Mainly through its requirements workflow RUP provides good support for understanding stakeholder needs, produce and refine requirements and manage change requests. |
| RSKM              | Fully | RUP itself is a risk driven development process. It aims to indentify as many risks as possible and to tackle them in an early phase (elaboration) of the project.            |
| TS   | Partially | RUP offers good support in this area. The devopment, design and implementation of solutions are covered in the Analysus & Design workflow. Product components and their documentation are implemented through the Implementation and Deployment workflows. However, RUP does not explicitly cover the consideration and selection criteria for alternative solutions.
| VAL  | Fully | In RUP, validation is covered by a product acceptance plan in the Project Management workflow and through beta testing during Deployment.             |
| VER  | Fully | Verification is also covered in RUP by means of planning and conducting system and integration tests. Through its *work guideline* Review it also prescribes the practice of peer reviews.        |
| **Level 4**|
| OPP  | Not at all | This is not in the scope of RUP.           |
| QPM  | Not at all | This is not in the scope of RUP.          |
| **Level 5**        |
| CAR  | Partially | This can be done in an Iteration Assessment. Howerver, RUP does not prescribe any analysis techniques for it.           |
| OPM  | Not at all | This is not in the scope of RUP.             |

## HealthCare.gov


| Cmmi Process Area | Covered | Rationale  |
| ------------------| ------- | ---------  |
| **Level 2**           |
| CM                | Unknown | There is no information found on how configuration management was dealt with during the HealthCare.gov project.           |
| MA                | Not at all | Obama claimed to not be well notified about the status of the project and an audit by the Inspector General office showed that CMs did not keep adequate track of records [IHBEAT]. This indicates that there were no processes defined on how to measure aspects of the project and report them to the relevant parties.             |
| PMC               | Not at all | There were a number of the issues found early in the project's lifecycle during audits, such as how there was not enough time allotted to test the system. The fact that these issues persist even after the launch of the site indicated that there was little to no control methods in place [POLI]. Scheduling timely internal audits would have likely aided the project.            |
| PP                | Partially | CMS established a clear plan with deadlines but the organization did not actively maintain these plans throughout the project [GAOR].        |
| PPQA              | Not at all | There were a number of external audits on the project but its clear from the events on the launch date that CMS did not properly deal with this internally [BAP]            |
| REQM              | Not at all | There was a complete lack of adequate requirements tracking and management, as contractors reported requirements changing up until several weeks before the launch of the website [NYTIMES].             |
| SAM               | Partially | Formal agreements were in place to manage contractors, but these had a lack of quality control measures. Furthermore, the employees responsible for the awarding contracts were inexperienced. CMS did not comply with a federal rule requiring employees who oversee contracts worth more than $10 million to receive 96 hours of training [IHBEAT].            |
| **Level 3**           |
| DAR               | Unknown | No information could be found on how this was performed during the project.           |
| IPM               | Partially | CMS was responsible for the project but it was clear that organization lacked the necessary experience to have a standard processes in place for stakeholder involvement and project management.              |
| OPD               | Not at all | The large amount of parties associated with the development of HealthCare.gov made this close to impossible to achieve and there were no processes in place to deal with this.            |
| OPF               | Not at all | The project had a clear of leadership and no clear decision-maker [HOTA].            |
| OT                | Unknown | CMS does offer trainings for the Affordable Care Act & the Marketplace, however, these are not targeted for people working in the project organization of HealthCare.gov. [TRAINING]             |
| PI                | Not at all | CMS did not plan for a lead systems integrator to coordinate all contractors' efforts and integrate their delivered components. [LEVINSON2]    |
| RD                | Unknown | The requirements for HealthCare.gov were developed by CMS staff with contractor support. It is not clear how formal this process was. [GAO2]     |
| RSKM              | Not at all | CMS did not develop a required acquisition strategy to identify risks and document mitigation strategies. [GAO2]         |
| TS                | Partially |            |
| VAL               | Partially | CMS defined a testing framework that was to establish a consistent, repeatable CMS testing life-cycle process for validation of product components. [GAO1] It is not clear how this framework maps on CMMi. |
| VER               | Partially | Testing was done but up until the last weeks. End-to-end testing was insufficient according to a report from McKinsey & Co. Also test documentation was missing key elements. [GAO1]           |
| **Level 4**                              |
| OPP               | Unknown | There is no information found on how this process area was dealt with during the HealthCare.gov project.           |
| QPM               | Unknown | There is no information found on how this process area was dealt with during the HealthCare.gov project.           |
| **Level 5**                              |
| CAR               | Unknown | There is no information found on how this process area was dealt with during the HealthCare.gov project.  |
| OPM               | Not at all | CMS was responsible to oversee the performance of subcontractors but did this inadequate according to Office of Inspector General. [LEVINSON] |

## Conclusion

Scrum and RUP are primarily designed to be software methodologies so they are lacking when they are being measured in terms of the CMMI maturity levels.
This is understandable because CMMI is intended to measure the maturity of organizations. 
So any organizations which base their processes on Scrum or RUP would need to supplement the them with more supporting processes. Furthermore, we find that RUP has a better coverage of CMMi than Scrum and that for both methodologies the coverage is spread among the different CMMi levels. Since both Scrum and RUP miss some process areas in level 2, (e.g. Supplier Agreement Management) this means that both are CMMi level 1 compliant.

|              | Scrum | RUP | HealthCare.gov |
| -------------|-------| --- | -------------- |
| # Not at all | 8     | 7   | 9              |
| # Partially  | 12    | 5   | 6              |
| # Fully      | 2     | 10  | 0              |
| # Unknown    | 0     | 0   | 7              |

It was difficult to obtain knowledge about the implementation of the CMMi process areas within HealthCare.gov. For that, most of the analysis of the different areas was based on outcome and results. From that we can not conclude whether the lack of a defined process or the failure to follow that process was the cause of the problems at HealthCare.gov.

## References

[CMMIREP] CMMI Product Team (2010), "CMMI for Development, Version 1.3" 

[GAOR] United States Government Accountability Office, "HEALTHCARE.GOV Ineffective Planning and Oversight Practices Underscore the Need for Improved Contract Management", July 2014  

[BAP] Ballotpedia.org, "Healthcare.gov website rollout - Ballotpedia", 2016. [Online]. Available: https://ballotpedia.org/Healthcare.gov_website_rollout. [Accessed: 26- Feb- 2016].

[SGUIDE] Ken Schwaber, Jeff Sutherland, “The Scrum Guide”, Scrum Alliance, 2013.

[RUPBOOK] P. Kruchten, The rational unified process. Reading, Mass: Addison-Wesley,
1999.

[IHBEAT] Ihealthbeat.org, "Audit Details Lapses in CMS Oversight Prior to HealthCare.gov Launch - iHealthBeat", 2015. [Online]. Available: http://www.ihealthbeat.org/articles/2015/9/15/audit-details-lapses-in-cms-oversight-prior-to-healthcaregov-launch. [Accessed: 20- Feb- 2016].

[NYTIMES] The New York Times, “From the Start, Signs of Trouble at Health Portal”,
2013.

[HOTA] HotAir.com, "A lack of leadership, not technological prowess, doomed the healthcare.gov launch - Hot Air", 2016. [Online]. Available: http://hotair.com/archives/2016/02/24/a-lack-of-leadership-not-technological-prowess-doomed-the-healthcare-gov-launch/. [Accessed: 26- Feb- 2016].

[POLI] Allen,J.(2013). Report warned of HealthCare.gov laws last spring. Retrieved from http:// www.politico.com/story/2013/11/report-warned-of-healthcaregov-flaws-last-spring-100037.html

[LEVINSON] Levinson, Daniel. “CMS Did Not Always Manage and Oversee Contractor Performance for the Federal Marketplace as Required by Federal Requirements and Contract Terms”, Office of Inspector General, September 2015, Report.

[CHAMERS] Chambers & Associates Pty Ltd, Case Study Saving Obamacare. 

[LEVINSON2] Levinson, Daniel. "Federal Marketplace: Inadequacies in Contract Planning and Procurement", January 2015, Report.

[TRAINING] CMS, "Affordable Care Act & the Marketplace", Webpage. 
https://www.cms.gov/Outreach-and-Education/Look-Up-Topics/ACA-and-Marketplace/Affordable-Care-Act-and-the-Marketplace-page.html

[GAO1] "CMS Has Taken Steps to Address Problems, but Needs to Further Implement Systems Development Best Practices", March 2015, Report. http://www.gao.gov/assets/670/668834.pdf

[GAO2] "Ineffective Planning and Oversight Practices Underscore the Need for Improved Contract Management", July 2014, Report.
http://www.gao.gov/assets/670/665179.pdf

[CGI5] "CGI’s Federal Health and Compliance Programs Business Unit becomes 10th in the United States to achieve CMMI® Development Maturity Level 5 rating", https://www.cgi.com/en/CGI-Federal-Health-Compliance-Programs-Business-Unit-achieves-CMMI-Development-Maturity-Level-5-rating
