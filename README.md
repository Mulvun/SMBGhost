# SMBGhost
This script connects to the target host, and compresses the authentication request with a bad offset field set in the transformation header, causing the decompressor to buffer overflow and crash the target.
