---
description: Add a plain text description here.
sidebar: false
datatable: true
toc: false
---


This page lists bioinformatics tools and software that are installed across several of the [**BioCommons infrastructure partner systems**](https://support.biocommons.org.au/support/solutions/articles/6000251977-compute-systems-at-the-biocommons-partner-infrastructures), including {% tool "gadi" %}, {% tool "nci-if89-new-tool" %}, {% tool "setonix" %}, {% tool "bunya" %}, and {% tool "galaxy-australia" %}.
\\
\\
Please let us know if you [**have any feedback**](https://forms.gle/DvRPqGWnPVNHtLLVA).

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
      <i class="fa-solid fa-circle-chevron-down ms-1"></i>
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
      <i class="fa-solid fa-circle-chevron-down ms-1"></i>
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


- The **Tool identifier** column (hidden by default) contains an identifier for the tool / workflow: typically the module name (used for matching to HPC lists).
- The **Topic(s)** column categorises the tools by purpose, using an {% tool "edam" %} concept where possible. 
- More information about a tool can be found by following the {% tool "biotools" %} links. 
- When a tool has been containerised to allow for easier installation on any compute infrastructure, a link to the containerised software that can be downloaded from {% tool "biocontainers" %} is shown in the **Containers available? (BioContainers)** column. 
- The primary source material for the table is manually curated, and while we endeavour to keep the information as current as possible, there is a natural limit to the volume of information maintained here. Production of this information will be automated over time, and tools that are not relevant for bioinformatics analyses removed.



