# Reddit Research
* Confused why they aren't more common in business
* Easier to add keys to the keychain than having to remember passwords
* Biometric keys are better for admins that have multiple accounts, for it is easier to fingerprint than type a PIN multiple times a day


## Products
## YubiKeys
* Entire orgs manage their FIDO2 via Yubikeys for their MFA
* The standard for users and single accounts

## Fetian
* 
  
* We have Yubikeys as our "standard" for users and single accounts. For admins that have multiple accounts across many tenants, we opted for biometric keys (Feitian in our case) as it is easier to fingerprint than type in a PIN eight times a day as an admin starts or shuts down various browser profiles.

Many users have multiple keys (home and office) plus whatever they have on their Microsoft Authenticator app, so they are pretty much never without a passkey.

Our breakglass accounts are hardware key base, with keys stored in safes onsite and off. The PIN for those are stored with the key (depending on the safe in use) or in our password manager (in the case of keys stored with the CIO or Director since we cannot guarantee that they use a safe or the quality of that safe; safes onsite are protected by multiple layers of physical security, are under camera review, and have alarms of their own in the event of breach).


## Sources
* [Fido2 Hardware Key authentication](https://www.reddit.com/r/sysadmin/comments/1srbeyj/fido2_hardware_key_authentication/)
