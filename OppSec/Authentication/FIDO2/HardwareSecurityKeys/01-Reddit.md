# (NF) Reddit Research
* Should be more common in business, for it is easier to add keys to the keychain than having to remember passwords
* Biometric keys are better for multiple accounts, for it is easier to fingerprint than type a PIN multiple times a day
* Always have a backup hardware security key
* PINs provide protection against stolen laptop or security key device
* The physical aspect of this tool protects it against remote access control and keylogger attacks

## Asset Management
* Should be stored onsite along with a backup(s) offsite
* On-site nano keys can be stashed inside laptops
* On-site regular-sized keys can be clipped to the access keys of employee lanyards
* Off-site key should be stored in SAFEs or other physically protected locations
     * Should be protected with multiple layers of security
     * CCTV cameras should act as a deterrent towards storage premises
     * Alarms should alert the security team in-case of a breach
* Enable PIN/Password
    * PIN should be stored physically with the hardware key OR stored in a password manager
    * Keep in-mind to also always have PIN/password protection on your physical machine
    * Keep in-mind to log out of your machine when you are done using it
* Enable AAGUID Attestation
    * Setup for specific keys
    * Set that policy to a breakglass account so they cannot add another software's passkey to the account
    * Keep breakglass accounts protected by security keys (no NFC)
* Keys should be kept in *parity*
    * Ensure that multiple YubiKeys are configured identically for the same accounts or services
    * Allows users to have backup keys that can be used interchangeably without losing access if one key is lost or damaged
    * Setup reminders to ensure this consistency
* Maintain a USB-C to USB-A adapter in-case you run into hardware compatibility issues


## Multi-Key Setup
* Enterprise-Level
    * User accounts
    * Admin accounts
* User-Level
    * Home
    * Office
    * Offsite


## Products

### (7) YubiKeys
* Entire orgs manage their FIDO2 via Yubikeys for their MFA
* The standard best for multiple user accounts or single admin accounts
* **YubiKey 5 Series**
    * **(4) YubiKey 5 NFC**
        * Smack them against a reader and type in a PIN
        * Overkill for normal user-use
    * **YubiKey 5C NFC**
    * **YubiKey 5Ci**
    * **(3) YubiKey 5C**
    * **(1) YubiKey 5 Nano**
        * Keep 2 keys for personal user accounts
        * Best for its portability to be easily locked away
    * **(2) YubiKey 5C Nano**
        * Can be stored within the laptop
* **YubiKey FIPS Series**
    * **YubiKey 5 NFC FIPS**
    * **YubiKey 5C NFC FIPS**
    * **YubiKey 5Ci FIPS**
    * **YubiKey 5C FIPS**
    * **YubiKey 5 Nano FIPS**
    * **YubiKey 5C Nano FIPS**
* **YubiKey Bio Series**
    * **YubiKey Bio - FIDO Edition**
    * **YubiKey C Bio - FIDO Edition**
    * **YubiKey Bio - Multi-protocol Edition**
    * **YubiKey C Bio - Multi-protocol Edition**
* **YubiKey Security Key Series**
    * **Security Key NFC**
        * Ideal for: Google, Microsoft, GitHub, Password Managers, Modern Websites
    * **(1) Security Key C NFC**
        * Ideal for: Modern laptops, Android Phones, and Macbooks
### (2) Feitian
* Biometric hardware security key best for managing multiple admin accounts
* Many different styles and interfaces for FIDO2 keys
* OTP token feature
### Google Titan
* Best for admin accounts

## Sources
* [Fido2 Hardware Key authentication](https://www.reddit.com/r/sysadmin/comments/1srbeyj/fido2_hardware_key_authentication/)
* [Best FIDO/FIDO2 Key](https://www.reddit.com/r/privacy/comments/1ctefsl/best_fidofido2_security_key/)
* [Which Hardware Security Key to Choose?](https://www.reddit.com/r/Bitwarden/comments/1jnaoad/which_hardware_security_key_to_choose/)
* [I'm Thinking About Buying Physical Security Key, Any Tips?](https://www.reddit.com/r/DigitalPrivacy/comments/1plvn0d/im_thinking_about_buying_physical_security_key/)
* [Verify Any YubiKey from Amazon](https://www.reddit.com/r/yubikey/comments/112812v/yubikey_from_amazon/)
