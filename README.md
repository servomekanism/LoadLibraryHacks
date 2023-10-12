# LoadLibraryHacks

 Jonas Lyk created this approach and implemented it as a proof of concept (POC) for creating a new process from an in-memory executable.

 See "dav.cpp" -> process host a WebDAV server, use LoadLibrary to load a path that resolves to your server, and have the server respond with the bytes of an in-memory library when that path is requested.
