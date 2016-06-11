Bash script for changing "From" address when using nullmailer.

Warning:

- tested only on Gentoo Linux with nullmailer v1.13-r5. Please refer to your Linux distribution manual for proper script configuration.

Usage:

- rename original "sendmail" (usually located in "/usr/sbin") to "sendmail-bin".
- copy "sendmail" file from this repository to "/usr/sbin/sendmail".
- make "/usr/sbin/sendmail" executable (chmod +x) and set proper rights if needed (chown).
- set your own values to $newFrom and/or $newAddress.
- modify line 62 in script if needed (it's pretty obvious, see comments in sendmail file).
- feel free to modify script for your own needs.

Original idea:

- https://gist.github.com/bbrodriges/2397565
