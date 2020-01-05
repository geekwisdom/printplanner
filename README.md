# My Daily Planner

> Those who fail to plan - Plan to Fail.

This project contains the simple planning system I use to organize my work and life.
It is based on the ideas embodied by the books "7 Habits of Highly Effective People"
- By Stephen Covey, and "Gettings Things Done" - By David Allen.

This project is NOT an automated planning system. It is a simple script for printing a 
paper based daily planner.  Why not an automated tool?  - Well I have yet to find 
any method that feels as satisifiying as physically crossing off a todo item.

If you are looking for a simple, easy to use paper based planner, this simple script
let's you schedule automated print outs of the pages on a daily, weekly, or monthy basis


## Getting Started

Extract the github project to a location on your linux box (eg: /usr/local/scripts/autoprint)

Schedule cronjobs on a daily, weekly, and monthly basis

Actually fill out the details of the planner each day !

## Cron Jobs (eg: at 5:55am, daily, weekly, monthly)

~~~~
55 05 * * * /usr/local/scripts/autoprint/print_planner daily
55 05 * * SUN /usr/local/scripts/autoprint/print_planner weekly
55 05 1 * * /usr/local/scripts/autoprint/print_planner monthly
~~~~
