nginx
=====

Installing the latest version on Ubuntu
---------------------------------------

Run the following commands as root:

.. code-block:: console

    add-apt-repository ppa:nginx/stable
    apt-get update && apt-get install nginx

Installing the latest version on Debian
---------------------------------------

Run the following commands as root:

.. code-block:: console

    wget -O key http://nginx.org/keys/nginx_signing.key && apt-key add key && rm -f key
    echo "deb http://nginx.org/packages/debian/ wheezy nginx" | tee /etc/apt/sources.list.d/nginx.list
    apt-get update && apt-get install nginx
