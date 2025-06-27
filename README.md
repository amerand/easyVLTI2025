# VLTI is easier than you tink!

If you have never done so, applying, observing and analysing data for [ESO](www.eso.org)'s [VLTI](https://www.eso.org/sci/facilities/paranal/telescopes/vlti.html) can be intimidating... but worry no more! a team of young and diverse scientists has put together some material to help you get familiar with all the steps necessary to get your awesome astrophysical result with VLTI, so you can join the [nearly 600 refereed papers published with VLTI](https://telbib.eso.org/?boolany=or&boolaut=or&boolti=or&yearto=2025&boolins=or&telescope%5B%5D=%22VLTI%22&booltel=or&boolsite=or&search=Search) (as of mid-2025):

- What is optical interfereomtry and VLTI in particular (by Farin Drewes)
- Convert your idea into a proposal (by Evgenia Koumpia)
- Prepare you proposal: using [ESO phase 1](https://www.eso.org/sci/observing/phase1.html) (by Emma Bordier)
- Prepare your observations: using [ESO phase 2](https://www.eso.org/sci/observing/phase2.html) (by James Leftley)
- Reduce your data, by yourself or with the help of the VLTI expertise centres (by Foteini Claire Lykou)
- Analyse your data with open tools (by Jens Kammerer)

# Useful links

## Support and assistance:
- [ESO USD](https://support.eso.org/en-GB)
- [Jean-Marie Mariotti Centre helpdesk](https://www.jmmc.fr/english/user-support/expertise-center/)
- [VLTI Expertise Centres](https://european-interferometry.eu/vlti-expertise-centers/)

## Trainings, JMMC tools and tutorials:
- [VLTI Summer School 2021 material](https://www.jmmc.fr/schools/vltischool2021/)
- [VLTI Summer School 2024 material](https://zenodo.org/communities/vltischool2024/records?q=&l=list&p=1&s=10&sort=newest)
- [JMMC tools (OIfits Explorer, ASPRO, SearchCal, OIDB)](https://www.jmmc.fr/
Video tutorials: https://www.jmmc.fr/english/training/tools-tutorials/)

## Phase 1 (proposals)
- [ESO P1 Call for proposals](https://www.eso.org/sci/observing/phase1/proposals.html)
- [ESO P1 tool](https://www.eso.org/p1/) and [demo](https://www.eso.org/p1demo/)
- [Anonymisation rules](https://www.eso.org/sci/observing/phase1/dual-anonymous-guidelines.html) for ESO proposals
- Manuals for a given period can be found on the webpages of the instruments: [GRAVITY](https://www.eso.org/sci/facilities/paranal/instruments/gravity/doc.html), [MATISSE](https://www.eso.org/sci/facilities/paranal/instruments/matisse/doc.html) and [PIONIER](https://www.eso.org/sci/facilities/paranal/instruments/pionier/doc.html),

## Phase 2 (Observation preparation)
- [SearchCal](https://www.jmmc.fr/english/tools/proposal-preparation/search-cal/)
- [P2 demo](https://www.eso.org/p2demo)

## Data reduction
- [ESO archive](https://archive.eso.org/eso/eso_archive_main.html) for raw data
- ESO pipelines for [GRAVITY](https://www.eso.org/sci/software/pipelines/gravity/), [MATISSE](https://www.eso.org/sci/software/pipelines/matisse/), including documentation and cookbooks
- links to additional tools (e.g. python scripting for pipelines) for [GRAVITY](https://www.eso.org/sci/facilities/paranal/instruments/gravity/tools.html) and [MATISSE](https://www.eso.org/sci/facilities/paranal/instruments/matisse/tools.html)
- JMMC's database of reduced data [OiDB](https://www.jmmc.fr/english/tools/data-bases/oidb/)

## Utilities
- General utilities from JMMC such as [Aspro2](https://www.jmmc.fr/~betaswmgr/Aspro2/): observations planning and simulation (a must!) or [OIFITS-explorer](https://www.jmmc.fr/english/tools/data-analysis/oifits-explorer/), a simple viewer for OIFITS files.
- The OIFITSv2 format is described in [Duvert et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017A%26A...597A...8D/abstract)

## Model fitting
- Basic tools such as [LITpro](https://www.jmmc.fr/apps/public/LITpro/) (basic model fitting with graphical interface) or [CANDID](https://github.com/amerand/CANDID): Companion detection and and upper limit
- More complex modeling (e.g. arbitrary combinations of components, chromatic, spectroscopic, time variable) check out [fouriever](https://github.com/kammerje/fouriever), [PMOIRED](https://github.com/amerand/PMOIRED) or [OIMODELER](https://github.com/oimodeler/oimodeler)

## Image reconstruction
- [OIMAGING](https://www.jmmc.fr/english/tools/data-analysis/oimaging/): is a project to make a wrapper for many of the image reconstruction tools such as  [MiRA](https://github.com/emmt/MiRA), [SQUEEZE](https://github.com/fabienbaron/squeeze) or [BSMEM](https://www.astro.phy.cam.ac.uk/research/ResearchFacilities/software-for-astrophyiscs/bsmem)
- Newer tools include machine learning, like [Organic](https://github.com/DePrinsT/organic) or [CASSINI](https://github.com/cosmosz5/CASSINI)
