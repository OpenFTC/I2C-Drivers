# I2C-Drivers

A collection of I2C drivers for devices not supported out of the box in the FTC SDK

## Installation instructions:

1. Open your FTC SDK Android Studio project

2. Open the `build.gradle` file for the TeamCode module:

    ![img-here](doc/images/teamcode-gradle.png)

3. At the bottom, add this:

        dependencies {
            implementation 'org.openftc:i2cdrivers:1.0.0'
         }

4. Now perform a Gradle Sync:

    ![img-here](doc/images/gradle-sync.png)

5. You're ready to go :)

## Changelog:

### v1.0.0

 - Initial release, with a driver for the Qwiic LED stick donated by FTC16072 - Quantum Quacks
