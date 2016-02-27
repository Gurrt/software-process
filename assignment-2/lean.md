The LEAN methodology, also known as a *Toyota Production System*, is an
engineering methodology which has its origin in the production method
that Toyota used to produce its cars. Later, the book *The Goal* from
Elia Goldratt extended the base of the methodology into a more
generalist one. The methodology has spread to other areas, like medicine
or software engineering, and many companies tried to replicate the
process but so far none has been as successful as Toyota applying the
methodology. \[1, pp 280\]

The methodology aims to eliminate everything which is not necessary or
does not have any value for the client, usually referred in general as
“wastes”: overburden (*muri*), inconsistency (*mura*) and over waste
(*muda*) in the process. Eliminating wastes is an effective way to
increase efficiency. To achieve that, they use a system to produce the
**exact** component, in the **exact** moment and the **exact** amount.

The waste is classified in three different types:

- *Muri* is the process overburden, doing things in a suboptimal way,
  executing processes that take more resources or time than the
  optimal one. It is solved by standardising the workflow optimally.
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
is to deliver whichever is the cost. This may lead to suboptimal
practices.

On one hand, RUP can be more wasteful than scrum. The early stages of
RUP (business modelling, requirements and analysis & design) take a long
period and effort and, although they produce deliverables and artefacts,
they are not the requested one by the client. This qualifies as *muda*
type I, as it is a waste, but it is necessary. This waste does not exist
in scrum. In scrum, the documentation is almost not existing or it is
very reduced based in the Agile Manifesto directives \[2\]. This means
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
suboptimal because it leads to a situation in which there are
intermediaries and artefacts between the clients and the team that will
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
belong to different organisations or divisions will not happen. RUP only
has one management team which is an improvement in terms of waste over
scrum.

Scrum also focuses on small iterations of the product: features are
added iteration after iteration. The client then will not receive the
final product requested during the first iterations, which is a waste
because it is not what was requested. We understand as an *incomplete
product*, a product which does not have all the features requested
originally by the client. Depending on the definition of done, a
complete product may include the testing and deployment. In addition,
those iterations may lead to having to reimplement features due to
changes in the architecture. This problem, which is inherited from the
agile development philosophy, does not exist in RUP as it has only one
implementation phase. Scrum also requires to perform testing every
iteration for the existing codebase, which RUP does only once the whole
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
still require testing and finalising. At certain point, depending of the
definition of done for the product, the amount of waste can vary: an
extensive definition of done would include also testing and deployment,
while other more relaxed could only include the coding. The wastes in
RUP are related to extended design phases and creation of deliverables
(design documents, requirements…) which are not the product requested by
the client. Both scrum and RUP have different objectives in their
methodologies which they are optimised for and the over waste is not a
priority for them.

This are the resources I used. As this is more a
comparison/argumentation exercise, I did not need to cite many papers
but the first two. The other 4 are papers that I read/consulted during
the writing.

\[1\] https://doi.org/10.1016/j.ijpe.2010.07.024

\[2\] http://www.agilemanifesto.org/principles.html

- https://doi.org/10.1016/j.ijpe.2010.07.024
- https://10.1111/j.0955-6419.2005.00369.x
- https:/doi.org/10.1109/TEM.2010.2081675
- https://doi.org/10.1016/j.annemergmed.2011.04.004
