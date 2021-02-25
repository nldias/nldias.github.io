a) copy filetype.Chapel.conf to ~/.config/geany/filedefs/

b) include the following lines into
~/.config/geany/filetype_extensions.conf (create it if it does not
exist)

[Extensions]
Chapel=*.chpl;
[Groups]
Programming=Chapel;

(if [Extensions] or [Groups] already exists in the file, do not
replicate these lines)

Close and reload Geany
