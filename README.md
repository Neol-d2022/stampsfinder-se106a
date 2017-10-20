# stampsfinder-se106a

## **Build Status**
- [![Build Status](https://travis-ci.org/Neol-d2022/stampsfinder-se106a.svg?branch=develop-travis)](https://travis-ci.org/Neol-d2022/stampsfinder-se106a)

## `S.sumUpStamps`
- 給定一組郵票，以及使用過的郵票，計算出總和
- 例如：`[1, 2, 3, 5, 10], [0, 0, 1, 2, 4]`
- 第一參數表示一組郵票有 1元 2元 3元 5元 10元
- 第二參數表示使用的郵票索引值
- 使用第一種面額的郵票(索引值：0)兩次、使用第二種面額的郵票(索引值：1)一次、使用第三種面額的郵票(索引值：2)一次、使用第五種面額的郵票(索引值：4)一次
- 輸出應該是17 (1 + 1 + 2 + 3 + 10)

## `S.initIA`
- 給定一組郵票，及一個目標值，利用最少的郵票，達到總合等於或大於目標值
- 例如：`[1, 2, 3, 5], 23`
- 一組郵票有 1元 2元 3元 5元
- 目標值為23
- 輸出應該是5張5元郵票
