# ZQRCode
###二维码扫描
- 利用AVFoundation 实现二维码扫描
- 利用CIDetector进行图片二维码解析 (iOS8 以上)
- 利用CIFilter 或者 libqrencode 两种方式 生成二维码 可自行选择
- 可生成带logo图片的二维码(原理其实就是二维码中间放一张图片,因为二维码有容错率所以不会有影响)

###问题
- 利用CIDetector进行图片二维码解析过程中对照相机照出来的图片解析能力不高, 不知道是否为个别机型的问题
