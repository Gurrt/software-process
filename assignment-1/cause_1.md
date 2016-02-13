# Contractor Management

## Key factors in failure

One of the most important reasons for the failure of the *HealthCare.gov*
project, from the process and management point of view, was a mismanagement of contractors.

The *Center for Medicare & Medicaid Services* (CMS) depended heavily on
contractors to develop and manage the *Federal marketplace*. Federal law
prescribes precise rules that contractor officers need to follow in order
to manage the performance of the contractors. The following mistakes were
made during the project [3]:

* **Contracting officers did not receive all
  contract deliverables and periodically neglected to use those to monitor the contractors
  performance.** Law enforces the contractor officers and their representatives
  to monitor the performance of their contractors. Sometimes reports were incomplete
  and deliverables handed in months after their deadlines, without any explanation requested by or given to the CMS.

* **Unauthorised CMS personnel added work and increased the cost of one of the
  contracts.** Contractor officers added extra work to one contract without having the authority to issue such work, around 40 work units were added for a total extra cost of $28 million.

* **Contract officer's representatives were not properly designated and
  authorised in written contracts.** 75% of the contracts reviewed missed
  important information like the contracting officer's representative or the
  specific duties and responsibilites assigned for each contract.

* **CMS's contracting officer representatives did not have the required certification.**
  Contracts that are valued at more than 10 million dollar require a Level III certifcation in risk management.
  Not all contracting officer's representatives, who worked with contracts of this size possesed the required certification.

* **CMS has not complied with the standards of ethical conduct in atleast one occasion.** In one case, one of the CMS panel members responsible for        awarding a contract had recently worked together with the party that applied for the contract, thus creating a possible conflict of   interests. The employee did not raise this as an issue to his supervisor(s) and as such acted in conflict with the CMS's ethical code.
 
* **Contracting officers did not always prepare contractor past-performance
  evaluations**. Some contracts were not registered at the instituion that keeps
  a record of government contractors. Subsequently, the CMS did not perform
  performance reviews for those contracts that are required for the logs of that institution.

## Scrum

### Principles applied during the project

A key part of the Scrum methodology is to prioritise communication over documentation.
Due to the all the legal requirements and licensing required for big government project like this one
scrum was not used as process for the overall project. Some of the contractors, like Development Seed [6], used Agile methods for their development internally. Unfortunately, the main problem for the contractors was in their communication with the CMS,
who were not involved on such a low level of the project.

### Which principles could help HealthCare.gov?

According to the Scrum Guide (http://www.scrumguides.org/scrum-guide.html#team) Scrum is most effective in small teams with up to 9 people. Considering the sheer size of this project, a pure Scrum approach for the entire project would have likely done more harm than good.
However, some parts of Scrum could have benefitted the CMS.

Take for example a **product backlog** together with having a dedicated **product owner**; These could have stopped unauthorized CMS employees from changing the scope of the project. Any product that needs to be added to backlog would have to be added by the product owner, who can check if the request is legitimate ( assuming that all product owners are authorized to change the scope of the contract ).

The main problem in this case was the lack of control on the contract deliverables. Perhaps if the CMS worked with a Scrum flow which included a **demo** phase, those deliverables could be incrementally shown to the CMS stakeholders, even if they aren't software but documents e.g. security audit reports and progress reports. However, the report by Daniel Levinson [3] makes it sound like the main cause for missing these deliverables is because CMS was not enforcing them too strictly. So for this approach to yield any success, the contract officers would also need to take a more professional stance on the deliverables.

## RUP

### Principles applied during the project

* Vision: The vision of what to build was clear, thousands of pages of legal
  documents provided documentation on what to build exactly.[1]

* Plan: The product was planned to launch on 1 October 2013 and did so. Testing
  was planned for two weeks before launch [2]. The plan might not have been
  ideal, but it was there.

* Risks: Laws on contracting dictate what has to be done to supervisor
  contractors to mitigate risks, however those laws were not always followed
  [3]. This means that this principle was not followed correctly.

* Issues: Due to a lack of data, it is hard to tell what has been done in order
  to track issues.

* Architecture: While there was an architecture set to integrate all the
  services, it was not designed to handle to load that it got on the launch
  day.[4]

* Product: This step focuses mainly on building the product step by step and
  testing it during every step. In some cases this was done, with the front-end
  for example. The front-end was made by [Development
  Seed](https://developmentseed.org/) and the non-interactive part of this went
  live before the rest of HealthCare.gov. This part of the HealthCare.gov
  website was generally well received and appreciated for its modern take on
  government websites [6]. While the system as a whole was only
  tested two weeks before launch. Which was too short to find all important
  bugs, and too close to launch to fix all the problems that were found.

* Evaluation: This principle assumes an interative approach, which was not
  present during the building of HealthCare.gov. So this principle was not
  followed at all.
* Change Requests: The Obama administration kepy modifying regulations and policies of the Affordable Care Act,
  which inherently meant that the scope of the HealthCare.gov website kepy changing too.
  Which probably has caused some hardship with the changes trickling down to all the contractors, but there is a lack
  of documentation on how the changes were documented and implemented.

### Which principles could help HealthCare.gov?

As stated above, a stricter monitoring of the deliverables by the contractors
could have helped this project. What also could have prevented the failure was
a better focus on product and evaluation. If a more Agile way of working was
promoted, with small deliverables, that can be tested. Then perhaps bugs and
the wrong scale for the architecture could have been identified earlier,
while there was still time to fix the problems. Instead of when the integration
happened, two weeks before the launch.

## Mars Lander

The Mars Lander's development approach focuses on durability and reliability to the extreme.
Judging by how the HealthCare.gov website only worked correctly for 1% of the visitors during their
launch week, this was not the case for the HealthCare.gov website.

Every part that is aboard the Mars Lander needs to go through a qualification testing procedure of
12 to 15 months. And then when all the components are combined there is another qualification testing
procedure which can take a few years [5]. This shows that the Mars Lander team takes their integration
tests very seriously, which was not the case for the CMS with all the missing deliverables.

Ofcourse there is a downside to this as well. If the CMS was to implement qualification testing on this
scale, costs for the project would likely skyrocket and the project would take longer. Then again, the
HealthCare.gov is not flying through space, where maintenance is impossible to perform. So the CMS could
definitely profit by looking how NASA does its integration tests and implementing those, albeit on a 
smaller scale.


## Sources

[1] Cleland-Huang, Jane. "Don't Fire the Architect! Where Were the Requirements?." Software, IEEE 31.2 (2014): 27-29.

[2] Morgan, David &  Humer, Caroline. "Timeline: U.S. healthcare law's technology breakdown" Reuters, 30 October 2013, Web. 9 February 2015.

[3] Levinson, Daniel. "CMS Did Not Always Manage and Oversee Contractor Peformance for the Federal Marketplace as Required by Federal Requirements and Contract Terms", Office of Inspector General, September 2015, Report.

[4] Anthopoulos, L., et al., Why e-government projects fail? An analysis of the HealthCare.gov website, Government Information Quarterly (2015), http://dx.doi.org/10.1016/j.giq.2015.07.003

[5] Harwoord, William. "Slow, but rugged, Curiosity's computer was built for Mars" CNET, 10 August, 2012, Web. 12 February 2015.

[6] Ford, Paul. "The Obamacare Website Didn't Have to Fail. How to Do Better Next Time", 16 October 2013, Web. 13 February 2015.
