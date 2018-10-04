# bandwidth-hero-proxy Docker container

This is a version of the infamous bandwidth-hero's extension proxy server as a Docker container.

All you need to do is install Docker or CRI-O and Podman and you're set for the day!

## Running 

All you need is Docker or CRI-O and Podman.

then: 
    - `docker pull claritymoe/bandwidth-hero-proxy` (for Docker)
    - `podman pull claritymoe/bandwidth-hero-proxy` (for Podman)

and finally run it using:
    - `docker run claritymoe/bandwidth-hero-proxy` (for Docker)
    - `podman run claritymoe/bandwidth-hero-proxy` (for Podman)

## Contributing

All contributions are accepted. But it falls under this three parameters:

- Images always and SHOULD always run on usermode.
- File permissions are set correctly.