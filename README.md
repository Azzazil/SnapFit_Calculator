[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FMechanical-Python%2FSnapFit_Calculator&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Profile+views&edge_flat=false)](https://hits.seeyoufarm.com)

Snap Joint Calculator v2.0
========

Snap Joint Calculator is simple program to calculate parameters and forces of cantilever, annular and torsional snap joint during design of plastic part for assembly.


FAQ
---

### How do I run Snap Joint Calculator?

Linux version:
--------------
Download files and navigate with terminal to:

`cd /home/_user_directory_/Downloads/SnapJointCalculator_v2.0_Linux/SnapJointCalculator` and run command `./SnapFitMainWindow`.

Windows version:
--------------
Download files and run installer, choose destination directory of files and navigate to:

`C:\_destination_directory_\SnapJointCalculator_v2.0_Win\SnapJointCalculator` and run `SnapJointCalculator.exe`.


### How to work with SnapJointCalculator?

After running command `./SnapJointCalculator` or exe file `SnapJointCalculator.exe` you will be brought to option window to choose desired type of joint to calculate forces and undercut.
 
![Snap Joint Calculator Main Window](https://github.com/Mechanical-Python/SnapFit_Calculator/blob/master/Snap_Joint_Calculator_Main_Window.png)

If you choose cantilever joint option and proceed to the next window with `Next` button.

![Cantilever Joint](https://github.com/Mechanical-Python/SnapFit_Calculator/blob/master/Cantilever_Joint.png)

You will be brought to anoter option windows to choose exact shape of cantilever joint.

![Cantilever Joint type A](https://github.com/Mechanical-Python/SnapFit_Calculator/blob/master/Cantilever_Joint_A1.png)

In box `Determine parameters of cantilever hook` it is mandatory to have at least 3 parameters filled. The one that is not filled in his value will be calculated by pressing on button `Calculate`. 

For example if you fill values for `Lenght`,`Strain` and `Undercut` than `Wall thickness` will be calculated. 

Notes: 

By entering values for `Wall thickness`,`Lenght` and `Strain` this values will appear in box `Calculate deflection force`.

By clicking `Back` button double time you will be brought to main option window, by choosing annular joint and press on button `Next` you will calculate parameters and forces of annular joint.

![Annular Joint](https://github.com/Mechanical-Python/SnapFit_Calculator/blob/master/Annular_Joint.png)

By going to main option window and choosing torsional joint you will be able to calculate allowed torsion angle and torque value. 

![Torsional Joint](https://github.com/Mechanical-Python/SnapFit_Calculator/blob/master/Torsional_Joint.png)

Example
-------

![Snap Joint Calculator Example](https://github.com/Mechanical-Python/SnapFit_Calculator/blob/master/Example_Torsional.png)
