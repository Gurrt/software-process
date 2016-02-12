## Failed case : Healthcare.gov

##### Initial complexity.

The construction of healthcare.gov was overseen by Centers for Medicare and Medicaid Services (CMS) which is a part of the US Department of Healt and Human Services (HHS). The primary contractor was CGI. Next to that there were 16 official subcontractors, but the total number of subcontractors was actually 55. All under the supervison of CMS

The client were according to [4, page 6]: Department of Health and Human Services (HHS); Others: CMS, HHS, 36 States, 300 private insurers, U.S. Chief Technology Office, GAO, Media, Citizens, Social Security Administration, the Internal Revenue Service, Veterans Administration, Office of Personnel Management, Peace Corps, etc.

The internal architecture of healthcare.gov is very complex. US residents who want to apply for an insurance needed a lot of personal information from different systems. Like their income and immigration status. The system needs to connect with all the different systems from the federal government. Like the Internal Revenue Service, Social Security Administration, the Peace Corps, etcetera. The idea was the information of all the different federal systems should be retrieved real time. According to [4]: 
>“The U.S. Chief Technology Officer Todd Park has said that the government expected HealthCare.gov to draw 50,000 to 60,000 simultaneous users but that the site was overwhelmed by up to five times as many users in the first week.“

#####Timeline of problems and solutions.
The Government Accountability Office (GAO) reported in June 2013 that there could be trouble with the goal of launching the website on the first of October 2013.

During its launch (1 October 2013) the website did not perform well. Only 271,000 of the 9.47 million users that try to registrate where succesfull. ?There was already $700 million dollar spend? In 2014 the total number of costs of the project is 1.7 billion dollar (reference). Intuitively I ask myself what would have happened if they had established a schedule of access to the site?. There were official warnings telling that the site was going to be unable to accommodate so many users at once.

An extra team is recluted (22th October 2013) It was recognized that product testing was insufficient. Serious underestimation of time.

QSSI is selected as the contractor responsible to now oversee federal website fixes (October 27, 2013). A single data center brings down the mission-critical website and should be presumed and avoided. Such requirements should be identiﬁed and addressed before project completion.

(October 31, 201) Again an unrealistic schedule, site crash for second time due small amount of servers, an explicit gap at project definition and planning.

(November 14, 2013) President Obama declares to press that he wasnt good inform of the situation. The project team was not prepared for the failure.

(November 30, 2013)  Enrollment statistics show that 137,000 individuals had signed up for plans using the site compared to the 227,000 that had enrolled through the 14 state run exchanges.

Obama Administration set deadline of a working site for the “vast majority” of users. (December 1, 2013)


### Failure causes & possible solutions.
The failure was caused by a complex interplay of problems:

##### Managing Contractors:
 6. Contractor delays and performance issues were not always identified.
 7. A contractor incurred unauthorized costs that increased the cost of the contract.
 8. Contracting officers in all Government agencies did not have access to contractor past-performance evaluations when making contract awards.
 9. Critical deliverables and management decisions were not properly documented.
 
> At this excerpt extracted from [source] we add the question: **where could it change?**. A stricter monitoring of the deliverables by the contractors which deliverables were small and testable, could have helped this project.


##### Architecture: non functional requirements.
 1. The system was not designed to handle the massive influx of initial users. 
 2. Insufficient effort made to build a system that would meet the performance and availability needs of it's stakeholders. 
 3. Security solutions were seemingly slapped together in a shoddy manner instead of through the kind of systematic approach that is expected in a highquality software solution.
 4. Many thousands of pages of legal healthcare regulations did not translated seamlessly into functional requirements.
 5. The basic architecture was designed and built around the notion that the system would forward requests for quotes from insurance seekers to external vendors in real-time; however, this massive interconnectivity and the subsequent burden on the government servers caused the system to collapse.

>However, all these points, extracted from [1] are an compilation of the triggers of the problem, but **where could it change?**
Besides all the disastrous organizational perspective, and scoping at the missing functional requirements, the elicitation, documentation and communication of those requirements probably could have helped this project. There are many structured techniques specifically designed to learn others about the system and what it should carry, some techniques such as 'planguage' or 'volere templates'.


 
##### Architecture: Change Managment.
The inability to handle a growing amount of work, its potential to be enlarged in order to accommodate that growth, or a limited space to accommodate iterations can be a very dangerous thing. In this case, three months before the deadline a requirement changed.
>**where could it change?** Finding scales and meters, RUP, and many others patterns and methods.


#### Sources

[1] Cleland-Huang, Jane. "Don't Fire the Architect! Where Were the Requirements?." Software, IEEE 31.2 (2014): 27-29.

[2] Morgan, David &  Humer, Caroline. "Timeline: U.S. healthcare law's technology breakdown" Reuters, 30 October 2013, Web. 9 February 2015.

[3] Levinson, Daniel. "CMS Did Not Always Manage and Oversee Contractor Peformance for the Federal Marketplace as Required by Federal Requirements and Contract Terms", Office of Inspector General, September 2015, Report.

[4] Anthopoulos, L., et al., Why e-government projects fail? An analysis of the Healthcare.gov website, Government Information Quarterly (2015), http://dx.doi.org/10.1016/j.giq.2015.07.003

[5] Government Accountability Office (GAO) (2013). “Patient protection and affordable care act: Status of CMS efforts to establish federally facilitated health insurance exchanges.” (GAO-13-601), 19 June 2013.

[6] Tom Gilb (Planguage). (2001) Intel Corporation "Quantifying Quality Requirements Using Planguage" by Erik Simmons.


