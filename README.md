kmake is a meta-build-tool for C/C++ projects similar in its functionality to
premake and cmake.
It is an extended fork of Node.js so it provides the speed of V8 and all of the
Node.js-API to kmake-build-scripts.

Use
./configure --openssl-no-asm --without-intl --node-builtin-modules-path $(pwd)
for when you are only changing TypeScript and/or JavaScript files to create a build that pulls them in at runtime.
