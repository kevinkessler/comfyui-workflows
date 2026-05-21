# comfyui-workflows

Personal ComfyUI workflow collection.

## Flux.2 Klein Image Edit

| File | Description |
|------|-------------|
| `klein_image_edit.json` | Reference-guided image editing with Flux.2 Klein 9B. Single reference image. Exposes megapixels, supports up to 2048×2048. |
| `klein_image_edit_v2.json` | Extends v1 with mask-guided editing via `SetLatentNoiseMask`. **Paint the mask over the people you want removed.** The unmasked region is never touched by the sampler — the person you want to keep is preserved exactly. Use the MaskEditor (right-click LoadImage → Open in MaskEditor) to paint. |
