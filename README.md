# BL616 PIO

This repo contains necessary patch to add PIO support to BL616 [Bouffalo SDK](https://github.com/bouffalolab/bouffalo_sdk).

Bouffalo Lab BL616 contains a RP2040 compatible PIO hardware and software support
is lacking. This repo adds the support.

It seems that BL616CL and BL616DG also support PIO.

It is reported that Qualcomm QCC74x is rebranded BL616 but PIO support is not verified.

# Patch notes

The patch should apply cleanly to Bouffalo SDK. Tested version is b3c904b47ec0f8487c3b640553cee582b1597925.
