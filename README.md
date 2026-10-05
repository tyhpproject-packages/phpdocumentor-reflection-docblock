<!-- tyhp-readme:start -->
# tyhpdef/phpdocumentor-reflection-docblock

Tyhp type definitions for `phpdocumentor/reflection-docblock` `6.0.3`.

```bash
composer require --dev tyhpdef/phpdocumentor-reflection-docblock:6.0.3
```

This is a metapackage. Composer also installs `tyhpdef/phpdocumentor-reflection-docblock-impl` (type files).
Require **this** name, not `tyhpdef/phpdocumentor-reflection-docblock-impl`.

See https://tyhplang.com.

## Maintain `phpdocumentor/reflection-docblock`? Ship the types yourself

If you are a Packagist maintainer of `phpdocumentor/reflection-docblock`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/phpdocumentor-reflection-docblock-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `phpdocumentor/reflection-docblock` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/phpdocumentor-reflection-docblock": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `phpdocumentor/reflection-docblock` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `phpdocumentor/reflection-docblock` with a real constraint,
   `"replace": { "tyhpdef/phpdocumentor-reflection-docblock": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `phpdocumentor/reflection-docblock` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/phpdocumentor-reflection-docblock` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
