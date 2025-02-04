Version 0.1.6 (March 29, 2019)
==============================

Finish adding ``MNI152NLin6Sym`` after curation of NIfTI volumes and exporting to S3.

Version 0.1.5 (March 29, 2019)
==============================

Add volumetric data to the ``fsLR`` template, and rename the segmentation of subcortical structures to be consistent with the new files.

Version 0.1.4 (March 28, 2019)
==============================

New release to include the new ``MNI152NLin6Asym`` template (the default MNI template of FSL).

Version 0.1.3 (March 14, 2019)
==============================

Update TemplateFlow skeleton to include ``tpl-fsaverage/tpl-fsaverage_dseg.tsv``, after TemplateFlow update.

Version 0.1.2 (March 12, 2019)
==============================

* FIX: ``api.get`` - robuster fetcher algorithm (allows S3 download on DL repos) and better error messages (#10)

Version 0.1.1 (March 12, 2019)
==============================

* FIX: Require environment variable to use DataLad (#8)

Version 0.1.0.post1 (March 05, 2019)
====================================

Testing a better ``.zenodo.json`` settings.

Version 0.1.0 (March 05, 2019)
==============================

First minimally functional TemplateFlow client release.

Version 0.0.5.post1 (March 04, 2019)
====================================

Hotfix release to retrieve correct version when pip installed. Adds .zenodo.json file.

Version 0.0.5 (March 04, 2019)
==============================

* [ENH] Datalad-free alternative for TemplateFlow (#7)
* [ENH] Use a BIDSLayout to index TemplateFlow (#6)

Version 0.0.4 (January 18, 2019)
================================

* Add a ``get_metadata`` utility

Version 0.0.3 (January 16, 2019)
================================

* Add ``api.templates()`` + one doctest

Version 0.0.2 (January 16, 2019)
================================

* Add one doctest


Version 0.0.1 (January 16, 2019)
================================

* First functional release
