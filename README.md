# lottery-sort-demo
Employee Lottery Sorting Demo  This project simulates a lottery-based method to determine  employee reward order by gradually drawing lottery numbers.
# 員工抽獎排序模擬

本專案模擬一種透過「樂透號碼抽取」決定員工領獎順序的方式。

目的：
避免一次抽籤決定全部順位，
透過多輪樂透號碼逐步產生排序。

---

初始化

無序區員工：
{AAA, BBB, CCC, DDD, EEE, FFF, GGG}

有序區員工：
{}

樂透可選號碼：
{1 ~ 30}

每位員工簽注：
5 個不重複號碼

主持人抽號規則：

第1次抽出
5 個號碼

若有序區未滿 5 人
每輪加抽
1 個號碼

---

排序規則

1 對中球數多者優先
2 球數相同 → 比號碼大小
3 完全相同 → 現場猜拳
