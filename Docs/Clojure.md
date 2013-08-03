## Zephyros - Clojure API

* [API docs](file://localhost/Users/sdegutis/projects/zephyros/libs/zephyros-clj/doc/zephyros.api.html)

#### Running the script manually

1. Download the subtree at https://github.com/sdegutis/zephyros/tree/tcp/libs/zephyros-clj
2. Copy it somewhere outside of Zephyros
3. `cd zephyros-clj`
4. `lein run`
5. Edit your [src/zephyros/core.clj](../libs/zephyros-clj/src/zephyros/core.clj)

#### Letting Zephyros run it for you

Put this as your auto-launch-command inside Zephyros:
```bash
cd path/to/zephyros-clj && lein run
```