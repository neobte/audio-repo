El problema era la organización del contenedor M4A.

Paso de
[ ftyp ][ mdat ][ moov ]

a
[ ftyp ][ moov ][ mdat ]

ffmpeg -i malo.m4a -c copy -movflags +faststart malo_fixed.m4a
