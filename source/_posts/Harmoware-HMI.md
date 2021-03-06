---
title: Harmoware-HMI
date: 2019-01-24 12:57:32
tags:
---
<img src="/images/harmoware-hmi.png" alt="Harmoware-HMI">
Harmoware-HMIは、自動運転プラットフォーム Autoware を音声や視線インタフェースを通じて利用するためのライブラリです。 
<!-- more -->

Harmoware-HMIでは、マルチモーダル対話シナリオ実現のためMMDAgent(音声対話エージェントソフトウエア）に対し、
対話シナリオを利用できる機能を追加しました。
また、音声や首振り等、視線による検索等の機能を実装し、また自動運転機能として統合動作計画機能に
ついて機能拡張を行い、Autoware で制御されている自動運転車両に対し、実際に音声で操作する実験を行いました。

開発したHarmoware-HMIは、実車に統合され、音声や目線、うなずき等を利用したマルチモーダルHMIにより、
自動運転車の始動、経路変更、視線による物体検索問いかけ等が実現可能であることを確かめるられました。

さらに、運転に伴う外乱や時間的制約等による課題の発見や調整が可能であることが確認できました。
これにより、実車でのインタラクションを検証可能であり、実験により対応時間や走行ノイズ等について課題が
あることなどが明らかになるなど、プラットフォームとしての有用性を確認しています。

ソースコードは Apache2.0 ライセンスで公開されているため、誰でも利用が可能です。
利用事例ができましたら、ぜひお知らせください。

なお、本ソフトウェアは、JST OPERA の支援の下、人間機械協奏技術コンソーシアム (HMHS: Human Machine Harmonization System) (http://hmhs.jp) において開発されたものです。

<a href="https://github.com/Harmoware/Harmoware-HMI"> Harmoware-HMI GitHub リポジトリ </A>
