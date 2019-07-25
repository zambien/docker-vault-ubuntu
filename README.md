# docker-vault-ubuntu

Dockerhub: https://hub.docker.com/r/zambien/docker-vault-ubuntu

Hashicorp's docker-vault runs Alpine. 

In some cases you might not want to use Alpine.  For example:

* You aren't allowed to for some reason
* You need CGO to be enabled and the libs aren't available.
* You have some other reason

Generally speaking, you should be able to use this by following the hashicorp docs here: https://github.com/hashicorp/docker-vault

Note, prior to 1.2.0-beta2 only release (not beta or RC) Vault versions 0.11.6 and higher are available.

