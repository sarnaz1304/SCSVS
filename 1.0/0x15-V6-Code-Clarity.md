# V6: Code Clarity

## Control Objective

[Description]

Category “V6” lists requirements related to the code clarity of the smart contracts.

## Security Verification Requirements

| # | Description | L1 | L2 | L3 | Since |
| --- | --- | --- | --- | -- | -- |
| **1.1** | Make sure that variables with similar names are not used. |  | ✓ | ✓ | 1.0 |
| **1.2** | Make sure constructor name is the same as contract's name. |  | ✓ | ✓ | 1.0 |
| **1.3** | Verify that all functions are used and there are no unused ones left in the code. |  | ✓ | ✓ | 1.0 |
| **1.4** | Fallback functions must be simple. |  | ✓ | ✓ | 1.0 |
| **1.5** | Use require instead of revert function in if statement. |  | ✓ | ✓ | 1.0 |
| **1.6** | Check if using low-level functions has been avoided (eg. call.value()). |  | ✓ | ✓ | 1.0 |
| **1.7** | Make sure that assembly was used only when it was necessary. |  | ✓ | ✓ | 1.0 |


## References

For more information, see also:

* [OWASP Threat Modeling Cheat Sheet](https://www.owasp.org/index.php/Threat_Modeling_Cheat_Sheet)
* [OWASP Attack Surface Analysis Cheat Sheet](https://www.owasp.org/index.php/Attack_Surface_Analysis_Cheat_Sheet)
* [OWASP Threat modeling](https://www.owasp.org/index.php/Application_Threat_Modeling)
* [OWASP Secure SDLC Cheat Sheet](https://www.owasp.org/index.php/Secure_SDLC_Cheat_Sheet)
* [Microsoft SDL](https://www.microsoft.com/en-us/sdl/)
* [NIST SP 800-57](https://csrc.nist.gov/publications/detail/sp/800-57-part-1/rev-4/final)