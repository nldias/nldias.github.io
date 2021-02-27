[For windows, replace ~/.config/geany with
C:\Users\"user"\AppData\Roaming\geany,
where "user" is your username]

a) copy filetype.Chapel.conf to ~/.config/geany/filedefs/

b) [copy filetype_extensions.conf to ~/.config/geany] OR [include the
following lines (-->) into ~/.config/geany/filetype_extensions.conf,
if it already exists]

under [Extensions]:
--> Chapel=*.chpl;

under [Groups]:
--> Programming=Chapel;

Close and reload Geany

