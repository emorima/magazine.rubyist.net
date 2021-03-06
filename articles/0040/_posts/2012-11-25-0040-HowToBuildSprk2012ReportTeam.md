---
layout: post
title: レポートチーム史上最大の作戦
short_title: レポートチーム史上最大の作戦
tags: 0040 HowToBuildSprk2012ReportTeam
---
{% include base.html %}


書いた人 : 前鼻毅

## はじめに

この記事では札幌 Ruby 会議の運営チームの中にある、 KaigiFreaks という特別編成チーム、とくにその中にあるレポート班の活動について紹介します。

日本 Ruby 会議の活動の中で、映像の配信やネットワークの敷設・提供、そして Kaigi の記録を文字に残すということを行う人達がいました。また海外の RubyConf では同じように、映像の配信やネットワークの管理を行う ConFreaks というチームがありました。その ConFreaks、Conference Freaks という名前から、映像配信・ネットワーク提供・レポートを行う人々に日本 Ruby 会議で名前がつけられたのが KaigiFreaks です。この KaigiFreaks という名前がはじめて登場したのは 2009 年の日本 Ruby 会議です。KaigiFreaks は役割によって二班にわかれています。映像の配信やネットワークの敷設、会場 WiFi の提供を行う配信班。そして、会議の様子を文字で書き起し、レポートとして発信するレポート班です。

この記事ではふたつのテーマについてお伝えしたいと考えています。ひとつは、普段あまり表にでることのないレポートチームが、どのように活動を行なっているか紹介すること。もうひとつは、今回のレポートチームが、札幌 Ruby 会議 2012 でどのようなことを行なったかという記録を残すことです。

今回紹介する札幌 Ruby 会議 2012 のレポートチームは、最終的には 11 人という史上最大のチーム体制で Kaigi へ臨みました。大人数での利点もあれば、人数が増えることによって難しくなることもありました。この記事が、これから大規模カンファレンスの速報レポートを書く方々の参考になれば幸いです。

## レポートチームの目的

KaigiFreaks の配信班とレポート班の大きな目的は、会場に来ることができない人にも Kaigi の雰囲気や内容を伝えることです。レポートチームの主な活動はその名の通りレポート、記事を作ることです。記事をつくるということはセッションの内容や会場の反応を元に、ポイントを拾って要約をすることであり、読む人にとっては動画をまるごとみるより短い時間でセッションの概要や雰囲気を知ることができます。記事を記録することにより、あとから見返すこともできますし、多くの人に読んでもらうことができます。また、検索等でキーワードを拾い、そこから技術や人にたどり着くポインタにもなることができます。

隠れた効果として、レポートを書く人が活動を通じて学べることが多いということがあります。レポートを書くということは、スピーカーの背景や言及する技術についての知識が必要です。当然レポートを書く前準備をしてからセッションに臨むので、前提知識なしで聞くよりも楽しく、内容を把握して聞くことができます。また「文章を書く」ということについても鍛えられます。

このように大きな目的として伝えること、記録すること。隠れた効果としてレポートチームの経験値となることがあげられます。

## 背景

2008 年から 2011 年までの 4 年間、技術評論社さんのサイトに日本 Ruby 会議のリアルタイム、速報レポートが掲載されました。また日本 Ruby 会議の地域開催である地域 Ruby 会議では、「るびま」にその報告をあげることが慣習となっていました。御存知の通り、 2012 年は日本 Ruby 会議は開催されませんでした。一方、札幌 Ruby 会議が日本 Ruby 会議とおなじ 3 日間という会期で開催することが決まりました。

今回のレポートチームは、はじめは 5 人からはじまりました。札幌で大きな地域 RubyKaigi が開催されることが決まった当初は、るびまへの会議開催レポートと Kaigi の事前特集記事の掲載のふたつがメインのミッションでした。

しかし「速報レポートをやらないのか」という話があがり、札幌 Ruby 会議 2012 の実行委員長である、しまださんに声がかかりました。そこから「るびま」だけではなく、速報レポートを行うことや、当初 1 トラックの予定だったセッションが 2 トラックになったこと[^1]、メンバーの経験が浅く体制として不安があったことなどがあり、徐々に規模を拡大しながらチームを形成していくことになりました。

## 準備期間

札幌 Ruby 会議の実行委員 KickOff は 2 月に開催されました、ここから会期の 10 月まで約 7 ヶ月間、 Kaigi をつつがなく行うために、実行委員は日夜動いていく事になりました。レポートチームのメンバーはこの KickOff 時に @sandinist、@h_hiro_、@yuskeuzuki、@ayako119、@tadsan の 5 人が任命され、その任につくことになりました。

はじめの課題はふたつあり、ひとつはメンバーの経験の少なさ、もうひとつは技術評論社さんの速報レポートをやるかどうか決めないといけないことでした。速報レポートはその場で、早く、仕上げなければいけない、というその特性上難易度が高いです。チームリーダーである僕は札幌 Ruby 会議 03 のるびまレポートの経験がありましたが、他のメンバーはレポートを書いたことがほとんどありませんでした。特に速報レポートの経験がある人はひとりもいませんでした。

速報レポートを行うかどうかを決めるために、まずは過去の日本 Ruby 会議ではレポートをどのように書いたのかということを学ぶために、[過去の日本 Ruby 会議の記事](http://gihyo.jp/tagList/RubyKaigi)や、[るびまの特集]({{base}}{% post_url articles/0037/2012-02-05-0037-MakingOfRubyKaigi04 %})、[過去の RubyKaigi でレポート班だった @june29 さんのブログ](http://june29.jp/2012/03/07/rapid-reporting/)などを見返すと共に、速報レポートをやらないか、と声をあげてくださった @oshow さんに話を聴くために、 3 月に渋谷で会談を開きました。

そこで聞いた内容を基本として、レポートチームの運営方法を決めて進めて行きました。Web 等から得た知識とあわせて、ここでその内容を紹介します。

### 速報レポート全体

* レポートの書き方については、簡単なルールがある以外は特にチェックなどは行なっていなかった
* 量は過去のレポートを参考に。基調講演のレポートなど長すぎたものもあった
* 公開は最も遅いもので 1 週間後のものもあった。溜まっていくと辛くなる
* 執筆にかかる時間はセッション時間の 2 〜 3 倍程度だが、人やセッションの内容によって大きく異なる
* 速報レポートはエクストリーム・スポーツ
* 2 人体制でひとつのセッションに臨む、ひとりだと辛い時もある
* 録画をすぐに見ることが出来るとうれしいことが多い
* 事前準備、予習大事！
* 主要なところを拾い、適当なところで切り上げ、いつまでもやらない


### レポートチームのインフラ

* レポートチーム内での連絡や議論は Skype で行う。これはオフライン時のログも確認できるためである。ここには技術評論社さんにも参加してもらう。
* レポートチームだけでなく、運営スタッフ全体へ決まった内容を一斉通知するときや、議論の記録として qwik にて行う。技術評論社さんにも連絡が必要な場合には CC にいれてチームリーダが送信する。
* ファイルの共有は Dropbox で行う。実行委員で使っている Dropbox と共用で使用する。


### 夜も眠れない問題

一番の困難は英語セッションのレポートでした。

* 翻訳 IRC はすごく大事
* 事前に英語スライドを入手することができれば備えられる
* 英語セッションを事前に聞いてレポートを書いてみる


これらの情報をもとにして、連絡チャネルの構築や不安なところの対策を打ちながらチームメイキングを進めて行きました。4 月に技術評論社さんに「速報レポートを行う」と回答するときには、サブリーダーとして @niku_name 、札幌 Ruby 会議レポートの経験があるメンバー @onodes を加え、 7 人という体制になっていました。

## レポートチームキックオフ！

7 月中旬にチーム体制を確定するキックオフの開催を計画していました。これは 8 月後半に公開予定の事前特集号に向けて、なかなか全員あつまることが難しいチームメンバーを集め、チームとしてスタートを切る意味がありました。

キックオフまでの間に、 5 月と 6 月の 2 度、もっとも不安のある英語セッションの練習を行ったり、 i18n チームと IRC でのリアルタイム翻訳についての打合せなどを行いながら徐々に会期へ向かっていきました。影響が大きかった出来事は、 5 月の終わりに運営スタッフのみんなでプレゼンテーション選考を行った結果、前述した通り、当初 1 トラック予定だったセッションが 2 トラック並行になったことでした。非常に多くの方から、聞いてみたいと思わされるプレゼンテーションの応募があり、興味深いセッションを数多く持つことができるのはとても価値があることです。ただし、セッションが増えるということは、当然レポートを書く対象も増えるということです。札幌で活躍している Rubyist である @volpe_hd28v をさらにメンバーに迎えて 8 人体制となり、 1 トラックであればある程度余裕をもって回せる、辛くならない体制で臨めると考えていましたが、余裕をもってすべてのセッションを行うのは難しくなりました。

7 月頭に東京にて技術評論社さんと打合せを行い、全セッションのレポートをやることは目標にせず、エクストリーム・スポーツにならないよう、担当範囲を限定することの合意をしました。また、当日の役割分担、記事の公開方法について話しました。ここで事前特集を gihyo.jp に掲載することも決定し、全体の進め方とおおまかな作業をだし、ようやく当日の姿が実感を持って見えて来ました。やはり顔合わせは大切で、ここで顔合わせを行なっていなければ Skype やメールでのやりとりなども違ったものになったのではないかと思います。

セッション数の増加対応もあり、不安な状況だということを聞いて、東京から @hokkai7go がレポートチームに 参加することを申し出てくれました。更に当日スタッフに応募してきた中から 2 名、 @onjiro_mohyahya と @shuji_w6e をチームに迎え、キックオフ前に 11人 という史上最大規模のレポートチームが編成されました。

体制を検討するなかで、経験不足を補うために記事を書くバディ (ペア) とは別にチェックを行う役割を置くことを決め、チェックを行うのは僕とにくさん、執筆のバディは 5 ペア (ひとつは僕がサブ担当として入る計算) という編成を決め、各バディがだいたい 1 時間担当したら、 2 時間以上は休みが入るように担当を割り振りました (30 分セッション x2 をバディのそれぞれがメインとサブを入れ替えて担当、次の担当まで 2 時間あける、など) 。全セッション網羅はせず、余裕をもって 9 割近くのセッションをレポートする計画をたてることができました。

そして、キックオフでは東京と Skype で接続し、各バディの顔あわせと担当の確認を行いました。事前特集の割り振りも決定し、全 4 回の公開予定日の 10 日前を締め切りと設定しました。進捗は PivotalTracker で管理を行い、並行してスライドの事前提出のお願いや、当日までの事前準備について再確認も行いました。細かい部分で、抜け漏れなどもありましたが、メンバーから指摘があがるなどもあって、事前特集号に向けてしっかりと舵を切ることが出来ました。多くの意見を出してくれた @shuji_w6e と素敵なサポートをくれた @niku_name に特に感謝です。

## 事前特集号

事前特集号は札幌 Ruby 会議の参加者向けメーリングリストからはじまり、日本 Ruby 会議でも 2010 年から「るびま」にて事前特集が組まれるようになりました。全 4 回の事前特集号は 8 月 21 日の第 1 回公開から、 1 週間おきに全体と基調講演、セッション 1 日目、 2 日目、 3 日目と続けて公開していきました。

チーム内では公開の 10 日前に記事を仕上げる、と早めの期日指定を行っており、技術評論社さんへの提出は公開の前日朝までという取り決めで進めていきました。チームメンバーは書き上げた記事を Dropbox へ置き、僕がとりまとめて技術評論社さんへメールするというやり方でレポートを提出していました。かなり余裕を持ったスケジュールでしたが、なかなか執筆の時間がとれない方もおり、早い人、遅い人のバラつきはどうしても起きていました。大人数の強みを活かして、最終的には余裕がある人が引き取るなどの調整ができたのはよいことでした。

第 4 回目の事前特集提出前に会期へ向けて、 9 月 8 日に最後のチームミーティングを行いました。そこでは、どのようなところが修正するポイントなのか、全員の認識をあわせることに重点を置いて、 4 回目の記事を全員でチェックをしました。会期の動きや、前日までにやることも確認しあい、レポートチームのしおりとして時間割やポイントをまとめた用紙をつくることなどを決めて、いよいよ本番へ向かいます。並行して事前にスライド提出のお願いをスピーカー向けにさせていただきました。案内をしてくれた @h_hiro_ と、忙しい中ご協力いただいたスピーカーのみなさまにこの場をかりて御礼申し上げます。

文章の中身については基本的な決まりごとに沿っていない文もあり、チェック担当が修正を行なって提出していましたが、チームへのフィードバックがうまく行えず、似たような修正を繰り返し行うこともありました。対策として、途中から技術評論社さんの校正結果をもらったり、 git でバージョン管理を行い、差分を見えやすくするなどを行いました。どこかに中央レポジトリを置くわけではなく、 Dropbox 上のファイルを git 管理にいれるという、乱暴なやり方だったので同時編集は行えませんが、ファイル単位に分けて執筆していたため大きな問題にはなりませんでした。

回を重ねるごとに文章を書くことに慣れ、修正箇所は減っていき完成度も上がっていきました。文章のバラつきについては上記の対策だけでは、なかなか改善せず、やはりある程度起きていました。もちろん違いがあること全てが悪いことではなく、技術評論社さんに校正されるパターンなどは改善できるよう、うまく共有したいと考えていました。

このような進め方をしていた事前特集はいつの間にか、よくも悪くもかなりの量になっていたと思います。Twitter やセッションの中で言及していただいたのは、とても励みになりました。感謝です！

事前特集の活動は、事前特集の記事を書くと同時に当日レポートの予習にもなります。当日レポートの事前準備はセッションの内容を確認して、そこで言及される技術について知ること、スピーカーについて知ることがあります。過去のスライド、ブログ、GitHub や Web 上のインタビュー記事をみたり、著書にはどのようなものがあるかを調べて把握しておきます。また、今回は厳密には行わず、各人任せにしていたのですが、予めスピーカーの紹介やセッション概要をまとめて、レポートのテンプレートを作成しておくとよいのでは、という話もありました。厳密にやらなかったのは、あまり定型化してしまうと、画一的になってスピーカーごとの表現の違いが失われてしまったり、当日の雰囲気を伝えるという意味で弱くなってしまうかもしれない、ということがありました。バランスが難しいですが、ある程度の枠をつくっておいて、穴埋めする状態にしておくと公開までの時間は短く出来るかもしれません。

## 当日レポート

前日会場設営を行い、レポートチームの席を確認。いよいよ長くて短い、札幌 Ruby 会議 2012 がはじまります。

9 月 14 日、初日の朝に技術評論社の高橋さんを迎え、チームメンバー全員で説明を受け、予定の確認をします。
@onjiro_mohyahya 作のレポートチームのしおりも全員に配って、準備万端です。前日が誕生日だった @shuji_w6e へのサプライズプレゼントを渡して、 12 人で円陣 (！) を組んで Kaigi がはじまりました。

作業予定だった部屋のネットワークが繋がらず、部屋を変えるということもありましたが、ネットワーク班の @darashi に助けて貰って作業場所に快適なネットワークを確保。また、配信班の @suzuki さんと連携をして、随時動画を回収します。配信班、ネットワーク班には会期を通じてずっとお世話になりました、本当にありがとうございます！

作業としては、大きな混乱もなく執筆を進めることが出来ました。しかし、ある程度余裕のある人員とスケジュールを揃えることができたと考えていましたが、初日のセッション終了時点では、レポートをひとつも公開することができませんでした。執筆が終わったら、 2 人一組の執筆バディ内でレポートの確認を行い、その後別バディの第 3 者にもレビューしてもらってから、僕やにくさんのチェックに回そうという計画でしたが、思った以上に初めてのレポートには時間がかかるということを痛感し、第 3 者のレビューは廃することにし、ホテル組は宿でもレポート業を行なっていました。

2 日目の朝会で状況を確認し、今の状況は速報レポートとしてはよくない状況である、という意識共有を行いました。事前にもっと各人が準備出来たのではという意見もあがっていましたが、文章を書くということに慣れている人と、そうではない人では速報レポートは特に差が顕著にでるというのが僕の感想です。2 日目からは会場の色々な部屋を使うことができるようになったのもあり、メンバーは色々な場所で作業を行なっていました。僕は 2 日目以降は、ほぼレポート部屋に篭ってチェック、校正を行なっていました。

だんだんとみんなが作業に慣れ、レポートを早く出せるようになり、公開時に Twitter での案内を出したり、 IRC から指摘を受けて反映するなど、うまくまわるようになっていきました。メンバーも独自にスライドを回収するなどして、積極的に動いて執筆をやりやすくしてくれました。特に @ayako119 には感謝です！

3 日目になると、 2 日目の夜に懇親会、 2 次会があったということもあり、大分疲れが溜まっていました。朝、会場の前でスタッフ全員で朝会をおこなってから、チームの朝会を行いました。疲れはありましたが、みんなの顔つきが初日よりも頼もしくなっているように感じました。

レポートチーム全員 3 日間で多くのことを学ぶことが出来たと思います。3 日目の締め時点で全 43 セッションのうち、半分以上を公開し、計画時には Nice to have (できたらやる) としていた 3 セッション以外はすべて 2 日程度で公開出来るという見通しで会期は終了しました。

会期後 1 日で残り 10 セッション、 2 日目で残り 6 セッション、 3 日目から Nice to have セッションにも着手。6 日目夜時点で残り 1 つとなり、担当メンバーと連絡がつかなかったため引き取って執筆、と最後までバタバタし、リミットの 1 週間を超えてしまいましたが、なんとかやり切ることができました。レポート本文は途中で動画へのリンクを付加したり、 Nice to have をやりきって全セッションを執筆、掲載することができたなど、よい仕上がりにすることが出来たと思います。

レポート執筆では IRC 翻訳に助けられました。i18n チーム、会場にて翻訳を行なってくれた有志の方々に感謝いたします。

## ふりかえり

今回のレポートチームでは、すごい人達がそれぞれ独立してレポートを仕上げていく、というスタイルではなく、チェック体制を作り、一定の品質を保つことに力を使ったという点がこれまでのレポート執筆と大きく異なる点だと思います。チームが大きくなるとコストがかかる、単純に人数を集めても早く出来ない (妊婦を 10 人集めても1ヶ月で子供は生まれない) というのはプログラムだけではないという実感がありました。

はじめての人が多かったレポートチームで、苦労をしたメンバーもいると思います。ふりかえってみると、良い物にしたいという思いからか、気がつけば文章がどんどん長くなり、速報レポートというには書き過ぎになっていたのは僕の反省点です。動画がすぐに見られるというのは、物凄く助けになる反面、「手間をいくらでもかけることができてしまった」という側面があったのも学びでした。当日その場では不安な点のみに絞る、後日確認するのに活かすなど、うまく使えば公開を早く行えたのではないかと思います。

この執筆を通して、 11 人がレポートチームを経験し、事前に情報収集をして、レポートを書いて、チェックして、すべてのセッションを公開することが出来たのは、つつがなく運営を行うことが出来た札幌 Ruby 会議と同様、大成功でした。このチームの仕事を僕は誇りに思いますし、見返してみると感極まるものがあります。チームのみんな、一緒に戦ってくれた技術評論社の高橋さん、当日スタッフから快くメンバーを移してくれた受付チーム、ずっと気をかけてくれていたしまださん、設楽さん、前田さん、谷口さん、レポート大先輩の @june29 さん、 @kei_s さん。英語セッション対応でたくさん相談させてもらったぬまたさんと母、事前特集の校正を手伝ってくれたいまづさん、記事を読んで反応や指摘をくれた皆様、支えてくれたすべての人にあらためて感謝をしたいと思います。ありがとう。

もしも次にレポートを書く機会があるとしたら、今回とは逆の方向で手間をかけ過ぎない、ゆるーい品質でのレポートを書いて、いい意味でこれまでのレポートを裏切った例を作りたいなぁと思います。

長い文章を最後まで読んでいただき、ありがとうございます。速報レポートは gihyo.jp さんの [Sapporo RubyKaigi 2012 スペシャルレポート](http://gihyo.jp/news/report/01/sapporo-rubykaigi2012)に掲載されています。

## レポート班からひとこと

@sandinist
: この記事が僕のふりかえりです。

@niku_name
: 振り返ると、色々な文脈の人達が、何とか同じ方向を向こうと苦労しながらやってきて、最終的に目標を達成できたチームだったのだなあと思いました。よくぞまとまろうとしてくれて、よくぞまとめてくれました。ありがとう。

@onodes
: 札幌 Ruby 会議には初回から関わらせてもらってます。今回は 2 度目のエクストリームスポーツ (レポートチーム) をさせてもらいました。初めて一緒に作業する方もいたり、英語に苦労したりと刺激的な会議 &amp; レポートでした！　レポートチームの皆さん本当にありがとうございました！　お疲れ様です！ :D

@h_hiro_
: 2 年前の札幌 Ruby 会議 03 における「Matz の目前に座ってタイムキーパーをする」という仕事から打ってかわって、今回はレポート班という裏方を務めさせていただきました。裏方とはいえ、非常にやりがいのある仕事が出来たと思いますし、今回も「参加者の皆様に楽しんでいただけるよう取り組む」という姿勢は変わらず取り組めたと思っています。

@volpe_hd28v
: RubyKaigi という大きなイベントに初のスタッフかつレポートチームで参加できてとても光栄でした。実際にやってみると当初考えていたよりもとても大変で、特に 2 日目や 3 日目でレポートが溜まってきた時は辛かったですが、担当したセッションのことをより深く知ることができたりチームで協力して仕事ができたりとても大きな収穫でした。みなさんありがとうございました！

@tadsan
: 最後にいろいろと悔いを残してしまったのですが、これに懲りずにがんばっていきたいと思ってます。次の RubyKaigi でも僕と握手！

@yuskesuzki
: RubyKaigi のレポート班でドキ☆ドキ☆初体験！　レポートは手強かった！　でも読んでお楽しみいただけたなら執筆者冥利に尽きるというもんです。レポートチームの皆様お疲れさまでした。

@ayako119
: 今回のレポートを書くにあたって事前に調べたりしたので、 Ruby 会議を深く知ることが出来た気がします。あと、エクストリームスポーツはやっぱ体力使いますね！　それだけやりがいもあって楽しかったです！　大変だけど濃い経験は貴重です！

@onjiro_mohyahya
: 今回初めてレポートを書き、今まであまり詳しく知らなかった Ruby 界隈の方々を知るまたとない機会を得ることができてとてもいい刺激をもらえました。レポート、またいつかチャレンジしたいなぁ。レポートチームのみなさま、レポート読んで下さったみなさま、お疲れ様でした &amp; ありがとうございました！

@shuji_w6e
: はじめての Ruby 会議はレポートチームでの参加となりました。ブログで書いているエントリーとはまた異なるライブレポートの執筆ということで新鮮な経験でした。また、どこかの Ruby 会議のレポートでお会いしましょうｗ

@hokkai7go
: レポート班経験者をここまで量産できたなんて (しかも札幌で！) すごいと思います。レポートの質とスピードという相反する価値観にぶつかりながらも、よいチームとしてまとまっていく過程がとてもおもしろかったです。経験させてもらってありがとうございました。

## 著者について

前鼻毅 (@sandinist)

[Ruby 札幌](http://ruby-sapporo.org/)、アジャイル札幌、[CLR/H](http://clr-h.jp/) で活動中。Ruby を使って開発するお仕事をしていたが、最近は Objective-C での開発が中心。Ruby Ruined My Life と感じる日々を過ごしている。

----

[^1]: セッションが並行開催されるということは、ある時点のセッションをレポートするのに二倍のレポート班が必要になります
