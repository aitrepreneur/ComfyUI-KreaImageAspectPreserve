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

These nodes were created specifically for my Krea 2 inpainting and outpainting system.

You will also need:

- [INPAINTKREA LoRA on Hugging Face](https://huggingface.co/Aitrepreneur/INPAINTKREA)
- [Krea 2 Ultra Workflow V3 on Patreon](https://www.patreon.com/aitrepreneur/posts/165393666)

The custom nodes alone are not the complete workflow.

They support:

- one-image edits;
- identity edits;
- face and head swaps;
- clothing swaps;
- dual-reference edits;
- localized edits;
- full-frame generations;
- exact native-resolution restoration.

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

## Before

<img width="480" height="268" alt="Before" src="https://github.com/user-attachments/assets/097b43bb-b67b-44bc-9e6e-bab7fc75e572" />

## After

<img width="480" height="268" alt="afterbirdinpaint" src="https://github.com/user-attachments/assets/54e91c71-984d-4357-b4d3-37c93378c5b7" />

<img width="480" height="268" alt="Krea2UniversalNativeRes_00005_" src="https://github.com/user-attachments/assets/e550025e-5964-4227-8622-cd14b8f24ab2" />


<img width="480" height="268" alt="Krea2UniversalNativeRes_00011_" src="https://github.com/user-attachments/assets/24cbb55f-6fff-47ca-b9d3-848cad710cbd" />

<img width="480" height="268" alt="Krea2UniversalNativeRes_00012_" src="https://github.com/user-attachments/assets/1fb348d2-cab1-4899-b80a-665114288a67" />


## Full Workflow

The complete ready-to-run workflows, recommended settings, LoRA setup, updates, installers, and support are available on Patreon:

[Patreon — Aitrepreneur](https://www.patreon.com/c/aitrepreneur)

Tutorials and demonstrations:

[YouTube — Aitrepreneur](https://www.youtube.com/@Aitrepreneur)

## License

Apache-2.0
