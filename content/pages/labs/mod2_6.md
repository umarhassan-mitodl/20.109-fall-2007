---
content_type: page
description: ''
learning_resource_types:
- Laboratory Assignments
ocw_type: CourseSection
parent_title: Labs
parent_type: CourseSection
parent_uid: fc19e690-0ca7-af8b-d48d-3a5a9e329f01
title: 'Module 2.6: Microarray Data Analysis'
uid: a26d0242-10aa-7e1f-9778-0a81bc2347cb
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Modules: {{% resource_link 7506446f-0ce3-4227-fbf7-0e265f4a7002 "2.1" %}} | {{% resource_link bbd13c95-2443-ade1-e9c6-5fff93334839 "2.2" %}} | {{% resource_link da42df1d-ffb9-a16b-951d-1267c9b1d8fa "2.3" %}} | {{% resource_link cd9396b1-623d-c638-8b39-94f34a2dccd5 "2.4" %}} | {{% resource_link cf154f53-d733-f827-825a-bd351c2db015 "2.5" %}} | 2.6

Introduction
------------

Sony Playstation® or Microsoft® X-box? Boxers or briefs? Coke or Pepsi? We all know that taste can't be mandated, but then how do standards arise. Standards are a fundamental and required aspect of engineering. Without them, machines can't talk to each other, hardware is difficult to repair, and profits disappear (try to estimate the recent earnings by Betamax). In many cases, standards are government mandated, e.g. the US public school curriculum, cell phone technology in Europe, internet protocols worldwide. On other occasions, external events or pressures influence standards. Sweet N' Low was essentially the only artificial sweetener on the market until the saccharine it contained was "shown" to cause cancer in lab rats. On rare occasions, standards arise through extreme behavior. In 1888, Thomas Edison wanted to demonstrate the superior safety of direct current (the technology his company marketed) so he publicly electrocuted dogs with 1000 volts of alternating current, the technology his competitor, Westinghouse, was marketing for use in homes.

\[Photo of metric system and English rulers removed due to copyright restrictions.\]

How do standards arise when there is no traditional financial market for them? In the case of {{% resource_link "5016b1b4-0918-4492-8644-486ef814e047" "BioBricks" %}}, the {{% resource_link "fb1134a6-8441-4d5a-a8e3-47153ad29a93" "Registry of Standard Biological Parts" %}} is relying on the goodwill of the community to contribute standard parts that conform to the Registry's rules. The payoff isn't market share of the biological parts market, but rather the establishment of a shared resource that is reliable, reusable and useful. Community compliance to standards for microarray experiments and data analysis is similarly driven. Despite disagreement within the scientific community about how to collect meaningful microarray data, a "Minimum Information About a Microarray Experiment" ({{% resource_link "25bf329e-8f6a-4769-b71c-eb9ef65009b0" "MIAME" %}}) checklist has been generated and is largely adhered to. "Minimum information" means only that the microarray data can be examined and interpreted by others…not a high bar for publication standards but one that is difficult to achieve since the arrays themselves are provided by different commercial vendors who disclose different amounts of information about their arrays. Moreover, the effort required to annotate MIAME data is significant and authors vary in their compliance.

Corroboration of published microarray data is further compounded by a lack of standards surrounding the data analysis itself. Processing the raw data mixes art and science. Algorithms used vary dramatically, and a single data set can appear compelling or noisy, depending on the analysis choices made by the investigator. For example, Cy3 and Cy5 are commonly used fluorescent probes but others dyes can be used and may be processed with different background correction and normalization factors. Not surprisingly, experiment protocols make a difference too. Researchers who indirectly label may find different outcomes than researchers who perform the same experiment but directly incorporate fluorescent dyes into their RNA. Also worth noting is human error, since microarrays experiments require many steps over many days. There are even stories of people scanning their slides backwards and consequently mis-identifying every spot on the array.

This lack of consensus should be both liberating for you today and also burdensome. You will have great freedom in how to analyze and interpret your data. Some initial steps are suggested but then you're free to try different approaches that you are interested in and that make sense to you. You will need to carefully annotate and justify the choices you make, to allow others to understand and critique your approach. Good luck and have fun!

Protocols
---------

Here is a rough outline of the steps you can take to examine your microarray data. There are many variations on this that are acceptable and that may be more interesting or appropriate for you. You should explore the data as you see fit.

1.  Open TXT file in XLS (tab delimited)
2.  Delete top 9 rows
3.  Label a new worksheet for working with your data
4.  Copy columns for: GeneName, SystematicName, Description, gMeanSignal, rMeanSignal gMedianSignal, rMedianSignal, gBGMeanSignal, rBGMeanSignal, gBGMedianSignal, rBGMedianSignal
5.  Format the numerical cells as numbers with no decimal place
6.  Consider mean and median variations and background, to correct as you see fit. Be sure you keep track in your notebook or in the XLS file of your analytical decisions.
7.  Start new column with ratio of green signal/red signal.
8.  Start new column called log2green/red and use data in green/red column as =LOG(cell#,base), for example =LOG(D3,2) and drag corner to apply formula to all 44K cells. Again format to whole numbers if this does not happen automatically.
9.  Select entire sheet by clicking on diamond in corner then sort by log2 (green/red).
10.  Sort cells in decending order according to log2green/red
11.  What do you see? Are the duplicates in agreement? Are there particular genes you expect to see up or down regulated in the two samples. Ask the questions you want about this data...
12.  Save as XLS worksheet or workbook.

DONE!

For Next Time
-------------

Your first draft of your {{% resource_link 1eed501b-947f-9694-08a9-5b5c8aece644 "lab report" %}} is due next time. Review the {{% resource_link 78cab3c7-1f19-b0dc-a42f-cd3f15022f6d "Guidelines for writing a lab report" %}} to remind yourself of the class expectations.