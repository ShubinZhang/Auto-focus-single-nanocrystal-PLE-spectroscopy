# **Auto-focus-single-nanocrystal-PLE-spectroscopy-measurement**

## **About the project**

Photoluminescence excitation (PLE) spectroscopy  is an powerful tool to study band Python scripts for controling multiple instruments to automatically measure the PLE of sinlge nanocrystal. 

### 1. Pump-probe luminescence thermometry ("PPLT.py"):

This appraoch is based on temperature dependent bandedge emission. It is relative simple and widely used for measuring temperature changes within cooling material during solid phase optical refrigeration. More theory and technical details can be found in https://aip.scitation.org/doi/abs/10.1063/1.4811759. 

#### Instrument list and corresponding libaray:

* Acton sp-2300i spectrometer: "acton.py"
* NKT Supercontinuum SuperK Extreme: "fianium.py"
* Andor Ixon CCD camera: "andor_camera.py"

### 2. Up-conversion thermometry ("Up-conversion thermometry.py"):

This apporach is based on temperature dependent up-conversion efficiency. It's designed for semiconductors with alomst temperature independent bandedge (e.g. CsPbBr3 Nanocrystal). It's a complementary appraoch for PPLT. More theory and technical details can be found in https://www.sciencedirect.com/science/article/abs/pii/S0022231319322847?via%3Dihub

#### Instrument list and corresponding libaray:

* Acton sp-2300i spectrometer: "acton.py"
* NKT Supercontinuum SuperK Extreme: "fianium.py"
* Andor Ixon CCD camera: "andor_camera.py"
* Thorlab Motorized Fast-Change Filter Wheel: "fw102c.py"
* National Instrument multifunction I/O device (4462) with home built photo reciever: "transrefl_lib.py"
* National Instrument multifunction I/O device (6229) with Newport electronic fast shutter: "digitalio.py"

## **Prerequisites**

* Instruments are properly connected physically.
* Connection ports in "config.py" are setted correctly.
* Python 2.x. Extra python packages required can be found in requiremnts.txt     

## **Liscence**

Distributed under the MIT License. See `LICENSE` for more information.

## **Contact**

Shubin Zhang - szhang14@nd.edu


