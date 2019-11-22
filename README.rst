UDMorpho: MacMorpho v3 dataset with UD tags
===========================================

.. note::

   In macmorpho v3 ``VAUX`` were merged with ``V``. Here this distinction is
   back. In UD tags they are ``AUX`` and ``VERB`` repectively.

The translation table is as follows:

* ``ART`` - ``DET|PronType=Art``
* ``ADJ`` - ``ADJ``
* ``N`` - ``NOUN``
* ``NPROP`` - ``PROPN``
* ``NUM`` - ``NUM``
* ``PROADJ`` - ``DET|PronType=prs``
* ``PROSUB`` - ``PRON``
* ``PROPESS`` - ``PRON|PronType=Prs``
* ``PRO-KS`` - ``PRON``
* ``ADV`` - ``ADV``
* ``ADV-KS`` - ``ADV``
* ``ADV-KS-REL`` - ``ADV``
* ``KC`` - ``CCONJ``
* ``KS`` - ``SCONJ``
* ``PREP`` - ``ADP``
* ``PREP+ART`` - ``ADP``
* ``IN`` - ``INTJ``
* ``PCP`` - ``VERB|VerbForm=Part``
* ``PDEN`` - ``ADV``
* ``VAUX`` - ``AUX``
* ``V`` - ``VERB``
* ``CUR`` - ``SYM``


The exceptions for this translation are possessive pronouns that originaly
were marked as ``PROADJ`` here are marked as ``PRON|PronType=prs|Poss=Yes``.

If you want to generate the udmopho translation by yourself, in the root dir
of this project execute:

.. code-block:: sh

   $ ./mac2ud
