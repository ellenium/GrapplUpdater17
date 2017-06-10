A new Grappl updater, for 2017's Grappl versions.


The old Grappl updater just always downloaded the GrapplClient.jar from grappl.io, however, this one won't download a .jar
if you already have it, nor will it download a .jar without asking the user. It only
downloads .jars if their MD5 hash differs from the one already found
on the disk, and the user has consented to this download.


Therefore, this updater doesn't have anything that could be construed as unexpected behavior, and provides a shield against the update pathway being abused.