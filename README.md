## 概要
ft_printfは、C言語の標準ライブラリ関数であるprintf()の機能を再現するプロジェクトです。  
このプロジェクトは、42東京のカリキュラムの一部であり、学生が可変長引数の取り扱いとフォーマット文字列の解析方法を学ぶことを目的としています。

## プロジェクトの目的

このプロジェクトの主な目的は以下の通りです: 
- 可変長引数を受け取る関数の実装方法を理解する
- フォーマット文字列の解析方法を学ぶ
- 文字列の出力を柔軟にカスタマイズできる関数を作成する

このプロジェクトを通して、以下のスキルを身につけることができます: 
- 可変長引数の扱い方
- フォーマット文字列の仕様理解
- 文字列操作とメモリ管理

## 仕様

ft_printf関数は、以下の仕様を満たす必要があります:
- 第1引数にフォーマット文字列を受け取り、後続の引数をフォーマットに従って出力する
- 右記の変換指定子に対応する： %c, %s, %p, %d, %i, %u, %x, %X, %%
- 返り値として、出力した文字数を返す
- エラー時には負の値を返す

## 使用方法
1. リポジトリをクローン: ```git clone https://github.com/ANS0025/42_ft_printf.git```
2. プロジェクトディレクトリに移動: ```cd 42_ft_printf```
3. コンパイル: ```make```
