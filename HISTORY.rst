=======
History
=======

---------------------------------
0.1.3 (2021-03-10): Full *pit*
---------------------------------

* Change of paradigm: start from the notebook and build the module cell by cell.

* Consequences: all modules from 0.1.2 are moved to the pit. They will be restored during the notebook transformation.

* sentence splitter optimized



---------------------------------
0.1.2 (2021-03-03): the *pit*
---------------------------------

* Batch import of remaining modules in a temporary submodule (the *pit*). The *pit* will be dispatched afterwards.

* Fix import issues (e.g. spacy neuralcoref version incompatibility, Qt5, sknetwork...)

* submodule gismo_wrapper on death row (may never leave the pit)

* Embedding_idf OK

* Building summary: summarize and make_tree have been updated to work.

* Lot's of cleaning remains (separating covid/generic, unified pre-proc and source convention,...)

* Take down neuralcoref for the moment. Does not build on github.


---------------------------------
0.1.1 (2021-02-23): data_loader
---------------------------------

* Finish import / transformation of the data_loader module.


---------------------------------
0.1.0 (2021-02-23): First release
---------------------------------

* First release on PyPI.

* Preprocessing submodule deployed
