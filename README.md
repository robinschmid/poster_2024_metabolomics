# Metabolomics Society Conference Poster 

Visit my profile on [https://robinschmid.github.io](https://robinschmid.github.io/)

[GitHub](https://github.com/robinschmid) [Twitter](https://twitter.com/rschmid1789) [Google Scholar](https://scholar.google.com/citations?user=fck2VigAAAAJ&hl=en&oi=ao) [ORCID](https://orcid.org/0000-0003-0922-3887)


### Interactive Molecular Networking Combined with microbeMASST

[Download Poster](2024_robin_schmid_metabolomics_poster.png?raw=true)

<a href="2024_robin_schmid_metabolomics_poster.png?raw=true"><img src="2024_robin_schmid_metabolomics_poster_preview.png?raw=true" width="50%"><a>

This poster combines tools and community resources like mzmine, Feature-based Molecular Networking (FBMN) in mzmine or GNPS, and domain specific Mass Spectrometry Search Tools (MASST) like microbeMASST, plantMASST, and foodMASST. These tools enable searches of (un)known fragmentation mass spectra against all public MS2 data within ~1 second. Matches are then mapped onto the global foodomics ontology and the NCBI taxonomy to provide context. This  reveals potential sources and producers for known metabolites or unknown MS2 features.   



## mzmine and the mzwizard

**mzmine** is a general purpose mass spectrometry analysis platform and open development platform. The tool has been actively developed for 20 years and aims to integrate workflows for any mass spectrometer, chromatography, imaging, and ion mobility spectrometry system. Use the **mzwizard** to easily setup wofklows in mzmine for your MS system and method.      

- [Download](https://github.com/mzmine/mzmine/releases/latest) the latest mzmine version
- Read the [documentation](https://mzmine.github.io/mzmine_documentation/)
- Apply our latest Nature Protocols workflows for LC-(IMS-)MS, GC-MS, and MALDI-(IMS-)MS ([ref](http://dx.doi.org/10.1038/s41596-024-00996-y)). 
- Contribute to the [discussions](https://github.com/mzmine/mzmine/issues) and [code](https://mzmine.github.io/mzmine_documentation/contribute_intellij.html) (Java, JavaFX, or ML models from Pytorch or other frameworks can be integrated easily)
- When using mzmine please cite:[Schmid, R., Heuckeroth, S., Korf, A. et al. Nat Biotechnol 41, 447–449 (2023).](https://www.nature.com/articles/s41587-023-01690-2)
- Follow mzmine project on social media: [YouTube](https://www.youtube.com/@mzmineproject/playlists), 

## Applications of mzmine and Feature-based Molecular Networking

- Feature-based Molecular Networking (FBMN) for improved resolution of isomers and statistics compared to classical Molecular Networking ([ref](http://dx.doi.org/10.1038/s41592-020-0933-6)).
- Ion Identity Molecular Networking (IIMN) for multi layered networking approach including MS1 feature shape and ion information ([ref](http://dx.doi.org/10.1038/s41467-021-23953-9)).
- IIMN applied to native metabolomics data to identify siderophores ([ref](http://dx.doi.org/10.1038/s41557-021-00803-1)).
- IIMN applied to native metabolomics data to identiy protein-small molecule interactions ([ref](http://dx.doi.org/10.1038/s41467-022-32016-6)).
- Integrative analysis of LC-(IMS-)MS and MALDI-(IMS-)MS data ([ref](http://dx.doi.org/10.1038/s41587-023-01690-2)).
- On-tissue dataset-dependent MALDI-TIMS-MS2 bioimaging for confident annotations ([ref](http://dx.doi.org/10.1038/s41467-023-43298-9)).


## Public Spectral Libraries

- Check out our latest MSnLib with MSn trees of 20,000 in positive and negative ion mode ([ref](https://chemrxiv.org/engage/chemrxiv/article-details/663ccc0a91aefa6ce19236c2)). 
- Explore and select spectral library entries here: [https://library.gnps2.org/](https://library.gnps2.org/)
- Universal Spectrum Identifier (USI) = a path to a public spectrum, e.g., a library spectrum for Ferrichrome: mzspec:GNPS:GNPS-LIBRARY:accession:CCMSLIB00005435755
- Visualize public spectra online ([ref](https://www.biorxiv.org/content/10.1101/2020.05.09.086066v2.abstract)): [http://metabolomics-usi.gnps2.org](http://metabolomics-usi.gnps2.org/dashinterface?usi1=mzspec%3AGNPS%3AGNPS-LIBRARY%3Aaccession%3ACCMSLIB00005435755&width=10.0&height=6.0&mz_min=None&mz_max=None&max_intensity=125&annotate_precision=4&annotation_rotation=90&cosine=standard&fragment_mz_tolerance=0.1&grid=True&annotate_peaks=%5B%5B128.0696258544922%2C%20173.09120178222656%2C%20230.11277770996094%2C%20287.13525390625%2C%20344.15631103515625%2C%20516.241455078125%2C%20688.3257446289062%5D%2C%20%5B%5D%5D)

## MASST - Search Spectra against all Public MS2

Use a library spectrum or other public MS2 by USI, input into any of the dashboards below, and click "Search USI". Alternatively, enter m/z-intensity pairs to describe an MS2 spectrum and search by spectrum.

- FASST / fastMASST: [https://fasst.gnps2.org](http://fasst.gnps2.org/fastsearch/?usi1=mzspec%3AGNPS%3AGNPS-LIBRARY%3Aaccession%3ACCMSLIB00005435755&precursor_mz=None&charge=None&library_select=gnpsdata_index&analog_select=No&delta_mass_below=130&delta_mass_above=200&pm_tolerance=0.05&fragment_tolerance=0.05&cosine_threshold=0.7&use_peaks=0#%7B%22peaks%22%3A%20null%7D)
- microbeMASST ([ref](http://dx.doi.org/10.1038/s41564-023-01575-9)): [https://masst.gnps2.org/microbemasst](https://masst.gnps2.org/microbemasst)
- plantMASST ([ref](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11118438/)): [https://masst.gnps2.org/plantmasst](https://masst.gnps2.org/plantmasst)
- foodMASST ([ref](http://dx.doi.org/10.1038/s41538-022-00137-3)): [https://masst.gnps2.org/foodmasst](https://masst.gnps2.org/foodmasst)
- Combined trees: [https://masst.gnps2.org/metadatamasst](http://masst.gnps2.org//metadatamasst#%7B%22usi1%22%3A%20%22mzspec%3AGNPS%3AGNPS-LIBRARY%3Aaccession%3ACCMSLIB00005435755%22%2C%20%22peaks%22%3A%20%5B%22%22%5D%2C%20%22precursor_mz%22%3A%20%5B%22%22%5D%7D)
