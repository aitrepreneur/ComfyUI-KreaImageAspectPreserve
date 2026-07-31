# ComfyUI Krea Image Aspect Preserve

Aspect-preserving prepare and restore nodes for Krea 2 image editing, identity, face swap, clothing swap, and dual-reference workflows.

They let Krea work inside a valid resolution bucket, then restore the result back to the exact native resolution without stretching, image shifting, or losing the original aspect ratio.

## Installation

Clone this repository into `ComfyUI/custom_nodes`:

```bash
git clone https://github.com/aitrepreneur/ComfyUI-KreaImageAspectPreserve.git
```

Restart ComfyUI.

## Included Nodes

- `Krea Image Aspect-Preserve Prepare`
- `Krea Universal Native-Res Restore`

## Important

These nodes were created specifically for my Krea 2 identity and editing workflows.

They support:

- one-image edits;
- identity edits;
- face and head swaps;
- clothing swaps;
- dual-reference edits;
- localized edits;
- full-frame generations;
- exact native-resolution restoration.

The custom nodes alone are not the complete workflow.

## What It Fixes

- distorted aspect ratios;
- smaller final outputs;
- image shifting;
- blurry resize-back results;
- broken local composites;
- corrupted GPU stripe outputs.

The restore node can automatically decide whether to use:

- a manual mask;
- an automatically detected local edit;
- or the full generated frame.

## Full Workflow

The complete ready-to-run workflows, recommended settings, LoRA setup, updates, installers, and support are available on Patreon:

[Patreon — Aitrepreneur](https://www.patreon.com/c/aitrepreneur)

Tutorials and demonstrations:

[YouTube — Aitrepreneur](https://www.youtube.com/@Aitrepreneur)

## License

Apache-2.0
