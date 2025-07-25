---
layout: default
title: ラスコの技術ノート
css: index.css
---
<div class="block">
    <p id="period">[2025-05-30/2025-06-07]</p>
    <h1 id="title">ラスコの技術ノート</h1>
    <p id="explainSite">IT技術に関して学んだことを、備忘のため記載しています。</p>
</div>

<div id="separateLine"></div>

<div id="tableOfContent">
    <h2 class="tableTitle">目次</h2>
    <div class="tableIndex">
        <div class="indexBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="#language">言語</a></h3>
            <ul>
                <li><a href="#Java">Java</a></li>
                <li><a href="#HTML">HTML</a></li>
                <li><a href="#CSS">CSS</a></li>
                <li><a href="#JavaScript">JavaScript</a></li>
                <li><a href="#MySQL">MySQL</a></li>
                <li><a href="#Python">Python</a></li>
                <li><a href="#C">C</a></li>
            </ul>
        </div>

        <div class="indexBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="#tool">ツール</a></h3>
            <ul>
                <li><a href="#Eclipse">Eclipse</a></li>
                <li><a href="#VSCode">VSCode</a></li>
                <li><a href="#Git">Git</a></li>
                <li><a href="#Linux">Linux</a></li>
                <li><a href="#Jekyll">Jekyll</a></li>
            </ul>
        </div>

        <div class="indexBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="#CS">CS</a></h3>
            <ul>
                <li><a href="#Web">Web</a></li>
            </ul>
        </div>

        <div class="indexBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="#dev">開発</a></h3>
            <ul>
                <li><a href="">要件定義</a></li>
                <li><a href="">設計</a></li>
                <li><a href="">開発</a></li>
                <li><a href="">テスト</a></li>
                <li><a href="">リリース</a></li>
            </ul>
        </div>

        <div class="indexBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="#others">その他</a></h3>
            <ul>
                <li><a href="">本棚</a></li>
                <li><a href="">自作アプリ</a></li>
                <li><a href="">暗記道場</a></li>
                <li><a href="{{ '//Note/others/hobby/hobby.html' | relative_url}}">趣味ページ</a></li>
            </ul>
        </div>
    </div>
</div>

<div id="separateLine"></div>

<div class="block" id="language">
    <h2 class="tableTitle">言語</h2>
    <div class="tableIndex">
        <div id="Java" class="grammarBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="{{ '/Note/language/Java/Java.html' |relative_url }}">Java</a></h3>
            <ul>
                <li><a href="{{ '/Note/language/Java/Java.html#JavaGrammar' |relative_url }}">文法</a></li>
                <li><a href="{{ '/Note/language/Java/Java.html#Servlet' |relative_url }}">Servlet</a></li>
                <li><a href="{{ '/Note/language/Java/Java.html#JSP' |relative_url }}">JSP</a></li>
            </ul>
        </div>   

        <div id="HTML" class="grammarBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="{{ '/Note/language/HTML/HTML.html' |relative_url }}">HTML</a></h3>
            <ul>
                <li><a href="{{ '/Note/language/HTML/HTML.html#HTMLBasic' |relative_url }}">基本</a></li>
                <li><a href="{{ '/Note/language/HTML/HTML.html#HTMLGrammar' |relative_url }}">文法</a></li>
            </ul>
        </div>

        <div id="CSS" class="grammarBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="{{ '/Note/language/CSS/CSS.html' |relative_url }}">CSS</a></h3>
            <ul>
                <li><a href="{{ '/Note/language/CSS/CSS.html#CSSGrammar' |relative_url }}">文法</a></li>
            </ul>
        </div>

        <div id="JavaScript" class="grammarBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">JavaScript</a></h3>
            <ul>
                <li>文法</li>
            </ul>
        </div>
        
        <div id="MySQL" class="grammarBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">MySQL</a></h3>
            <ul>
                <li>文法</li>
            </ul>
        </div>

        <div id="Python" class="grammarBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">Python</a></h3>
            <ul>
                <li>文法</li>
            </ul>
        </div>

        <div id="C" class="grammarBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">C</a></h3>
            <ul>
                <li>文法</li>
            </ul>
        </div>
    </div>
</div>
    
<div class="block" id="tool">
    <h2 class="tableTitle">ツール</h2>
    <div class="tableIndex">
        <div id="Eclipse" class="toolBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">Eclipse</a></h3>
            <ul>
                <li>文法</li>
            </ul>
        </div>

        <div id="VSCode" class="toolBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="{{ '/Note/tool/VSCode/VSCode.html' |relative_url }}">VSCode</a></h3>
            <ul>
                <li>文法</li>
                <li><a href="{{ '/Note/tool/VSCode/VSCode.html#VSCodeFunction' |relative_url }}">機能</a></li>
            </ul>
        </div>

        <div id="Git" class="toolBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">Git</a></h3>
            <ul>
                <li>文法</li>
            </ul>
        </div>

        <div id="Linux" class="toolBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">Linux</a></h3>
            <ul>
                <li>文法</li>
            </ul>
        </div>

        <div id="Jekyll" class="toolBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="{{ '/Note/tool/Jekyll/Jekyll.html' |relative_url }}">Jekyll</a></h3>
            <ul>
                <li><a href="{{ '/Note/tool/Jekyll/Jekyll.html#JekyllBasic' |relative_url }}">基本</a></li>
                <li><a href="{{ '/Note/tool/Jekyll/Jekyll.html#JekyllFeature' |relative_url }}">仕様</a></li>
            </ul>
        </div>
    </div>
</div>

<div class="block" id="CS">
    <h2 class="tableTitle">Computer Science</h2>
    <div class="tableIndex">
        <div id="Web" class="csBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="{{ '/Note/CS/Web/Web.html' |relative_url }}">Web</a></h3>
            <ul>
                <li><a href="{{ '/Note/CS/Web/Web.html#WebBasic' |relative_url }}">基本</a></li>
            </ul>
        </div>

    </div>
</div>

<div class="block" id="dev">
    <h2 class="tableTitle">開発</h2>
    <div class="tableIndex">
        <div id="development" class="devBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">要件定義</a></h3>
            <ul>
                <li>基本</li>
            </ul>
        </div>

        <div id="development" class="devBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">設計</a></h3>
            <ul>
                <li>基本</li>
            </ul>
        </div>

        <div id="development" class="devBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">開発</a></h3>
            <ul>
                <li>基本</li>
            </ul>
        </div>

        <div id="development" class="devBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">テスト</a></h3>
            <ul>
                <li>基本</li>
            </ul>
        </div>

        <div id="development" class="devBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">リリース</a></h3>
            <ul>
                <li>基本</li>
            </ul>
        </div>
    </div>
</div>

<div class="block" id="others">
    <h2 class="tableTitle">その他</h2>
    <div class="tableIndex">
        <div id="" class="othersBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">本棚</a></h3>
            <ul>
                <li><a href="{{ '/Note/others/bookshelf/bookshelf.html' |relative_url }}">参考図書</a></li>
            </ul>
        </div>

        <div id="" class="othersBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="">自作アプリ</a></h3>
            <ul>
                <li></li>
            </ul>
        </div>

        <div id="" class="othersBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="{{ '/workspace/test/test.html' |relative_url }}">暗記道場</a></h3>
            <ul>
                <li></li>
            </ul>
        </div>

        <div id="" class="othersBlock indexMiniBlock">
            <h3 class="indexTitle"><a href="{{ '/Note/others/hobby/hobby.html' | relative_url}}">趣味ページ</a></h3>
            <ul>
                <li><a href="{{ '' |relative_url }}">MyScene</a></li>
            </ul>
        </div>
    </div>
</div>
<div id="separateLine"></div>

<script src="{{ '/assets/js/index.js' |relative_url }}"></script>