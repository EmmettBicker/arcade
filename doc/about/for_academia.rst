.. _academia:

For Researchers & Instructors
=============================

.. _citation template: https://github.com/pythonarcade/arcade#citation

Python Arcade was created by Paul V. Craven while teaching at Simpson College.

In addition to the primary documentation you are currently viewing,
there are further resources and affordances for academic users.
These include:

* A `citation template`_ in Arcade's GitHub landing page
* An `Arcade book`_ by the framework's creator
* Many third-party libraries and tutorials

.. _academia_citations:

The Citation Template
---------------------

The `citation template`_ in the ``README.md`` uses `BibTeX`_ format.
For other citation formats, please consult the appropriate style guide or
converter manual.


.. _academia_version_2v3:

Version Considerations
----------------------

Educators may prefer Arcade ``2.6.X`` over ``3.0.0`` due to its mature
documentation.

The Companion Book
^^^^^^^^^^^^^^^^^^

Arcade 2.6 has an instructor-designed `companion book <Arcade book>`_. Although
the documentation you're reading now also aims to be an all-ages document, it
lacks the translations and clear curriculum structure provided by the book. It
integrates these with crucial materials:

* embedded videos demonstrating both concepts and past student projects
* a gentle introduction to industry-standard tools which often intimidate CS graduates
* languages and CS topics applicable at the univerity level and beyond

.. list-table:: Differences from Arcade's Main Documentation
   :header-rows: 1

   * - Aspect
     - Main Documentation
     - Arcade Companion Book

   * - Near-Term Target Version
     - 3.0.0+
     - 2.6.X

   * - Structure Level
     - Low
     - High

   * - Translation
     - None
     - `Swedish / Svenska <book_sv>`_, `German / Deutsche <book_de>`_

.. _book_sv: https://learn.arcade.academy/sv/latest/
.. _book_de: https://learn.arcade.academy/de/latest/

.. _2_6_maintenance:

2.6.X Maintenance
-----------------

The Arcade team is exploring maintenance-only releases for 2.6.X. The goals
for these releases would be the following:

#. Security updates
#. Compatibility with newer Python versions
#. Highly limited bug fixes

New features are not a priority unless crucial for security or compatibility.


A Computer Lab on a Budget
--------------------------

This section is provides a starting point for educators who:

* aim to teach programming workshops for 5-15 students
* have not yet acquired the hardware to do so
* wish to make effective use of their budget

It is not a step-by-step guide because it is impossible to make
one general enough.

General Considerations
^^^^^^^^^^^^^^^^^^^^^^

If you do not already have network infrastructure to plug into,
you may want to budget for router and a cheap switch. This isn't
for multiplayer, but for downloading packages or boot images to
user machines.

For younger students, be sure to limit unsupervised network access. You
may also need to allocate time to cover the basics of file and folder
structures since many students now grow up with mobile devices rather
than traditional PCs.

For offline work, this list of `PyPI mirror tools`_ may be helpful.

.. _PyPI mirror tools: https://packaging.python.org/en/latest/guides/index-mirrors-and-caches/#existing-projects


Surplus Hardware
^^^^^^^^^^^^^^^^
This is often the best option and sometimes the only one.

Even if a device does not have, many enterprise-oriented desktop PCs
from the past decade can be revived with a low-resource Linux installation.


Raspberry Pi and other SBCs
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Single-Board Computers (SBCs) such as the Raspberry Pi 4 and 5
are not always the most cost-effective option.

However, they may be worth considering when one or more of the
following applies:

* Surplus hardware isn't an option
* You have an educational discount
* You have grant or non-profit funding

.. _sbc_rule_of_thumb:

SBC Rules of Thumb
^^^^^^^^^^^^^^^^^^

ARM64 and AMD64 CPUs Will Be Easier
"""""""""""""""""""""""""""""""""""
RISC systems *may* work, but such SBCs do not have the same amount
of beginner-friendly community around them.


Credit Card Rule
""""""""""""""""

As of October 2024, all compatible and widely-available SBCs are
larger than credit cards:

* 3.375 inches by 2.125 inches
* 85.60 mm by 53.98 mm

If you try to use this rule:

#. Compare to the actual circuit board's size, not the size of the package
#. Use an old hotel key card, expired credit card, or expired debit card

It's unlikey that an SBC board will have magnets. However, the package
might include them in motors (in kits) or as part of the box itself.
Using an old card stops you from accidentally wiping a magnetic strip you need.

Although this errs on the side of caution, it also:

* quickly rules out :ref:`incompatible Raspberry Pi models <sbc_unsupported_raspis>`
* should apply to other SBCs as well
