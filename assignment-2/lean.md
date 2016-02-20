#Lean

The LEAN methodology, also known as a *Toyota Production System*, it is
engineering methodology which has its origin in the production method
that Toyota used to produce its cars. The methodology has spread to
other areas, including software engineering, and many companies
replicate the process trying to achieve the same success that Toyota
had, although so far none has been as successful as Toyota.

The methodology aims to eliminate the wastes: overburden (*muri*),
inconsistency (*mura*) and over waste (*muda*) in the process.
Eliminating wastes is an effective way to increase profitability. To
achieve that, they use a system known as **JIT** (*Just-In-Time*). JIT
means to produce the **exact** component, in the **exact** moment and
the **exact** amount.

The waste is classified in three different types:

- *Muri* is the process overburden, doing things in a suboptimal way.
  It is solved by standardising the workflow optimally.
- *Mura* is the inconsistency of the stock of products available. It
  is solved by a JIT inventory: there is only a little or no inventory
  of products or components and when there is a request of a product,
  the components are requested through a pull system in which all the
  components recursively call the components until they reach the
  external supplier.
- *Muda* is the over waste in its more general meaning: all those
  added processes or goods that are not request or have any value for
  the customer. *Muda* can be divided into two types: *muda* type I,
  which has no value for the customer but it is necessary for the
  manufacturing of the product; and *muda* type 2, which has no value
  for the customer and it is not necessary either. The aim is to
  eliminate the *muda* type 2 but there is no straightforward way of
  doing it because of the variety of things that can be
  considered waste.

The concept of waste is a traversal concept in other software
development methodologies. *RUP* (Rational Unified Process) focuses on
reducing risks and scrum focuses on delivering product. Both of them do
not pay special attention on waste.

On one hand, RUP can be more wasteful that scrum. The early stages of
RUP (business modelling, requirements and analysis & design) take a long
period and effort and, although they produce deliverables, they are not
the one requested by the client. This qualifies as *muda* type I, as it
is a waste, but it is necessary. This waste does not exist on scrum. In
scrum, the documentation is almost not existing. This means that the
team does not produce any other deliverables but the product that
the client requests.

RUP also have more phases besides development. The early phases focus on
having clear requirements and late ones focus on deployment and testing.
The division of the phases aims to reduce the risks in the project by
specifying the details of the project ahead and making sure that the
product has been properly deployed and tested. Although necessary, these
phases add extra waste in terms of processes and bureaucracy, instead of
being integrated within the development. In scrum, this waste does not
exist because it is considered part of the development and it does not
carry extra overhead due to being integrated into the development phase.

On the other hand, scrum can be more wasteful than RUP. Scrum works with
smalls teams and big projects require more than one scrum team working
on it. This means that those team would have each one their own *scrum
master* and *product owner* who will talk with the *stakeholders*. This
situation will lead to role duplicity which is not optimal at all. RUP
only has one management team which is an improvement in terms of wasting
over scrum.

Scrum also focuses on small iterations of the product: features are
added iteration after iteration. The client then will not receive the
final product requested during the first iterations, which is a waste
because it is not what was requested. In addition, those iterations may
lead to having to reimplement features due to changes in the
architecture. This problem, which is inherited from the agile
development philosophy, does not exist in RUP as it has only one
development phase. Scrum also requires to perform testing every
iteration, which RUP does only once.

Scrum might deliver a product which is not the exact one requested.
*Product owner* will discuss details with the *stakeholders* but during
development and the discussions with the developers, some features might
stay in the backlog and never make it into development, suffer changes
or directly taken off from it. Usually those features are small details
but they still differ from the originally requested product. RUP states
that the final product delivered will be the one discussed during the
design phases.

In conclusion, both scrum and RUP are both wasteful from the LEAN
perspective. The wastes in scrum are related with the overhead that
having different iterations of the product have attached and with the
deliverable of incomplete products from the client point of view which
still require testing and finalising. The wastes in RUP are related with
extended design phases and creation of deliverables (design documents,
requirements…) which are not the product requested by the client. Both
scrum and RUP have different objectives in their methodologies which
they are optimised for and the over waste is not a priority for them.
