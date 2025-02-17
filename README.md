DATABASE - NANOMATERIALS INTERACTIONS WITH BIOLOGICAL SYSTEMS (nanotox_db) - Version 1.0
===============================================================================

The `nanotox_db_1.csv` file is in version 1.0 and it was obtained from the
processsing of 53,335 articles abstracts. The title of each
article indexed in the `nanotox_db_1.csv` is detailed in the file
`filename_id_1.csv`.

The database was generated from the
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

-------------------------------------------------------------------------------

The features (columns in file `nanotox_db_1.csv`) extracted are:

1. nanomaterial composition (composition) / Physical Unit = None (categorical terms has no PU);
2. nanomaterial morphology (morphology) / Physical Unit = None (categorical terms has no PU);
3. organism species (species) / Physical Unit = None (categorical terms has no PU);
4. nanomaterial size (size) / Physical Unit = nm;
5. nanomaterial surface area (surface_area) / PU = m<sup>2</sup> g<sup>-1</sup>;
6. nanomaterial zeta pontential (zeta_potential) / Physical Unit = mV;
7. microbial log reduction (microbe_killing_log) / Physical Unit = dimensionless;
8. microbial minimum inhibitory concentration (microbe_killing_mic) / Physical Unit = mg mL<sup>-1</sup>;
9. microbial inhibition percentage (microbe_killing_perc) / Physical Unit = %;
10. organism effective concentration 50 % (toxic_ec50) / Physical Unit = mg mL<sup>-1</sup>;
11. organism inhibitory concentration 50 % (toxic_ic50) / Physical Unit = mg mL<sup>-1</sup>;
12. organism lethal concentration 50 % (toxic_lc50) / Physical Unit = mg mL<sup>-1</sup>; 
