# 🎧 Hearing Heart Sounds with a Camera From Defocused Speckle Video to Heart Sound Audio

We compared the audio reconstruction results of different methods. 

The reconstructed audio was visualized by generating videos that combine the corresponding Mel spectrograms with the audio for intuitive comparison.

## 🔊 Results Visualization

Each comparison video includes:

- **Mel spectrogram** (visual representation of reconstructed audio)
- **Synchronized audio playback**

<table style="width:100%; border-collapse:collapse;">
<tbody>
<tr>
<td width="33%"><strong>GT</strong><br/><video src="./videos/1/GT.mp4" controls style="width:100%"></video></td>
<td width="33%"><strong>Linear</strong><br/><video src="./videos/1/Linear.mp4" controls style="width:100%"></video></td>
<td width="33%"><strong>TFNet</strong><br/><video src="./videos/1/TFNet.mp4" controls style="width:100%"></video></td>
</tr><tr>
<td><strong>CleanUNet</strong><br/><video src="./videos/1/CleanUNet.mp4" controls style="width:100%"></video></td>
<td><strong>WSRGlow</strong><br/><video src="./videos/1/WSRGlow.mp4" controls style="width:100%"></video></td>
<td><strong>EDSR - 1D</strong><br/><video src="./videos/1/EDSR.mp4" controls style="width:100%"></video></td>
</tr><tr>
<td><strong>DBPN - 1D</strong><br/><video src="./videos/1/DBPN.mp4" controls style="width:100%"></video></td>
<td><strong>RCAN - 1D</strong><br/><video src="./videos/1/RCAN.mp4" controls style="width:100%"></video></td>
<td><strong>SwinIR - 1D</strong><br/><video src="./videos/1/SwinIR.mp4" controls style="width:100%"></video></td>
</tr><tr>
<td colspan="3" style="text-align:left;">
<strong>HHC</strong><br/><video src="./videos/1/HHC.mp4" controls style="width:33%"></video></td>
</tr></tbody>
</table>


