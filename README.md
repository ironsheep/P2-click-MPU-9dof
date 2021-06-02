# P2-click-MPU-9dof
Parallax Propeller V2 Interface object for MPU 9DOF Click module 

![Project Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE) 

We might use this module in our P2 P2 Cube project to determine cube orientation.

The goals of this project are:


- Establish working commmunication with the MPU 9DOF module
- Configure the module for Cube use
- Calibrate the module to get best results
- Implement logic to convert 3-axis Accel, Gyro and Mag values into Roll, Pitch and Yaw

## Current status

What's completed and what's not:

```
02 Jun 2021 17:35
- Add detection of MPU9150, MPU9250, and MPU9255
- Alter die temp algorithm to be correct by chip model
- Alter mag scaling to be correct by chip model
- Calibration appears to work but still testing
Known Issue
- Get Accel/Gyro conversion from raw still not correct
27 May 2021 14:02
- I/O is working better and sign propagation of reading  has been corrected.
25 May 2021
- I/O working (single bytes/words and Mag access)
- chip configuration seems to be working (May want to be tuned for our use)
```

## Up Next

- Convert floating math for row/pitch/yaw calcs into spin2

---

> If you like my work and/or this has helped you in some way then feel free to help me out for a couple of :coffee:'s or :pizza: slices! 
> 
> [![coffee](https://www.buymeacoffee.com/assets/img/custom_images/black_img.png)](https://www.buymeacoffee.com/ironsheep)

---

## License

Copyright © 2021 Iron Sheep Productions, LLC. All rights reserved.<br />
Licensed under the MIT License. <br>
<br>
Follow these links for more information:

### [Copyright](copyright) | [License](LICENSE)



[maintenance-shield]: https://img.shields.io/badge/maintainer-stephen%40ironsheep%2ebiz-blue.svg?style=for-the-badge

[marketplace-version]: https://vsmarketplacebadge.apphb.com/version-short/ironsheepproductionsllc.spin2.svg

[marketplace-installs]: https://vsmarketplacebadge.apphb.com/installs-short/ironsheepproductionsllc.spin2.svg

[marketplace-rating]: https://vsmarketplacebadge.apphb.com/rating-short/ironsheepproductionsllc.spin2.svg

[license-shield]: https://camo.githubusercontent.com/bc04f96d911ea5f6e3b00e44fc0731ea74c8e1e9/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f69616e74726963682f746578742d646976696465722d726f772e7376673f7374796c653d666f722d7468652d6261646765

