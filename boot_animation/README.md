# Boot animation Imx8mq
# Case 1:
-   Prepare the boot animation file : example: my_file_boot.zip
-   copy the boot animation image in :  packages/services/Car/car_product/bootanimations/
-   add the file name_devices.mk 
# Boot animation
PRODUCT_COPY_FILES += \
    packages/services/Car/car_product/bootanimations/my_file_boot.zip:system/media/bootanimation.zip
# Case 2: 
- create the myfile.mk
![alt text](/image/boot aimation.PNG)
- include the myfile.mk in imx8mq.evk
![alt text](/image/add.PNG)
