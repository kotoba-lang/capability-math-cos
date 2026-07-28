# capability-math-cos

Atomic authority package for `math/cos`.

- imports: `#{:cos}`
- effects: `#{:pure-compute}`
- default policy: `:autonomous`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
