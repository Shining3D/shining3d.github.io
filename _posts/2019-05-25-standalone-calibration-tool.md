---
layout: post
title: Standalone calibration tool
---

In the old version of SDK, there is a standalone calibration executable, which can be used directly by 3rd party developers to calibrate our scanners. In the new version of SDK, the handy tool is missing. Instead, we provide an open-sourced calibration demo to demonstrate how to do the calibration using the ZMQ interfaces of the SDK. 

Soon we realized that many developers still want a ready-to-use calibration tool with well-designed instructions and interactions. Therefore, we've extracted the calibration page from EXScan Pro to a standalone executable, which is called Calibration.exe.

We've submitted the executable to the github repo 2XSDK along with all the dependencies. Please feel free to pull from the latest repo and evaluate the new calibration tool!