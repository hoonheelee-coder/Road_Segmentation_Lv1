

# HELLO
Welcome to KARI ACADEMY, a group of talented students selected from university students in Korea.

# Road_Segmentation_Lv1
This repository is for an exercise code to teach college students to understand the principles of artificial intelligence using satellite imagery.

# TIPs

## How to prevent Google Colab from automatically disconnecting
```
function ClickConnect(){
    console.log("prevent Google Colab from disconnecting at every 1 min."); 
    document.querySelector("#top-toolbar > colab-connect-button").shadowRoot.querySelector("#connect-icon").click();
}
setInterval(ClickConnect, 1000 * 60);
```
## How to remove log messages from Google Colab
```
function CleanCurrentOutput(){
    var btn = document.querySelector(".output-icon.clear_outputs_enabled.output-icon-selected[title$='running now...'] iron-icon[command=clear-focused-or-selected-outputs]");
    if(btn) { console.log("remove log messages from Google Colab at every 10 min."); btn.click(); } 
}
setInterval(CleanCurrentOutput, 1000 * 60 * 10);
```
# Reference
This training material references the [UNet-based road segmentation](https://www.kaggle.com/code/balraj98/unet-resnet50-frontend-road-segmentation-pytorch) public domain and has been modified to correct errors in the code encountered during the learning process and to upload datasets directly to the Goolge Colab.
