The `eslint-config-frost-standard` dependency provides both the `eslint-plugin-ember-standard` and `eslint-plugin-ocd` dependencies, both of which provide the `remark-lint` dependency at version `^6.0.1`.  This version of `remark-lint` is incompatible with this repository's code though, so this repository has its own explicit dependency on `remark-lint` at version `^5.4.0`.