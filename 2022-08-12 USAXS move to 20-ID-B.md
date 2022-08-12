# USAXS move to 20-ID-B

- Expect to start commissioning last week of September.
- Should have hardware by Sept 12.
- First work with BS after SAS2022
- All beam time is commissioning until APS-U dark time
- APS [starts in singlet mode on 2022-09-13](https://www.aps.anl.gov/Machine-Status/APS-Long-Range-Operations-Schedule)

## plans as of 2022-06-23

Timeline :

- 2022-07: dismantle and package as soon as reasonable
- 2022-08: Clean hutch and get grouted plate removed by contractors is scheduled
- 2022-08-22 week: Move to 20ID
- 2022-08-29 week: Aerotech installation on site
  - 2022-09-06: will make hardware and their stuff available
  - after: configure epics and get stuff under our control
- 2022-10-21: measure first useful data

## Software repositories on [GitHub](https://github.com/APS-USAXS)

[Project planning](https://github.com/orgs/APS-USAXS/projects/1/views/1)

## wxmtxy

- production code that is used
- the USAXS variant is not used and can be retired
- code is Python 2 and works now
- candidate for upgrade to Py3 and Qt
- lower priority at this time
- ignore this repo for the 2022-10 move

## caQtDM-screens

- Jan manages
- and wonders if in SVN rather than GitHub
- GitHub is not updated very often
- Jan should know how to keep this updated

## ipython-usaxs

- this is the BS repo
- moved all open issues to new milestone and organization project

## livedata

- this is the web page
- moved all open issues to new milestone and organization project

## scanLog

- historical plots for the web page
- need to move all open issues to new milestone and organization project

## spec

- in SVN
- Jeff will manage

## EPICS IOCs

- Kevin will manage
- either SVN or GitLab
