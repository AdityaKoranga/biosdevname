# biosdevname
bios eth name info using cmd line

```bash
sudo biosdevname -i eno1
```

```bash
sudo biosdevname -i ens1f0
```

![image](https://github.com/AdityaKoranga/biosdevname/assets/95766110/20c23724-b43a-4c3b-811c-3ae8eda25eb5)

![image](https://github.com/AdityaKoranga/biosdevname/assets/95766110/499f4e2a-fac8-4b71-8778-0039047fef06)

`em` stands for "Embedded NIC" and the number that follows indicates the order of the NIC as defined by the BIOS.
By using biosdevname, you're translating the newer naming convention (like eno1) to an older BIOS-provided naming convention (em1).

`en`: Ethernet
`s1`: Slot 1
`f0`: Function 0
This suggests that the NIC is in slot 1, function 0.

The returned name p3p1 is in line with another older BIOS-provided naming convention:

`p3`: PCI slot 3
`p1`: Port 1
