# IFC Project Section Part 1
I've been doing a study on IFC project. Mapping the data model to Django model classes to learn it's structure and to learn IFC in general.
Mindlessly mapping classes to data types and abstract classes has made me think about the value of proliferating for project delivery.  Here's my experience on the current project planning tools.


## IFC Project for Task Exchange
Projects I've worked on use a mixture of MS Project (MSP), P6 XER, Gantt PDFs, and P6 xlsx data dumps.
### MS Project 
Many project managers have MS Project on their PC and are familiar with it's simple interface and functions. Problem with MSP is there's no free viewer for the resultant project plan.
Everyone who needs to review the project programme needs to have Project installed. IT departments monitor project and turn off the license for users who don't use it as it's like $15 per month for a license the reviewer uses 4x in a year.

It's feature set is incomplete as soon as you wwant to advanced rules. Was creating a simple program that had tasks that spanned multiple days and required two days of travel and two days of work.
Project kept splitting the task across two weeks which is not viable. The autoscheduling feature lacks basic constraint functionality. Older users do hacks with the calendar but I rufuse to do hacks on 30 year old software that costs $15 per month.
Project for Web is compelling but I'm weary of Power Apps (it's just a reskin).

### P6
Obviously the best and correct tool for the job. 
- Powerful
- Advanced rules (in my simple mind)
- Plugs into JDE and SAP
- Unifier is sweet
- The whole Oracle construction suite is a compelling value proposition

Obviously the worst and wrong tool for the job.
- Expensive
- Requires loads of training to get planners to use it correctly
- I'll suited for small jobs
- The Oracle Construction Suite is expensive

### Synchro 4D
My favourite of the proprietary scheduling software. It has a free viewer, it has a free scheduling tool that has all the features and more of Microsoft Project, its scripting language is pretty easy to teach new scripters, and it converts and consumes most scheduling datatypes.
It's expensive and proprietary which is a always a minus in my book. I do appreciate their open pricing on their website. Nothing irks me more than opaque pricing webpages ("Contact US!") I believe it's the best choice if Primavera is too expensive or the project doesn't require all its features.
I also believe it's also the best in lieu of good open source alternatives as it has a similar interface to MSP 

### Excel
Good god why is everything Excel. It has been good for my career as I'm pretty decent with excel but god there's been so many bad project plans in excel. The most used project planning tool I've seen used outside of planning professionals.
Everyone has a license, everyone knows how to use (poorly), and it has excellent interchangeability.

### SASS Project tools
I've tried them all. I get the feeling they could be replaced with a SharePoint list.
Other than a central database i feel like they don't provide much value. The most frequent problem I've seen are small teams using the tool to great effect to manage 20 staff on one or two projects.
Now scale that to 500 people across multiple sites, trades, skills. The project manager who's set up the project has also set the project to the exact requirements of their project. Senior managers then want to scale their sucess to the whole busines.

### MPXJ
Great project to exchange data between different file formats. It's stable and been around for awhile. I've been using it via its Python bindings to do analysis via Pandas. Only one big negative: JAVA. I hate Java.
Probably worth doing a blog on MPXJ.

## To Be Continued
I'll talk about where IFC Project compatible tools should go. It's benefit of a project task data exchange, a lack of a stand alone viewer, and directions a IFC project should go.
