DATABASE - NANOMATERIALS INTERACTIONS WITH BIOLOGICAL SYSTEMS (nanotox_db) - Version 1.0
===============================================================================

Both databases `abstracts_nanotox_db_all_1.csv` and `abstracts_nanotox_db_superior_organisms_1.csv` 
are in version 1.0 and they were obtained from the
processsing of 53,335 articles abstracts. The DOI of each
article indexed in the databses is detailed in the file
`abstracts_filename_id_1.csv`.

The features (columns in file `abstracts_nanotox_db_all_1.csv`) extracted are:

1. nanomaterial composition (nanomaterial_composition) / Physical Unit = None (categorical terms has no PU);
2. nanomaterial morphology (nanomaterial_morphology) / Physical Unit = None (categorical terms has no PU);
3. organism species (biological_species) / Physical Unit = None (categorical terms has no PU);
4. nanomaterial size (nanomaterial_size) / Physical Unit = nm;
5. nanomaterial surface area (nanomaterial_surface_area) / Physical Unit = m<sup>2</sup> g<sup>-1</sup>;
6. nanomaterial zeta pontential (nanomaterial_zeta_potential) / Physical Unit = mV;
7. microbial log reduction (microbe_killing_log) / Physical Unit = dimensionless;
8. microbial minimum inhibitory concentration (microbe_killing_mic) / Physical Unit = mg mL<sup>-1</sup>;
9. microbial bactericidal inhibitory concentration (microbe_killing_mbc) / Physical Unit = mg mL<sup>-1</sup>;
10. biofilm inhibition percentage (microbe_killing_perc) / Physical Unit = %;
11. organism lethal concentration 50 % (toxic_lc50) / Physical Unit = mg mL<sup>-1</sup>.

The features (columns in file `abstracts_nanotox_db_superior_organisms_1.csv`) extracted are:

1. nanomaterial composition (nanomaterial_composition) / Physical Unit = None (categorical terms has no PU);
2. nanomaterial morphology (nanomaterial_morphology) / Physical Unit = None (categorical terms has no PU);
3. organism species (biological_species) / Physical Unit = None (categorical terms has no PU);
4. tocicity endpoint (toxicity_endpoints) / Physical Unit = None (categorical terms has no PU);
5. toxicity confirmation (toxicity_yes_no) / Physical Unit = None (categorical terms has no PU).


File `fulltext_filename_id_1.csv` has a list of DOIs of fulltext articles that are being currently processed by our group.

-------------------------------------------------------------------------------

The databases were generated from the
processing of scientific articles by the [a.RIX
engine](https://github.com/amaurijp/aRIX). Details on the use of the a.RIX
engine is presented in:

> *An automated domain-independent text reading, interpreting and extracting
> approach for reviewing the scientific literature.*
> Amauri J. Paula.
> Solid-Biological Interface Group (SolBIN), Department of Physics,
> Universidade Federal
> do Ceará – UFC, P.O. Box 6030, Fortaleza, CE, 60455-900, Brazil
>
> [https://arxiv.org/abs/2107.14638](https://arxiv.org/abs/2107.14638)
