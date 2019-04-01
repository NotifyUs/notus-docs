Getting Started
***************

Notus ships with a complete, tiny JavaScript library to communicate with our API.

-----

Installing in Node.js
=====================

Install the notus-js library from your project directory::

    $ npm install --save notus-js

Or with Yarn::

    $ yarn add notus-js

-----


Importing
---------

.. code-block:: javascript
    :caption: *JavaScript (ES3)*

    var notusClient = require('notus-js');

.. code-block:: javascript
    :caption: *JavaScript (ES5 or ES6)*

    const notusClient = require('notus-js');

.. code-block:: javascript
    :caption: *JavaScript (ES6) / TypeScript*

    import { notusClient } from 'notus-js';


Configuration
-------------

.. code-block:: javascript

    notusClient.config({
      apiKey: '<YOUR API KEY>',
      ...
    })



.. -----

.. Including in Web Applications
.. =============================

.. For security purposes, it is usually best to place a **copy** of `this script`_ on
.. the application's server, but for a quick prototype using the Ethers CDN (content
.. distribution network) should suffice.

.. .. code-block:: html
..     :caption: *HTML*

..     <!-- This exposes the library as a global variable: ethers -->
..     <script src="https://cdn.ethers.io/scripts/ethers-v4.min.js"
..             charset="utf-8"
..             type="text/javascript">
..     </script>


.. -----

.. .. _this script: https://cdn.ethers.io/scripts/ethers-v4.min.js
