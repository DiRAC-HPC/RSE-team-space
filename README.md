# RSE team space

This repository is for the DiRAC RSE team to track its projects, store documents, etc.

Projects are tracked as [GH issues](https://github.com/DiRAC-HPC/RSE-team-space/issues), organised with labels, and visualised in the [DiRAC RSE team planning project board](https://github.com/orgs/DiRAC-HPC/projects/2). 


## To add a new project

1. Create a new issue with a title of the form **`<project category>: <project name>`**. For example, `RAC17: SPHNG`.
   Then, in the menus on the right
   1. Assign the appropriate people in `Assignees`
   2. Add the appropriate label for the project category (eg. `RAC17`) and the **`Project`** one.
   3. Add to the `DiRAC RSE team planning` project in `Projects`
   4. Inside the drop-down menu for `DiRAC RSE team planning`, add the status, start and end dates, and total FTE needed for that project, **as requested by the proposal**.
2. Add a sub-issue **for each person** working on the project, with a title of the form **`<project category>: <project name> - <person initials>`**. For example, `RAC17: SPHNG - GK`.
   Then, in the menus on the right
   1. Assign the appropriate person in `Assignees`
   2. Add the appropriate label for the project category (eg. `RAC17`) and the **`PersonProject`** one.
   3. Add to the `DiRAC RSE team planning` project in `Projects`
   4. Inside the drop-down menu for `DiRAC RSE team planning`, add the status, start and end dates **for the involvement of the particular assignee** (can be a sub-period of the whole project),
      total FTE needed for that project as requested by the proposal (same as in the parent issue), the FTE months effort that **the assignee will be allocating on the project
      for the period of this issue only**, and the location/affiliation of the assignee.
3. If there are going to be gaps of more than a month or so in the same person's assignment to the same project, add a new sub-issue for each such period, with a title of the form
   **`<project category>: <project name> - <person initials> - <sub-period number>`**. For example, `RAC17: SPHNG - GK - 1`. Annual leave and conferences do not count as gaps, just include them as work.

***Example:*** The [RAC17 SPHNG project](https://github.com/DiRAC-HPC/RSE-team-space/issues/3) has a total FTE of 0.6 (about 7 months) allocated to it spread from 1 July 2025 to 31 March 2026.
This is shared between [Mashy](https://github.com/DiRAC-HPC/RSE-team-space/issues/4) giving 3.5 months FTE spread through the whole duration of the project, and Gokmen in two distinct periods,
[one](https://github.com/DiRAC-HPC/RSE-team-space/issues/5) of 2 months FTE spread from 1 July 2025 to 31 October 2025, and [another](https://github.com/DiRAC-HPC/RSE-team-space/issues/8)
of 1.5 months FTE spread from 1 January 2026 to 31 March 2026.
*Disclaimer: the numbers in the issues linked above might change, so use this as an illustrative example correct at the time of writing these docs.*


## The DiRAC RSE team planning project board

There are several views of the project board that RSEs and DiRAC management can use to track progress and team allocations and capacity.

- **Kanban board**: All project issues and sub-issues are included here, therefore the progress of whole projects, as well as sub-periods, can be visualised. Please move across status columns
  as projects/sub-periods begin and end.
- **Roadmap - projects**: This is a timeline view of people's allocation to projects, grouped by project. Next to each project title, the sum of all the people's FTE allocated to the project is shown (in months).
- **Project table**: This is the same information as above, but with all the fields shown as a table, not a timeline.
- **Roadmap - people**: This is a timeline view of people's allocation to projects, grouped by person. Next to each person's name, the sum of all the projects' FTE that the person is allocated to is shown (in months).
- **Team capacity**: This is the same information as above, but with all the fields shown as a table, not a timeline. In addition, one can choose to view all the people affiliated with a specific institute/location only,
  using the buttons on the left, therefore the allocations/capacity per institute can easily be calculated by eye.
