# Minutes

## Mantid PMB Meeting 15

**Minutes of: 2020-04-03 UTC12:00-14:00**

**In Attendance:**

```
* CSNS - Junrong Zhang
* ESS - Andrew Jackson, [Jon Taylor (normally PMB chair) mostly ABSENT for family emergency]
* ILL - Miguel Gonzalez, Paolo Mutti, Gagik Vardanyan
* ISIS - Lamar Moore, Toby Perring (acting Chair), Pascal Manuel, Hannah Griffin
* ORNL - Mathieu Doucet, Andrei Savici
* Non-facility - Nick Draper (PM), Peter Peterson (TSC chair), Stephen Cottrell (User Group Chair), Daniel Murphy (Secretary)
```

## 1. PMB Membership 

 - Welcome to Junrong Zhang from CSNS

## 2. PM Report:
**N. Draper talked through the main points of the report.**

- Some COVID-19 related risk-planning,
- Difficulties and benefits of move to Python 3. ORNL still working on their move to Python 3.
- Workbench Staus: Many key features have been implemented. Currently working on Slice/Peaks viewer, which is holding back Single Crystal from moving to workbench. 
- Breaking-point for Mantidplot will be from Ubuntu 20.04 (released at end of April 2020) won’t support Qt4
- Agreed upon need for a worldwide date for MantidPlot to be dropped, requiring planning and feedback from scientists and developers at all facilities.

In light of MantidPlot Deprecation should we: 
- Plan 1.) Do not support Ubuntu 20.04 yet 
- Plan 2.) Support Ubuntu 18.04 and 20.04, but only workbench.

Many felt that Plan 1 would help focus the development effort on Workbench, and that Plan 2 was only worth pursuing if it did not require much effort, espcially as facilities aren’t going to move to Ubuntu 20.04 any time soon.

**COVID impact discussed at each facility:**
ISIS / ORNL: Working from home, communicating online, not much slow down.
ILL: Find it hard for helping new starters. Trying to teach newcomers.
ESS:  Not much development into mantid code base
CSNS: Back to their facility somewhat
*Overall, not much affect, with a new opportunity for different facilities to join meetings.*

## 3. TSC Report – Pete

Currently no CSNS member.
Currently no developer working on Conda.
It would be great to have a mac developer license.

ESS are willing to work on Mantid and Skip in parallel, with small Mantid forces. They want to commission beamlines in 2022, which may involve using Workbench.

## 4. ~~European~~ Review / Advisory board

A remote review was decided against by the review panel. So it has been delayed until the end of the year (November / December). Lots of time to prepare. Paul Butler, Jon Taylor and panel have worked out a plan for the review. 

General ideas behind the review were discussed, such as having a large Scientific / User focus.
The software management, approach, and process are to be reviewed, not in a very technical manner, but technically informed.

- Will PSI, ANSTO and MLZ be involved as collaborators? Should they be asked if they would like to contribute more?
- CSNS are glad to join the review, and will liase with Lamar Moore about this.
- SNS also want to be involved in some way with the review. 
- No longer a European Review but a Mantid Advisory Board.

Getting user input has been hard. Getting small feedback through forms has been the way forward. About 90 forms off and online. Ideally would be 2 or 3 users to represent different techniques.

## 5. User and Developer Meeting planning

- Sort out a venue and possible dates for the next user meeting, SNS are still happy to host.
- User meeting probably won’t be until Spring 2021, therefore Developer meeting should be split from this, and could even be virtual.
- Could attach Developer meeting to NOBUGS 2020 in mid-October, if it goes ahead.
- Hannah proposed 1 in person and one virtual Dev meeting, which would be good as more often and they have different benefits.

## 6. Licenses

Agreed we need the gsl license for a long list of dependencies.

Although, the current license is restrictive to downstream users of the Mantid framework ie. Skip has to be gpl compliant as Mantid is. People may not choose to use Mantid due to this gpl license. This has nothing to do with European fair use.

If we did change, then we would need to have all the facilities agree including any past contributors.
Need specific examples and strong intent if we are to alter our license.

## 7. Mac Dev IDs

General interest in having a handful of developers that can sign the Mac package, spread across different facilities. Cost is $ 99 /year.

## Summary of Actions: 

-    [ ] Nick will coordinate an assessment of a MantidPlot deprecation date.
-    [ ] Nick and Martyn will work with SNS to get estimates for Sliceviewer and getting Workbench feature complete.
-    [ ] Nick to set a date (6-8 weeks from now) to hold emergency PMB about implementation of MantidPlot deprecation and full move to Workbench.

-    [ ] Nick will sort out whether Plan 1 or Plan 2.

-    [ ] Junrong to provide a CSNS member for TSC.
-    [ ] TSC is to decide how to make the international meetings with CSNS member possible.

-    [x] Lamar will email PMB with Review member list, current schedule and the outcomes from the last meeting.
-    [ ] Lamar will send CSNS information about the review.

-    [ ] Each facility to come prepared at emergency PMB with possible dates for User meeting between Jan-April 2021.

-    [ ] Nick to complete dependencies list (with licenses involved) and distribute this info to other PMB members.
-    [ ] Nick will push forward on organising Mac Dev IDs for signing Mac packages

-    [ ] All to look over PMB / Mantid Project governance documents (give Nick a week or two to update)
-    [ ] Nick will update PMB / Mantid Project governance documents with annotations as to the current activities (not deleting things that are no longer relevant) AND inform PMB members that they can now look through these documents in time for the next meeting.
-    [ ] Lamar and Hannah to look at governance of other similarly sized open source projects 


## Next Agenda

- Date and Planning for MantidPlot deprecation (user/scientist feedback)
- Update on Advisory Board Status
- User and Developer Meeting (DEV = virtual OR attaching to NOBUGS, possible dates for User meeting between Jan-April 2021)
- Review PMB / Mantid Project governance documents (all should look through beforehand)
