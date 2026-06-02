# WeigthFile

This repository stores the LoRA weight files for the `Friday770/Diffusion` code repository.

## Default LoRA Weight

The default weight used by the code repository is:

```text
lora_weights/mine_blast_pile.safetensors
```

Place this file at the same relative path inside the code repository:

```text
Friday770/Diffusion/lora_weights/mine_blast_pile.safetensors
```

The corresponding code repository is:

```text
https://github.com/Friday770/Diffusion
```

## Training Checkpoints

All downloaded LoRA weight files are also kept under:

```text
lora_weights/checkpoints/
```

Current checkpoint files:

```text
mine_blast_pile_v2_rank16_768_lr5e5.safetensors
mine_blast_pile_v2_rank16_768_lr5e5-step00000500.safetensors
mine_blast_pile_v2_rank16_768_lr5e5-step00001000.safetensors
mine_blast_pile_v2_rank16_768_lr5e5-step00001500.safetensors
mine_blast_pile_v2_rank16_768_lr5e5-step00002000.safetensors
mine_blast_pile_v2_rank16_768_lr5e5-step00002500.safetensors
```

## Notes

- Weight files are stored with Git LFS.
- The current LoRA was trained as SDXL LoRA, rank 16, resolution 768.
- `lora_weights/mine_blast_pile.safetensors` is the recommended default file for deployment and inference.
