# SignXS - ファイル署名ソフトウェア

# 概要
SignXSは、簡単かつセキュアな方法でファイルに署名するためのツールです。
このソフトウェアには署名の作成と検証のための2つの主要な機能が含まれています。

SignXS.exe: ファイルに電子署名を作成します。
Sign_chk.exe: ファイルの署名を検証します。

インストール
このリポジトリをクローンするか、ZIPファイルとしてダウンロードします。

ダウンロードしたZIPファイルを解凍します。

ソフトウェアと同じディレクトリに Big.flf フォントファイルを配置します。

# 使用方法
SignXS.exe - ファイルに署名を作成する

SignXS.exe sign :起動後、ファイルパスを指定するとsignsフォルダが作成され、そこに秘密鍵などが配置されます。
(public_[ファイル名].pemとsignature.bin以外は公開しないでください)

Sign_chk.exe - ファイルの署名を検証する

Sign_chk.exe: 起動後、ファイルパスを指定すると自動でpublic_[ファイル名].pemとsignature.binが認識され検証結果が表示されます。
(public_[ファイル名].pemとsignature.binはsignsフォルダにコピーしてください)


# カスタムフォントの配置
このソフトウェアは、カスタムフォント Big.flf を使用しています。ソフトウェアの実行ファイルと同じディレクトリに Big.flf フォントファイルを配置してください。
（このリポジトリには、カスタムフォントは含まれません)

## フォント「big.flf」について

このソフトウェアはフォント「big.flf」を使用しています。以下は「big.flf」の著作権情報とライセンス条件です。

### big.flf 著作者

- Glenn Chappell
- Ian Chai
- John Cowan
- Christiaan Keet
- Claudio Matsuoka

### ライセンス

Copyright (C) 1991, 1993, 1994 Glenn Chappell and Ian Chai
Copyright (C) 1996, 1997, 1998, 1999, 2000, 2001 John Cowan
Copyright (C) 2002 Christiaan Keet
Copyright (C) 2011 Claudio Matsuoka
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

1. Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.
3. Neither the name of the copyright holders nor the names of their
   contributors may be used to endorse or promote products derived
   from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS
FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE
COPYRIGHT HOLDERS OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS
OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR
TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE
USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

このフォントは上記の条件のもとで使用されています。詳細については、LICENSE ファイルを参照してください。