# SUITer v1.0


![Github2](https://user-images.githubusercontent.com/83271085/208655707-6880c81e-efdf-454e-b4d4-b34f1f25108a.png)



SUITer is a user friendly MATLAB App that allows accurate segmentations of infratentorial structures (cerebellar lobules, cerebellar white matter and brainstem) across different resolutions and MR fields.


[The original paper](https://onlinelibrary.wiley.com/doi/10.1111/jon.12672) and the full citation is the following:
El Mendili MM, Petracca M, Podranski K, Fleysher L, Cocozza S, Inglese M. SUITer: An Automated Method for Improving Segmentation of Infratentorial Structures at Ultra-High-Field MRI. J Neuroimaging. 2020 Jan;30(1):28-39. doi: 10.1111/jon.12672. Epub 2019 Nov 5.


## SUITer requirements

**(1)**	MATLAB version R2021b (or newer) 

**(2)**	SPM12 to be installed on your computer

**(3)**	CAT12-r1907

**(4)**	SUIT-3.5

You can install CAT12 and SUIT toolboxes for spm12 manually, or use the built-in installer that is provided within SUITer.
Any requirement of SPM12, CAT12 and SUIT is also naturally required for SUITer.
In some cases SUITer needs MATLAB to be run as Administrator on Windows vista or higher and MacOS 10.15.6 or higher systems. If you get “Permission Denied” errors during execution, then you most likely need to run MATLAB as Administrator, and then you can run SUITer correctly.


## The SUITer Pipeline
**Step 1:** Setup (Files folder selection and data and folder organization) 

**Step 2:** CAT12 Segmentation

**Step 3:** Infratentorial Isolation

**Step 4:** Dartel Normalization

**Step 5:** Reslicing into SUIT atlas space 

**Step 6an:** Cerebellar GM, Lobules, Brainstem, Cerebellar WM and Cerebellar Peduncles Segmentations

**Step 7a:** Computing volumes and Creating tabular outputs

**Step 8:** Clean up
