<article>
<div class="l">
<div class="l">
<section>
<div class="ia ib ic id ie">
<ul class="">
<li id="6bd9" class="je jf ih jg b jh ji jj jk jl jm jn jo jp jq jr js jt ju jv gi" data-selectable-paragraph="">Minima node kurulumu&nbsp;<strong class="jg ii">&ccedil;ok basittir&nbsp;</strong>.. telefona bile kurulabilir ama biz telefonunuzu bu node ile meşgul etmenizi&nbsp;<strong class="jg ii">&ouml;nermiyoruz</strong>&nbsp;..</li>
<li id="d3c0" class="je jf ih jg b jh jw jj jx jl jy jn jz jp ka jr js jt ju jv gi" data-selectable-paragraph="">Gereksinimleri &ccedil;ok &ccedil;ok d&uuml;ş&uuml;k g&uuml;nde 1 adet minima token kazanıyorsunuz&hellip; Fiyatı 0.60&ndash;1 dolar arası olması planlanıyor&hellip; Mainnet&nbsp;<strong class="jg ii">eyl&uuml;l</strong>&nbsp;demişlerdi ama uzayacak gibi duruyor..</li>
<li id="9567" class="je jf ih jg b jh jw jj jx jl jy jn jz jp ka jr js jt ju jv gi" data-selectable-paragraph="">Genelde herkes&nbsp;<strong class="jg ii">AWS</strong>&nbsp;&uuml;cretsiz &uuml;yelik a&ccedil;ıyor minimayı oraya kuruyor.. aylardır 1 kuruş &ouml;demedik bizde AWS&rsquo;ye kurmuştuk&hellip;&nbsp;<a class="au kb" href="https://medium.com/@nodeswizard/%C3%B6nemli%CC%87-not-nodeswizard-ekibi-olarak-amazon-aws-yi-sadece-free-sunucu-se%C3%A7ene%C4%9Fi-ile-a%C3%A7man%C4%B1z%C4%B1-ve-58b7465143d8" rel="noopener"><strong class="jg ii">LINK</strong></a></li>
<li id="cf3b" class="je jf ih jg b jh jw jj jx jl jy jn jz jp ka jr js jt ju jv gi" data-selectable-paragraph="">Digital ocean en dandik pakete kurabilirsiniz .. Google cloud ile kurmak isterseniz 9&ndash;10 dolarlık makine&nbsp;<strong class="jg ii">1 gb ram 1 cpu&nbsp;</strong>bile yeterli olacaktır..</li>
<li id="7a8d" class="je jf ih jg b jh jw jj jx jl jy jn jz jp ka jr js jt ju jv gi" data-selectable-paragraph=""><strong class="jg ii">Videoda s&ouml;ylemedim fakat, Contabo da sunucunuz varsa &ouml;rnek veriyorum i&ccedil;inde Stride , Source yada başka kurulu bir node varsa onun yanına da kurabilirsiniz</strong></li>
</ul>
<p id="7f9d" class="pw-post-body-paragraph kc kd ih jg b jh ji ke kf jj jk kg kh jl ki kj kk jn kl km kn jp ko kp kq jr ia gi" data-selectable-paragraph=""><strong class="jg ii">Aşağıdaki kodla kurulum başlatalım</strong></p>
<pre class="kr ks kt ku fz kv bt kw"><span id="24e5" class="gi kx ky ih kz b dn la lb l lc" data-selectable-paragraph="">wget -O minima_setup.sh https://raw.githubusercontent.com/minima-global/Minima/master/scripts/minima_setup.sh &amp;&amp; chmod +x minima_setup.sh &amp;&amp; sudo ./minima_setup.sh -r 9002 -p 9001</span></pre>
<p id="0d1a" class="pw-post-body-paragraph kc kd ih jg b jh ji ke kf jj jk kg kh jl ki kj kk jn kl km kn jp ko kp kq jr ia gi" data-selectable-paragraph=""><strong class="jg ii">Başlattıkdan sonra aşağıdaki siteden &uuml;ye oluyoruz</strong></p>
<div class="ld le fv fx lf lg">
<div class="lh o hh">
<div class="li o db dy eo lj">
<h2 class="bn ii dn bp lk ll lm ln lo lp lq ig gi"><a href="https://incentive.minima.global/account/register?inviteCode=LBR2CRLM">https://incentive.minima.global/account/register?inviteCode=LBR2CRLMIncentive Program</a></h2>
<div class="lr l">
<h3 class="bn b dn bp lk ll lm ln lo lp lq co"><span style="font-size: 14px;">Daha sonra &uuml;ye olduğumuz yerden </span><strong class="jg ii" style="font-size: 14px;">Incentice ID&nbsp;</strong><span style="font-size: 14px;">alıyoruz .. aşağıdaki koddaki&nbsp;</span><strong class="jg ii" style="font-size: 14px;">XXX&nbsp;</strong><span style="font-size: 14px;">olan yere yapıştırıp terminalde giriyoruz.</span></h3>
</div>
</div>
</div>
</div>
<pre class="kr ks kt ku fz kv bt kw"><span id="4509" class="gi kx ky ih kz b dn la lb l lc" data-selectable-paragraph="">curl 127.0.0.1:9002/incentivecash+uid: <strong class="kz ii">XXX</strong></span></pre>
<p id="7b85" class="pw-post-body-paragraph kc kd ih jg b jh ji ke kf jj jk kg kh jl ki kj kk jn kl km kn jp ko kp kq jr ia gi" data-selectable-paragraph="">Daha sonra siteden kontrol ediyoruz log geldiyse olay&nbsp;<strong class="jg ii">bitmiştir..</strong></p>
</div>
</section>
</div>
</div>
</article>
