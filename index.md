---
description: Add a plain text description here.
sidebar: false
datatable: true
---


This page lists bioinformatics tools and software that are installed across several of the [**BioCommons infrastructure partner systems**](https://support.biocommons.org.au/support/solutions/articles/6000251977-compute-systems-at-the-biocommons-partner-infrastructures). Tool / software status on other infrastructure partner systems will be added over time.


{% include callout.html type="important" content="`NCI (if89)` in the table refers to the [Australian BioCommons Tools and Workflows repository](https://australianbiocommons.github.io/ables/if89/), located in project allocation `if89` at the National Computational Infrastructure (NCI)." %}


<div class="d-flex flex-column">
  <div class="mb-2">
    <button
      class="btn btn-secondary text-light"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#collapse1"
      aria-expanded="false"
      aria-controls="collapseExample"
    >
      Can’t find the software you need? Click here to see other options for
      finding software.
    </button>
    <div class="collapse" id="collapse1">
      <div class="card card-body">
        <ul>
          <li>
            {% tool "biotools" %}
          </li>
          <li>
            {% tool "biocontainers" %}
          </li>
          <li>
            {% tool "galaxy-toolshed" %}
          </li>
          <li>
            {% tool "dockstore-tools" %}
          </li>
        </ul>
      </div>
    </div>
  </div>

  <div>
    <button
      class="btn btn-secondary text-light"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#collapse2"
      aria-expanded="false"
      aria-controls="collapseExample"
    >
      Click to find out how to request installation of software on ToolFinder
      listed infrastructures.
    </button>
    <div class="collapse" id="collapse2">
      <div class="card card-body">
        <ul>
          <li>
            {% tool "galaxy-new-tool" %}
          </li>
          <li>
            {% tool "nci-new-tool" %}
          </li>
          <li>
            {% tool "nci-if89-new-tool" %}
          </li>
          <li>
            {% tool "pawsey-new-tool" %}
          </li>
          <li>
            {% tool "rcc-new-tool" %}
          </li>
        </ul>
      </div>
    </div>
  </div>
</div>

<div markdown="0"> 
{% include table.html %}
</div>


Table last updated **2024-01-12**.

- The **Tool identifier** column (hidden by default) contains an identifier for the tool / workflow: typically the module name (used for matching to HPC lists).
- The **Topic(s)** column categorises the tools by purpose, using an [EDAM](https://github.com/edamontology/edamontology) concept where possible. 
- More information about a tool can be found by following the [bio.tools links](https://bio.tools/). 
- When a tool has been containerised to allow for easier installation on any compute infrastructure, a link to the containerised software that can be downloaded from [BioContainers](https://biocontainers.pro/) is shown in the **Containers available? (BioContainers)** column. 
- The source material for the table is currently manually curated, and while we endeavour to keep the information as current as possible, there is a natural limit to the volume of information maintained here. Production of this information will be automated over time, and tools that are not relevant for bioinformatics analyses removed.



