==========================================================
Data Repository
==========================================================
Source code and data files for the manuscript Emergence of spinons in layered trimer iridate Ba4Ir3O10. Execute plot.ipynb to view the data.

How to cite
-----------
If this data is used, please cite Emergence of spinons in layered trimer iridate Ba4Ir3O10 Y. Shen, J. Sears, G. Fabbris, A. Weichselbaum, W. Yin, H. Zhao, D. G. Mazzone, H. Miao, M .H. Upton, D. Casa, R. Acevedo-Esteves, C. Nelson, A. M. Barbour, C. Mazzoli, G. Cao, and M. P. M. Dean

but means to realize spinons in higher dimensions is the subject of intense research. Here, we use
resonant x-ray scattering to study the layered trimer iridate Ba4Ir3O10, which shows no magnetic
order down to 0.2 K. An emergent one-dimensional spinon continuum is observed that can be
well-described by XXZ spin-1/2 chains with magnetic exchange of ∼55 meV and a small Ising-like
anisotropy. With 2% isovalent Sr doping, magnetic order appears below TN=130 K along with
sharper excitations, indicating that the spinons become more confined in (Ba1−xSrx)4Ir3O10. We
propose that the frustrated intra-trimer interactions effectively reduce the system into decoupled spin
chains, the subtle balance of which can be easily tipped by perturbations such as chemical doping.
Our results put Ba4Ir3O10 between the one-dimensional chain and two-dimensional quantum spin
liquid scenarios, illustrating a new way to suppress magnetic order and realize fractional spinons.

Run locally
-----------

Work with this by installing `docker <https://www.docker.com/>`_ and pip and then running

.. code-block:: bash

       pip install jupyter-repo2docker
       jupyter-repo2docker --editable .

Change `tree` to `lab` in the URL for JupyterLab.

Run remotely
------------

.. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/mpmdean/Shen2022emergence/HEAD?filepath=plot.ipynb
