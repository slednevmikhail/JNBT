JNBT 1.5 Beta

The original JNBT project seems to have been abandoned.
This fork of JNBT has mainly added support for Tag_Int_Array

Thanks to:
Ancient (a.k.a. grahamedgecombe) - JNBT 1.0 and 1.1
osici - for the TAG_Lists bug
Jocopa3 - Initial Int-Array support
Morlok8k - Maintaining the project
peerkoel - Adding Long-Array support

--------------

For more information about the license, see LICENSE.TXT.

For more information about the project, see http://jnbt.sf.net/.

--------------

JNBT: The Java NBT Library

What is NBT?

NBT, or Named Binary Tag, is a file format created by Markus Persson for use with Minecraft levels. Although originally designed for Minecraft levels, it is appropriate for the vast majority of use cases.

What is JNBT?

JNBT is a library that can read and write NBT files, written in Java by Graham Edgecombe and available open-source under the BSD license.

--------------

Version History:
My additions:
 - CompoundTag getTagByPath added

1.5 (peerkoel)
- TAG_Long_Array support

1.4
- (pruby) InputStream gzip/not-gziped support
- (ensirius) Raw DataInputStream support

1.3 (Morlok8k)
- Changed encoding of .java files to UTF-8
- added "[JNBT]" to error output
- added .equals and .hashcode to tags
- cleaned source and formatting, etc...

1.2 (Morlok8k)
- Tag_Int_Array Support

1.1 (grahamedgecombe)
- fix for writing TAG_Lists
- toString() methods on each tag type

1.0 (grahamedgecombe)
- Initial Release



