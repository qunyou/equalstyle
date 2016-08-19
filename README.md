# Equalstyle


----
## 特色說明
* 未定義 wrap 或 container 的寬度，可與 Bootstrap、Material Design 等 css Framework 併用。
* 版面重新分割欄位數，只需要改外層的數字，不需要每個欄位都修改。


例如 bootstrapb 分割四欄：

    .row
        .col-md-3
        .col-md-3
        .col-md-3
        .col-md-3

如果修改為兩欄：

    .row
        .col-md-6
        .col-md-6
        .col-md-6
        .col-md-6

若使用 Equalstyle，分割四欄：

    .eqs4
        .column
        .column
        .column
        .column

如果修改為兩欄：

    .eqs2
        .column
        .column
        .column
        .column

Responsive
> 一般畫面四欄，手機一欄，平板兩欄

    .eqs4.enlarge-xs.enlarge2-sm
        .column
        .column
        .column
        .column

> 不指定分割欄位數，依內容寬度自動靠左對齊

    .eqs
        .column
        .column
        .column
        .column

> 設定欄位間距、與下方欄位的間距，可設定的值值 5、10、15、20、25、30

    .eqs2.gutter_10.bottom_20
        .column
        .column
        .column
        .column

> 一般畫面靠右對齊，手機畫面靠左對齊

    .pull-right-md pull-left-xs

> Bootstrap 的 form-control 寬度 100% 修改為自動寬度

    .form-control.width-auto

----
## Demo
[Equalstyle](http://equalstyle.onepoint.com.tw)