# 01 Simple Design

- #### What should the tests cover within the code?

  Tests should provide confidence that the software behaves as expected.

  From my experience as a Frontend Engineer, I believe they should mainly cover two areas:

  1- **The logical functionality we want to implement.** By this I mean how we want functions to communicate with one another, how we want them to process commands, and what results they should return.

  2- **User experience.** Whilst we are writing code to give a logical structure to what we are doing, we also need to consider how the user might interact with the application; therefore, it is good practice to carry out end-to-end (E2E) testing to cover the entire workflow.

- #### DRY Principle

  DRY is often misunderstood as simply removing duplicated code.

  However, the real goal is to eliminate duplicated knowledge rather than duplicated syntax.

  Duplicated code is not always a problem if each copy represents different business concepts that may evolve independently.

- #### KISS & YAGNI

  One of the biggest risks in software development is solving problems that do not yet exist.

  KISS and YAGNI remind us that every abstraction introduces maintenance cost.

  Instead of designing for hypothetical future requirements, software should evolve incrementally as real needs emerge.

  From my experience, over-engineering not only increases maintenance costs but also delays delivery.

  Trying to anticipate every future requirement often leads to unnecessary abstractions that consume valuable development time without delivering immediate value.

  That time could instead be invested in solving real user problems or shipping new features.

### Engineering Decision

For future projects, I think it’s important to avoid over-engineering, whether to address a future problem or simply to give what we’re working on a ‘professional’ touch. Unless it’s a real or current problem, I don’t think we should add technical complexity.
