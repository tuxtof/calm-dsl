# calm-dsl-engine

Calm DSL Engine describes a simpler Python 3 based DSL for writing Calm blueprints.

Use:
 - `make _init` to setup your CentOS 7 VM for development. This will create a python 3 virtualenv in `$TOPDIR/venv` . Activate it by sourcing `$TOPDIR/venv/bin/activate` . It will also setup jupyter for dev purposes.
 - `make dist` to generate a `calm.dsl` python distribution
 - `make test` to run the test cases


## ToDo

 - Language Enhancements:
   - Add Port type - tcp/udp
   - List of supported protocols - ssh
   - EnumType support
 - Elegance wishlist
   - Allow inline definition of stateless classes like `Port`
   - Show required vs optional attributes
   - Add YAML dumper
   - Make all attrs available on the class for ease of discovery aand use
 - DSLs
   - DSL for runbooks
   - DSL for policies (quotas and notification)
   - DSL for apps (for app LCM)
 - Mega ToDo:
   - Generate idiomatic python code from blueprint JSON (decompile)
 - Build CLI tooling to interact with calm-server
 - Build docker container for jupyter + DSL
 - ~Make License as GPL~
 - ~Get rid of attributes field~
