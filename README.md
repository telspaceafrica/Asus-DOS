# Asus Denial of service

Denial of Service for Asus Precision TouchPad 11.0.0.25 - DoS/Privesc

TSA-2019-001: Asus Precision TouchPad 11.0.0.25
CVE number: CVE-2019-10709

Summary:

The AsusPTPFilter.sys driver on the Asus Precision TouchPad 11.0.0.25 hardware has a Pool Overflow associated with the \\.\AsusTP device, leading to a DoS and could also potentially lead to privilege escalation via a crafted DeviceIoControl call with a specific IOCTL code.

Vendor:

Asus

Product:

Asus Precision TouchPad

Version:

11.0.0.25

Vendor:

https://www.asus.com/us/News/SupportNews/
https://www.asus.com/

Vendor response:

The vendor has patched the vulnerability and released a new version. 

Disclosure Timeline:

25-03-2019 – Initial Discovery

27-03-2019 – Vendor Notification

29-08-2019 – Vendor Patch

30-08-2019 – Public Disclosure

Credit:

This vulnerability was discovered by Athanasios Tserpelis of Telspace Systems
