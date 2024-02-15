# Library
Application intended to start as an API and slowly evolve.

# The project.
It will be a library management system. Since it's meant to be something used by workers, it'll allow a worker to add books and users to the system, along with doing the process of borrowing and returning for the user.

The objective of this project is for me to work on something, allowing me to apply the knowledge I've gathered over the years. The idea is to start small and slowly evolve it, eventually snowballing it to a point where there's even a front-end for it, and possibly even using cookies, sessions, logins, security tokens, and other useful technologies in the mix.
# The Start.
I will start by organizing everything, creating a trello to keep track of what I'll need to do, what I have done so far, and what I need to learn in order to do certain functionalities. Next up is planning how it's going to go. After organizing my trello, I'll build a visualization of roughly what the back-end will look like, modelling the DB, which functions it will have, which DTOs, models, utility classes, etc. Likely will end up using something similar to UML for that visualization. A few mock-up screens of how the front-end should look like will also be made for future reference.
# Development.
Coding will only begin after organizing and planning everything, as it's important to not get ahead of myself and then have to fix an oversight later on. The first priorities will be to create the SQL code for the data, a CRUD for books and users, and the logic to borrow and return books. It might sound simple, but there are things to consider in terms of logic and business rules, including a limit on how many books a user can borrow at a time, the exclusion of data needing to be done in a different manner to comply with LGPD standards, while simultaneously not compromising the databank logs, and others. The idea will be to make the back-end easy to understand, use swagger to document what each address does, and JUnit to test it all.
# Later on.
With the back-end done, the front-end will then start to take shape. Once the visual aspects have been made, I'll see about running the entire project locally, on a docker container, and maybe even from the web. The reason why this section is shorter and less descriptive than the others is because it isn't my specialty, so it'll be a bit of a learning process as well.
