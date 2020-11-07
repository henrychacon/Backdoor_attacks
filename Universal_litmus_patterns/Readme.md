# Universal Litmus Patterns, Jupyter Notebook adaptation

In the Notebook file, we reviewed the ULP method to detect backdoor attacks in CNN models proposed by Kolouri et al. [paper link](https://openaccess.thecvf.com/content_CVPR_2020/html/Kolouri_Universal_Litmus_Patterns_Revealing_Backdoor_Attacks_in_CNNs_CVPR_2020_paper.html).

The original code shared by the authors is based on individual `.py` files. Therefore, in the file shared here, the most relevant ones to construct the classifier are adapted to be run in one file.






++ Number of universal patterns (z) = 1. Pattern images:
![Image1](ulp_patterns_N1.png)

   Model: Clean, ULP detection: Clean 0.241, Backdoor 0.759
   Model: Clean, ULP detection: Clean 0.010, Backdoor 0.990
   Model: Clean, ULP detection: Clean 0.997, Backdoor 0.003
   Model: Backdoor, ULP detection: Clean 0.586, Backdoor 0.414
   Model: Backdoor, ULP detection: Clean 0.116, Backdoor 0.884
   Model: Backdoor, ULP detection: Clean 0.999, Backdoor 0.001

++ Number of universal patterns (z) = 5. Pattern images:
![Image2](ulp_patterns_N5.png)

   Model: Clean, ULP detection: Clean 1.000, Backdoor 0.000
   Model: Clean, ULP detection: Clean 1.000, Backdoor 0.000
   Model: Clean, ULP detection: Clean 1.000, Backdoor 0.000
   Model: Backdoor, ULP detection: Clean 0.000, Backdoor 1.000
   Model: Backdoor, ULP detection: Clean 0.000, Backdoor 1.000
   Model: Backdoor, ULP detection: Clean 0.040, Backdoor 0.960

++ Number of universal patterns (z) = 10. Pattern images:
![Image3](ulp_patterns_N10.png)

   Model: Clean, ULP detection: Clean 1.000, Backdoor 0.000
   Model: Clean, ULP detection: Clean 1.000, Backdoor 0.000
   Model: Clean, ULP detection: Clean 1.000, Backdoor 0.000
   Model: Backdoor, ULP detection: Clean 0.000, Backdoor 1.000
   Model: Backdoor, ULP detection: Clean 0.000, Backdoor 1.000
   Model: Backdoor, ULP detection: Clean 0.000, Backdoor 1.000

