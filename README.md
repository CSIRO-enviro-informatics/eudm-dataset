# EUDM Profile
Profile of metadata standards for EUDM datasets

This ontology contains a range of resources describing a profile of well-known metadata standards to be used to characterise datasets within the [EUDM project](https://eudm.csiro.au).


## Profile repository contents
* [alignments/](alignments/)
  * listed and documented alignments of this profile (of DCAT) several other metadata models including [shcmea.org](https://schema.org), [AGRIF](http://reference.data.gov.au/def/ont/agrif) and [AGLS](http://agls.gov.au).
* [model/](model/)
  * the metadata model for this profile, including schemas & constraints
  * note the parts of the model are formalised according to PROF (see next section)
* [vocabs/](vocabs/)
  * vocabularies used by this profile. Note that many of the vocabularies references in this profile are managed elsewhere.


## Profile model
The metadata model for EUDM is essentially the [DCAT 2018](https://github.com/w3c/dxwg/tree/gh-pages/dcat) metadata model currently under development by the W3C's [Dataset Exchange Working Group](https://www.w3.org/2017/dxwg/wiki/Main_Page) with a series of restrictions placed on it that require certain EUDM-specific properties to be used.

Figure 1 shows the basic DCAT classes adapted from the [DCAT vocabulary](https://www.w3.org/TR/vocab-dcat/) diagram.

![](dcat.png)
Figure 1: This EUDM profile described using the Profile Description Ontology.

Figure 2 shows some of the EUDM-specific restrictions formalised in the [dataset constrains file](model/eudm-dataset-constraints.ttl).

![](eudm-constraints.png)
Figure 2: Some of the EUDM constraints on DCAT Datasets and related classes.

Figure 3 shows Figure 2 with some explanatory notes in plain English (in red) detailing the requirements EUDM imposes on general DCAT classes and properties.

![](eudm-constraints-annotated.png)
Figure 3: Figure 2 annotated in plain English.


## Profile Description
This profile is described using the emerging *Profile Description Ontology* (PROF), currently under development by the [W3C](https://www.w3.org/)'s [Data Exchange Working Group](https://www.w3.org/2017/dxwg/wiki/Main_Page) of which the authors are members.

PROF is managed here:

* <https://github.com/w3c/dxwg/tree/gh-pages/profiledesc>

Within the documentation of PROF is contained this profile's description as an example:

* <https://github.com/w3c/dxwg/tree/gh-pages/profiledesc/examples>

The image of describing this profile is also reproduced below.

![](eg_eudm.png)
Figure 4: This EUDM profile described using the Profile Description Ontology.


## Profile Constraints
The constraints for this profile are expressed using [Shapes Constraint Language (SHACL)](https://www.w3.org/TR/shacl/).


## Profile Alignments





## License
This repository is licensed under the [GPL v3 License](https://www.gnu.org/licenses/gpl-3.0.en.html). See the [LICENSE deed](LICENSE) in this repository for details.

## Contacts
Authors:  
**Nicholas Car**  
*Senior Experimental Scientist*  
CSIRO Land & Water    
<nicholas.car@csiro.au>  
<http://orcid.org/0000-0002-8742-7730>

**Simon Cox**  
*Research Scientist*  
CSIRO Land & Water    
<simon.cox@csiro.au>  
<http://orcid.org/0000-0002-3884-3420>

**Jonathan Yu**  
*Senior Experimental Scientist*   
CSIRO Land & Water    
<jonathan.yu@csiro.au>  
<https://orcid.org/0000-0002-2237-0091>
