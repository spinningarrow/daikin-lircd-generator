# daikin-lircd-generator

This is a fork of the [HomeAutomationServer][] project. It is a simplified
version that removes everything except for the parts that generate the
configuration for the LIRC remote.

For fun, I mixed in some Clojure to invoke the code that builds the configs and
then print it to stdout.

## Usage

- Update the desired configs in `-main` in `src/main/clojure/daikin/core.clj`
- Execute `lein run` to print the config file to stdout

[HomeAutomationServer]: https://github.com/opensourcerebel/HomeAutomationServer
