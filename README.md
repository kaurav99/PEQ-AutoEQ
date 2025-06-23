# PEQ from AutoEQ compatible with HiByMusic Player 

This repository contains a collection of parametric EQ (PEQ) files converted from the AutoEQ GitHub repository by Jaakko Pasanen. All the PEQ files here can be readily imported into the HiByMusic Player app for an enhanced music listening experience.

AutoEQ is a project for equalizing headphone frequency responses automatically and it achieves this by parsing frequency response measurements and producing equalization settings which correct the headphone to a neutral sound.
<p float="left">
<img src="https://github.com/o2rhkzqx/PEQ/assets/104969742/d3fe0acb-e10c-406a-8b40-aa42f0d2d4b9" alt="drawing" width="300" height="700"/>          
<img src="https://github.com/o2rhkzqx/PEQ/assets/104969742/ba699953-1386-489e-8d48-99440e2e2efd" alt="drawing" width="300" height="700"/>                
<img src="https://github.com/o2rhkzqx/PEQ/assets/104969742/cdd35e29-3974-41e8-b72f-fbcded12caf5" alt="drawing" width="300" height="700"/>
</p>






## Visual Sound Profiles

Here are a few examples of sound profiles you might come across in the PEQ files:

![Flat Profile](https://www.soundguys.com/wp-content/uploads/2018/03/Frequency-Response-Good-vs-Bad.png.webp)

*Flat EQ profile, which aims to produce a balanced sound across all frequencies.*

*Bass Boost profile, for those who prefer a more bass-heavy sound.*

*Vocal Boost profile, emphasizing the frequencies commonly associated with vocals.*

## Usage

1. Clone this repository or download the desired PEQ files.
2. Import the PEQ file(s) into your HiByMusic Player app.
3. Apply the imported PEQ preset to your headphones in the app settings.

Note: Each PEQ file is named according to the headphone model it corresponds to.

**🎯 Important: Due to recent changes, HiByMusic now only recognizes PEQ files located in:**

*Internal Storage/ANDROID/DATA/com.hiby.music/files/peqfile*

This folder isn't accessible from regular file managers because of Android's security changes.

**📂 If Your Device Is Rooted**

You can easily copy your PEQ files to the correct directory:

cp /path/to/your/*.peq /sdcard/Android/data/com.hiby.music/files/peqfile/

Alternatively, use a root-enabled file manager to move the files. Once done, open HiByMusic and import them normally.

**🔧 If Your Device Is NOT Rooted, Use Shizuku + Wireless Debugging**

Shizuku allows apps to access the restricted directory with system-level privileges — without rooting — by pairing via ADB over Wi‑Fi.

👉 Follow the official Shizuku setup guide here: https://shizuku.rikka.app/guide/setup/

Quick Steps:

Install Shizuku (from F‑Droid or Play Store) and a compatible file manager.

Supported file managers:

AirData UAV

Amarok-Hider

FV File Manager

MiXplorer

MiXplorer Silver

MT Manager

NMM File Manager / Text Edit

SDMaid-SE

Solid Explorer

SwiftBackup

Total Commander (version 3.60 beta or later)

X-Plore

ZArchiver

Follow the step-by-step instructions on the official Shizuku website to enable Wireless Debugging and start the Shizuku service.

In your file manager, enable Shizuku access to Android/data.

Use your file manager to navigate to:

Internal Storage/ANDROID/DATA/com.hiby.music/files/peqfile

Copy or move your .peq files into this folder.

Launch HiByMusic and import the presets as usual.

*🔄 Note: Shizuku must be reactivated after every device reboot to maintain access to Android/data.*


## Acknowledgement

This work would not have been possible without the extensive research and groundwork laid by Jaakko Pasanen in his [AutoEQ](https://github.com/jaakkopasanen/AutoEq/tree/master) project. Please consider supporting his work if you find this repository helpful.

The PEQ files in this repository are direct conversions from the parametric EQ files found in the AutoEQ repository, with no additional modifications. Credit for the original parametric EQ settings goes to Jaakko Pasanen.

## License

This project is licensed under the MIT License. The original AutoEQ project by Jaakko Pasanen is also licensed under the MIT License.

## Contact

If you have any questions, comments, or would like to contribute to the project, please feel free to contact me at:
- Email: [ralkau@proton.me](mailto:ralkau@proton.me)
- GitHub: [@kaurav99](https://github.com/kaurav99)

Happy Listening! 🎵
