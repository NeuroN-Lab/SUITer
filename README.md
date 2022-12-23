# SUITer v1.0


![Github](https://user-images.githubusercontent.com/83271085/208666444-ee273897-7b59-4840-946c-965893d3bf6e.png)



SUITer is a user friendly MATLAB App that allows accurate segmentations of infratentorial structures (cerebellar lobules, cerebellar white matter and brainstem) across different resolutions and MR fields (3T and 7T).

Comprehensive documentation is provided inside [SUITer v1.0 zip files](https://drive.google.com/file/d/19GEJEMoyqOTtReBpA76qo4oTn6WC_jiz/view?usp=share_link)

[The original paper](https://onlinelibrary.wiley.com/doi/10.1111/jon.12672) and the full citation:
El Mendili MM, Petracca M, Podranski K, Fleysher L, Cocozza S, Inglese M. SUITer: An Automated Method for Improving Segmentation of Infratentorial Structures at Ultra-High-Field MRI. J Neuroimaging. 2020 Jan;30(1):28-39. doi: 10.1111/jon.12672. Epub 2019 Nov 5.



## Requirements

**+**	MATLAB R2021b (or newer) 

**+**	SPM12

**+**	CAT12-r1907

**+**	SUIT-3.5

You can install CAT12 and SUIT toolboxes for spm12 manually, or use the built-in installer that is provided within SUITer.
Any requirement of SPM12, CAT12 and SUIT is also naturally required for SUITer.
In some cases SUITer needs MATLAB to be run as Administrator on Windows vista or higher and MacOS 10.15.6 or higher systems. If you get “Permission Denied” errors during execution, then you most likely need to run MATLAB as Administrator, and then you can run SUITer correctly.




## Installation

**Step 1:** Install SUITer App in Matlab

**Step 2:** Select the SPM12 path

**Step 3:** Install CAT12-r1907 and SUIT-3.5

If you need data to test the app with, you can find a small dataset [here](https://figshare.com/articles/media/SUITer_An_Automated_Method_for_Improving_Segmentation_of_Infratentorial_Structures_at_Ultra-High-Field_MRI/21162487)



## Pipeline steps ⇢ Outputs
**Step 1:*** Setup (Files/folder selection and data/folder organization) 

**Step 2:** CAT12 Segmentation  **⇢**  p1.nii, p2.nii, p3.nii

**Step 3:** Infratentorial Isolation

**Step 4:** Dartel Normalization

**Step 5:** Reslicing into SUIT atlas space 

**Step 6ab:** Cerebellar GM, Lobules, Cerebellar WM, Brainstem and Cerebellar Peduncles Segmentations  **⇢**  SUITer_GM.nii, SUITer_WM.nii, SUITer_BS.nii and SUITer_CerebPed.nii

**Step 7ab:** Computing volumes and Creating tabular outputs  **⇢**  Full Stats.csv, SUITer_CAT12_Volumes.csv, SUITer_NumvoxGM.csv, SUITer_NumvoxWM.csv and SUITer_NumvoxBS.csv 

**Step 8:** Clean up



## Uninstallation

You can uninstall SUITerApp from the MATLAB GUI. Find the SUITerApp App in your application list, right click on it and select “Uninstall”.



## Contact information
If you have any issues or questions regarding SUITerApp, please send us an email to suiter.help@gmail.com, we’ll try to help you as best we can.

