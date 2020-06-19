Azure migrate
========================

This is a module to management Azure migrate based on REST API
[Docs Azure REST API](https://docs.microsoft.com/en-us/rest/api).

Installation
========================
To install azure-migrate from PYPI:

.. code-block:: bash

    $ pip install azure-migrate

Get Credentials
========================
You need set three environments variables to use this module:
 - CLIENT_ID
 - SECRET
 - TENANT

After this, you can import this is module.

```
Import the module credentials contained in this same package.

from azure_migrate.credentials import CredentialsAzure

```

Usage
========================

.. code-block:: bash

    $ migr = MigrateVmAzure()

Contact
========================

- Github: https://github.com/alissonit
- Linked: http://linkedin.com/in/alisson-castro-8b0556101