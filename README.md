# Magento 2 Quickstart module

A brief description of your module.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-module.git
    ```

2. Copy the module files to the appropriate location in your Magento installation:
    ```bash
    cp -R app/code/YourVendor/YourModule <path-to-magento>/app/code/
    ```

3, make sure to rename the Vendor and Module name folders to your own vendor and module name.

4, make sure to rename the module name in the registration.php file.

5, make sure to rename the module name in /{Vendor}/{Module}/etc/module.xml file.


6. Run the following commands from your Magento root directory:
    ```bash
    bin/magento module:enable YourVendor_YourModule
    bin/magento setup:upgrade
    bin/magento cache:clean
    ```