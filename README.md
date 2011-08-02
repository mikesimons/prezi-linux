# Prezi linux

Feed it a prezi zip and it'll give you an executable to run a webserver to serving your prezi presentation.

  ./prezi-linux prezi.zip my_prezi
  ./my_prezi

## Requirements

To convert you need unzip which is the only thing that doesn't come with most modern distros that I'm aware of.
To run the presentation you need ruby & rackup installed.

## Issues

Could possibly do with checks in bootstrap for required deps (ruby / rackup)
