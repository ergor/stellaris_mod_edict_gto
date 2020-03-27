# Greater Than Ourselves via Tradition
Stellaris mod to unlock `Greater Than Ourselves` edict by selecting the `The Greater Good` (or equivalent for gestalts) harmony/synchronicity tradition rather than being a Galactic Community resolution.

### Note to self on localisation:

- The file name must end in `_l_<language>.yml`, otherwise it will not be read.
- The first line of any localisation file must be `l_<language>:`, otherwise it will not be read.
- Stellaris's localisation files are encoded as `UTF-8-BOM`. They must be encoded in UTF-8-BOM, as even UTF-8 will fail to be parsed by Stellaris, and will not work.

Saving as UTF-8-BOM with `vim`:

```
:set fileencoding=utf8
:set bomb
:w myfilename
```

[More on localisation modding](https://stellaris.paradoxwikis.com/Localisation_modding)
