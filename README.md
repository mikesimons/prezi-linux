# Prezi linux

Feed it a prezi zip and it'll give you an executable to run a webserver to serving your prezi presentation.

./prezi-linux prezi.zip my_prezi
./my_prezi

## Requirements

To convert you need unzip & tar.
To run you need ruby & rackup installed.

## Issues

Currently presentations are not compressed due to some kind of corruption when appending the binary data. If you can figure out the issue or streamline the deps, please do!
