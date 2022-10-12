# D-EDN-GTM: Distilled Encoder-decoder Network with Guided Transmission Map for Real-time Driving Dehazing

Authors: Le-Anh Tran, Dong-Chul Park

## I. Introduction

<p align="center">
<img src="docs/d-edn-gtm0.png" width="1000">
</p>

## II. Results

2.1 Chart
<p align="center">
<img src="docs/ssim_densehaze.png" width="1000">
</p>

2.2 Quantitative Results
<table>
  <tr>
    <th rowspan="2">Method</th>
    <th colspan="2">Dense-HAZE</th>
    <th colspan="2">NH-HAZE</th>
    <th rowspan="2">#Parameters</th>
  </tr>
  <tr>
    <th>PSNR</th>
    <th>SSIM</th>
    <th>PSNR</th>
    <th>SSIM</th>
  </tr>
  <tr>
    <td>DCP (TPAMI’10)</td>
    <td>10.06</td>
    <td>0.3856</td>
    <td>10.57</td>
    <td>0.5196</td>
    <td>-</td>
  </tr>
  <tr>
    <td>DehazeNet (TIP’16)</td>
    <td>13.84</td>
    <td>0.4252</td>
    <td>16.62</td>
    <td>0.5238</td>
    <td>0.01M</td>
  </tr>
  <tr>
    <td>AOD-Net (ICCV’17)</td>
    <td>13.14</td>
    <td>0.4144</td>
    <td>15.40</td>
    <td>0.5693</td>
    <td>0.002M</td>
  </tr>
  <tr>
    <td>GridDehazeNet (ICCV’19)</td>
    <td>13.31</td>
    <td>0.3681</td>
    <td>13.80</td>
    <td>0.5370</td>
    <td>0.96M</td>
  </tr>
  <tr>
    <td>FFA-Net (AAAI’20)</td>
    <td>14.39</td>
    <td>0.4524</td>
    <td>19.87</td>
    <td>0.6915</td>
    <td>4.68M</td>
  </tr>
  <tr>
    <td>MSBDN (CVPR’20)</td>
    <td>15.37</td>
    <td>0.4858</td>
    <td>19.23</td>
    <td>0.7056</td>
    <td>31.35M</td>
  </tr>
  <tr>
    <td>KDDN (CVPR’20)</td>
    <td>14.28</td>
    <td>0.4074</td>
    <td>17.39</td>
    <td>0.5897</td>
    <td>5.99M</td>
  </tr>
  <tr>
    <td>AECR-Net (CVPR’21)</td>
    <td>15.80</td>
    <td>0.4660</td>
    <td>19.88</td>
    <td>0.7173</td>
    <td>2.61M</td>
  </tr>
  <tr>
    <td>EDN-GTM (PCS’22)</td>
    <td>15.43</td>
    <td>0.5200</td>
    <td>20.24</td>
    <td>0.7178</td>
    <td>49.36M</td>
  </tr>
  <tr>
    <td>Distilled EDN-GTM (ours)</td>
    <td>15.30</td>
    <td>0.5490</td>
    <td>19.64</td>
    <td>0.7206</td>
    <td>2.10M (&#8595;96%)</td>
  </tr>
</table>


## References
- https://github.com/tranleanh/edn-gtm

Created on 29 Sept., 2022.

Have fun!

LA Tran
