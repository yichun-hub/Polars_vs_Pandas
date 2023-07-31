# Polars_vs_Pandas  
詳細的介紹放在[Medium](https://medium.com/@fearless_fusion_snake_755/%E5%8F%96%E4%BB%A3pandas-%E5%BC%B7%E5%A4%A7%E7%9A%84%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90%E5%87%BD%E5%BC%8Fpolars-polars-10-%E5%A4%A7%E5%8A%9F%E8%83%BD%E7%B0%A1%E4%BB%8B-b2097ad6685d)   
## Polars 十大功能
1. 創建一個DataFrame Polars.DataFrame()
2. 取得前n筆及後n筆的資料 DataFrame.tail(n) , DataFrame.head(n)
3. 取得某欄(行)資料 DataFrame.select() , DataFrame.get_column(name)
4. 取得某列資料 DataFrame.row(index)
5. 取得特定位置的值 DataFrame.item(row, column)
6. 篩選資料 DataFrame.filter()
7. 新增DataFrame資料 Polars.concat()
8. 計算某欄位各個值的個數 polars.Expr.value_counts()
9. 組成群組及聚合函數 DataFrame.groupby() , GroupBy.agg()
10. 對某欄的值進行計算或處理 DataFrame.apply()
