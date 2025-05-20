# この設計資料の使用許諾事項
この資料は、金沢工業大学先端電子技術応用研究所（以下「当研究所」という）の研究活動により設計・制作された脳磁計関連の周辺機器に関するものです。 </br>
利用にあたっては、下記の趣旨を理解していただくとともに、著作権を含めた資料図書の利用規定の厳守を約束いただきます。

## 設計資料公開の趣旨

当研究所の研究活動により設計・制作された脳磁計関連の周辺機器の設計情報が、外部の研究者や技術者によって再利用が可能となること、また当該設計をアイディアの起点として新たな機器を設計するといった新たな発展の足掛かりとなれるよう、設計情報を希望する全ての組織・個人に **オープンソースハードウエア** として公開するものです。

# 利用規定
> 策定：2024年9月　金沢工業大学　先端電子技術応用研究所

この資料を利用する組織・個人は、下記の規定について承諾したこととみなします。

## 1. 設計資料の保証
> [!NOTE]
> **この公開された設計資料において、明示的または黙示的な保証および責任は一切放棄されます。**

開示した資料をもとに作成された機器に発生する動作不具合や、その機器の不備による損失・損害、また同資料を用いたことにより第三者の所有する知的財産権への侵害の発生やその侵害よる損失・損害など、**本設計資料の使用から何らかの形で生じた直接的、間接的、偶発的、懲罰的、または結果的ないかなる損失・損害について、たとえそのような損害の可能性について知らされていたとしても、当研究所は責任を負いません。**

設計資料の内容の妥当性についてはベストエフォートを基本とし、当該機器の仕様書の規定を満たす動作・性能が実現できると公開時点で判断した資料を開示します。</br> 
これは、ここに開示された資料が規定された動作・性能を満たすこと、および標準規格等への適合性、特許などの知的財産権の非侵害などを保証をするということではありません。



## 2. 設計資料の記述内容
> [!NOTE]
> **この公開された設計資料は全てがあるがままの状態(As-Is)で公開されています。**

設計資料に記述してある内容は当研究所での機器製造に必要十分であると考えられる内容であり、この資料を利用する組織・個人が設計資料に要求する網羅性・完全性とは異なります。

当研究所は利用者の個別の要求に適合した網羅性・完全性に合わせて資料を再作成することは致しません。

## ３. 著作権とライセンス

### 3-1 組織名とロゴ、機器の型式
> [!NOTE]
> **公開された設計資料にある大学名やそれに付随する組織名およびそのロゴ、企業名およびそのロゴ、機器型式の使用は禁止**

資料の作成には、当研究所から派生した企業「（株）イーグル・テクノロジー」が携わっており、資料には同社の社名（日本名・英名）、ロゴ、型式名などが多く使われていることをご承知ください。</br> 
当該社名は研究所名や大学名とともに「名称又は商号」として法的保護の対象であるため、以下の項目について、公開された資料を元に製造された機器や付随する書類等、全ての二次的な制作物・著作物での使用を禁止します：
- 組織名（「金沢工業大学」、「金沢工業大学 先端電子技術応用研究所」等）
- 組織のロゴ
- 企業名（「Eagle Technology, Inc.」、「イーグル・テクノロジー」等）
- 企業ロゴ（「ET」等）
- 機器の型式名

### 3-2 ファームウエアのソースコードおよびHDLのコード
> [!NOTE]
> **公開された設計資料に含まれる、HDLを含むソースコードは「３項 BSDライセンス」で提供します。**

機器に内蔵されるマイクロプロセッサ等の**ファームウエア（プログラム）のソースコートについては、その著作権を当研究所が保持します。** また機器に使われる回路の中で、HDLにより記述された回路設計情報には著作権があると考えております。HDLの記述に著作権が発生するか否かは見解の分かれるところですが、当研究所としてはファームウエアのソースコードと同様と捉え、**HDLの記述によるソースコード類について当研究所に著作権があることを主張します。**

**これらに該当する資料は「３項 BSDライセンス」で提供します。**

> BSD 3-Clause License
>
>Copyright (c) 2024, Applied Electronics Lab / Kanazawa Institute of Technology
>
>Redistribution and use in source and binary forms, with or without
>modification, are permitted provided that the following conditions are met:
>
>1. Redistributions of source code must retain the above copyright notice, this
>   list of conditions and the following disclaimer.
>
>2. Redistributions in binary form must reproduce the above copyright notice,
>   this list of conditions and the following disclaimer in the documentation
>   and/or other materials provided with the distribution.
>
>3. Neither the name of the copyright holder nor the names of its
>   contributors may be used to endorse or promote products derived from
>   this software without specific prior written permission.
>
>THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
>AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
>IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
>DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
>FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
>DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
>SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
>CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
>OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
>OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

当研究所提供のソースコードを改変またはそれに追加して用いる場合、上記ライセンス表示とともに改変の年、改変者を追記するようにしてください。改変者は改変・追加部分について独自の著作権を主張でき、最初に設定されたライセンス（ここでは、「３項　BSDライセンス」）に矛盾しない範囲で新たなライセンスを改変部分に設定することができます。

当研究所提供のソースコードを参照せず、仕様書等と周辺回路図を元にHDLのコードをスクラッチから書きあげるなど、提供されたソースコードそのものを利用しない場合はこのライセンスに拘束されません。

### 3-3 その他文書・図面
> [!NOTE]
> **その他の文書・図面については、[「クリエイティブ・コモンズ・ライセンス　CC-CC0」](https://creativecommons.org/publicdomain/zero/1.0/) （パブリックドメイン）で提供します。**

![cco_icon](https://mirrors.creativecommons.org/presskit/buttons/88x31/png/cc-zero.png)

その他の製造用図書、具体的には仕様書・回路図・パターン図・製造／試験手順書・試験成績書・取り扱い説明書・部品表についてはその記述内容についての著作権は発生しないと考え、当研究所に権利がないことを明確にするためパブリックドメインライセンスで公開します。
CC-CC0での許諾条項については、[こちらのリンク](https://creativecommons.org/publicdomain/zero/1.0/legalcode.en)を参照し内容を必ず確認してください。﻿

**この場合でも3−1で禁止した項目についてはその制限を有効とします。**
同禁止事項を以下に再掲します：

> 以下の項目について、公開された資料を元に製造された機器や付随する書類等、全ての二次的な制作物・著作物での使用を禁止します：
> - 組織名（「金沢工業大学」、「金沢工業大学 先端電子技術応用研究所」等）
> - 組織のロゴ
> - 企業名（「Eagle Technology, Inc.」、「イーグル・テクノロジー」等）
> - 企業ロゴ（「ET」等）
> - 機器の型式名

以上。
