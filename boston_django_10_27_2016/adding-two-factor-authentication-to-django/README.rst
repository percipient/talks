Django Boston Meetup October 27, 2016
#####################################

`Patrick Cloke <https://github.com/clokep/>`_ presented a lightning talk on the
`django-allauth-2fa <https://github.com/percipient/django-allauth-2fa/>`_
library, which helps add two-factor support to Django projects which use
`django-allauth <https://github.com/pennersr/django-allauth>`_.

To build the slides:

.. code-block:: bash

    pip install -r requirements.txt
    make slides

Or to continually build changes:

.. code-block:: bash

    sphinx-autobuild -b slides -d _build/doctrees . slides

Slides are available here.
