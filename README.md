# jfe
Programmable Timeline Journal for Engineers

# Dependency Notes

## NW.js
Since I'm not looking to release this (certainly not any time soon, anyway) I am developing against the 0.13.x branch of nw.js even though there are known issues and functionality gaps.  There are two main builds of nw.js, the normal build that is used for releases and such and the "SDK" build that has the devtools available.  The "build" process should move the correct version into the correct spot to package the application correctly.  Will have to figure this out later, for now just keep nwjs builds in the `/nwjs` folder.

**Current Version:** nwjs-sdk-v0.13.0-alpha5-win-x64

Symlink the current version into the `/build` folder:
`mklink /j build\nwjs nwjs\nwjs-sdk-v0.13.0-alpha5-win-x64`
