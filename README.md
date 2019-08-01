# Configuring OSPFv3 on PANOS
OSPFv3 configuration skillet provides quick way to configure OSPFv3 parameters to enable routing for the IPv6 dataplane interface. It provides quick options for enabling OSPFv3 and routes export rules.

## Prerequisites
1) IPv6 configured interfaces
2) Neighbouring router with OSPFv3 enabled 

This skillet configures the following
1) Enables OSPFv3
2) Router id
3) Area id
4) Route Export Rule (Redistribution Profile)

You can use "IPv6-Configuration" skillet in order to configure the IPv6 address on the dataplane interfaces.  In this skillet we have only enabled static and connected routes under export rules. No Auth Profile is configured via this skillet
 

## Support Policy
The code and templates in the repo are released under an as-is, best effort,
support policy. These scripts should be seen as community supported and
Palo Alto Networks will contribute our expertise as and when possible.
We do not provide technical support or help in using or troubleshooting the
components of the project through our normal support options such as
Palo Alto Networks support teams, or ASC (Authorized Support Centers)
partners and backline support options. The underlying product used
(the VM-Series firewall) by the scripts or templates are still supported,
but the support is only for the product functionality and not for help in
deploying or using the template or script itself. Unless explicitly tagged,
all projects or work posted in our GitHub repository
(at https://github.com/PaloAltoNetworks) or sites other than our official
Downloads page on https://support.paloaltonetworks.com are provided under
the best effort policy.
