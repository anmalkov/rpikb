# Speed test: Micro SD vs SSD

timings:

* first apt update rpi3 SD - 38 sec
  85 packages can be updated
  
  second pi - 36 sec
  66 packages
  
* first apt upgrade rpi3 SD - 09:55 sec

  second pi - 09:22 sec
  
  
  SSD
  
* first apt update rpi3 SSD - 9 sec
  96 packages can be updated

* first apt upgrade rpi3 SSD - 13:40 sec


  # final tests
  
  pi1
  on login - 103 updates, 41 security
  SSD update (96 packages) - 41 sec, 7 sec
  SSD upgrade - 14:00

  on login - 78 updates, 17 security
  SD update (78 packages) - 10 sec, 7 sec
  SD upgrade - 09:34
  
   
  
  pi2
  on login - 66 updates, 0 security
  SD update (66 packages) - 10 sec, 7 sec
  SD upgrade - 09:06
  
  on login - 103 updates, 41 security
  SSD update (96 packages) - 10 sec, 7 sec
  SSD upgrade - 13:45
  
  
  pi4
  on login - 83 updates, 21 security
  SD update (83 packages) - 5 sec, 4 sec
  SD upgrade - 05:50
  
  on login - 99 updates, 37 security
  SD update (92 packages) - 5 sec, 4 sec
  SD upgrade - 06:30  
  
  on login - 93 updates, 32 security
  SSD update (86 packages) - 5 sec, 5 sec
  SSD upgrade - 05:43
  
  Raspberry OS
  
  SSD update (19 packages) - 10 sec, 7 sec
  SSD upgrade - 01:40
