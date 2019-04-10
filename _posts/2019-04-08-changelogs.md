---
layout: post
title: ChangeLogs
---

- News:  
  - Add simplify set interface.
  - Add acquiring the point cloud interface and fix the problem that cannot save point cloud data by 3mf.
  - Add scan operation interface.
  - Add Q&A doc.
  - Add enter & exit calibration.
  - Add enter cali & exit cali.
  - Add tested interface doc.
  - Add mesh, export data and manual align.
  - Add start/end/cancle scanning.
  - Add save interface.

- Improved:  
  - Improve sdk platform stability.

- Bugfixed:  
  - Modify point cloud parse offset calculation interface.
  - Modify the array index out of bounds problem.
  - Modify json parse problems.
  - Modify the unconsistent field problem.
  - Repair the sdk platform crash problem which is caused by reference local variable.
  - Modify the problem that cali-type acquire error.
  - Repair the asyn message not emitted by sdk service if client press the enter scan button.
  - Repair sdk platform crash if the request payload is empty.
  - Modify onDataReady sdk interface.
  - Change the startScan interface to unified control interface.
  - Modify the big data workflow image.