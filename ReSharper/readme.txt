On XP Resharper stores its settings in:
%userprofile%\Application Data\JetBrains\ReSharper\[R# Version]\[VS Version]

and of Vista/7:
%userprofile%\AppData\Roaming\JetBrains\ReSharper\[R# Version]\[VS Version]

where [R# Version] is the version of ReSharper installed (e.g. v4.5) and [VS Version] is your Visual Studio version (e.g. vs9.0).

Just copy all the files from that folder to backup, and put them back there to restore.