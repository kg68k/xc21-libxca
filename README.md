# xc21-libxca
XC ver2.11のライブラリを[xc21-ltoa](https://github.com/kg68k/xc21-ltoa)で
lib*.a形式に変換したものです。

仕様や再配布に関しては[LICENSE.txt](LICENSE.txt)を参照してください。  
これは「許諾条件.txt」からGitHub掲載用に文字コード、改行コード、ファイル名を変更したものです。

## include/doscall.equ
真里子版GCCとXCのライブラリを組み合わせて使う際に必要なファイルです。

[XC2102_02.LZH](http://retropc.net/x68000/software/sharp/xc21/)
に収録されているINCLUDE/DOSCALL.MACを改変したものです。

## include/sxcall.equ

真里子版GCC(SXモード)とXCのライブラリを組み合わせて使う際に必要なファイルです。

[SXWORK1.LZH](http://retropc.net/x68000/software/sharp/xc21/)
に収録されているINCLUDE/SXCALL.MACを改変したものです。

リポジトリに登録されているファイルは文字コードがUTF-8に変換されているので、
X680x0/Human68k上で使用する場合はShift_JISに変換する必要があります。

