# ftp.etica.ai
Etica.AI main repository of files. It can be accessed both via anonymous FTP and by HTTP/HTTPS

## Mount ftp.etica.ai as one read-only local disk (RECOMMENDED!)

- <ftp://ftp.etica.ai>
- <sftp://ftp.etica.ai>
    - Note: browsers like Chrome, Firefox, etc maybe not work with SFTP

Anonymous FTP is enabled (it means you can access the files without one user and
password). People can use Android, Linux file navigators, etc, to add the FTP /
SFTP as a type of read-only extra disk.

This method can be specially useful for who have very small disk space on
smartphones. As reference, 4 GB is a popular storage size on Androids on
Etica.AI target audicence on Africa.

## Access via HTTPS (or HTTP)
- HTTP: <http://ftp.etica.ai>
- HTTPS: <https://ftp.etica.ai>

We use a [even more optimized version for low data usage](https://github.com/fititnt/cplp-aiops/issues/4#issuecomment-488220452)
of the [lrsjng/h5ai](https://github.com/lrsjng/h5ai) (_"HTTP web server index
for Apache httpd, lighttpd, nginx and Cherokee"_).

The HTTPS/HTTP version does consume more data than the SFTP/FTP version, but
have extra options, like search by file names and download selected files as
a single zip file.

## Where the files are stored?
The files of ftp.etica.ai are not on this repository, but on the [Mamba VPS](https://github.com/EticaAI/forum/issues/72).
For who is interested, the setup of this repository is documented on the
[cplp-aiops](https://github.com/fititnt/cplp-aiops) <sup>(destiny in Portuguese)</sup>.
