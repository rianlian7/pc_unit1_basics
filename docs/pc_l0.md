# Lesson 0: Setting up hardware and software

Setting up hardware and software

## Task 1 - Connect the microcontroller to the computer

![Image of connecting microcontroller to the computer](images/l0_connect_makeruno.jpg)

## Task 2 - Download and install the coding environment

If you already have mBlock 5 installed, you can skip Task 2 and go to Task 3.

1. Go to [mBlock Website](https://www.mblock.cc/en/download/ "mBlock Download" target="_blank")

2. Choose the suitable version for your operating system.

    ![](images/l0_2_mBlockVersion.jpg)

3. Download and install mBlock 5 into your computer.

4. Once you installed, launch mBlock 5 from the Start Menu ![](images/startMenu.png) or from your Desktop.

    ![](images/l0_3_icon.jpg)

5. The user interface will look something like this
    ![](images/l0_4_userInterface.jpg)

## Task 3 - Setting up your microcontroller (Arduino Uno) with mBlock.

1. Let's add the Arduino UNO into the **device section**.

    ![](images/l0_5_addingDevice.jpg)

2. Make sure Arduino Uno device is selected in the **devices section**. Then click **Connect**

    ![](images/l0_6_toConnect.png)

3. You will see this pop-up menu, if it shows "No device can be detected...", then check **Show all connectable devices**.

    ![](images/l0_7_showDevices.jpg)
    ![](images/l0_8_selectCom.jpg)

4. Select the right COM device and click **Connect**. 

    **If you are unsure if that is the Maker Uno, disconnect all USB devices except the Maker Uno.**

5. Your **Devices** section should look like this.

    ![](images/l0_9_deviceSection.jpg)

## Task 4 - Switching between Live and Upload mode

1. In mBlock, there are two modes we use: **Live** mode and **Upload** mode.


    - **Live**: This is when your code runs right away on the device. 
        
        Remember to "Update Firmware" every time you switch to Live Mode.

    - **Upload**: Your code only runs when you click the ![](images/btnUpload.jpg)  button.


2. You can change the mode through this **Mode Switch** toggle.

    ![](images/btnModeSwitch.jpg)

3. When switching to **Live** coding, you will have to "Update Firmware".
    1. Switch to **Live** mode
    2. Click Update Firmware
    3. Click Updates

    ![](images/l0_10_enableLiveCoding.png)

4. We will often switch between **Live** and **Upload** mode throughout this unit. Remember to "Update Firmware" every time we switch to **Live** mode.

