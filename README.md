# A Replication of Are LLMs Correctly Integrated into Software Systems?
<div style="overflow: auto;">
  <img src="./Hydrangea.png" alt="Alt text" width="300" style="float: right; margin-left: 10px;">
  <p>
    This artifact accompanies our paper, "Are LLMs Correctly Integrated into Software Systems?" It contains metadata from 100 non-trivial open-source projects that incorporate LLMs, along with a comprehensive defect library detailing issues encountered when integrating LLMs and RAG into software systems. We hope this artifact can aid the development of LLM-enabled software and motivate future research.
  </p>
</div>


The artifact has been published as [a project on Github](https://github.com/SOFTWARE-2024/Hydrangea).

## What's inside the artifact:

For enhanced availability and reusability, we offer an organized defect library utilized in our manual studies.

Below are details of what is included in each part:

### Metadata of applications
A suite of 100 non-trivial projects which tightly integrates LLMs and vector databases in their workflow, containing
   1. software project name
   2. GitHub link and commit ID
   3. classification
   4. used LLM and vector database

### Hydrangea Defect Library
The result of TABLE Ⅱ in our paper can be reproduced by this organized defect library. 

In the uploaded `application.csv`, we have documented different cases for the same defect type, as defects can manifest in various ways. For each distinct case of the same defect, we have separated them with a blank line and labeled them as case 1, case 2, and so on, according to the specific circumstances.

It contains:

A collection of defects in these projects (involves 100 projects),containing
   1. the defect type and its detailed explanation
   2. the exact file and source-code line location of the defect
   3. the consequences of defect
   4. the defect-triggering tests




