# Android Support BottomSheet

[![Circle CI](https://circleci.com/gh/eaglesakura/andorid-support-bottomsheet.png?style=badge)](https://circleci.com/gh/eaglesakura/andorid-support-bottomsheet)

[JavaDoc](http://eaglesakura.github.io/maven/doc/andorid-support-bottomsheet/javadoc/)

## 概要

Support Library 23.2で追加されたBottomSheetのカスタマイズ版です。

公式ライブラリではBottomSheetを引っ張りだした時の挙動が使いにくいので、使いやすくなっています。
package名以外の使い方は全て同じです。

## LICENSE

Android Design Libraryのライセンスを引き継ぎます。

## 使用例

### build.gradle

 1. repositoriesブロックにリポジトリURLを追加する
 1. dependenciesブロックに任意バージョンのライブラリを追加する
 	* 現時点では1.0.+系列

<pre>
repositories {
    maven { url "http://eaglesakura.github.io/maven/" }		// add maven repo
    mavenCentral()
}

dependencies {
    compile 'com.eaglesakura:andorid-support-bottomsheet:1.0.+'	// add library
}


</pre>
