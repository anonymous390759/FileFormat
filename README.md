# FileFormat
A tool to find formats/specs for various file extensions.

| File Signature | Extension Name | Use(s) | Format |
|----------------|----------------|--------|--------| 
| ``` FD 37 7A 58 5A 00 ``` | .xz | XZ compression | [doc/xz-file-format.txt](https://chromium.googlesource.com/chromium/deps/xz/+/77022065014d48cf51d83322264ab4836fd175ec/doc/xz-file-format.txt) |
| ``` 4E 45 53 1A ``` | .nes | (iNES) nes rom |[INES - NESdev Wiki](https://www.nesdev.org/wiki/INES) |
| ``` 89 50 4E 47 0D 0A 1A 0A ``` | .png | Portable Network Graphics image | [PNG Specification](http://www.libpng.org/pub/png/spec/1.2/PNG-Structure.html) |
| ``` 52 61 72 21 1A 07 01 00 ``` | .rar | Roshal Archive file | [RAR 5.0 archive format](https://www.rarlab.com/technote.htm) |
| ``` 50 4B 03 04 ``` | .zip  | Phil Katz zip compression | [The structure of a PKZip file](https://users.cs.jmu.edu/buchhofp/forensics/formats/pkzip.html) |
| ``` 1F 8B ``` | .gzip, .gz | GNU zip compression | [https://www.ietf.org/rfc/rfc1952.txt](https://www.ietf.org/rfc/rfc1952.txt) |
| ``` __ 41 54 41 52 49 37 38 30 30 ``` | .a78 | Atari 7800 rom | [A78 Header Specification](https://7800.8bitdev.org/index.php/A78_Header_Specification) |
| ``` 66 74 79 70 ``` | .mp4 | Moving Picture Experts Group 4 part 14 file | [Microsoft Word](https://ossrs.io/lts/zh-cn/assets/files/ISO_IEC_14496-14-MP4-2003-9a3eb04879ded495406399602ff2e587.pdf) |
| ``` FF D8 ``` | .jpg, .jpeg | Joint Photographic Experts Group image file | [(Thank you corkami)](https://github.com/corkami/formats/blob/master/image/jpeg.md) |
| ``` 47 49 46 38 __ 61 ``` | .gif | Graphics Interchange Format image file | [w3.org](https://www.w3.org/Graphics/GIF/spec-gif89a.txt) |
| ``` 5A 4D  -OR-  4D 5A ``` | .exe | Microsoft Executable file | [(Thank you joachimmetz)](https://github.com/libyal/libexe/blob/main/documentation/Executable%20(EXE)%20file%20format.asciidoc) |
| ``` 42 5A 68 ``` | .bz2 | BZip2 Archive | [(Thank you dsnet)](https://github.com/dsnet/compress/blob/master/doc/bzip2-format.pdf) |
| ``` 42 4D ``` | .bmp | Bitmap file | [THE BMP FILE FORMAT](https://www.ece.ualberta.ca/~elliott/ee552/studentAppNotes/2003_w/misc/bmp_file_format/bmp_file_format.htm) |
| ``` __ 57 53 ``` | .swf | Adobe Shockwave file | [untitled](https://open-flash.github.io/mirrors/swf-spec-19.pdf) |
| ``` 50 41 54 43 48 ``` | .ips | International Patching System | [IPS format](https://www.anosh.se/ips/) |
| ``` 4D 54 68 64 ``` | .mid | Musical Instrument Digital Interface file | [Standard MIDI File Structure](https://ccrma.stanford.edu/~craig/14q/midifile/MidiFileFormat.html) |
| ``` 37 7A ``` | .7z | 7-Zip archive | [.7z format specification](https://py7zr.readthedocs.io/en/latest/archive_format.html) |
