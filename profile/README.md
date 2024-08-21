# Agent-based modeling project homepage and overview: Chicago Center for HIV Elimination (CCHE) at the University of Chicago

## Integrated Framework for Modeling Social Determinants of HIV Transmission (INFORM-HIV)
INFORM-HIV is a stochastic, discrete-time, agent-based network model designed to simulate HIV transmission among Black sexual minority men (SMM) and transgender women (TGW) in Chicago and to evaluate interventions to reduce HIV transmission. The model aims to better understand the potential impact of interventions to address social determinants of health (SDOH), including housing, incarceration, and employment, on HIV transmission. INFORM-HIV can be used to examine the impact of socio-structural interventions, alone and in combination with one another and with biomedical interventions, under different scenarios and assumptions about the underlying causal structures in the model.

INFORM-HIV is written in Python using the [Repast for Python (Repast4Py)](https://repast.github.io/repast4py.site/index.html) HPC toolkit, with dynamic network modeling using the [statnet](https://statnet.org/) toolkit. The R package [rpy2](https://rpy2.github.io/) is used to integrate the two frameworks. Automated parameter sweeping procedures are created using the [Swift/T](http://swift-lang.org/Swift-T/) parallel scripting language and are implemented to enable efficient model exploration and calibration.

This work is supported by funding from NIH grants R01DA057350 and R21MH128116.

- [Github](https://github.com/UChicago-CCHE-Modeling/INFORM-HIV)

## INFORM-HIV-Analysis
This repository Analysis code and workflows for running the INFORM-HIV model.
- [Github](https://github.com/UChicago-CCHE-Modeling/INFORM-HIV-Analysis)

## Previous Modeling Projects
## P2M4Py
- [Github](https://github.com/UChicago-CCHE-Modeling/p2m4py)
- [Meeting Notes](https://docs.google.com/document/d/1C5nz3TNKu7zm_yNRSkqlMUElOzt0tzvq9zXx0_m_QAk/edit#)
- [Small group meeting notes](https://docs.google.com/document/d/1jlW-A54vX7gBymFH1PsKfIKP_ze3yytQOUJIj-tycJg/edit#heading=h.lmdw739kbg6v)
- [Google Drive Folder](https://drive.google.com/drive/u/0/folders/1YINU88DH4hJfCe-jsEv3y89Qvbo7QMLn)
- [Experimental notebook](https://docs.google.com/document/d/1hhenwS_Z_tgQPALh0L-3RyqQ5Cle8_O9DVPfCxtDqTo/edit?usp=sharing)
- [Progress Log](https://docs.google.com/document/d/18HVnTeyzqKbrlu_hW2uz-rzVTYxg-GWUu1MnJgGFEBo/edit#)
- [Trello / Roadmap](https://trello.com/b/RA9tMvMg/p2m4py-roadmap)

## P2M
- [Github](https://github.com/jozik/p2m)
- [Meeting Notes](https://docs.google.com/document/d/1C5nz3TNKu7zm_yNRSkqlMUElOzt0tzvq9zXx0_m_QAk/edit#heading=h.fuq2v14b6qxg)
- [Box Folder](https://uchicago.app.box.com/folder/48561258186)

## NEST
- [Github](https://github.com/jozik/p2m/tree/hiv+syphilis)
- [Meeting Notes](https://docs.google.com/document/d/1AGcQA698_RBl_SwUjHqYB8LMIqmMyg_ArE3IpD6CH38/edit#heading=h.3m87vzbsz1a0)
- [Box Folder](https://uchicago.box.com/s/n7mj0oz7borxldj5j1c9lp39ev723skd)

## BARS
- [Github](https://github.com/khanna7/BARS)
- [Box Folder](https://uchicago.box.com/s/jiulksk22cv85afxby1rhvt5gcqtos13)
- [GTZ Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6760326/)
- [BARS Running the Model “Quick-start Guide”](https://docs.google.com/document/d/1XHhmn8uwgCQpVK7l9bDTPfvhAGCgga9TL3oxlQopxsM/edit?usp=sharing) 
