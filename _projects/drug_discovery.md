---
layout: page
title: computational drug discovery
description: Docking 6000+ inhibitors using OpenBabel against the RSV RdRp Polymerase (2022 Gwinnett Science and Engineering Fair)
img: assets/img/micafungin.png
importance: 1
category: competitions
---

**Developed Technical Skills:**:
- **Bioinformatics**: Worked with in-silico drug discovery techniques (virtual screening, database preparation) and softwares (AutoDock Vina, OpenBabel).
- **Script Development**: Developed data analysis pipelines using bash scripts.
- **Data Analysis**: Utilized Excel and Perl scripts for organizing, sorting, and filtering large datasets.
- **Parallel Computing**: Currently working with a 192-core supercomputer for efficient docking/optimizing workflows for high-throughput screening through paralellization.
- **Scientific Communication**: Wrote scientific manuscripts, created figures, and presented to scientific audiences.
- **Team Collaboration and Project Management**: Created weekly progress reports and managed timelines/roles within a collaborative environment.

After my first experience with scientific research/engineering in sophomore year, I was excited to try again in junior year. I gathered a team with interests in bioinformatics (due to the accessible nature of the field), and we decided to attempt to find inhibitors for Respiratory Syncytial Virus, due to a team member's experience with the disease as an infant.

I was in charge of database preparation and docking methods research initially, but gradually moved towards script development and data analysis. I utilized online tutorials for AutoDock Vina and OpenBabel to run our database of inhibitors through a docking process, then used Excel to sort our results, with additional data filtering through Perl scripts and bash.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/drugdockingbox.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/druginteractionprofiler.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/drugmap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Three screenshots of softwares used, from left to right: AutoDock GUI (with bounding box), Protein-Ligand Interaction Profiler (for viewing the possible interactions of the best ligands), Proteins Plus (for additional information about ligand-protein interactions)
</div>

After discovering what seemed to be a possible inhibitor candidate, we decided to reach out to labs at Emory, for wet-lab validation. Dr. Liang from the Liang Lab at Emory University had worked with RSV, so we hoped he would have specific advice regarding our protein. After a series of emails, he invited us to present our findings to the lab. 

My team and I presented to the Liang Lab on February 21, 2023, and the lab decided to run in-vitro experiments to validate the inhibitory effects of the small molecules that we discovered via docking. Dr. Cao conducted the wet lab testing (due to his expertise in that area), and after he successfully validated Micafungin as an inhibitor for RdRp, he became an additional mentor. 

Unfortunately, we did not advance past the regional competition, but Dr. Liang was able to continue to provide assistance to progress the project past just the in-silico discovery.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/drugdiscoveryphoto.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Presenting at the Gwinnett Regional Science and Engineering Fair (2022)
</div>

On this particular research project, I worked 30 hours/week from December 28, 2022 – June 14, 2023, which is around 24 weeks total. We held virtual meetings every Thursday at 5:00 PM, with additional in-person meetings at Emory on occasion. At each meeting, my team members and I would present what we did each week to work on the project, and our mentors would provide feedback and propose ways to continue by running additional testing or data analysis. 

As we transitioned to writing the manuscript, they gave advice on editing and the general flow of information, which helped us improve our writing over time. Emory has a policy against letting high schoolers do hands-on experiments in labs, so Dr. Cao conducted the wet lab validation, and thus wrote that section of the paper. However, neither Dr. Liang nor Dr. Cao wrote any other sections of the research paper, as they only provided editing advice and feedback.

I worked primarily on the Introduction and Results sections of the paper, as well as creating every figure and creating final edits.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/emoryrecognition.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Recognition at an Emory University Department of Biochemistry luncheon.
</div>

During the summer of 2023 our paper was accepted into Microorganisms, and was eventually published. It was the first time that anything I had created had 'real-life' significance, and it was awe-inspiring.

<div class = "row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/finalemorymeeting.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    My team's final meeting at the Liang Lab, before going to college.
</div>

While my partners and I eventually parted ways as we went to college, I still work in the lab, now working with parallelized versions of the docking software to comb through a much larger database (alongside utilizing the Liang Lab's gracious investment of a 192-core supercomputer specifically for computational drug discovery). The inhibitor that we discovered, Micafungin, is also being submitted as a drug patent, while another department is working on creating a medication.

Throughout the experience I've learned about several aspects of ssh tunneling, script production, python coding, docking methodologies, and bioinformatics machine learning algorithms, to name a few.