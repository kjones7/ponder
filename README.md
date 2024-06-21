# Ponder

## Installation
I ran into some issues with `node_modules` syncing between the container and my local machine. I removed `node_modules` from the bind mount, which should help. I'd recommend calling `npm install` locally before building/starting the containers.
