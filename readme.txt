『増補改訂版Java言語で学ぶデザインパターン入門』結城浩著
ソフトバンクパブリッシング(株)刊
http://www.hyuki.com/dp/
hyuki@hyuki.com

2004年4月23日

■はじめに

このアーカイブには、
書籍『増補改訂版Java言語で学ぶデザインパターン入門』の
サンプルプログラムなどが格納されています。

■サンプルプログラムのディレクトリ構造

サンプルプログラムのディレクトリ構造は、以下のようになっています。


    src
    +------ Observer
    |       +------ Sample
    |       |       +------ DigitObserver.java
    |       |       +------ GraphObserver.java
    |       |       +------ NumberGenerator.java
    |       |       +------ Observer.java
    |       |       +------ RandomNumberGenerator.java
    |       |       +------ Main.java
    |       |
    |       +------ Q1
    |       |       +------ Main.java
    |       |
    |       +------ A1
    |       |       +       .
    |       |       |       .
    |       |       +------ Main.java
    |       |
    |       +------ A2
    |       |       +       .
    |       |       |       .
    |       |       +------ Main.java
    |       
    +------ TemplateMethod
    |       +------ Sample
    |       |       .
    |       .       .
    .       .
    .

各ディレクトリの意味は、次のとおりです。

    src/パターン名/Sample      サンプルプログラム
    src/パターン名/Q☆...      練習問題に登場するリスト（☆は問題番号）
    src/パターン名/A☆...      解答に登場するリスト（☆は問題番号）


■著作権とライセンス

このアーカイブに含まれているファイルは
以下のThe zlib/libpng License
に従って取り扱ってください。

Copyright (C) 2001,2004 Hiroshi Yuki.
http://www.hyuki.com/dp/
hyuki@hyuki.com

This software is provided 'as-is', without any express or implied warranty.
In no event will the authors be held liable for any damages
arising from the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it freely,
subject to the following restrictions:

1. The origin of this software must not be misrepresented; you must not claim
that you wrote the original software. If you use this software in a product,
an acknowledgment in the product documentation would be appreciated but is not
required.

2. Altered source versions must be plainly marked as such, and must not be
misrepresented as being the original software.

3. This notice may not be removed or altered from any source distribution.

（以下、参考訳）
このソフトウェアは現状のまま提供されるものであり、
明示的にあるいは暗黙のうちにどんな保証もしない。
このソフトウェアを使うことによって生じるいかなる損害に対しても、
作者はまったく責任を負わない。

以下の制限を守る限りにおいて、誰であっても、
このソフトウェアを商用アプリケーションを含む任意の目的に使用すること、
このソフトウェアを変更すること、そして自由に再配布することができる。

1. このソフトウェアの起源を誤って提示してはならない。すなわち、
あなたは元のソフトウェアを自分が書いたと主張してはならない。
もしもこのソフトウェアを製品の中で使用するときには、製品の文書中で
謝意を示すことは歓迎する。しかしそれは必須ではない。

2. 変更したソースの版ははっきりとそれがわかるようにしなければならず、
元のソフトウェアと混同されるようにしてはいけない。

3. いかなるソース配布からも、この注意書きは削除したり変更したりしてはならない。
