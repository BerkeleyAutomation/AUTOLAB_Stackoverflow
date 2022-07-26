# AUTOLAB_Stackoverflow
This is a meta doc for recording the useful doc links and the debugging process that's can be useful for others.

## Useful links for Robot:
YuMi, Phoxi and Webcam: https://docs.google.com/document/d/1wcb_WaNOi0-3-BGLk5qZy-KSK7pbfM2BJA0eJescOVg/edit

Fetch Guide: https://docs.google.com/document/d/1z7l20Krf1NrwVbhekSg6_X8yal9MAlSLyJk3lToodP0/edit#heading=h.vux48k5rcn34

## Debug Info: Please add the error msg and the debug process here.

### Problem Description: Pyembree error.
Debugging process: 
Install pyembree from https://github.com/embree/embree/releases/tag/v2.17.7
```shell
tar xzf embree-2.17.7.x86_64.linux.tar.gz
source embree-2.17.7.x86_64.linux/embree-vars.sh
git clone https://github.com/scopatz/pyembree
pip install -e .
source embree-2.17.7.x86_64.linux/embree-vars.sh
```
