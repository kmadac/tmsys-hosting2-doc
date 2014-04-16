.. TMsys Hosting documentation master file, created by
   sphinx-quickstart on Wed Apr 16 14:37:41 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

µHosting 2.0
==================

Nová verzia hostingu, ktorá je založená na Cloud technológiach, `DevOps <http://en.wikipedia.org/wiki/DevOps>`_ a CI princípoch.

Konfigurácia a správa celého prostredia je automatizovaná pomocou projektu `Ansible <http://www.ansible.com/>`_. Zmeny v produkčnom prostredí nie sú nikdy vykonávané manuálne. Každá zmena je najprv testovaná v testovacom prostredí a keď je daná zmena funkčna, aplikuje sa Ansible playbook na produkčné prostredie.

Funkcionalita jednotlivých služieb je rovnako automaticky testovaná po každej zmene ako v testovacom prostredí, tak aj v produkčnom prostredi, aby sme zaručili funkčnosť každej funkcionality.

Každá zmena v konfigurácii je uchovávaná v Git-e, čiže 

Nastavenie emailového klienta
##############################

Mozilla Thunderbird IMAP
************************

.. toctree::
   :maxdepth: 2



.. Indices and tables
.. ==================
.. 
.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`

