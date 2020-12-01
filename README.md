# Inspection Reports

This repository was created for the IIEP Hackathon "Hacking Planning", which will take place virtually on the 30th and 31st of January, 2021. The purpose of this event is to bring together educational planners and programmers to tackle some of the challenges facing educational planning worldwide, harnessing the considerable potential of spatial data and open source software for the benefit of countries around the globe. 

More information on the event can be found at iiep.unesco.org/hackaton 

In particular, this challenge focuses in the issue of Inspection reports. Inspection visits are an important tool to maintain or improve the quality of education, since regular inspection or supervision visits help to identify school shortcomings, propose solutions, and make them follow-up.

Inspection reports are often written in free form (text) and can usually have the same structure within a single administration. The quantity of reports published each year makes careful reading impossible for a single person working at an administrative level at the regional or national level. Thus, being able to use a semi-automated process to identify major themes and sentiments could prove to be a tool used to make these reports, and therefore the inspection service, even more useful and efficient.

The challenge is to analyze the inspection reports of primary schools in Ireland and provide an analysis of the topics covered and how they are addressed, and provide georeferenced visuals to be able to illustrate the prevalence of certain topics in specific regions of the Irish territory. For example, it could be interesting to see if questions of absenteeism are more frequent in certain places, questions of availability of equipment elsewhere, etc.

The challenge has no precise format, and leaves a lot of freedom for the team. This challenge is exploratory and the results will serve to demonstrate that the idea of using semi-supervised textual analysis may be of use to IIEP-UNESCO.

The expected deliverable is a "proof of concept" that the use of textual data from inspection reports is possible, and that the results can be modeled and georeferenced in order to obtain a mapping of inspection results. We would like the deliverable to be accompanied by a list of recommendations that could be used by ministries of education to rethink their inspection questionnaires and / or systematize their analyzes.

The 3,850 inspection reports from all over Ireland, in PDF format, and following a single structure can be retrieved from the inspection site by webscraping. This repository contains Python and R code that downloads inspection reports, transforms them into text format, and does simple analyzes. The repository also contains a GeoPackage with geospatial data for schools in Ireland.

The focal point for this challenge is German Vargas Mesa (g.vargas@iiep.unesco.org) from the Development unit at IIEP.
