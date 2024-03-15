# Project 10: Ultrasonic Sensor

Objective: To program the microcontroller to read value from an ultrasonic sensor to detect distances.

Before we begin, switch to **Upload Mode**

![](images/toggle_UploadMode.jpg)

## Installing the Upload Mode Broadcast extension.

1. Construct the circuit below. You may use a breadboard if you like.
    - VCC  ➡️  5V
    - Trig ➡️  Digital Pin 12
    - Echo ➡️  Digital Pin 11
    - Gnd  ➡️  Gnd

    ![](images/p10_circuit.png)

1. Then, we must install the extension **Upload Mode Broadcast** in mBlock 5 in the **Devices** tab.

    Make sure the devices tab is selected.
    
    ![](images/tabDevices.jpg)

    Then, at the bottom of the screen, click the **extension** ![](images/btn_extension.png) button.

    ![](images/p10_instruction1.png)

1. Search for **Upload Mode Broadcast**. Then look for the extension and click **+ Add**.

    ![](images/p10_instruction2.png)

    Once you added the extensions, you will see a new section from your coding toolbox.

    ![](images/p10_instruction3.png)

1. Next, we will also install the **Upload Mode Broadcast** for the **Sprites** tab.

    Click the **Sprite** tab. ![](images/tabSprites.jpg)

1. Click the Extensions button ![](images/btn_extension.png).

    Then add the **Upload Mode Broadcast**.


### Remember

The **Devices** and **Sprites** tab each have their own coding workspace.

The code in **Devices** tab will only work in the **Devices** section.
The code in **Sprites** tab will only work in **Sprites** section.


Now we are going to code the microcontroller to:

- *Receive* distance data from the ultrasonic sensor into the microcontroller (Devices tab), and

- *Broadcast* (send) it to the Panda (Sprite tab) to display the distance.



## Getting the data from the Ultrasonic Sensor.

1. Switch to the **Devices** tab and enter the code below.

    ![](images/p10_instruction6.png)

1. Click the ![upload](images/btnUpload.jpg) button to upload the code to the microcontroller.

1. Next, switch to the **Sprites** tab and enter the code below.

    ![](images/p10_instruction7.png)

1. Then, press ![the Green Flag](images/btnGreenFlag.jpg). You should be able to see the distance displayed on the Panda.

    ![](images/p10_instruction8.png)


## Explanation

In mBlock, the **sprite** and **device** sections each have their own coding tools.

The device section connects to the microcontroller and reads the distance data from the ultrasonic sensor.

This distance information is then sent directly to the sprite section.

![](images/p10_instruction9.png)

The panda (which is a sprite) receives the distance message and displays it on the screen using the "say" block.

## Performing a conditional statement

1. Now let's create a variable name *distance*.

    Select ![**Variables**](images/btn_Variable.png).

    Then click ![**Make a Variable**](images/btn_MakeAVariable.png).

    Set the new variable name to *distance* and click **OK**.

    ![](images/p10_instruction10.png)


1. Now we will assign a value to the variable.

    Switch to **Sprites** tab.

    Delete the previous code and replace it with this code.

    ![](images/p10_instruction11.png)

1. Press the ![Green flag](images/btnGreenFlag.jpg).

    Then use the palm of your hand and place it close to the ultrasonic sensor and far away.

    The panda should say "too far" when your hand is far away from the sensor and "too close" when your hand is close to the sensor.




