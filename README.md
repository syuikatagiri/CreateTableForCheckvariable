# CreateTableForCheckvariable

ソースコード(C#)を解析して、変数名、関数名etc.をカンマ区切りでcsvとして出力する

C#でCSVのデータをリストにコピーする際にマッピングのためにclassを作った。

「CSVの中の見出し列名」と対応する「列名」をコード内に記述して、
その後、「列名」に対応する「変数名」の記述をする必要があり、
列の数に比例して「変数名」が増えるため把握が仕切れなくなると感じた。

一括管理するために作ることにした。

    [Name("仮Name")]
    public string test{get; set; }
    
    一行目が列名
    二行目が列名に対応することになる変数名


