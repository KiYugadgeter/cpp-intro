# 序

本書はプログラミングの経験はあるがC++は知らない読者を対象にしたC++を学ぶための本である。本書はすでに学んだことのみを使って次の知識を説明する手法で書かれた。C++コンパイラーをC++で書く場合、C++コンパイラーのソースコードをコンパイルする最初のC++コンパイラーをどうするかというブートストラップ問題がある。本書はいわばC++における知識のブートストラップを目指した本だ。これにより読者は本を先頭から読んでいけば、まだ学んでいない概念が突如として無説明のまま使われて混乱することなく読み進むことができるだろう。

C++知識のブートストラップを意識した入門書の執筆はなかなかに難しかった。ある機能Xを教えたいが、そのためには機能Yを知っていなければならず、機能Yを理解するためには機能Zの理解が必要といった具合に、C++の機能の依存関係の解決をしなければならなかったからだ。著者自身も苦しい思いをしながらできるだけ今までに説明した知識のみを使って次の知識を教えるように書き進めていった結果、意外な再発見をした。ポインターを教えた後はC++のほとんどの機能を教えることに苦労しなくなったのだ。けっきょくC++ではいまだにポインターの機能はさまざまな機能の土台になっているのだろう。


本書の執筆時点でC++は現在、C++20の規格制定に向けて大詰めを迎えている。C++20では`#include`に変わるモジュール、軽量な実行媒体であるコルーチン、高級なassert機能としてのコントラクトに加え、とうとうコンセプトが入る。ライブラリとしてもコンセプトを活用したレンジ、`span`、`flat_map`などさまざまなライブラリが追加される。その詳細は、次に本を出す機会があるならば『江添亮の詳説C++17』と似たようなC++20の参考書を書くことになるだろう。C++はまだまだ時代に合わせて進化する言語だ。


本書の執筆はGitHub上で公開した状態で行われた。

<https://github.com/EzoeRyou/cpp-intro>

本書のライセンスはGPLv3である。ただし、本書の著者近影はGPLv3ではなく撮影者が著作権を保持している。


本書の著者近影の撮影は、著者の古くからの友人でありプロのカメラマンである三浦大に撮影してもらった。

三浦大のWebサイト: <http://www.masarumiura.jp/>
