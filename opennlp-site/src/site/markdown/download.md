Title: Download

## Last Offical Release

Apache OpenNLP 1.7.2 is now available for download.

File | Signatures 
------- | ------- 
[apache-opennlp-1.7.2-bin.tar.gz] [1] | [md5] [2]  [sha1] [3] [asc] [4] 
[apache-opennlp-1.7.2-bin.zip] [5] | [md5] [6]  [sha1] [7] [asc] [8] 
[apache-opennlp-1.7.2-src.tar.gz] [9] | [md5] [10]  [sha1] [11] [asc] [12]
[apache-opennlp-1.7.2-src.zip] [13] | [md5] [14]  [sha1] [15] [asc] [16]

Note: Please note that the tar.gz archive contain file names longer than 100 characters and has
been created using GNU tar extensions. It must be untarred with a GNU compatible version of tar.

### Verifying Signatures
The md5, sha1 and asc files are signature files and can be used to verify the integrity of the
downloaded distribution package.

Use the following commands to verify the integrity:

* gpg --print-md MD5 fileName.zip
* gpg --print-md SHA1 fileName.tar.gz
* gpg --verify fileName.tar.gz.asc

It might be necessary to import the [KEYS file][0] to verify the integrity
of the asc files.

That can easily be done with:

* gpg --import KEYS

More information about release signing and verifying signatures can 
be found [here](https://www.apache.org/dev/release-signing.html).

## Models
The models over at SourceForge for 1.5.0 can be [found here](http://opennlp.sourceforge.net/models-1.5/)
and are fully compatible with Apache OpenNLP 1.7.2.

The models can be used for testing or getting started, please train your own models for all other use cases.

## Archive
Historical releases can be downloaded from the archived [SourceForge project](https://sourceforge.net/projects/opennlp/)
or the [Apache archive](https://archive.apache.org/dist/opennlp/).

[0]: https://www.apache.org/dist/opennlp/KEYS
[1]: https://www.apache.org/dyn/closer.cgi/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-bin.tar.gz
[2]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-bin.tar.gz.md5
[3]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-bin.tar.gz.sha1
[4]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-bin.tar.gz.asc
[5]: https://www.apache.org/dyn/closer.cgi/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-bin.zip
[6]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-bin.zip.md5
[7]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-bin.zip.sha1
[8]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-bin.zip.asc
[9]: https://www.apache.org/dyn/closer.cgi/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-src.tar.gz
[10]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-src.tar.gz.md5
[11]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-src.tar.gz.sha1
[12]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-src.tar.gz.asc
[13]: https://www.apache.org/dyn/closer.cgi/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-src.zip
[14]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-src.zip.md5
[15]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-src.zip.sha1
[16]: https://www.apache.org/dist/opennlp/opennlp-1.7.2/apache-opennlp-1.7.2-src.zip.asc
