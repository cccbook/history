# 電腦史：數學、機器與程式

> -- 以 Python + C 實作這些故事背後的程式

年代 | 標題                          | 說明              | 圖靈獎 | Python+C 實作
-----|-------------------------------|----------------------|------|-----
1900 | [希爾伯特的問題](1900-希爾伯特的問題.md) | 數學證明機械化後能完備嗎？ | | 推理引擎
1930 | [哥德爾的定理](1930-哥德爾的定理.md) | 完備與不完備定理 | | 完備的一階邏輯推理器
1936 | [丘奇的函數](1936-丘奇的函數.md) | λ-Calculus | | Python 重現 λ-Calculus
1937 | [圖靈的機器](1937-圖靈的機器.md) | 圖靈機與有限狀態機 | | 圖靈機 + 有限狀態機
1943 | [電腦的發明](1943-電腦的發明.md) | ENIAC 與早期的電腦 | | 設計簡易 CPU (nand2tetris)
1945 | [馮紐曼的報告](1945-馮紐曼的報告.md) | 馮紐曼架構 Stored Program 與組合語言 | | 組合語言 + 組譯器
1948 | [夏農的資訊理論與編碼](1948-夏農的資訊理論.md) | 資訊熵 / 交叉熵 / KL 散度 | [1968] | 霍夫曼編碼 + 漢明碼
1950 | [早期的程式語言](1950-早期的程式語言.md) | Fortran / COBOL / ... | [1977] [1979] | 運算式編譯器
1955 | [蕭克萊的半導體](1955-蕭克萊的半導體.md) |PNP-NPN-MOS-CMOS 電晶體 / 仙童 + Intel 公司 | | 邏輯閘轉 CMOS
1956 | [喬姆斯基的語法](1956-喬姆斯基的語法.md) | 生成語法 + 喬姆斯基階層 | [1977] [2005] | 語法生成器
1958 | [麥卡錫的LISP語言](1958-麥卡錫的LISP語言.md) | 受 λ-Calculus 啟發的美麗語言 LISP | [1971] | LISP 解譯器
1960 | [Algol語言與編譯技術](1960-Algol語言與編譯技術.md) | 啟發 Pascal/C/....等眾多語言 | [1966] [1972] [1984] [2005] | LISP 編譯器
1961 | [CTSS分時系統與虛擬機](1961-CTSS分時系統與虛擬機.md) | IBM M44+CP-40 | [1990] | VM4 堆疊式虛擬機
1968 | [從Linkabit到高通的無線通訊產業](1968-從Linkabit到高通的無線通訊產業.md) | | | 馬可夫 + 引馬可夫 + 維特比演算法
1969 | [ARPANET與TCPIP網路](1969-ARPANET與TCPIP網路.md) | 封包網路與 Socket 函式庫 | [2004] | Python Socket 程式
1970 | [關聯式資料庫與B-Tree](1970-關聯式資料庫與B-Tree.md) | E.F.Codd 的關聯式代數 與 System R | [1981] [1998] [2013] [2014] | B-Tree (C) + Sqlite 範例
1969 | [UNIX作業系統](1969-UNIX作業系統.md) | Multics 失敗後的小而美系統 | [1983] | mini-riscv-os / xv6 作業系統
1972 | [C語言的發明與重寫UNIX](1972-C語言的發明與重寫UNIX.md) | 從 1972 年用到現在，歷久不衰的 C 和 UNIX | [1983] | C4 編譯器
1972 | [全錄PARC研究中心的 Alto 視窗電腦](1972-全錄PARC研究中心的Alto視窗電腦.md) | 影印機公司成為視窗電腦先驅 | [1992] [2009] [2022] | TkInter 視窗介面
1972 | [物件導向與Smalltalk語言](1972-物件導向與Smalltalk語言.md) | 艾倫、凱 在 PARC 參與視窗電腦研發的成果 | [2003] | Python 的物件導向
1973 | [類比電路模擬軟體SPICE](1973-類比電路模擬軟體SPICE.md) | 柏克萊大學參考 BIAS, SLIC, TIME, CANCER 等軟體做出來的 | | Python Spice 
1975 | [RISC處理器與管線技術](1975-RISC處理器與管線技術.md) | IBM 801 + Power / Berkley RISC  | [1987] [2017] | Verilog 管線處理器專案
1976 | [庫克與NP-Complete](1976-庫克與NP-Complete.md) | 非確定型圖靈機 / P 是否等於 NP 呢？ | [1976] [1982] [1985] | 將 SAT 化約為整數規劃
1976 | [賈伯斯、蘋果、個人電腦與皮克斯](1976-賈伯斯、蘋果、個人電腦與皮克斯.md) | Apple I/II , Lisa , Macintosh | | 光跡追蹤法
1976 | [RCA與台灣的新竹科學園區](1976-RCA與台灣的新竹科學園區.md) | RCA 技轉晶圓廠，衍生後來的聯電，台積電、聯發科等公司 | | 
1977 | [RSA公鑰私鑰加解密系統](1977-RSA公鑰私鑰加解密系統.md) | 現代密碼學最重要的方法 | [2002] [2015] | RSA 加解密
1980 | [IBM/PC、微軟與視窗系統](1980-IBMPC、微軟與視窗系統.md) | DOS、視窗與 Visual Basic | | BIOS 系統呼叫 / VB 程式範例
1985 | [史托曼的GPL授權與GNU的gcc編譯器](1985-史托曼的GPL授權與GNU的gcc編譯器.md) | 開放原始碼運動的起點 |  | gcc 工具鏈使用範例
1986 | [辛頓與神經網路技術](1986-辛頓與神經網路技術.md) | 反傳遞演算法重新被發明並用在語音辨識上 | [2018] | 梯度下降法 + 反傳遞算法
1986 | [數位電路EDA與Verilog語言](1986-數位電路EDA與Verilog語言.md) | Candence 與 Synopsys 公司為何都是美國的？ | | EDA 電路化簡 + Spice 類比電路模擬
1989 | [從Web、瀏覽器到Yahoo](1989-從Web、瀏覽器到Yahoo.md) | HTTP / URL / HTML / CSS / JavaScript | [2016] | Http Server
1991 | [托瓦茲創建Linux作業系統](1991-托瓦茲創建Linux作業系統.md) | UNIX 在 PC 上的實現 |  | Linux 系統程式
1997 | [爬蟲、搜尋引擎與Google](1995-爬蟲、搜尋引擎與Google.md) | 從分類目錄到搜尋引擎 | | 爬蟲 + 全文檢索
1998 | [楊立昆與CNN卷積神經網路](1998-楊立昆與CNN卷積神經網路.md) | 神經網路在影像辨識的重要突破 | [2018] | CNN 手寫數字辨識
2000 | [Web的泡沫化與重生](2000-Web的泡沫化與重生.md) | YouTube / Web 2.0 / Facebook / ... | | AJAX / FetchAPI 範例 (JS)
2002 | [循環神經網路RNN發明](2002-循環神經網路RNN發明.md) | RNN / LSTM / GRU ， 電腦會學人類寫文章了 ... | [2018] | RNN 語言學習
2005 | [托瓦茲與git版本管理軟體](2005-托瓦茲與git版本管理軟體.md) | 和 CVS/RCS 理念不同的分散式版本管理系統 | | diff 指令實作
2010 | [中本聰與比特幣區塊鏈](2010-中本聰與比特幣區塊鏈.md) | 中本聰是誰？SHA256 猜數字遊戲與挖礦 | | SHA256 + 挖礦程式
2011 | [神經網路深度學習技術的發展](2011-神經網路深度學習技術的發展.md) | 神經網路結合 GPU 技術再度回歸 | | AlexNet 模型
2013 | [Docker容器式虛擬機與雲端技術](2013-Docker容器式虛擬機與雲端技術.md) | Linux 上的快速虛擬環境，演變成 K8S | | 500 行的小型容器實作
2014 | [詞向量技術的提出與發展](2014-詞向量技術的提出與發展.md) | 詞向量 / embed 層 / RNN | | GenSim 詞向量使用
2017 | [深度學習套件蓬勃發展](2017-深度學習套件蓬勃發展.md) | Tensorflow / Pytorch 套件蓬勃發展 / Python 崛起 | | PyTorch 簡介
2018 | [注意力與Transformer模型](2018-注意力與Transformer模型.md) | Attention 注意力機制與 Transformer 模型 | | MinGPT
2022 | [大型語言模型與ChatGPT](2022-大型語言模型與ChatGPT.md) | OpenAI 的 GPT 1/2/3/4/... 模型 | | 呼叫 ChatGPT
20XX | [程式語言的未來](2030-程式語言的未來.md) | AI 會寫程式了？然後呢？ | | Llama2.c

[1966]:圖靈獎/1966.md
[1967]:圖靈獎/1967.md
[1968]:圖靈獎/1968.md
[1969]:圖靈獎/1969.md
[1970]:圖靈獎/1970.md
[1971]:圖靈獎/1971.md
[1972]:圖靈獎/1972.md
[1973]:圖靈獎/1973.md
[1974]:圖靈獎/1974.md
[1975]:圖靈獎/1975.md
[1976]:圖靈獎/1976.md
[1977]:圖靈獎/1977.md
[1978]:圖靈獎/1978.md
[1979]:圖靈獎/1979.md
[1980]:圖靈獎/1980.md
[1981]:圖靈獎/1981.md
[1982]:圖靈獎/1982.md
[1983]:圖靈獎/1983.md
[1984]:圖靈獎/1984.md
[1985]:圖靈獎/1985.md
[1986]:圖靈獎/1986.md
[1987]:圖靈獎/1987.md
[1988]:圖靈獎/1988.md
[1989]:圖靈獎/1989.md
[1990]:圖靈獎/1990.md
[1991]:圖靈獎/1991.md
[1992]:圖靈獎/1992.md
[1993]:圖靈獎/1993.md
[1994]:圖靈獎/1994.md
[1995]:圖靈獎/1995.md
[1996]:圖靈獎/1996.md
[1997]:圖靈獎/1997.md
[1998]:圖靈獎/1998.md
[1999]:圖靈獎/1999.md
[2000]:圖靈獎/2000.md
[2001]:圖靈獎/2001.md
[2002]:圖靈獎/2002.md
[2003]:圖靈獎/2003.md
[2004]:圖靈獎/2004.md
[2005]:圖靈獎/2005.md
[2006]:圖靈獎/2006.md
[2007]:圖靈獎/2007.md
[2008]:圖靈獎/2008.md
[2009]:圖靈獎/2009.md
[2010]:圖靈獎/2010.md
[2011]:圖靈獎/2011.md
[2012]:圖靈獎/2012.md
[2013]:圖靈獎/2013.md
[2014]:圖靈獎/2014.md
[2015]:圖靈獎/2015.md
[2016]:圖靈獎/2016.md
[2017]:圖靈獎/2017.md
[2018]:圖靈獎/2018.md
[2019]:圖靈獎/2019.md
[2020]:圖靈獎/2020.md
[2021]:圖靈獎/2021.md
[2022]:圖靈獎/2022.md

<!--
## 附錄

* [編譯器技術](編譯器技術.md)
    * [從語言到機器](A1-從語言到機器.md)
* [作業系統技術](作業系統技術.md)
* [網路技術](網路技術.md)
* [人工智慧技術](人工智慧技術.md)
* [參考文獻](參考文獻.md)
-->