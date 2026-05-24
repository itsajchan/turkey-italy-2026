# Turkey and Italy Travel Blog

Static travel blog prepared for Coolify deployment.

## Deploy on Coolify

1. Push this `coolify-site` folder to a Git repository.
2. In Coolify, create a new Docker-based application from that repository.
3. Use this folder as the project root if the repository contains other files.
4. Set the exposed port to `80`.
5. Attach your domain or subdomain.

The Docker image uses nginx and serves `index.html` plus the optimized images in `web-optimized/`.
