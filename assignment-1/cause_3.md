# Change Management

In order to shop for a healthcare plan, consumers had to register on the site for an account first. 
It was reported that the response times of the registration pages were very high with load times up to 71 seconds [9,21].
This symptom occured because architecture was not able to handle the concurrent users for the registration pages. 
Around September 2013, just weeks before the deadline, a decision was made that all users had to register first, before they could start shopping for a health plan [22]. Because of this change the registration pages became a bottleneck for the entire site. The changing functional requirement had a major impact on the architecture of the site.

## Key factor in failure

Many failures regarding performance were due to a poor architectural design in the first place which in turn was caused by the omission of well defined quality constraints [1]. This was discussed in the previous chapter. 
However, the cause for the performance problems at the registration pages was a requirement that changed in a late stage during the development. The requirement had a major impact on the architectural constraints of the site that was not captured. Changing requirements during the course of a project is a common phenomenon in software engineering. We analysed whether Scrum or RUP have proper mechanisms to deal with this and if these mechanisms could have prevented the problems at HealthCare.gov.

|         | Description                                                                       |
| ------- | --------------------------------------------------------------------------------- |
| Symptom | High response times for the registration pages.                                   |
| Failure | The architecture could not handle the many concurrent users.                      |
| Cause   | Three months before the deadline a requirement changed that stated that consumers | 
|         | must register before able to shop for health plans.                               |
| Context | Changing requirements with major architectural impact.                            |
| Problem | No mechanism to deal with changing requirements.                                  |

## Scrum

In Scrum requirements are expressed in Product Backlog Items and are maintained by a Product Owner who is also 
the sole person reposonsible for them. These Product Backlog Items can change any time up until the moment they become 'in sprint' and are being developed by the Development Team. It is during the Sprint Planning at the start of each Sprint that the Development Team descides on how to implement the Product Backlog Items requested by the Product Owner [17]. Scrum however does not specify what the 'how' should answer in terms of quality constraints. Capturing the impact of the change at HealthCare.gov would have been greatly dependent of the expertise of the Development Team or Product Owner. 

Another principle of Scrum is that at the end of each Sprint the team delivers a fully tested and deployable product. In general, if this were the case at HealthCare.gov the performance failure would still have occurred but it would be detected within the duration of a sprint. The project management would than have more time to handle the problem. Note however, that this specific requirement change was made weeks before the final deadline so having sprints would have made no difference either.

Overall Scrum does not provide well defined mechanisms to handle quality assurance needed when dealing with changing requirements.

## RUP

The Rational Unified Process (RUP) is an iterative software development process. One of the ten essentials 'Change Requests' specifically deals with changing requirements by providing a process for risk and impact analysis for any proposed change [23].

> "The benefit of Change Requests is that they provide a record of decisions, and, due to their assessment process,
> ensure that impacts of the potential change are understood by all project team members. The Change Requests are essential
> for managing the scope of the project, as well as **assessing the impact of proposed changes.**" [23]

It is this part of RUP that could have prevented the performance problems during registrations. Had the change been properly analysed on its impact it could have on the architecture, the project team could have decided to make the proper adjustments 
on the architecture.
