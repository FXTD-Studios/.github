<div align="center">

<img src="https://avatars.githubusercontent.com/u/333458250?s=280&v=4" alt="FXTD Studios" width="140" />

# FXTD Studios

**Colour science, HDR and VFX tools for generative and real-world imagery.**

[Website](https://fxtdstudios.com) · [LinkedIn](https://linkedin.com/company/fxtdstudios) · [Hugging Face](https://huggingface.co/fxtdstudios) · [contact@fxtdstudios.com](mailto:contact@fxtdstudios.com)

</div>

---

## About

FXTD Studios is a research and development studio based in Cairo, Egypt. We build tools that bring film-grade image handling to AI pipelines: scene-linear HDR, ACES and OpenColorIO colour management, EXR delivery, and review tools that show honestly what your pixels are doing.

Most generative and consumer imagery arrives as 8-bit SDR, while professional pipelines expect 32-bit float, scene-linear, colour-managed frames. Our work closes that gap.

FXTD Studios is a member of **NVIDIA Inception**, NVIDIA's program for startups building with AI.

---

## Open Source Projects

<table>
<tr>
<td width="140" align="center" valign="top">
<img src="https://raw.githubusercontent.com/FXTD-Studios/radiance/main/r_icon.png" alt="Radiance" width="96" />
</td>
<td valign="top">

### [Radiance](https://github.com/FXTD-Studios/radiance)

HDR, colour management, VFX tools and image review inside ComfyUI.

A suite of 140+ ComfyUI custom nodes for 32-bit generation with real colour science, GPU accelerated. It covers HDR VAE encode and decode, SDR to HDR conversion, ACES and OpenColorIO, LUTs and CDL, a Viewer with scopes and playback, VFX passes and relighting, and EXR delivery for Nuke and DaVinci Resolve.

Install from ComfyUI Manager by searching for **Radiance**.
License: GPL-3.0

</td>
</tr>
<tr>
<td width="140" align="center" valign="top">
<img src="https://raw.githubusercontent.com/FXTD-Studios/RUDRA/main/ui/assets/rudra-mark.png" alt="RUDRA" width="96" />
</td>
<td valign="top">

### [RUDRA](https://github.com/FXTD-Studios/RUDRA)

Radiance Universal Dynamic Range Adapter.

Turns 8-bit SDR images and video into scene-linear HDR, and shows exactly where it changed the picture. It ships as a browser-based Studio, a delivery CLI for HDR10, HLG and ProRes masters, and a native desktop app now in beta. RUDRA also powers the SDR to HDR nodes in Radiance.

Models are available on [Hugging Face](https://huggingface.co/fxtdstudios/RUDRA).
License: Apache-2.0

</td>
</tr>
</table>

---

## Private Work

Alongside our public repositories, we develop private projects and internal tools that are not published here. Two of them define where the studio is heading:

**Radiance Studio** is an AI-native VFX software, built from the ground up for artists who combine generative models with professional compositing and colour pipelines.

**RADIX** is our efficient intelligence (EAI) technology, designed to deliver capable AI models that run fast and lean on everyday hardware.

For collaboration or early access enquiries, contact us at [contact@fxtdstudios.com](mailto:contact@fxtdstudios.com).

---

## Our Principles

**Correct colour, end to end.** Every tool knows the space it reads, works in and writes, and says so.

**Honest measurement.** We publish results as they are, with the limitations beside them.

**Built for artists.** Tools for colourists, compositors and VFX artists that fit into Nuke, DaVinci Resolve and ComfyUI.

---

## Technology

Python · PyTorch · C++20 · Qt 6 · CUDA · ONNX Runtime · OpenColorIO · ACES · OpenEXR · FFmpeg · ComfyUI

---

## Get Involved

Report bugs and request features through each repository's issue tracker. Before opening a pull request, please read the [contributing guide](https://github.com/FXTD-Studios/radiance/blob/main/CONTRIBUTING.md). For commercial licensing, partnerships or studio work, write to [contact@fxtdstudios.com](mailto:contact@fxtdstudios.com).

---

<div align="center">

[fxtdstudios.com](https://fxtdstudios.com) · Cairo, Egypt

</div>
