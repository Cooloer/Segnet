# Segnet
月球图像分割<br>
<img src="https://img.shields.io/badge/gitHub-%E8%AE%A9%E8%87%AA%E6%88%91%E4%BB%8B%E7%BB%8D%E5%8F%98%E5%BE%97%E6%9B%B4%E5%A5%BD-brightgreen" /><br>
项目背景<br>
吉林卫星拍摄的月球图像，想要获取其图像分割后的图像数据。<br>

本项目主要内容及结果<br>
项目主要使用神经网络实现语义分割，通过已有的原始数据和标签训练。但首先需要对图像进行二值化处理，然后再去训练。最后可以实现针对同时期的不同月球图像分割。<br>

小结<br>
实现过程中遇到不少问题，诸如图像数据类型问题、网络泛化能力不足等。但最终都一一解决，并取得一定成果。<br>

<div align=center>
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td align="center"><img src="img/1.jpg" /> </td>
  </tr>
  <tr>
    <td align="center">Fig.1 左为提供的标签二值化图像，右为网络测试结果图像。</td>
  </tr>
</div>
  <div align=center>
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td align="center"><img src="img/2-8.jpg"  /></td>
  </tr>
  <tr>
    <td align="center">Fig.2 左为提供的标签二值化图像，右为网络测试结果图像。</td>
  </tr>
</div>
