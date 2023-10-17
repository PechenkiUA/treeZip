# treeZip

The script recursively collects files in folders by file name or part of them, preserving the structure and zipping everything into one zip archive

You need to install 7z [https://www.7-zip.org/download.html]

Build files nfme to zip file
```
iex ([System.Net.WebClient]::new().DownloadString('https://raw.githubusercontent.com/PechenkiUA/treeZip/main/tree.pc1')); run -archiveName "out.zip" -targetFileName "php*.*"

```
