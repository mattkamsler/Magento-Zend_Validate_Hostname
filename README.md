Magento-Zend_Validate_Hostname
==============================

Updated Zend_Validate_Hostname with list of TLDs.

To install simply copy file into the specified location.

This has only been lightly tested on Magento 1.9.0.1.  Use at your own risk!  Author is not responsible for any issues, damages or losses of any kind that may arrise from the use of this code.  Always make backups of your code and test all updates on a non-live test site first.

TODO:
Create a better way overriding the Zend library file.  Possibly use a Magento module to inject an extended version of the Zend_Validate_Hostname file into the Zend_Validate_EmailAddress validator.

This extension does not validate the domain to the exact specifications of many of the TLDs that were added.  This needs to be added to improve the validation that is performed.