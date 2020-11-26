
## Formats

These are some suggested formats for use-cases and requirements.  These formats
should by no means be taken as absolute canon, but might be useful for
kick-starting your thought process when contributing to the planning process. 

### Use-case

Like a good playwright, before starting to write a use-case, consider two
important fundamentals:

* What is the motivation of the subject <span class="term">actor</span>
* Is the action in <span class="term">scope</span> (relevant)? Which one?

If you've found a use-case that is properly motivated, and in scope, proceed by
writing down the following elements:
<ol type="a">
   <li>Who is the actor?</li>
   <li>What are they trying to do?</li>
   <li>What is the scope / context of the action?</li>
   <li>Who cares that the action is being fulfilled?</li>
   <li>What triggers the action?</li>
</ol>


You now have everything you need to write a bare-bones use case. A template for
this use-case could look like this:

```
Primary actor: {a}
Goal: {b}
Scope: {c}
Stakeholders: {d}
Trigger: {e}

Flow:
   1. {...}
   2. {...}
   n. {...}
```

Writing the flow means imagining how the interaction between the actor and the
tooling takes place. Writing an accurate flow is difficult, but the important
part is really the "header" of information about actors, goals and
stakeholders. This goes back to the fact that the most important element of
use-case gathering is elucidating _goals_, not designing the system. Therefore,
don't worry about figuring out the exact workflow, as it will probably need
some adjustment.

Something should also be said about the level of detail when writing the flow.
Workflows are composed of steps, which in themselves might be described as
use-cases (the turtle-problem). Finding the right balance between detail and
brevity is an art.
