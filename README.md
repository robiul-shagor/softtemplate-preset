# SoftTemplates preset library

Online template presets for the SoftTemplates for Elementor plugin.

```
index.json                 list of presets
templates/<id>.json        one template per preset (Elementor export format)
thumbnails/<id>.svg|png    preview image, about 600 × 360
```

To add a preset: export it from **Templates > My templates** (download icon), put it in
`templates/`, add a thumbnail, and add an entry to `index.json`. To update a preset, keep its
`id` and raise its `version`. Sites refresh every 12 hours, or at once with
**Templates > Library > Refresh**.
