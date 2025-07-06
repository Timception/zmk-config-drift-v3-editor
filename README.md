## Drift Keyboard V3 by Timception  

- This is the wireless [ZMK](https://zmk.dev/) version of the [Original Drift Keyboard](https://github.com/Timception/Drift)  

  - [Default Keymap](#default-keymap) to see where all your keys are, or go straight to the:  
  
    - [Keymap Editor by Nick Coutsos](https://nickcoutsos.github.io/keymap-editor/)  

- The PCB is not open source, but you could [contact me](https://www.instagram.com/majin.keyboards) if you would like a pair
  <br/>  


## Quickstart Guide   
  - [1.	How to change your keys](/docs/change-keys/) - Detailed guide on how to change your keys  

  - [2.	How to install batteries](/docs/batteries/) - Battery installation and alternate options  

  - [3.	Connecting through Bluetooth](/docs/bluetooth/) - Bluetooth connections and troubleshooting  

  - [4.	Charging](/docs/charging/) - How to charge the keyboard and use with USB-C  

  - [5.	Switching to low profile](/docs/low-profile/) - Removal of some parts to use low profile switches  

  - [6.	3D Printables](https://github.com/Timception/3d-printables) - This will take you to the 3D printable part repository  
<br/><br/>  


# Default Keymap

  - This keyboard is powered by [ZMK](https://zmk.dev/), an open‑source firmware. ZMK lets you place several “layers” of key functions on the same physical keys. When you press a designated layer key—much like holding "Fn" on a laptop—the keyboard shifts to a different layer, giving you extra controls (for example, volume, brightness, or any custom shortcuts) without adding more keys.  

  - Split keyboards come with their own set of terms, and one important one to know is the “thumb cluster.” This refers to the group of keys at the bottom in the form of an arc where a traditional keyboard would have the spacebar.  
    
  - Unlike standard keyboards, split keyboards make better use of this space by letting you place and customize useful keys there. This reduces the need to reach for commonly used keys.  

  - For example, on this keyboard, I’ve placed Shift on the left-most thumb cluster key and Backspace on the right-most. The spacebar is in the center of each thumb cluster—so whether you hit the spacebar with your left or right thumb, it’s easy to reach.  

  - You can [change the keys on your keymap](/docs/change-keys/) if you prefer different placing of any key.  


> [!Note]  
> The "&trans" keys seen on the thumb clusters on layers 1 and above act as transparent keys, copying the key set on the layer beneath it.  
> If you are confused about what some of these keys represent, you may find [more information here](https://zmk.dev/docs/keymaps/list-of-keycodes)  
> Information on layers can also [be found here](https://zmk.dev/docs/keymaps/behaviors/layers)  


## Base/Default Layer (layer 0)  
- This is the default layer or layer 0 on this keyboard and the keys are as follows:  
  
  <img src="images/0_default_layer.png"><br/><br/>  


## Lower Layer (layer 1)  
- This is the lower layer or layer 1. This is where the F-Keys and Arrow-Keys are:  
  
  <img src="images/1_lower_layer_n.png">  
  The "&mo 1" key is held to access this layer as seen in the bottom right of this image.  <br/><br/>  


## Raise Layer (layer 2)  
- This is the lower layer or layer 2. This is where the Bluetooth Functions and Mouse Keys are:  
  
  <img src="images/2_raise_layer_n.png">  
  The "&mo 2" key is held to access this layer as seen in the bottom right of this image.  <br/><br/>  


## Adjust Layer (layer 3)  
- This is the adjust layer or layer 3. This is pretty much a clone of Layer 2 as my usage doesn't go beyond 3 layers:  
  
  <img src="images/3_adjust_layer_n.png">  
   Both "&mo 1" and "&mo 2" keys are held to work together to activate the conditional layer function, taking us to layer 3.  <br/><br/>  


This version of the Drift Keyboard supports:  

 - 5-Pin MX switches (3-Pin switches will also work)  
 - Kailh Choc V1 switches  
 - Kailh Choc V2 switches  
<br/>  

How to [change your build](/docs/low-profile/) to use choc switches.  
<br/>  

<img src="images/switch-support.png" width="500">  
<br/>  

>[!Warning]
>Important Note on LiPo Batteries  
>  
>LiPo (Lithium Polymer) batteries are considered a fire hazard due to their sensitivity
>to overcharging, punctures, or improper handling, which can lead to overheating or combustion.
>Because of strict shipping regulations, LiPo batteries cannot be included with this keyboard
>and must be purchased separately by the builder.  
>  
>Disclaimer: I am not responsible for any damage, injury, or loss resulting from the use,
>charging, or installation of LiPo batteries. Use at your own risk and follow all safety guidelines
>provided by the battery manufacturer.  
>  
>More on how to install batteries [here](/docs/batteries/)  
<br/><br/>  

You can see more actual builds [HERE](https://www.instagram.com/majin.keyboards)  

This project was made possible thanks to the incredible support of [Friction](https://github.com/friction07)  
Your generosity truly made all the difference—thank you!  
