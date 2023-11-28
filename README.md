# Drone Repair - Final-Project
Final project for the course LMT 4042, Fall 2023
The main objective, as we know, was to identify and check the operation of all the elements of the drone, in order to make it suitable to fly, however, the NAZE 32 rev5 board is quite old board, which was used about 8 years ago with old versions of Windows, so the configuration software is obsolete, as it was tried on several platforms and none was suitable for this board.

Speaking of the ESC controller, there is a Qbrain 4x25A, which is also not sold today, so we can deduce that it is obsolete or that improved versions are produced. Figure \ref{esc} shows this device.

Regarding the remote control and the signal receiver, it was observed that the former has 9 channels, while the receiver has 8, which could represent a problem when connecting the motors and sending the signals to each of the channels. Since the motors are disconnected, it is necessary to identify which cable corresponds to each motor in order to check its operation. In addition, the remote control uses 8 1.5V batteries. Both Control and Signal receiver can be seen in the document.

In conclusion, the project focused on the physical repair and enhancement of a drone presented several challenges, primarily due to the outdated components such as the NAZE 32 board and Qbrain 4x25A ESC controller. The initial goal was to restore the drone's functionality and enable it to fly or at least interact with the flight controller. However, limitations in the compatibility and availability of software for the existing hardware prompted the need for alternative solutions.

The identification of the problem highlighted the obsolescence of the NAZE 32 board and the Qbrain 4x25A ESC controller, posing significant hurdles to configuration and operability. Additionally, issues with the remote control and signal receiver, including a mismatch in the number of channels, added complexity to the project.

To address these challenges, the proposed solution involves replacing the outdated NAZE 32 board with a more modern and configurable SpeedyBee F405 V3 board. This newer board offers enhanced features, ease of configuration through Betaflight configurator software, and Bluetooth compatibility for convenient adjustments. Despite being slightly heavier, the SpeedyBee F405 V3 board presents a cost-effective solution, with prices ranging from \$9 to \$12 USD, making it a favorable alternative compared to the discontinued and costlier NAZE 32 board.

In summary, the project's success hinges on the implementation of this strategic solution, providing not only a functional drone but also a guide for replication. The proposed modifications aim to ensure the drone's compatibility with contemporary technology and contribute to the longevity of its operational capabilities.
