# Change Management
-----

In order to shop for a healthcare plan, consumers had to register for an account first. 
It was reported that the response time of the registration pages were very high with load times up to 71 seconds. [source]
Analysis showed that the architecture was not able to handle the concurrent users for the registration pages. 
[source] It was reported that around September 2013, three months before the deadline,
the decision was made that all users had to register first, before they could start shopping for a health plan. 
Because of this the registration pages became a bottleneck for the entire site. 
The changing functional requirement had a major impact on the architecture of the site.

|         | Description                                                                                  |
| ------- | --------------------------------------------------------------------------------- |
| Symptom | High response times for the registration pages                                    |
| Failure | The architecture could not handle the many concurrent users.                      |
| Cause   | Three months before the deadline a requirement changed that stated that consumers | 
|         | must register before able to shop for health plans.                               |
| Problem | No mechanism to deal with changing requirements.                                  |
| Context | Changing requirements with major architectural impact.                            |

# Key factor in failure

Many failures regarding performance were due to a poor architectural design which in turn was caused by the omission
of quality requirements. [source don’t fire the architect] This was discussed in the previous chapter. 
[review: make sure it is] However the cause for the performance problems at the registration pages was caused 
by a requirement that changed in a late stage during the development. The requirement had a major impact on the 
architectural constraints of the site that was not captured. 

# Scrum

* Requirements can change until they are in-sprint.
* Product Owner responsible for requirement specification in product backlog.
* No mechanisms for dealing with QA in scrum, except maybe in DoD.
* Capture of the impact of the requirement would be dependent on the expertise of the product owner.
* SCRUM would offer no solution

# RUP



# Mars


