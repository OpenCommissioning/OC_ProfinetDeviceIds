# Profinet Vendor- and DeviceIDs

The file `DeviceIds.json` represents a dictionary of Profinet Vendor- and DeviceIDs, collected from different sources.

The key represents either the GSDML filename or the SIEMENS ordernumber of the device.
The value is a 32-bit hex value (0xAAAABBBB), representing the VendorID (A) and DeviceID (B) of the device.

The dictionary is used by the [OC.Assistant](https://github.com/OpenCommissioning/OC_Assistant) to obtain the corresponding Value- and DeviceIDs when running a Profinet scan.
Further devices may be added over time.
