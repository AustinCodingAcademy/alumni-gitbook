{% include "/includes/header.md" %}

# First Day on the Job

## Setting up your Environment

After filling out any paperwork and being introduced to everyone, you'll most likely
be task with reading READMEs or wikis about how to set up your environment. An unfortunate
reality is that new hires are usually have to navigate potentially outdated documentation
and update it where needed. This is a great opportunity to get to know the team,
learn how to ask questions and for help, and to learn how to use your machine.

* Setting up a local database instance
  * MySQL + MySQL Workbench
  * Postgres + pgAdmin
  * MongoDB + Robo 3T
* Building containers or vitualization tools
  * Vagrant + VirtualBox
  * Docker
* Installing better language and package managers
  * `nvm` (Node.js)
  * `rvm` (Ruby)
  * `conda` or `virtualenv` (Python)
  * MAMP or XAMPP (PHP)
  * etc.
* Learning to possibly use services other than GitHub
  * GitLab
  * BitBucket
  * Continous Integration
    * CircleCI
    * TravisCI
    * Jenkins

## Agile Workplaces and Scrum

You'll probably here a lot about implementing [Agile](https://en.wikipedia.org/wiki/Agile_software_development)
principles throughout the workplace. While there is plenty of literature on that
subject alone, here is a short practical guide for what to expect as a developer

### Tickets

A task assigned to a developer, usually accompanied with information, screenshots,
etc. Tickets are usually assign a certain number of "points"

### Points

These are a fluid measurement of how "big" a ticket is. It can kind of be seen
an amount of time it should take to finish the ticket, but is not an exact hour
match. An example baseline for points **could** be

points|time
---|---
1|Quick Fix (typos)
2|About an hour
3|About a day
5|A few days
8|About a week

### Kanban

This is usually visualized by a board with multiple "lanes". The most basic
idea of Kanban would be a two-dimensional TODO list

ToDo|Doing|Done
---|---|---
Mow the grass||
||Fix the Sink||
|||Clean the garage
Fix the car||

In Agile software development, you typically have more lanes

Icebox (Backlog)|Inbox|Ready|Doing|Review|Done
---|---|---|---|---|---
Tickets that are not going to be worked on this sprint|New tickets that need to be decided on if they are going to be worked on next sprint|Tickets that are ready to be worked on this sprint|Tickets currently being worked on|Tickets ready to be reviewed for completeness|Tickets Completed

The Project Manager, Engineering Manager, or "Product Owner" ultimately decided what tickets
will be worked on which sprint

### Sprint

Everything revolves around a "Sprint". Typically two weeks long, it is a unit of
time every developer has to try to get their assigned tickets done. You can sort
of see where this is going. For example, a developer can take up to 16 points
worth of tasks for a sprint.

### Sprint Planning

Typically ran by the Project Manager, Engineering Manager, or "Product Owner",
(sometimes this is all the same person in a smaller team or organization), this is
where it is decided what tickets will be worked on for the upcoming sprint. It is
vital that this person know what features need to be completed by what date so
they can pick the "theme" of sprints accordingly

### Restrospective

At the end of a sprint, the developers can show off any new features, inform the team
that something took longer than planned and will need to bleed over into the next sprint,
and talk about anything learned in the sprint. Sometimes this is and organized way
using "hats" to make sure it doesn't run too long

hat|subject|Example
---|---
White|Information|Announcements
Yellow|What Went Well?|Our API calls are getting faster!
Black|What did not go well?|Our documentation is falling behind
Green|How to fix each Black hat|Write a ticket and assign some developer hours to update documentation
Pink|How are are feeling?|People aren't washing their dishes in the kitchen!

### Daily Standups

Quick meeting where everyone stands-up away from their computers and says what they
are currently working, if they are stuck on anything, and to learn parts of the codebase
other engineers are working on. This helps:

* Prevent two engineers working on the same thing or on the same code, which could cause conflicts
* Know who is struggling and can ask the right person for some insight
* Who finished early and can take some extra tickets
* etc.

## Common Perks and Pitfalls

### Equipment

As an employee, you'll usually be given a computer. This is great, BUT it is meant
for ONLY work related projects. Don't do personal projects, web surfing, etc. You'll
also have to give it back if you leave the company.

### Open Vacation Policy

Sometimes a company will brag about an "open" vacation policy. This has some
implicit rules:

* Make sure to ask for vacation well ahead of time, so project managers can plan
* Make sure to actually take vacation. It has been well documented that employees feel pressured (whether internally or externally) to not take vacation becuse they feel like it'll slow team momentum. This is a common fallacy and it will cause developer burnout. Make sure to take 14 - 28 days spread out over the year each year.
  * If this feels awkward, the key is communication with your Project Manager, Engineering Manager, or "Product Owner".

## What if I'm unhappy at this job?

Then I have some good news for you. [Developers are known for not buying into the
whole company loyalty thing](https://www.inc.com/business-insider/tech-companies-employee-turnover-average-tenure-silicon-valley.html).
Every 2-3 years at a company, you should re-assess if you are still learning new things and remaining engaged, if not, start looking
elsewhere, your second job and third jobs could sometimes pay up to twice your first
job in only 4 - 6 years!

The high salaries come at a cost, you have to stay updated and relevant. You must always
be learning something new, and it can be exhausting. 10+ years doing the same thing on the
same app with the same stack, one layoff and you can find yourself playing catch-up. It is not
meant to be stressful, just remember to always invest in yourself, and when the opportunity
to learn something new comes up at your job JUMP ON IT.

It is ok to look for, interview, and recieve an offer while still at your job. You
don't need to communicate that you are doing it, but you do need to inform your current
company ASAP when you receive an offer you are considering. If you are happy where
you work but want a raise, this is great leverage to get that raise. If you are unhappy
or just want to engage a new opportunity, then the Project Manager, Engineering Manager, or "Product Owner"
needs to know so they can plan accordingly. Two weeks is the minimum that should be offered,
but it is not unusual to stay up to a month depending on the situation.

## What if I am an intern or contractor?

If you are brought on as an intern or contractor, you are not prevented from finding
a salaried job with benefits somewhere else. In fact, if you do find an offer somewhere
else, you can use it as leverage to become a salaried employee at your current workplace.
Typical formalities are still expected, (eg, two-week notices, etc).

{% include "/includes/footer.md" %}
