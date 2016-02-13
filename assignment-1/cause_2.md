# Architecture - rigid and lacking non-functional requirements

## Key factors in failure

One of the primary problems with HealthCare.gov was its performance.
The architecture was designed to pass on requests from the web servers real-time to the back-end systems.
The system was not designed to be able to handle the high loads that it faced after going to production [2].
Late during development, they discovered that the new requirements would need changes in the architecture.
However, the current architecture did not provide the flexibility to allow such changes in it.

Another one of the problems the site faced, was that there were a number of security vulnerabilities [6].
These came to light during a security breach in the July of 2014. The breach was discovered by a CMS security team in the following month. It occurred due to a development server not being properly configured and this led to malware being uploaded to the system. 


##  Software development methodologies

Could the problems stated above have been fixed by using software methodologies?


### Scrum

The back-end of HealthCare.gov is reported to have been built using agile practices but they were likely not applied correctly due to the project having explicit phases defined such as testing [1].
In Scrum, architecture is designed as required for the next production increment [5]. This does not necessarily lead to the architecture becoming more flexible.
If a Scrum approach would have been implemented properly, a minimal viable product would have been created first, which should have already contained the performance requirements.
The different teams working on the project should have agreed on a definition of done.
A large amount of work on HealthCare.gov was left unfinished during the launch [8]. 
A clear and formal definition of done would have resulted in an architecture containing all quality attributes of the system. 
However, a minimal viable product might not have included integration with all systems, which is where the performance really starts to hurt.

On the other side of the spectrum, the front-end of HealthCare.gov is considered to be a success. A start-up known as Development Seed was responsible for the front-end of the website and made use of agile practices [1].


### Rational Unified Process

A number of contractors have said that on the day of the launch that the site was tested and apparently could not even handle 1000 concurrent users . This likely indicates an issue with validating the architecture[].
Next to iterative development, RUP also defines phases of a project's lifecycle [4].
In the elaboration phase, most of the architecture should be done. At HealthCare.gov most of the architecture was also done up front. This did not help them forsee the problems that occured during the go-live.
RUP does promote a risk first approach. If RUP would have been properly implemented, the riskier parts of the process, such as integration and  performance, would have been tackled in the beginning.


### MARS Rover

The software methodology used to build the Mars rover is based on risk-reduction principles [7].
The U.S. government has built a large number of software systems and thus has a history of security vulnerabilities that can possibly occur.
One of the security vulnerabilities found was due to a development system being configured with default credentials which is a mistake made by the developers.
This made it possible for an automated attacker to take advantage of the system and thus use it to upload malware [6].
Apparently this weak-link in the security was not identified in the architecture of HealthCare.gov.
If CMS were to have taken measures to reduce the amount risk involved when building the system, this would have have likely prevented the vulnerability, simply due to it being an extremely common error.
The development system would have been properly identified as a point of weakness. Because of this, it would not have been insecurely configured.


## References

[1] A. Jeffries, "Why Obama's Healthcare.gov launch was doomed to fail", The Verge, 2013. [Online]. Available: http://www.theverge.com/2013/10/8/4814098/why-did-the-tech-savvy-obama-administration-launch-a-busted-healthcare-website. 

[2] USA TODAY, "Obama adviser: Demand overwhelmed HealthCare.gov", 2016. [Online]. Available: http://www.usatoday.com/story/news/nation/2013/10/05/health-care-website-repairs/2927597/. 

[3] M. Heusser, "6 Software Development Lessons From Healthcare.gov's Failed Launch", CIO, 2016. [Online]. Available: http://www.cio.com/article/2380827/developer/developer-6-software-development-lessons-from-healthcare-gov-s-failed-launch.html. 

[4] P. Kruchten, The rational unified process. Reading, Mass.: Addison-Wesley, 1999.

[5] Schwaber, Ken. Scrum development process, 1997.

[6] Cbsnews.com, ""Critical" flaw found in HealthCare.gov security", 2016. [Online]. Available: http://www.cbsnews.com/news/critical-flaw-found-in-healthcare-gov-security/. 

[7] A. Scoică, "Profile Benjamin Cichy", XRDS: Crossroads, The ACM Magazine for Students, vol. 20, no. 3, pp. 68-69, 2014.

[8] B. Ehley, "After 2 Years and $2.1 Billion, HealthCare.gov Is Unfinished", The Fiscal Times, 2016. [Online]. Available: http://www.thefiscaltimes.com/2015/03/05/After-2-Years-and-21-Billion-HealthCaregov-Unfinished. 
