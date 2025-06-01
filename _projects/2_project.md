---
layout: page
title: Are Biomedical Ontologies Sustainable?
description: An attempt to understand how well biomedical ontologies are maintained after their initial development!
img: assets/img/ont_sus.jpg
importance: 2
category: work
giscus_comments: false
---

Read the full article <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6371329/">here</a>!

Biomedical ontologies are developed with great investment of time, effort, and
budget. But are biomedical ontologies regularly maintained? If not, what are the root causes
behind this? We attempt to investigate these questions both from a
quantitative and qualitative perspective.

The information on ontologies from BioPortal was used to analyze various aspects of the
ontologies. There were a total of 684 ontologies listed on BioPortal as of Jan 18, 2018.

First, some basic analysis...

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/sust_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/sust_5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/sust_2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Number of ontologies released per year, based on the first release info. in BioPortal; Middle: Number of days since the last update vs. number of visits since the last update; Right: Number of ontologies based on their last update date in BioPortal.
</div>

For this study, the the primary interest was in ontologies that have not been updated for a
long time, and that are of a substantial size. The goal was to understand why ontologies that
were apparently built with a great investment of time, effort, and budget are not being
maintained/sustained and how big a problem this constitutes. Another question of interest
was whether the fact that an ontology is not actively maintained has an effect on the frequency
of access to it.

To limit the scope of the study to a manageable size, only those ontologies that had not
been updated in BioPortal since January 1, 2016, were chosen. There was a total of 317
such ontologies. For further analysis we filtered out from the above 317, a subset of 83 ontologies with at least 1,000
distinct concepts. To identify the root causes why the ontologies are not regularly updated/maintained,
personalized email messages were sent to the curators/owners on file for these 83
ontologies.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/sust_4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Total number of visits for the 11 most-visited ontologies not updated between
January 1, 2016, and January 18, 2018.
</div>

Our findings explaining the reasons behind the sparse updates of these ontologies are categorized into 7 major categories as shown in the table below. The largest number of responses indicated a variation on the theme that there was a lack of funding or manpower. This indicates that some ontology development projects are apparently conceived without
either (a) a plan for sustaining and maintaining the ontology after the initial development period or (b) an underestimate of the resources in staff and budget that might be required
to maintain an ontology over a longer period.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/sust_3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

It will be advisable for any project team that wishes to create a sustainable ontology to plan for the “long tail of maintenance” already at the time of project inception and to attempt to secure future funding from sources other than federal agencies.
