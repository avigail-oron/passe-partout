Passe partout v0.1
==================

passe-partout is a tool to extract SSL private keys from process memory written by Nicolas Collignon and Jean-Baptiste Aviat (passe-partout@hsc.fr).

More information may be found at the following URLs:

* http://www.hsc.fr/ressources/breves/passe-partout.html.en
* http://www.hsc.fr/ressources/breves/passe-partout.html.fr

Tested to work with:
* ssh-agent (from OpenSSH 6.1)
* Apache httpd 2.2.23
* Nginx 1.2.6
* Node.js v0.8.15
* CherryPy 3.2.2 + Python 2.7.3 (load generation is required to catch live SSL_CTX objects)
* Tornado 2.4.1 + Python 2.7.3 (load generation is required to catch live SSL_CTX objects)
* Tornado 2.4.1 + Python 3.3.0 (load generation is required to catch live SSL_CTX objects)

License: Beerware

Authors: Nicolas Collignon and Jean-Baptiste Aviat


