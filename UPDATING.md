# Updating to latest protos

1. Clone/pull latest [POGOProtos](https://github.com/AeonLucid/POGOProtos)
2. Copy all folders from `src\POGOProtos` to the `proto` directory
3. Execute in node-pogo-protos directory:
    - `npm run compile`
    - `npm run js`
    - `npm run ts`
4. Bump version number (same version as POGOProtos) in `package.json` and add version tag
