# Grok-Host

Public https host for Grok concept art and discussion pictures.
Not Tracker-Vault. Vault XML only stores `<image href="https://..."/>`.

## Layout

```
Asteria/<ticket>-<slug>.jpg
FrameField/<ticket>-<slug>.jpg
Tracker/<ticket>-<slug>.jpg
```

Raw URL pattern:

`https://raw.githubusercontent.com/Stackocakes-Hub/Grok-Host/main/Asteria/<file>.jpg`

jsDelivr fallback:

`https://cdn.jsdelivr.net/gh/Stackocakes-Hub/Grok-Host@main/Asteria/<file>.jpg`

GitHub file tools from this Grok session are text-only, so binary plates may live at a public object URL listed in `INDEX.md` until raw files can be pushed.
