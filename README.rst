nginx
=====

Installing the latest version of nginx on Ubuntu
------------------------------------------------

.. code-block:: console

    sudo add-apt-repository ppa:nginx/stable
    sudo apt-get update && sudo apt-get install nginx

Installing the latest version of nginx on Debian
------------------------------------------------

.. code-block:: console

    wget -O key http://nginx.org/keys/nginx_signing.key && apt-key add key && rm -f key
    echo "deb http://nginx.org/packages/debian/ wheezy nginx" | tee /etc/apt/sources.list.d/nginx.list
    apt-get update && apt-get install nginx
