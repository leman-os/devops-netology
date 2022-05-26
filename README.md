<ol>
<li class="has-line-data" data-line-start="0" data-line-end="1"></li>
</ol>
<p class="has-line-data" data-line-start="1" data-line-end="5">Ответ:<br>
commit aefead2207ef7e2aa5dc81a34aedf0cad4c32545<br>
Комманда:<br>
git show aefea</p>
<ol start="2">
<li class="has-line-data" data-line-start="5" data-line-end="6"></li>
</ol>
<p class="has-line-data" data-line-start="6" data-line-end="10">Ответ:<br>
tag: v0.12.23<br>
Комманда:<br>
git show 85024d3</p>
<ol start="3">
<li class="has-line-data" data-line-start="10" data-line-end="11"></li>
</ol>
<p class="has-line-data" data-line-start="11" data-line-end="18">Ответ:<br>
2 родителя:<br>
cd7859e05c36c06b56d013b55a252d0bb7e158, 9ea88f22fc6269854151c571162c5bcf958bee2b<br>
Комманды:<br>
git show b8d720<br>
git show 56cd7859e<br>
git show 9ea88f22f</p>
<ol start="4">
<li class="has-line-data" data-line-start="18" data-line-end="19"></li>
</ol>
<p class="has-line-data" data-line-start="19" data-line-end="31">Ответ:<br>
b14b74c4939dcab573326f4e3ee2a62e23e12f89 [Website] vmc provider links<br>
3f235065b9347a758efadc92295b540ee0a5e26e Update <a href="http://CHANGELOG.md">CHANGELOG.md</a><br>
6ae64e247b332925b872447e9ce869657281c2bf registry: Fix panic when server is unreachable<br>
5c619ca1baf2e21a155fcdb4c264cc9e24a2a353 website: Remove links to the getting started guide’s old location<br>
06275647e2b53d97d4f0a19a0fec11f6d69820b5 Update <a href="http://CHANGELOG.md">CHANGELOG.md</a><br>
d5f9411f5108260320064349b757f55c09bc4b80 command: Fix bug when using terraform login on Windows<br>
4b6d06cc5dcb78af637bbb19c198faff37a066ed Update <a href="http://CHANGELOG.md">CHANGELOG.md</a><br>
dd01a35078f040ca984cdd349f18d0b67e486c35 Update <a href="http://CHANGELOG.md">CHANGELOG.md</a><br>
225466bc3e5f35baa5d07197bbc079345b77525e Cleanup after v0.12.23 release<br>
Комманда:<br>
git log v0.12.23…v0.12.24 --pretty=oneline</p>
<ol start="5">
<li class="has-line-data" data-line-start="31" data-line-end="32"></li>
</ol>
<p class="has-line-data" data-line-start="32" data-line-end="39">Ответ:<br>
8c928e835 - создана<br>
5af1e6234 - изменена<br>
Комманды:<br>
git log -S ‘func providerSource’ --oneline<br>
git show 8c928e835<br>
git show 5af1e6234</p>
<ol start="6">
<li class="has-line-data" data-line-start="39" data-line-end="40"></li>
</ol>
<p class="has-line-data" data-line-start="40" data-line-end="49">Ответ:<br>
78b122055<br>
52dbf9483<br>
41ab0aef7<br>
66ebff90c<br>
8364383c3<br>
Комманды:<br>
git grep -n globalPluginDirs<br>
git log -L:‘globalPluginDirs’:‘plugins.go’ -s --pretty=format:&quot;%h&quot;</p>
<ol start="7">
<li class="has-line-data" data-line-start="49" data-line-end="50"></li>
</ol>
<p class="has-line-data" data-line-start="50" data-line-end="55">Ответ:<br>
Martin Atkins<br>
Комманды:<br>
git log -S ‘synchronizedWriters’ --oneline<br>
git show 5ac311e2a</p>
