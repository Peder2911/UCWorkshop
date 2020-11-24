
## Requirements engineering 

Hey! 👋

I am really looking forward to the week 49 ViEWS workshop. During W49, we will
work together as a team to determine how we will move forward with ViEWS 3
development. The project is potentially quite extensive and complex, which
means that it will be important to make goods plans before investing too much
time and effort into development.

This document gives a brief overview of why this process is important, and what
we're hoping to achieve, both during this week, and moving forward in 2021. If
you have any questions or comments, reach out on slack. This document is alive
👹, and will be updated!

Sincerely, Peder 👨‍💻

### Background 📚

We are currently planning a rewrite of the ViEWS codebase, which was initiated
as a joint decision between me, Håvard and Mihai. The rewrite aims to address
some open issues with the ViEWS system, which are difficult to handle within
the current system. 

The rewrite prompted a conversation about the aims and goals of the ViEWS
project. Writing good code takes a lot of time and effort, which is why there
exists an extensive literature focused on software project management.  The
collective experience of the software development community shows that
planning, not effort, is the key to succeeding with software. This is why we
also decided to perform a proper, semi-structured planning process before
starting work on the codebase.

### Planning to succeed 🎯

When planning a trip, the first thing you must figure out is where you want to
go. Similarly, with software development, the most important thing to figure
out is what you are trying to achieve. Saying that planning is all about
figuring what to do sounds like an oxymoron, but the important point is
to step back from the "what", and to focus on the "why". 

For us, this meant asking some pointed questions directed at the ViEWS project
as a whole:

* What are our goals with ViEWS
* Who is using ViEWS
* What external stakeholders do we serve with ViEWS 

It didn't make sense to proceed without first answering these important
questions. To start the process of answering them, we prompted the team to
start brainstorming by writing down 
<span class="term">use cases</span>.

The rationale behind this is that by describing the way we are currently using
ViEWS, or how we imagine using ViEWS, we uncover the goals we are achieving, or
want to achieve, with our codebase, figuring out the purpose of the project by
examining its current, and prospective use patterns.

With a growing collection of use-cases, it will be possible for us to chart a
clear(er) course for ViEWS, which will enable the programmers on the team to
proceed with writing _the right code_. With a clear mandate, several beneficial
things are made possible:

* Measurable progress ⏱️
* Easier working with externals 🤝
* Preventing <span class="term">feature creep</span> 🧟‍♂️

### The process ⚙️

In week 49, we are planning to have daily meetings, to extract as much
information from the team as possible. Following this, we produce an 
<span class="term">artifact</span>
, which attempts to codify the information gathered
during our meetings.

This artifact could include

* A list of external/internal stakeholders
* A general statement about our goals
* A list of use-cases, tying into the above
* Prioritizations of the above
* A time-plan informed by the prioritized work items

The process of realizing this artifact must start with a thorough audit our
primary goals and ambitions, which will inform the rest of the document.
Your use-cases will be very _useful_ in this regard, since they help indicate
what goals you are already trying to achieve with using the system.

### Moving forward 🚀

It's important to emphasize that this process won't mean complete lock-in of
our goals and use-cases. Particularly, if we manage to secure new customers for
our products, we will revise our offering accordingly.

There are certainly many unknown unknowns that are lying in wait for us when we
begin development, and when you start using what we create. I am certain we
will discover some of the most important uses of the software we are writing
now, long after it's been first "shipped", and is being used to deliver on
whatever goals we stated in the original document. Finding the right balance
between stability and flexibility is and art, and the only recommendation I can
make in this regard is to keep the tradeoff in mind when emphasizing either.

When we've completed the first of what will probably be several planning
workshops, we'll get to work implementing software to fulfill your goals and
make possible your use-cases. I am very much looking forward to getting on our
feet with this, and to enable you to deliver what you need.
