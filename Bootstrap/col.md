# col
- ## 列を表すクラス
- ## col クラスの間に、1-12 の数字を入れることで、その col がグリッドをどれだけ占めるか決めることができます
- ## col の後に数字を入れない場合は、col の分だけ等分に分割されます。例えば、col クラスが 3 つなら、1 つあたりの col は 4 (12 ÷ 3) の大きさになります。col クラスが 2 つなら、1 つあたりの col は 6 (12 ÷ 2) の大きさになります
- ## 12を超えると最後のcolは次の行になる
```html
<div class="container border border-dark bg-secondary">
        <!-- col-4クラスとbg-primaryクラスを記述してください -->
        <div class="col-4 bg-primary">
            1. col-4
        </div>
         <!-- クラスを使って見本のレイアウトを実現しましょう。 -->
        <div class="col-8 bg-danger">
            2. col-8
        </div>
         <!-- クラスを使って見本のレイアウトを実現しましょう。 -->
        <div class="col-12 bg-green">
            3. col-12
        </div>
</div>
```