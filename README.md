# Image & Video Processing

![OpenCV/Python](https://user-images.githubusercontent.com/78969613/121968925-d821a380-cd90-11eb-94a1-b738162b5a66.png)

This project experiment contains basic image and video processing techniques based on including Fourier Transform, Wavelet Transform, etc. The project is carried out on Google Colaboratory. It will help newbies stepping into the world of Image Processing/Computer Vision. The content table is subject to expansion in the future with more tutorials.

### [Project Link](https://colab.research.google.com/drive/1UNVsdbJq0zYgCxCEsgQLK0R-M1RLUJos?usp=sharing)

**NOTE**: 
- Google Colab supports cv2_imshow instead of cv2.imshow.
- cv2.CAP_PROP_POS_FRAMES hammers the CPU as video compressors exploit time redundancy. To reduce memory space and optimize performance, we make use of cv2.CAP_PROP_POS_MSEC by tweaking the frame rate.
- Hence the video processing cells are not run in the attached Jupyter Notebook file as its output contains a large number of frames that consume a lot of memory. However, for visualization purposes, they are added to the Colab project found in the above link provided.

## Content

<table>
 <tr>
    <td><b>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Image Processing</b></td>
    <td><b>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Video Processing</b></td>
 </tr>
 <tr>
    <td>1. Basic 2-D Signal Handling</td>
    <td>1. Frame Extraction</td>
 </tr>
  <tr>
    <td>2. Arithmetic Operations</td>
    <td>2. Reverse Playback</td>
 </tr>
 <tr>
    <td>3. Specific Intensity Search</td>
    <td>3. Background Subtraction</td>
 </tr>
 <tr>
    <td>4. Edge/Point/Line Detection</td>
 </tr>
 <tr>
    <td>5. Image Fusion</td>
 </tr>
 <tr>
    <td>6. Image Thresholding</td>
 </tr>
 <tr>
    <td>7. Image Segmentation</td>
 </tr>
 <tr>
    <td>8. Discrete Cosine Transform (DCT)</td>
 </tr>
 <tr>
    <td>9. Image Compression</td>
 </tr>
 <tr>
    <td>10. Discrete Wavelet Transform (DWT)</td>
 </tr>
 <tr>
    <td>11. Color Replacement</td>
 </tr>
 <tr>
    <td>12. Color Detection</td>
 </tr>
 <tr>
    <td>13. Change of Planes</td>
 </tr>
 <tr>
    <td>14. Color Space Transformations</td>
 </tr>
</table>
