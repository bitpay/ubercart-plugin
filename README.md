> [!WARNING]
> **This repository is archived and no longer maintained by BitPay.**
>
> It is read-only and will not receive updates, bug fixes, or security fixes. Please do not start new integrations from this code.
>
> For currently supported integrations, see [eCommerce Plugins](https://developer.bitpay.com/docs/plugins) and [Libraries](https://developer.bitpay.com/docs/libraries). If you already use this code, we recommend moving to a supported integration.

# Description

Bitcoin payment plugin for Drupal 6 Ubercart using the bitpay.com service.

[![Build Status](https://travis-ci.org/bitpay/ubercart-plugin.svg?branch=master)](https://travis-ci.org/bitpay/ubercart-plugin)

## Quick Start Guide

To get up and running with our plugin quickly, see the GUIDE here: https://github.com/bitpay/ubercart-plugin/blob/master/GUIDE.md

# Support

**BitPay Supprt:**

* [Github Issues](https://github.com/bitpay/ubercart-plugin/issues)
  * Open an Issue if you are having issues with this plugin
* [Support](https://help.bitpay.com)
  * Checkout the BitPay support site

**Ubercart Support:**

* [Homepage](http://www.ubercart.org/)
* [Documentation](http://www.ubercart.org/docs)
* [Forums](http://www.ubercart.org/forum)

## Troubleshooting

0. Sometimes a download can become corrupted for various reasons.  However, you can verify that the release package you downloaded is correct by checking the md5 checksum "fingerprint" of your download against the md5 checksum value shown on the Releases page.  Even the smallest change in the downloaded release package will cause a different value to be shown!
  * If you are using Windows, you can download a checksum verifier tool and instructions directly from Microsoft here: http://www.microsoft.com/en-us/download/details.aspx?id=11533
  * If you are using Linux or OS X, you already have the software installed on your system.
    * On Linux systems use the md5sum program.  For example:
      * md5sum filename
    * On OS X use the md5 program.  For example:
      * md5 filename
1. Ensure a valid SSL certificate is installed on your server. Also ensure your root CA cert is updated. If your CA cert is not current, you will see curl SSL verification errors.
2. Verify that your web server is not blocking POSTs from servers it may not recognize. Double check this on your firewall as well, if one is being used.
3. Check the version of this plugin against the official plugin repository to ensure you are using the latest version. Your issue might have been addressed in a newer version! See the [Releases](https://github.com/bitpay/ubercart-plugin/releases) page for the latest.
4. If all else fails, contact us using one of the methods described in the Support section above.

**TIP**: When contacting support it will help us is you provide:

* Shopping Cart and BitPay Plugin Version
* Other plugins you have installed
  * Some plugins do not play nice
* Configuration settings for the plugin (Most merchants take screen grabs)
* Any log files that will help
  * Web server error logs
* Screen grabs of error message if applicable.

## Contribute

Would you like to help with this project?  Great!  You don't have to be a developer, either.  If you've found a bug or have an idea for an improvement, please open an [issue](https://github.com/bitpay/ubercart-plugin/issues) and tell us about it.

If you *are* a developer wanting contribute an enhancement, bugfix or other patch to this project, please fork this repository and submit a pull request detailing your changes. 

This open source project is released under the [MIT license](http://opensource.org/licenses/MIT) which means if you would like to use this project's code in your own project you are free to do so.

## License

Please refer to the [LICENSE](https://github.com/bitpay/ubercart-plugin/blob/master/LICENSE) file that came with this project.
