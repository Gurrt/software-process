# Architecture - rigid and lacking non-functional requirements

One of the problems with healthcare.gov was the performance.
The architecture was designed to pass on requests from the webservers real-time to the backend systems.
The system was not designed to be able to handle the high loads that it faced during go-live.
Late during development, they discovered that the new requirements required changes in the architecture.
However, the current architecture did not provide the flexibility to allow such changes in it.

# Architecture - Software methodologies
Could the problems stated above have been fixed by using software methodologies?

#Scrum
In Scrum, architecture is designed as required for the next production increment. This does not necesarily make it a more flexible architecture.
If a Scrum approach would have been implemented properly, a minimal viable product would have been created first, which should  have already contained the performance requirements.
The different teams working on the project should have agreed on a definition of done, including all quality attributes of the system.
However, a minimal viable product might not have included integration with all systems, which is where the performance really starts to hurt.

#RUP
Next to iterative development, RUP also defines phases of a projects lifecycle.
In the elaboration phase, most of the architecture should be done. At healthcare.gov most of the architecture was also done up front. This did not help them forsee the problems that occured during go-live.
RUP does promote a risk first approach. If RUP would have been properly implemented, the riskier parts of the process, such as integration  and  performance, would have been tackled in the beginning.


#MARS
// TODO