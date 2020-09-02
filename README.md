# No-Exif
Removes Exif Data from Images


## NoExif
It is a command line tool which can remove exif data from images.
Currently, image types such as JPG, JPEG, PNG, TIFF, NEF, CR2, RAW etc. are supported.


## What is EXIF Data?

EXIF is short for Exchangeable Image File Format, a format that is a standard for storing interchange information in digital photography image files using JPEG compression.

It stores metadata such as:
- Device Name
- Device Model
- Camera Software
- Camera Settings
    - ISO
    - Exposure
    - Focal Length
    - Shutter Speed
    - Flash Settings
- Image Unique ID
- Date and time of the image
- Exact Location with Latitude and Longitude of the place where Image was taken (If location is enabled)

- It can store upto 70 different types of data.

You can see all the exif data for an image using *exiftool*.

It is capable of storing such important data as camera exposure, date/time the image was captured, and even GPS location.


## Why it is necessary / required to remove the EXIF data?

- To remove Sensitive information such as your device info and GPS location
- To post images to a low-bandwidth site and keep their sizes small
- To protect your work and hide information that reveals your camera gear, settings and even post-processing adjustments

