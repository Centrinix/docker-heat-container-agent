# docker-heat-container-agent

This repository provides a custom GitHub Actions-based CI/CD process for
building the `docker-heat-container-agent` Docker image for AArch64 and x86-64
hosts, because the upstream OpenStack project does not provide the AArch64
images.

It is intended to be used by the Centrinix Cloud infrastructure; but, nothing
in this repository should prevent its reuse in a third-party OpenStack Magnum
cluster.
