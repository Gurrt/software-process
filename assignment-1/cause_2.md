# Architecture - rigid and lacking non-functional requirements

One of the problems with healthcare.gov was the performance.
The architecture was designed to pass on requests from the webservers real-time to the backend systems.
The system was not designed to be able to handle the high loads that it faced during go-live.
Late during development, they discovered that the new requirements required changes in the architecture.
However, the current architecture did not provide the flexibility to allow such changes in it.

Another one of the problems the site faced, was that there were a number of security vulnerabilities.
These came to light during a security breach in the July of 2014. The breach was discovered by a CMS security team in the following month. It occurred due to a development server not being properly configured and this led to malware being uploaded to the system. 


# Architecture - Software methodologies

Could the problems stated above have been fixed by using software methodologies?


#Scrum

In Scrum, architecture is designed as required for the next production increment. This does not necesarily make it a more flexible architecture.
If a Scrum approach would have been implemented properly, a minimal viable product would have been created first, which should  have already contained the performance requirements.
The different teams working on the project should have agreed on a definition of done, including all quality attributes of the system. 
However, a minimal viable product might not have included integration with all systems, which is where the performance really starts to hurt.

//Development Seed was responsible for the front-end of the website and made use of agile practices. The front-end is apparently considered to be a success. The back-end is also reported to have been built using agile practices but they were likely not applied correctly due to the project having explicit phases defined such as testing.


#RUP

Next to iterative development, RUP also defines phases of a projects lifecycle.
In the elaboration phase, most of the architecture should be done. At healthcare.gov most of the architecture was also done up front. This did not help them forsee the problems that occured during go-live.
RUP does promote a risk first approach. If RUP would have been properly implemented, the riskier parts of the process, such as integration and  performance, would have been tackled in the beginning.

//A number of contractors have said that on the day of the launch that the site was tested and apparently could even handle 1000 concurrent users. This likely indicates an issue with validating the architecture.


#MARS

The software methodology used to build the Mars rover is based on risk-reduction principles.
The U.S. government has built a large number of software systems and thus has a history of security vulnerabilities that can possibly occur.
One of the security vulnerabilities found was due to a development system being configured with default credentials which is an inexcusable mistake made by the developers.
This made it possible for an automated hostile to take advantage of the system and thus use it to upload malware. Apparently this weak-link in the security was not identified in the architecture of healthcare.gov. If CMS were to have taken measures to reduce the amount risk involved when building the system, this would have have likely prevented the vulnerability, simply due to it being an extremely common error. The development system would have been properly identified as a point of weakness. Because of this, it would not have been insecurely configured.
