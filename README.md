
<h2 align="center">DP-SfM: Dual-Pixel Structure-from-Motion without Scale Ambiguity</h2>

<h4 align="center">
    <a href="https://lilika-makabe.github.io/"><strong>Lilika Makabe</strong></a>
    ·
    <a href="#"><strong>Kohei Ashida</strong></a>
    ·
    <a href="https://sites.google.com/view/hiroaki-santo/"><strong>Hiroaki Santo</strong></a>
    ·
    <a href="http://cvl.ist.osaka-u.ac.jp/user/okura/"><strong>Fumio Okura</strong></a>
    ·
    <a href="http://www-infobiz.ist.osaka-u.ac.jp/en/member/matsushita/"><strong>Yasuyuki Matsushita</strong></a>
</h4>

This is the official repository (pre-release) for our paper: “**DP-SfM: Dual-Pixel Structure-from-Motion without Scale Ambiguity**”

### 🌐 Project Page (TBA) | 📄 Paper (TBA) | 💻 Code & Data (upcoming)


## 🔔 News
- **2026-04-30**: Pre-release repository created. Code and data will be released soon.  


## 📝 Abstract
Multi-view 3D reconstruction (SfM + MVS) suffers from an unknown global scale ambiguity unless a reference object of known size is present. In this work, we show that **dual-pixel (DP) images** can automatically resolve the scale ambiguity **without requiring a reference object or prior calibration**. Specifically, DP defocus blur provides sufficient information to determine the absolute scale when paired with depth maps (up to scale) recovered from multi-view reconstruction. We propose a **simple linear method** to estimate absolute scale and per-view focus distances, followed by an **intensity-based optimization** stage that aligns left/right DP images via re-blurring with blur kernels. Experiments demonstrate the effectiveness of the proposed approach across diverse scenes captured with different cameras and lenses.


## Citation
```
@article{makabe_dpsfm_tpami,
  title   = {DP-SfM: Dual-Pixel Structure-from-Motion without Scale Ambiguity},
  author  = {Makabe, Lilika and Ashida, Kohei and Santo, Hiroaki and Okura, Fumio and Matsushita, Yasuyuki},
  journal = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
  pubstate    = {Accepted for publication (to appear)},
  year    = {TBA}
}
```

