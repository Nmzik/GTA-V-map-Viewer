GTA V Map Viewer
=====
## NOTES
DLC is not supported.

As mobile platforms are known NOT to support S3TC texture format, what we are doing is uncompressing each texture on CPU and then sending it over to GPU in uncompressed format. And as a result it takes a lot of ram/vram (on mobile vram and ram is unified) to get all required textures loaded. In theory we could recompress every single texture to “mobile friendly” format 😂.

## Attention!
There is currently no way to load PC textures at their original resolution (you need at least 2.2 GB free ram) so that's why all textures with be loaded from mipmap level >= 2 to save some vram resulting in low resolution (blurred) textures.

## Required free ram on device:
> `>1 GB`

Tested on iPhone XR

## How do I run it?

* Sign ipa with your certificate (development / 7 day personal) and install on device.

You also need to copy the following files to your iPhone/iPad via iTunes File Sharing:
* Executable “GTAV.exe” (for decryption keys)
* All files with extension .rpf from your local GTA V folder on PC
## NOTE:
  While there is no “check” inside app to have all RPF files copied, I **DO** recommend to have every single RPF file on your device otherwise in some cases “player” will fall through the world infinitely…

## WHAT TO EXPECT
A lot of bugs!
A lot of memory leaks!

## THANKS TO
* Dexyfex https://github.com/dexyfex/CodeWalker
* gta-toolkit https://github.com/Neodymium146/gta-toolkit
