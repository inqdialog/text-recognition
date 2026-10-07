# text-recognition
Tools for optical-character and handwritten-text recognition of Middle High German

All files are compatible with [eScriptorium](https://escriptorium.eu/).

mhgerman_print.mlmodel is based on [german_print.mlmodel](https://zenodo.org/records/10519596), with extensive adaptation to accommodate modern critical editions of Middle High German texts.

mhd_seg_prose.mlmodel is a customization of eScriptorium's default blla - general segmentation model intended for critical editions of prose works. It is trained to omit running headers and critical apparatus.

mhd_seg_verse.mlmodel is a segmentation model trained from scratch. It is intended for critical editions of verse works. It is trained to omit running headers, critical apparatus, and marginal folio numbering. As with other segmentation models, indentations can perturb the proper ordering of lines.
