# HCAP5 Product Brief

## Overview
This document provides description on an application called HCAP5 and its specificaiton.
This document is written for users or prospect users of HCAP5. It is expected readers have basic understanding of broadcast video/audio format and technologies required to perform capturing and editing.


## What is HCAP5 ?
HCAP5 is an enterprise-strength 64-bit Cocoa application on Mac OSX platform capable of capturing HD/SD video and audio via supported video I/O hardware(\*1) and digitize them into supported file formats such as QuickTime and MXF Op1a utilizing supported codecs.



    input video signal standard:
      - ITU-R BT.601 NTSC 480i
      - ITU-R BT.709 1080i

    supported file format (wrapping format):
      - QuickTime mov
      - MP4
      - MXF OP1a

    supported codec:
      - ProRes Proxy/LT/422/4444/
      - DVCPro 50/100
      - XDCAM HD 422 50/35/25Mbps
      - H.264
      - HEVC

    supported timecode:
      - RP-188
      - LTC (SMPTE 12M)(dependent on type of I/O device)
      - SYSTEM TIME
      - NETWORK TIME (w/ helper app HurryController)


## Who needs HCAP5 ?
    -Broadcast Station, Cable TV
    -Production house
    -Public service entity, local government office
    -OTT operator
    -PR, event company

HCAP5 achieves the same end result that other expensive professional VTR or ingest system create while lowering overall TCO such as eliminating cartridge costs and other maintenance cost. On top of that, HCAP5 allows users start editing while capturing is still going on. This feature surely serves faster delivery especially useful in the field of sports event coverages.


## Key Feature
- Edit While Capturing
    With HCAP5, users can access files that are still being captured with various Non-Linear Editing application such as FCPX, Adobe Premiere, etc... Users don't need to wait until the recording ends unlike traditional VTR workflow.
- Proxy and image sequence
    HCAP5 may be set to create not just on-line file but also proxy (lower resolution) file as well as image sequence (poster frames) out of the same input. Users may utilize those proxy files for media searching and offline editing.
- Multiple destinations
    HCAP5 also may be set to store files multiple destinations. same on-line file can be stored not just on main storage destination but also secondary storage location as well(Secondary Destination).
- Schedule feature
    HCAP5 has scheduled recording feature by specifying start and end timecode or by choosing the length of recording at duration.
- Schedule capturing with iCal
- Buffer feature
    HCAP5 may set to have file buffer so that it may be unaffected by temporal storage bandwidth shortage.


## How HCAP5 works
HCAP5 digitizes video/audio signals from Video I/O device into files and store them onto designated path on the storages such as internal SSD, external HDD, NAS, etc..


## MSRP
400,000 Japanese Yen per license（w/o tax）

## System Requirement

- **Operating System**

    Mac OS X 10.12 (Sierra) or later


- **Suppported Video I/O devices(\*)**
    - BlackMagic Design Video I/O devices
        - DeckLink
        - UltraStudio Express
        - UltraStudio 4K
        - UltraStudio 4K Plus
        - UltraStudio 4K Extreme 3
        - UltraStudio HD Mini


    - AJA Video I/O devices
        - I/O Express
        - I/O XT
        - I/O 4K
        - I/O IP
        - I/O 4K Plus

- **Macintosh hardware minimum requirement**
    - iMac Pro or Mac Pro
    - CPU 3.0GHz 8Core Intel Xeon E5 or 3.2GHz Intel Xeon W processor
    - RAM 16GB 1,866MHz DDR3 ECC
    - Storage 256GB PCI SSD

