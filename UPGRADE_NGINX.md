# Upgrade NGINX version used

1. Update golang version in `GOLANG_VERSION`
1. Update ingress controller `TAG` file
1. Update NGINX `images/nginx/TAG` file
1. Update NGINX `images/nginx/rootfs/build.sh` version and hash below
1. Update `images/nginx/rootfs/Dockerfile` Alpine image
1. Update `rootfs/Dockerfile-chroot` Alpine image
1. Trigger workflow "Container Images"
1. Update `README.md` versions, tags and digest
1. Update `NGINX_BASE` digest
