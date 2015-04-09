# CropImage
类似facebook图片裁剪，裁切区域自定义，图片大小任意，保证图片宽高比，支持缩放、拖动

# Demo
http://sandbox.runjs.cn/show/uqfwtnpj

#使用方法
    var crop = new CropImage({
    realWidth: 500,
    realHeight: 300,
    imageSrc: "https://scontent-sjc.xx.fbcdn.net/hphotos-xpf1/t31.0-8/11082173_1375191982809420_8824827256454539423_o.jpg"
    });
    
    document.appendChild(div, crop.domNode);
    crop.startup();
    
    //{
    //w:
    //h:
    //}
    var currentImageSize = crop.getImageSize();
    
    //{
    //l:
    //t:
    //w:
    //h:
    //}
    var cropSize = crop.getCropSize();
