<div align="center">

<h1>Robust Descriptor Algorithm Considering the Changing Gray Value Trends Inside Ground Objects for Heterogeneous Optical Image Matching</h1>

<p>
  <b>Li Xue, Yehua Sheng, and Ka Zhang</b>
</p>

</div>

---

## 📖 Overview

This repository provides the implementation of the **SDCT** algorithm, as described in the paper:

> *Robust Descriptor Algorithm Considering the Changing Gray Value Trends Inside Ground Objects for Heterogeneous Optical Image Matching*

The main feature of this algorithm is its **superior stability and capability** over commonly used algorithms, including:

- Radiation-Invariant Feature Transform (**RIFT**)
- Adaptive Binning SIFT
- Gradient Orientation Modification SIFT
- **LSS**

---

## ✨ Contributions

The main contributions of this study include the following:

1. **Gray Value Change as a Stability Basis.** Based on the stability of the internal gray value changes of ground objects, we suggest that the **change orientation** and **pixel gray values** can be used to express the stability of the same area of heterogeneous images, providing the basis for image matching.

2. **Change Orientation & Degree for Descriptors.** Unlike many existing methods that use gradient information to calculate feature orientation and descriptors, the proposed algorithm uses **change orientation** and **degree** to calculate the feature orientation and descriptor, enabling it to obtain stable descriptors in image matching with **large illumination changes**.

3. **Experimental Validation.** Experiments using **homologous and heterogeneous images** demonstrate that the robustness of this algorithm is higher than comparative algorithms.

---

## 🚀 Run

This code is written in **C#**.

### Option 1: Just run it (image matching only)

If you only use this code for image matching, simply run:SDCT_CSDN发布\SDCT_CSDN发布\bin\x64\Debug\SDCT_CSDN发布.exe



### Option 2: Modify the code

If you need to change the code, please use the **Visual Studio** platform.

> Developed with **Visual Studio 2017**.

The code implements the **SDCT** algorithm (paper: *Robust Descriptor Algorithm Considering the Changing Gray Value Trends Inside Ground Objects for Heterogeneous Optical Image Matching*).

---

## 📊 Result

<img width="1400" height="515" alt="result" src="https://github.com/user-attachments/assets/3bc4ef62-59ff-4311-bbe2-e3f8ba05bb7f" />

---

## 📌 Notes

- I wish you all a happy life and successful scientific research! 🎉

---

## 📝 Cite

If you find this repository useful in your research, please consider giving a star ⭐ and a citation.

**BibTeX:**

```bibtex
@article{xue2023robust,
  title={Robust descriptor algorithm considering the changing gray value trends inside ground objects for heterogeneous optical image matching},
  author={Xue, Li and Sheng, Yehua and Zhang, Ka},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing},
  volume={16},
  pages={9515--9528},
  year={2023},
  publisher={IEEE}
}
```

Email: 1151617653@qq.com

<div align="center">
<b>⭐ If this project helps you, please give it a star! ⭐</b>

</div> 
