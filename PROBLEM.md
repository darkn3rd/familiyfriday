# Family Friday

On the last Friday of every month, Apartment List abandons the convenience of
our usual catered lunch in favor of getting some fresh air. The more we grow,
the harder it is to see people who aren't on our immediate teams, so we shuffle
ourselves into random groups for a chance to talk to (or even meet for the first
time) people we otherwise miss out on.

We used to have everyone's name on a lottery ball and roll them out of a
spinning cage, but at around 40 people that started taking too long&mdash;hungry
A-Listers are merciless. So you, intrepid coder, are going to help us automate the
process!


## Project

Your initial implementation should be short and sweet. Before your interview,
please take a moment to understand the problem, ask any questions you have, and
build an initial solution. Depending on your approach, most solutions take
somewhere from 30 to 90 minutes. You're welcome to take as long as you like or
add bells and whistles, but you should by no means feel pressure to spend your
whole night or weekend on this.

The requirements are intentionally high-level, so implement them however you see
fit. Some options include, but are certainly not limited to:

  - A CLI backed by the file system
  - Rails scaffolding and Postgres
  - A React app with local storage
  - A Slack `/command` hitting a Phoenix app
  - An Emacs mode

If you are interviewing for a role on the Web Team, please write a web app for 
your initial solution so we can extend and modify it together. If you're 
interviewing for the DevOps role, write a web app that you can deploy to AWS 
during your Google Hangout with your interviewer. 

Ultimately, use whatever you're most comfortable in and will best show off your skills.
Whatever you choose, your code should be something you're proud to push to production.

When you're done, please send us a link to the GitHub repository containing your
code so we can clone it and be prepared for the session. During your interview, 
we'll talk about your decisions and then extend the program together.


## Requirements

### Usability

Someone relatively non-technical should be able to operate your program, which
means some kind of CLI or GUI. What it shouldn't be is typing code into a
console or editing data by hand.

### New hires

When someone (like you!) joins the company, we can add them to the list of
people going to lunch.

### Persistence

With on the order of 100 employees and an average tenure of 2.5 years, adding
everyone every week would take longer than the old lotto cage. Once someone's
been added, they should remain in the list across restarts, etc.

### Lunchtime!

On Friday, anyone should be able generate a complete set of random groups to go
eat with. No group should be fewer than 3 people (the conversation dies easily)
or greater than 5 (it's hard to get a table).

### Tests

It would be sad if anyone got left out or had to eat alone! Make sure you have
some tests in place to ensure your program works the way it should.

### Documentation

Include a README describing your approach and any interesting decisions you
made. Comment your code the way you would at work. If there's anything
non-obvious we need to do to run your program, make sure to include
installation/startup instructions too. Your commit history is interesting too,
since it shows some of your process.


## Example

Say we pivot into mining precious gems and hire some experts in the field:

- Happy
- Dopey
- Grumpy
- Sneezy
- Bashful
- Sleepy
- Doc
- Snow (Chief Tunneling Officer)

When we shuffle everyone into lunch groups, one valid output would be:

| Group 1 | Group 2|
| ------- | ------ |
| Bashful | Doc    |
| Happy   | Dopey  |
| Sneezy  | Snow   |
| Sleepy  | Grumpy |
