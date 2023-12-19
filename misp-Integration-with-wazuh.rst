Monitoring network activity with MISP.
======================

In this use case, we demonstrate how to integrate MISP with Wazuh. MISP can provide additional insights into your network's security with its threat intelligence. We will use the Sysmon tool in the Windows endpoint and forward Sysmon logs to Wazuh. 

About MISP
----------------

The MISP is an open-source software solution for collecting, storing, distributing and sharing cyber security indicators and threats about cyber security incidents analysis and malware analysis. MISP API allows you to query, create, modify data models, such as Events, Objects, Attributes. This is extremely useful for interconnecting MISP with external tools and feeding other systems with threat intel data.

.. _MISP_terms:

Terms of Service
----------------
