# Brother catalogue photo asset checklist

The catalogue is prepared to load exact-model product photos from `images/brother/`.

## Upload requirements
- Use approved manufacturer/distributor images only, with permission to publish.
- Supply a verified photo for each of the **34 brochure models** as a WebP file.
- Put images in `images/brother/`; filenames should follow the model slug (e.g. `dcp-t430w.webp`, `hl-l2400d.webp`).
- For brochure anomalies, the page explicitly maps `DCP 230` to `dcp-t230.webp`, `MFCT4500DW` to `mfc-t4500dw.webp`, and `HL T4000DW` to `hl-t4000dw.webp`. Verify these against the supplier document before using those photos.
- When the requested image is not present, the existing illustration remains visible. No model image has been added by this PR.
- Do not merge until assets have been verified, and check browser console for image failures.

The product prices, filters, sorting, stock status, and modal details remain unchanged.

## Manufacturer image preview (draft only)
Four exact-model image URLs are now wired into the draft page for DCP-T230 (brochure: DCP 230), DCP-T430W, DCP-T530DW and DCP-T730DW. These external Brother-hosted images are a **preview**, not cleared production assets. Manufacturer or distributor permission and locally hosted copies are still required before deploying. The remaining 30 cards will show their category illustrations until verified images are sourced.
