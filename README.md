# sourcemap-not-served-repro

This is repro for this [github issue](https://github.com/snowpackjs/snowpack/issues/1478).

Uses `app-template-react-typescript`.

`start` script (using snowpack 3.0.13) will trigger the bug: original files are served instead of their sourcemap

`start-with-local-snowpack` script (using a local snowpack: branch main, HEAD 906f25) won't trigger the bug
