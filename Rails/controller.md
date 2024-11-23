#### before_action: set_*を使うか否か
賛否あるが、暗黙的にインスタンス変数の初期化と代入という重大な副作用が暗黙的に行なわれていることが問題。
Rails の controller におけるインスタンス変数は view で使う変数、すなわちレスポンスとして送り返すために必要なものが入っている。
インスタンス変数が暗黙的に代入されると、その action がどういうことに関心があるのかがパッと見ではわからない。
ref：https://osa.hatenablog.com/entry/good-bye-before-action-setter
