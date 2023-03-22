# Laser On Gimbal
2 axis custom gimbal with laser pointer


# Things to do TODO for this project:
- Arduino stepper motor demo
- arduino BLDC motor demo
- Arduino DC motor demo:
  - keep the motor slowly gyrating CW and CCW then stop and fix in one position. To test if it's suitable for a gimbal.  


# Components:
#### - [DRV8313, 65-V max, 3-A peak 3-phase motor driver](https://www.ti.com/product/DRV8313#:~:text=The%20DRV8313%20provides%20three%20individually,2%2DH%2Dbridge%20configuration.)
  - ![image](https://user-images.githubusercontent.com/42329930/226759702-d4d19a19-e6f5-4592-a5da-2082641f13b1.png)
  
#### Gimbal motor
- A gimbal motor is a 3-phase brushless motor whose stator is wound with many turns, and as such exhibits much larger resistance and inductance compared to the high-current brushless motors used to provide lift to drones, rc planes etc.
- https://tinymovr.readthedocs.io/en/latest/hardware/gimbal.html



# Weblinks, Videos, Tutorials, Etc.
https://www.youtube.com/watch?v=wTYCF0Vpy4M&ab_channel=iforce2d
- Product page (GearBest): http://goo.gl/M6NS8i
- STorM32 gimbal controller wiki: http://goo.gl/HdttwA
- RCGroups thread, STorM32 BGC: 32-bit 3-axis brushless gimbal controller: http://goo.gl/YBvaKs
- Reasons to use 2nd IMU: https://goo.gl/TueBfK
- OlliW's YouTube channel:   / olliw42  
 
# Tinymovr: 
- Driving a Gimbal Motor with Tinymovr: https://www.youtube.com/watch?v=YM__oxuWL3o&ab_channel=Tinymovr
- https://github.com/tinymovr/Tinymovr
- https://tinymovr.readthedocs.io/en/latest/
- Tinymovr for Gimbal motors: https://tinymovr.readthedocs.io/en/latest/hardware/gimbal.html

# Gimbal controllers (verify these links before buying)
- from BaseCam: https://www.basecamelectronics.com/
- from Ardupilot: https://ardupilot.org/copter/docs/common-simplebgc-gimbal.html
- https://shop.iflight-rc.com/basecam-simplebgc-32-bit-extended-encoder-version-gimbal-controller-pro276
- from ArialPixels: https://aerialpixels.com/product-category/gimbals/brushless-gimbal-controllers/
- https://www.youtube.com/watch?v=Bk_Q47tTlBI&ab_channel=OlliW42   <-- 
- 


# Notes:
#### Types of Gimbal controllers:
- brushless direct drive gimbals (Tarot, SimpleBGC, SToRM32)
- simpler servo-driven gimbals



