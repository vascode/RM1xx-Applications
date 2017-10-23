# RM1xx-Applications

This repository contains example smartBASIC applications for the RM186 and RM191 devices. 

Some of these applications require the RM1xx-defs.h file located in the firmware release package. Please be sure to use the RM1xx.h file associated with the firmware loaded on the module. The firmware version can be checked at the smartBASIC command prompt with the "ATI 3" command.

## Please Note:

For simplicity reasons, some sample apps have been written without important features such as error handling or result code checking. However, when writing your applications, please ensure that result codes returned from the API functions are always checked to ensure that your applications are robust and error-free.

## Older firmwares

The files in this repository are designed for use with the latest RM1xx firmware which at the time of writing is:

* 100.6.1.0 (RM186 Central EU)
* 101.6.1.0 (RM191 Central US)
* 102.6.1.0 (RM191 Central AU)
* 103.6.1.0 (RM191 Central AS)
* 110.6.1.0 (RM186 Peripheral EU)
* 111.6.1.0 (RM191 Peripheral US)
* 112.6.1.0 (RM191 Peripheral AU)
* 113.6.1.0 (RM191 Peripheral AS)

For applications targetting older firmwares, please check the [Releases tab](https://github.com/LairdCP/RM1xx-Applications/releases)