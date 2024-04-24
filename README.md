# item_modifier-set_loot_table
item_modifierの1項目であるset_loot_tableのサンプルになります。

詳しくはブログ記事『[【マイクラ】set_loot_tableで中身を決定する【item_modifier】](https://natsumake.com/item_modifier-set_loot_table/)』を参考にしてください。

<h3>概要</h3>
チェストなどに対して、ルートテーブルを適用させることが出来ます。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

タラを倒すことで、チェストをドロップします。<br>
このチェストは砂漠の村の家のチェスト内容（ルートテーブル）が適用されているため、設置して開封すると砂漠の村の家のチェストと同様の内容になります。

また、以下のitemコマンドを手元にチェストなどのアイテムを格納できるアイテムを持った状態で実行することで、古代都市のルートテーブルを適用させることが可能です。

```copy
/item modify entity @s weapon.mainhand sample:set_loot_table
```
