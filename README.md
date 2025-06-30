# InpaintingMamba: A State Space Model for Image Inpainting

# 📊 Code

The code will be released after acceptance.

---

# 📊 Experimental Results

This document presents a comparison of our method with other approaches on the CelebA-HQ and Places2 datasets, as well as additional visual results.

---

## 📁 Comparisons to SOTAs

<table>
  <tr>
    <th>Input</th>
    <th>LaMa</th>
    <th>Wavefill</th>
    <th>W-Net</th>
    <th>CMT</th>
    <th>HINT</th>
    <th>Ours</th>
    <th>Ground Truth</th>
  </tr>

[//]: # (1)
  <tr>
    <td><figure><img src="images/comparisons/input_1.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/LaMa_1.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Wavefill_1.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/W-Net_1.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/CMT_1.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/HINT_1.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Ours_1.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/GT_1.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (2)
  <tr>
    <td><figure><img src="images/comparisons/input_2.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/LaMa_2.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Wavefill_2.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/W-Net_2.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/CMT_2.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/HINT_2.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Ours_2.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/GT_2.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (8)
  <tr>
    <td><figure><img src="images/comparisons/input_8.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/LaMa_8.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Wavefill_8.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/W-Net_8.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/CMT_8.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/HINT_8.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Ours_8.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/GT_8.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (9)
  <tr>
    <td><figure><img src="images/comparisons/input_9.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/LaMa_9.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Wavefill_9.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/W-Net_9.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/CMT_9.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/HINT_9.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Ours_9.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/GT_9.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (10)
  <tr>
    <td><figure><img src="images/comparisons/input_10.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/LaMa_10.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Wavefill_10.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/W-Net_10.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/CMT_10.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/HINT_10.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Ours_10.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/GT_10.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (3)
  <tr>
    <td><figure><img src="images/comparisons/input_3.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/LaMa_3.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Wavefill_3.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/W-Net_3.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/CMT_3.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/HINT_3.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Ours_3.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/GT_3.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (4)
  <tr>
    <td><figure><img src="images/comparisons/input_4.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/LaMa_4.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Wavefill_4.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/W-Net_4.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/CMT_4.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/HINT_4.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Ours_4.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/GT_4.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (5)
  <tr>
    <td><figure><img src="images/comparisons/input_5.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/LaMa_5.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Wavefill_5.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/W-Net_5.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/CMT_5.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/HINT_5.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Ours_5.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/GT_5.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (6)
  <tr>
    <td><figure><img src="images/comparisons/input_6.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/LaMa_6.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Wavefill_6.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/W-Net_6.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/CMT_6.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/HINT_6.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Ours_6.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/GT_6.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (7)
  <tr>
    <td><figure><img src="images/comparisons/input_7.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/LaMa_7.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Wavefill_7.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/W-Net_7.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/CMT_7.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/HINT_7.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/Ours_7.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/comparisons/GT_7.png" width="75" height="75" style="object-fit: cover;"/></figure></td>
  </tr>
</table>


## 📁 More Visual Results on Places2 Dataset
<table>
  <tr>
    <th>Input</th>
    <th>Ours</th>
    <th>Ground Truth</th>
    <th>Input</th>
    <th>Ours</th>
    <th>Ground Truth</th>
  </tr>

[//]: # (1)
  <tr>
    <td><figure><img src="images/places2/input_1.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_1.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_1.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/input_2.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_2.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_2.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (2)
  <tr>
    <td><figure><img src="images/places2/input_3.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_3.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_3.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/input_4.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_4.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_4.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (3)
  <tr>
    <td><figure><img src="images/places2/input_5.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_5.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_5.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/input_6.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_6.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_6.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (4)
  <tr>
    <td><figure><img src="images/places2/input_7.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_7.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_7.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/input_8.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_8.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_8.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (5)
  <tr>
    <td><figure><img src="images/places2/input_9.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_9.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_9.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/input_10.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_10.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_10.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (6)
  <tr>
    <td><figure><img src="images/places2/input_11.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_11.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_11.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/input_12.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_12.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_12.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (7)
  <tr>
    <td><figure><img src="images/places2/input_13.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_13.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_13.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/input_14.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_14.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_14.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (8)
  <tr>
    <td><figure><img src="images/places2/input_15.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_15.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_15.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/input_16.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/Ours_16.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/places2/GT_16.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>
</table>

---

## 📁 More Visual Results on CelebA-HQ Dataset
<table>
  <tr>
    <th>Input</th>
    <th>Ours</th>
    <th>Ground Truth</th>
    <th>Input</th>
    <th>Ours</th>
    <th>Ground Truth</th>
  </tr>

[//]: # (1)
  <tr>
    <td><figure><img src="images/celeba/input_1.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_1.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_1.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/input_2.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_2.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_2.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (2)
  <tr>
    <td><figure><img src="images/celeba/input_3.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_3.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_3.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/input_4.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_4.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_4.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (3)
  <tr>
    <td><figure><img src="images/celeba/input_5.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_5.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_5.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/input_6.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_6.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_6.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (4)
  <tr>
    <td><figure><img src="images/celeba/input_7.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_7.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_7.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/input_8.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_8.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_8.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (5)
  <tr>
    <td><figure><img src="images/celeba/input_9.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_9.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_9.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/input_10.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_10.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_10.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (6)
  <tr>
    <td><figure><img src="images/celeba/input_11.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_11.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_11.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/input_12.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_12.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_12.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (7)
  <tr>
    <td><figure><img src="images/celeba/input_13.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_13.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_13.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/input_14.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_14.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_14.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>

[//]: # (8)
  <tr>
    <td><figure><img src="images/celeba/input_15.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_15.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_15.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/input_16.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/Ours_16.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
    <td><figure><img src="images/celeba/GT_16.png" width="100" height="100" style="object-fit: cover;"/></figure></td>
  </tr>
</table>