# PolyUSCCv2

## 1. Introduction

PolyUSCCv2 is a screen content (SC) video dataset. The current release contains 28 sequences, including self-captured sequences and selected JCT-VC screen content test sequences [1].

## 2. Sequence Dataset

The current release contains 28 raw YUV video sequences. As indicated by their filenames, all sequences have a resolution of **1920 × 1080**, an **8-bit** depth, **YUV 4:4:4** chroma sampling, and **300 frames** per sequence. The frame rate is either **30 fps** or **60 fps**.

The **20 sequences at 30 fps** are: `Amazon`, `AppleStore`, `Appskip`, `BitstreamAnalyzer`, `ChineseDocumentEditing`, `CircuitLayoutPresentation`, `ClearTypeSpreadsheet`, `cmd3`, `consoledocument`, `consolenew`, `docgooglemap`, `docvideoplanets`, `JDStore`, `MSstore`, `PPTtemplate`, `purecmd`, `SCCCodec`, `scconsolecmdcpu`, `Windowskip2`, and `Youtube`. Each sequence has a duration of 10 seconds.

The **8 sequences at 60 fps** are: `airplanevideocmd`, `consolecmd`, `Folderskip`, `googlemap`, `Paperskip`, `PPTskip`, `Websiteskip`, and `Windowskip`. Each sequence has a duration of 5 seconds.

Filenames follow the pattern `<sequence>_1920x1080_<fps>_8bit_300_444.yuv`. The `AppleStore`, `SCCCodec`, and `Youtube` files use `8bits` instead of `8bit`; both spellings indicate the same 8-bit depth. Sequence names retain the capitalization used in the archive.

## 3. Download

Download **PolyuSCCv2.zip** from [Google Drive](https://drive.google.com/file/d/1wy91Qos-F4e5Ffr_ODWOc89ar78IP76R/view?usp=sharing).

## 4. References

- [1] Screen Content Sequences Provided by JCT-VC. Available: ftp://mpeg.tnt.uni-hannover.de/testsequences/
- [2] “Common test conditions for screen content coding,” JCT-VC, JCTVC-X1015, pp. 1–6, May–June 2016.

## 5. Citation

If you use the **PolyUSCCv2** dataset in your research, please cite **both** the following paper and the JCT-VC sequence source:

### Research Paper

Ziyin Huang, Yui-Lam Chan, Sik-Ho Tsang, Ngai-Wing Kwong, Kin-Man Lam, and Wing-Kuen Ling, “Spatio-temporal feature learning for enhancing video quality based on screen content characteristics,” *Journal of Visual Communication and Image Representation*, vol. 104, Article 104270, 2024. DOI: [10.1016/j.jvcir.2024.104270](https://doi.org/10.1016/j.jvcir.2024.104270).

```bibtex
@article{huang2024spatio,
  author  = {Huang, Ziyin and Chan, Yui-Lam and Tsang, Sik-Ho and Kwong, Ngai-Wing and Lam, Kin-Man and Ling, Wing-Kuen},
  title   = {Spatio-temporal feature learning for enhancing video quality based on screen content characteristics},
  journal = {Journal of Visual Communication and Image Representation},
  volume  = {104},
  pages   = {104270},
  year    = {2024},
  doi     = {10.1016/j.jvcir.2024.104270},
  url     = {https://doi.org/10.1016/j.jvcir.2024.104270}
}
```

### JCT-VC Source Sequences

JCT-VC. *Screen Content Sequences Provided by JCT-VC*. Available: ftp://mpeg.tnt.uni-hannover.de/testsequences/

```bibtex
@misc{jctvc_screen_content_sequences,
  author = {{JCT-VC}},
  title  = {Screen Content Sequences Provided by {JCT-VC}},
  url    = {ftp://mpeg.tnt.uni-hannover.de/testsequences/}
}
```
