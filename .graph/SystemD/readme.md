https://distrobox.it/usage/distrobox-create/

quote:
"""
The --init is useful to create a container that will use its own separate init system within. For example using:

distrobox create -i docker.io/almalinux/8-init --init --name test
distrobox create -i docker.io/library/debian --additional-packages "systemd" --init --name test-debian
Inside the container we will be able to use normal systemd units:
"""