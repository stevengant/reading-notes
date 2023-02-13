# Reading 02

## An introduction to NodeJS and Express

1. Explain middleware, answer as though I were a non-technical recruiter.
    [AWS - What is Middleware?](https://aws.amazon.com/what-is/middleware/#:~:text=Middleware%20is%20software%20that%20different,that%20you%20can%20innovate%20faster.)
      - Middleware is software that different applications use to communicate with eachother. Middleware acts like a bridge between technologies, tools and databases.

2. Express the most popular __ __ ____.
    [MDN - How Popular are Node and Express?](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction#how_popular_are_node_and_express)
      - Server-side framework

3. Express is “unopinionated.” What does that mean?
    [MDN - Is Express opinionated?](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction#how_popular_are_node_and_express)
      - An unopinionated framework has fewer restrictions than Opinionated frameworks. Express allows you to insert almost any compatible middleware, in nearly any order you wish.

4. What is a module and why is modularity useful to us as developers?
    [MDN - Importing and creating modules](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction#how_popular_are_node_and_express)
      - A module is a JS library/file that can imported into other code. 
    [TinyCloud - Why do modular programming?](https://www.tiny.cloud/blog/modular-programming-principle/#:~:text=Modular%20programming%20usually%20makes%20your,understand%20compared%20to%20monolithic%20code.)
      - Modular programming usually makes code easier by allowing you to break code up into smaller, specialized functions.

## What is NPM?

1. What version of npm are you running on your machine?
    - 8.19.3

2. What command would you type to install a library/package called ‘jshint’ into your node project?
    - npm install jshint


## What is TDD?

1. Explain why tests are important. Please explain as though I were your non technical elder.
    [Agile Alliance](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))
      - Tests help the programmer to make sure their code is working as expected

2. What are three expected benefits of testing
    + Reduction in defect rates, at the cost of a small increase in initial development
    + Initial overhead more than offset by reduction in effort at projects' final phases
    + Leads to improved design qualities in code and higer degree of internal/technical quality


3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
    + Forgetting to run tests frequently
    + Writing too many tests at once


## CI/CD

1. What are three benefits of Continuous Integration?
    [GitHub Traning & Guides - Continuous Integration Continuous Delivery](https://www.youtube.com/watch?v=xSv_m3KhUO8)
      - Ensure everyone's changes integrate
      - Catch bugs
      - Reduce merge conflicts

2. What is the difference between Continuos Delivery and Continuous Deployment?
    - Continuous Delivery is the development of application to release at  any time.
    - Continuous Deployment means to deploy new features immediately.


3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background
    - GitHub tracks changes made to code and communicates those changes with other systems. 