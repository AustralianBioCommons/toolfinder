---
description: Add a plain text description here.
sidebar: false
datatable: true
---


This page lists bioinformatics tools and software that are installed across several of the [**BioCommons infrastructure partner systems**](https://support.biocommons.org.au/support/solutions/articles/6000251977-compute-systems-at-the-biocommons-partner-infrastructures). Tool / software status on other infrastructure partner systems will be added over time.


{% include callout.html type="important" content="`NCI (if89)` in the table refers to the [Australian BioCommons Tools and Workflows repository](https://australianbiocommons.github.io/ables/if89/), located in project allocation `if89` at the National Computational Infrastructure (NCI)." %}

**Can’t find the software you need?** Here are some other options for finding software: {% tool "biotools" %}, {% tool "biocontainers" %},  {% tool "galaxy-toolshed" %}, {% tool "dockstore-tools" %}

**Need to request installation of software on ToolFinder listed infrastructures?** {% tool "galaxy-new-tool" %}, {% tool "nci-new-tool" %}, {% tool "nci-if89-new-tool" %}, {% tool "pawsey-new-tool" %}, {% tool "rcc-new-tool" %}

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
      finding software
    </button>
    <div class="collapse" id="collapse1">
      <div class="card card-body">
        <ul>
          <li>
            <a href="https://bio.tools/">bio.tools registry</a>: discover
            software tools
          </li>
          <li>
            <a href="https://biocontainers.pro/registry"
              >BioContainers registry</a
            >: discover and access containers for software tools
          </li>
          <li>
            <a href="https://toolshed.g2.bx.psu.edu/">Galaxy toolshed</a>:
            discover tools which can be requested for installation on Galaxy
            Australia
          </li>
          <li>
            <a
              href="https://dockstore.org/search?entryType=tools&searchMode=files"
              >Dockstore tool search</a
            >: discover containers for single tools
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
      listed infrastructures
    </button>
    <div class="collapse" id="collapse2">
      <div class="card card-body">
        <table class="table table-striped table-sm">
          <thead>
            <tr>
              <th scope="col" class="w-25">Infrastructure</th>
              <th scope="col">Process</th>
            </tr>
          </thead>
          <tbody class="table-group-divider">
            <tr>
              <td><a href="https://usegalaxy.org.au/">Galaxy Australia</a></td>
              <td>
                Complete a
                <a href="https://site.usegalaxy.org.au/request/tool"
                  >tool install request</a
                >
              </td>
            </tr>
            <tr>
              <td><a href="https://nci.org.au/">NCI</a></td>
              <td>
                <a
                  href="https://opus.nci.org.au/display/Help/5.+Software+Applications"
                  >Contact NCI</a
                >
              </td>
            </tr>
            <tr>
              <td><a href="https://pawsey.org.au/">Pawsey</a></td>
              <td>
                Visit the
                <a
                  href="https://support.pawsey.org.au/portal/servicedesk/customer/user/login?destination=portals"
                  >Helpdesk Portal</a
                >
                or email: help@pawsey.org.au with your request
              </td>
            </tr>
            <tr>
              <td>
                <a href="https://www.qriscloud.org.au/">QRIScloud</a> /
                <a href="https://rcc.uq.edu.au/">UQ-RCC</a>
              </td>
              <td>
                Complete a
                <a
                  href="https://support.qcif.edu.au/Request-for-installation-of-QRIScloud-HPC"
                  >tool install request</a
                >
              </td>
            </tr>
          </tbody>
        </table>
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



