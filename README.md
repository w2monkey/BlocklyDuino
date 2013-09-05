### Welcome to BlocklyDuino.
BlocklyDuino is a web-based visual programming editor for [Arduino](http://www.arduino.cc/).

BlocklyDuino is based on [Blockly](http://code.google.com/p/blockly/), the web-based, graphical programming editor. Provide static type language blocks and code generators for arduino programming.

BlocklyDuino also support [Grove](http://www.seeedstudio.com/wiki/GROVE_System) blocks to easily get started with microcontroller-based experimentation and learning.

[We also have Google+ Page](https://plus.google.com/111979846292233941175).

### ようこそ BlocklyDuino へ

BlocklyDuinoは、ウェブベースの[Arduino](http://www.arduino.cc/)向けのビジュアルプログラミングエディタです。

BlocklyDuinoは、[Blockly](http://code.google.com/p/blockly/)をベースにしていて、ウェブベースで、グラフィカルなプログラミングエディタです。Arduino プログラミングのための、静的な言語ブロックとコードジェネレータを提供します。

BlocklyDuinoは、[Grove](http://www.seeedstudio.com/wiki/GROVE_System)ブロックもサポートし、マイクロコントローラを使用した実験と学習が簡単に始められます。

[Google+ ページもあります。](https://plus.google.com/111979846292233941175)

### Features

* Programming Arduino with visually drag and drop code blocks
* Generate fully compatible arduino source code
* Interacive Arduino board with 10+ predefined Grove sensor blocks
* Load different on-site examples with url parameters

### 特徴

* Arduinoプログラミングがビジュアル的なコードブロックのドラッグ・アンド・ドロップで行えます。
* Arduinoの完全互換ソースコードを生成します。
* インタラクティブなArduinoボードとして、10以上の定義済みのGroveセンサーブロックを使用できます。
* URLパラメータにより、オンサイトの例を参照することができます。


### Demo

BlocklyDuino is a web tool. You can give it a try at
[Web](http://www.gasolin.idv.tw/public/blockly/demos/blocklyduino/index.html) to see the working BlocklyDuino.

You can link directly to examples
* [demo 1](http://www.gasolin.idv.tw/public/blockly/demos/blocklyduino/index.html?url=/public/blockly/demos/blocklyduino/examples/blink.xml)
* [demo 2](http://www.gasolin.idv.tw/public/blockly/demos/blocklyduino/index.html?url=/public/blockly/demos/blocklyduino/examples/servo_potentio.xml)

Or watch the [video demo](http://www.youtube.com/watch?v=_swiyXcUvNY)


BlocklyDuinoは、ウェブツールです。[Web](http://www.gasolin.idv.tw/public/blockly/demos/blocklyduino/index.html)で、実際に動作するBlocklyDuinoを試すことができます。

### デモ

例のダイレクトリンク
* [demo 1](http://www.gasolin.idv.tw/public/blockly/demos/blocklyduino/index.html?url=/public/blockly/demos/blocklyduino/examples/blink.xml)
* [demo 2](http://www.gasolin.idv.tw/public/blockly/demos/blocklyduino/index.html?url=/public/blockly/demos/blocklyduino/examples/servo_potentio.xml)

ビデオデモを見る [video demo](http://www.youtube.com/watch?v=_swiyXcUvNY)

### Run locally on your web browser

If you want to install it locally. Get code from github and open blockly/demos/blocklyduino/index.html in your browser.

The preffered way is to put the BlocklyDuino/web folder into a web server and open the url like localhost/public/blockly/demos/blocklyduino/index.html for use.

### ローカル環境のウェブブラウザで実行する

ローカル環境にインストールしたいなら、ブラウザで、blockly/demos/blocklyduino/index.html をオープンして github からコードを入手できます。

最善の方法は、ローカル環境のウェブサーバに BlocklyDuino/web フォルダを配置して、その url 例えば を localhost/public/blockly/demos/blocklyduino/index.html を開いて使用します。

### Usage (3 Step)

1. Open browser to BlocklyDuino, Drag and Drop blocks to make arduino program. 
2. Select 'Arduino' tab to copy source code to Arduino IDE
3. press 'upload' button to burn the code into arduino

### 利用法（３ステップ）

1. BlocklyDuinoをブラウザで開く、ブロックをドラッグ・アンド・ドロップしてArduinoプログラムを作る。
2. 'Arduino' タブを選択して、ソースコードを全て選択してArduinoIDEにコピーする。
3. ArduinoIDEの 'upload' ボタンを押してArduinoにコードを送る。


### ChangeLog

Check changelog [here](https://github.com/gasolin/BlocklyDuino/blob/master/CHANGELOG.txt)


### 変更履歴

変更履歴の確認 [here](https://github.com/gasolin/BlocklyDuino/blob/master/CHANGELOG.txt)


### Authors and Contributors
Fred Lin (@gasolin) .

Thanks Neil Fraser, Q.Neutron from Blockly http://code.google.com/p/blockly/
Thanks Arduino and Seeeduino guys for Arduino and Grove blocks.

The project is also inspired by arduiblock https://github.com/taweili/ardublock and modkit http://www.modk.it/



### License

Copyright (C) 2012 Fred Lin gasolin+blockly@gmail.com

 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *   http://www.apache.org/licenses/LICENSE-2.0
