# metadata-csv

Code snippets to explore the transportdata.be API and see how we can use it for our checks.

Transportdata.be use CKAN. Docs are here: https://docs.ckan.org/en/2.8/api/

The source for the website (or part of it at least) is here: https://github.com/belgium-its-steering-committee

Details about dataset fields are specified here: https://github.com/belgium-its-steering-committee/ckanext-benap/blob/master/ckanext/benap/benap_schema.json

Getting all datasets: https://transportdata.be/api/3/action/package_list

Getting details about one dataset: https://transportdata.be/api/3/action/package_show?id=cambio-belgium

Getting organizations list: https://transportdata.be/api/3/action/organization_list

Getting orgnanization details: https://transportdata.be/api/3/action/organization_show?id=sncb

With datasets: https://transportdata.be/api/3/action/organization_show?id=sncb&include_datasets=true

Getting users list: https://transportdata.be/api/3/action/user_list

