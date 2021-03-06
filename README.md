<p align="center">
    <a href="https://blymp.io">
      <img src="./icon.png" alt="blymp.io logo" width="250"/>
    </a>
</p>

<h1 align="center">
  blymp.io
</h1>
<h2 align="center" style="margin-bottom:2rem">
  Easily transfer files between devices
</h2>

blymp.io is a webapp that allows you to easily transfer files between devices with high speeds.

It uses modern technologies like WebRTC, Blobs and WebSockets to allow files to be transferred as fast as possible.

You can use blymp.io by going to <https://blymp.io>

- [Quick Start](#quick-start)
- [Folder Structure](#folder-structure)

## Quick Start

```bash
# Clone the repository
git clone https://github.com/vantezzen/blymp-io

# Go inside the directory
cd blymp-io

# Install dependencies
yarn (or npm install)

# Start development server
yarn dev (or npm run dev)

# Build for production
yarn build (or npm run build)

# Start production server
yarn start (or npm start)
```

## Folder Structure

All the source code will be inside **src** directory. Inside src, there is client and server directory. All the frontend code (react, css, js and any other assets) will be in client directory. Backend Node.js/Express code will be in the server directory.
