#### saved_change_to_attribute
attribute method の1つ。
オブジェクトの保存前後の属性が取得できる
#### saved_change_to_attribute?
オブジェクトの保存前後の属性が相違するか判定できる
ロギングや after_save のコールバックに使えそう
ref：https://qiita.com/maabow/items/0a5a228fb6c1447877e0#saved_change_to_attribute:~:text=without%20an%20ID)%3A-,saved_change_to_attribute,-%E6%8C%87%E5%AE%9A%E3%81%97%E3%81%9Fattribute

#### sanitize
XSS対策で<script>など指定した文字列からタグを削除できる。
html_safe で文字列のHTMLタグをエスケープせずにレンダリングできるが、XSS対策など考慮事項が多く、sanitize の方がおすすめ
ref：https://qiita.com/kamohicokamo/items/571c58f2d6738a7dfe6a
ref：https://zenn.dev/kanazawa/articles/d7ec7e90041c23
