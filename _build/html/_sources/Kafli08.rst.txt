Hraðafræði
==========

Efnahvörf gerast mishratt, og það getur verið gagnlegt að vita hvaða þættir hraða eða hægja á efnahvarfinu, og stjórna þeim eftir því hvað hentar. *Hraði* efnahvarfs er þá breyting á styrk á tíma, sambærilegt og í eðlisfræði er hraði breyting á staðsetningu á tíma.

Ef það er verið að mynda járn(II) jónir úr járn(III) jónum er hægt að skrifa hraðann sem:

.. math::

  \text{hraði} =\frac{\Delta[Fe^{2+}]}{\Delta t}=\frac{-\Delta[Fe^{3+}]}{\Delta t}

.. note::

	:math:`\Delta` er gríski bókstafurinn "Delta" og í efnafræði táknar hann *breytingu*. :math:`\Delta[Fe^{2+}]` er því breyting á styrk járn(II) jóna og er reiknaður sem lokagildi mínus upphafsgildi.

Styrkur járn(III) jóna minnkar eftir því sem líður á efnahvarfið, og :math:`\Delta[Fe^{3+}]` er því neikvæð stærð. Til þess að efnahvarf haldi áfram þarf hraðinn að vera jákvæður, og því er notað mínusmerki fyrir framan breytingu á hvarfefnum. Til að samræma þessar tölur þarf einnig að deila með mólhlutfallsstuðlinum í efnajöfnunni.


.. math::

	aA + bB \rightarrow cC +dD

Fyrir stilltu efnajöfnuna, þar sem litlu bókstafirnir eru mólhlutföllin er hraðinn:

.. math::

	\text{hraði} =-\frac{1}a\frac{\Delta[A]}{\Delta t}=-\frac{1}b\frac{\Delta[B]}{\Delta t}=\frac{1}c\frac{\Delta[C]}{\Delta t}=\frac{1}d\frac{\Delta[D]}{\Delta t}

Til að mæla hraða efnahvarfs er nóg að fylgjast með einu efni, og hægt er að reikna breytingu á styrk hinna efnanna.

.. tip::

 **Vetnisperoxíð er algengt sótthreinsefni fyrir sár, en það brotnar niður samkvæmt efnahvarfinu:**

 .. math::

   2H_2O_2\text{(aq)} \rightarrow 2H_2O\text{(l)} + O_2\text{(g)}

 **Í upphafi (t=0) var styrkur vetnisperoxíðs 0,120 M en eftir 89 sekúndur var styrkurinn 0,035M. Hver er hraði hvarfsins?**

 Hér var fylgst með vetnisperoxíðinu og því fæst:

 .. math::

   \text{hraði}= -\frac{1}{2}\frac{\Delta [H_2O_2]}{\Delta t}=-\frac{1}{2}\frac{(0,035\,\text{M}-0,120\,\text{M})}{(89\,\text{s}-0\,\text{s})}=9,55 \times 10^{-4} \text{M/s}

 Þetta er meðalhraði hvarfsins yfir þennan tíma.

Hraði getur verið breytilegur í gegnum hvarfið, og þetta er því einungis gilt til að finna meðalhraða yfir þann tíma sem var mælt. Til að finna hraðann á hverju augnabliki þyrfti að *diffra* en hraðinn er hægt að skrifa sem :math:`-\frac{1}{a} \frac{d[A]}{dt}`.
Ekki er nauðsynlegt að vera vel að sér í diffri fyrir hraðafræðina, og hún mun einungis koma fram í sönnunum hér, sem eru einungis fyrir áhugasama.

Áhrif styrks hvarfefna á hraða
------------------------------

Hraði hvarfs getur byggst að miklu leyti á styrk ákveðins hvarfefnis, eða ekki neitt. Það fer allt eftir *hvarfgangi* (e. mechanism) hvarfsins, sem lýsir hvernig hvarfið gerist, skref fyrir skref. Þetta er ákvarðað með tilraunum þar sem breytilegt magn hvarfefna er notað. Þá er gagnlegt að setja upp formúlu sem lýsir hraða efnahvarfs.

.. math::

	aA + bB \rightarrow cC +dD

Fyrir þetta efnahvarf væri *hraðalíkanið* (e. rate expression) eftirfarandi:

.. math::

	\text{hraði}=k[A]^{m} [B]^{n}

hér er :math:`k` *hraðafasti* (e. rate constant) hvarfsins og stuðlarnir :math:`m,n` sýna *stig* (e. order) efnahvarfsins m.t.t. hvarfefnisins. Þessar tölur eru ákvarðar með tilraunum og passa skal að :math:`m,n` eru **ekki** endilega tengdir stuðlunum :math:`a,b` en klassísk villa er að rugla þeim saman. Þegar talað erum stig efnahvarfs og ekki tilgreint hvarfefni, er
lagðir saman stuðlarnir :math:`m+n`.

Þegar smíða á hraðalíkan skal hafa öll hvarfefnin, en ef veldisstuðull reynist vera 0 fyrir hvarfefni má taka það úr líkaninu.

Hraðafasti
~~~~~~~~~~

Hraðafastinn er einkennandi fyrir hvert hvarf, en hann breytist þó með *hitastigi*, en almennt gerast hvörf hraðar í heitari aðstæðum. Hraðafastinn er stundum skrifaður sem :math:`k(T)`, en táknar hraðafastann sem fall af hitastigi.

Hraðafastinn hefur mismunandi einingar fyrir mismunandi stig hvarfa. Reglan er sú að hraðinn hefur alltaf eininguna M/s, og eining hraðafastans er ákvörðuð út frá því

Núllta stigs hvarf
------------------

Fyrir *núllta stigs hvörf* er hraðinn *ekki* háður neinu hvarfefni, og helst stöðugur þangað til takmarkandi hvarfefnið er uppurið. Þá er :math:`m=n=0` og hraðalíkanið verður einfaldlega:

.. math::

  \text{hraði}=k

Á grafi liti þá styrkbreyting hvarfefnis svona út:

.. figure:: ./myndir/efnahvorf/zero.svg
  :align: center
  :width: 45%

.. note::

	Algengur ritháttur að nota undirskriftina :math:`_0` eða :math:`_i` fyrir upphafsgildi. Þetta stendur fyrir :math:`t=0` eða "initial". Að sömu leyti er einnig oft notað :math:`_f` fyrir "final" til að tilgreina lokagildi. Notað er undirskriftin :math:`_t` til að tákna gildi fyrir ákveðinn tíma :math:`t`.

Fyrir núllta stigs hvörf er auðvelt að ákvarða hraðafastann, :math:`k`, en hann, margfaldaður við :math:`a` er neikvæð hallatalan á grafinu. Þ.e.

.. math::

	a \cdot k=-\frac{[A]_f-[A]_0}{t_f-t_0}=\frac{[A]_0-[A]_f}{t_f-t_0}

Jafna línunnar á grafinu er:

.. math::

  [A]_t=-akt+ [A]_0

.. tip::

 **Gefið er að eftirfarandi efnahvarf sé núllta stigs.**

 .. math::

	  A -> B + C

 **Upphafsstyrkur A er 0,180 M, og það tekur hvarfið 4 mínútur að klárast við 25°C. Hver er hraðafastinn við 25°C?**

 Hér er hægt að nota báðar jöfnur en notum þá fyrri. Hér er :math:`[A]_0=0,180\text{ M}`, :math:`[A]_f=0 \text{ M}` og :math:`t_f=4 \text{ mín}`, :math:`t_0= 0 \text{ mín}`. Ef gildin eru upphafs- og lokagildi einfaldast jafnan í:

 .. math::

 	k=\frac{[A]_0}{t_f}=\frac{0,180 \text{ M}}{4 \text{mín}}=0,045\text{ M/mín}

 Hérna er hraðafastinn gefinn upp með einingu M/mín, en einnig væri hægt að breyta í M/sek. Enginn regla er á því hvað skal nota en oft er hægt að meta bestu eininguna út frá stærðargráðu fastans.


Fyrsta stigs hvarf
------------------

Hvarf er *fyrsta stigs* (e. first order) þegar hraðinn byggist á styrk hvarfefnis í fyrsta veldi.

.. math::

  aA + bB -> cC

Hraðalíkanið fyrir þetta hvarf væri þá:

.. math::

  \text{hraði}=k[A]^m [B]^n

þar sem :math:`m+n=1`. Oftast nær er önnur talan 0 og hraðalíkanið þá :math:`\text{hraði}=k[A]` eða :math:`\text{hraði}=k[B]`. Í jöfnum hér á eftir var A valið sem hvarfefni sem hraðinn er háður, en sambærilegt gildir fyrir B.

Styrkur sem fall af tíma er ekki lengur línulegur heldur gildir jafnan:

.. math::

  \text{ln}([A]_t)=-a k t +\text{ln}([A]_0)

.. begin-toggle::
  :label: Sönnun
  :starthidden: True

**Ekki þarf að kunna sannanir og er fyrst um sinn einungis fyrir áhugsama**

Fyrir fyrsta stigs hvarf gildir:

.. math::

  \text{hraði} =-\frac{1}a\frac{d[A]}{dt}=k[A]

Þetta er aðgreinanleg diffurjafna sem hægt er að heilda:

.. math::

  \int_{[A]_0}^{[A]_t} \frac{d[A]}{[A]}=\int_{0}^{t} -ak

Með því að heilda báðum megin fæst svo jafnan:

.. math::

  \text{ln}([A]_t)-\text{ln}([A]_0) =-akt


.. end-toggle::


Efnahvarfið hægir þá á sér eftir því sem líður á.

.. figure:: ./myndir/efnahvorf/fyrsta.svg
  :align: center
  :width: 45%

.. tip::

  **Borðsykur, eða súkrósi er tvísykra sem brotnar niður í líkamanum í glúkósa og frúktósa skv. efnajöfnunni:**

  .. math::

    C_{12}H_{22}O_{11} + H_2O \rightarrow C_6H_{12}O_6 + C_6H_{12}O_6

  **Þetta er fyrsta stigs hvarf með hraðafasta** :math:`2,3 \times 10^{-5}\text{ 1/s}` við 15 °C. **Hver er styrkur súkrósalausnar 136 mínútum inn í hvarfið, ef hún hafði upphafsstyrk 0,010 M?**

  Hérna, líkt og í mörgum dæmum er :math:`a=1` og þarf því ekki að hugsa nánar út í það. Þá þarf bara að stinga inn gildunum í jöfnuna fyrir ofan og þá fæst:

  .. math::

    \begin{aligned}
      \text{ln}([C_{12}H_{22}O_{11}] _{t=6 \text{ mín}}) &= - 2,3 \times 10^{-5} \text{ 1/s}\cdot 136\text{ mín}  \cdot \frac{60 \text{ s}}{1 \text{ mín}} + \text{ln}(0,010\text{ M})\\
      &=-4,7929\\
    \end{aligned}

  Til að losna við lografallið er tekið *veldisvísifallið*:

  .. math::

    \begin{aligned}
      {[C_{12}H_{22}O_{11}]}_{t=6 \text{ mín}} &=e^{-4,7929}\\
      &=0.0083 M
    \end{aligned}

Annars stigs hvarf
------------------

Hvarf er *annars stigs* (e. second order) þegar hraðinn byggist á styrk hvarfefna í öðru veldi.

.. math::

  aA + bB -> cC

Hraðalíkanið fyrir þetta hvarf væri þá:

.. math::

  \text{hraði}=k[A]^m [B]^n

þar sem :math:`m+n=2`. Algengustu annars stigs hvarfslíkön eru :math:`k[A]^2`, :math:`k[B]^2` eða :math:`k[A][B]`. Fyrir fyrstu tvö líkönin er hægt að leiða út jöfnuna fyrir styrk:

.. math::

  \frac{1}{[A]_t}=akt + \frac{1}{[A]_0}

Ákvarða stig hvarfefnis
-----------------------

Til að ákvarða stig hvarfefnis í hraðalíkanið, þ.e. stuðlana :math:`m,n`, þarf tilraunir. Þá er blandað saman mismunandi styrk af hvarfefnum og athuga hvernig það hefur áhrif á hraðann.


.. math::

  A+B \rightarrow C

Fyrir þetta efnahvarf væri hraðalíkanið

.. math::

  \text{hraði} = k[A]^m[B]^n

Segjum sem svo að hraðinn er mældur tvisvar og í seinna skiptið er notað tvöfaldan styrk af hvarfefni :math:`A`. Þá er hægt að finna stuðulinn :math:`m` með jöfnunni:

.. math::

  \frac{\text{hraði}(2\times A)}{\text{hraði}(1\times A)}=2^m

Þessi jafna er fyrir þegar tvöfaldað er styrkinn af hvarfefni A. Ef notað er :math:`x` sinnum meiri styrk af hvarfefninu, er jafnan:

.. math::

  \frac{\text{hraði}(x\times A)}{\text{hraði}(1\times A)}=x^m

.. begin-toggle::
    :label: Sönnun
    :starthidden: True

Ef notað er :math:`x` sinnum meira af hvarfefni A er styrkurinn :math:`x[A]`. Hraðalíkanið verður þá:

.. math::

  \require{cancel}

  \begin{aligned}
  \text{hraði}&=k(x[A])^m[B]^n\\
  &=kx^m[A]^m[B]^n
  \end{aligned}

Þetta er hægt að deila í hraðalíkanið sem fæst fyrir upphaflega magnið af hvarfefni A:

.. math::

    \begin{aligned}
    \frac{\text{hraði}(x\times A)}{\text{hraði}(1\times A)}&=\frac{\bcancel{k} x^m\bcancel{[A]^m}\bcancel{[B]^n}}{\bcancel{k}\,\,\,\,\,\,\,\bcancel{[A]^m}\bcancel{[B]^n}}\\
     &=x^m
    \end{aligned}

.. end-toggle::

Þessar jöfnur geta litið flóknar út og því gæti verið auðveldara að skilja þetta í dæmi.

.. tip::

 **Mældur var hraðinn fyrir efnahvarfið með mismunandi styrk hvarfefna**

 .. math::

  	A+ B \rightarrow C

 **Niðurstöðurnar voru settar upp í töflu:**

 .. math::

  	\begin{array}{c|c|c}
    [A]&[B]& \text{hraði} [\text{M/s}]\\
      \hline
    0.100\text{ M}&0.100\text{M}&1,2\times 10^{-4}\\
    0.200\text{ M}&0.100\text{M}&2,4\times 10^{-4}\\
    0.100\text{ M}&0.300\text{M}&10,8\times 10^{-4}\\
    \end{array}

 **Hvert er hraðalíkan hvarfsins? Finndu hraðafastann, sem og stuðlana** :math:`m,n`.

 Almenna hraðalíkan hvarfsins er

 .. math::

   \text{hraði}=k[A]^m[B]^n

 Til að finna :math:`m` er hægt að athuga hvað gerist þegar styrkur A er *tvöfaldaður*. Það sem gerist er að hraðinn *tvöfaldast*. Þá er:

 .. math::

 	2 = 2^m

 Þetta gefur að :math:`m=1`. Athugum nú hvað gerist þegar styrkur A er *þrefaldaður*. Það sem gerist er að hraðinn *nífaldast*. Þá er:

 .. math::

  9= 3^n

 Þetta gefur að :math:`n=2`. Hraðalíkanið er þá orðið:

 .. math::

 	\text{hraði}=k[A][B]^2

 Hvarfið er þá þriðja stigs. Til að finna hraðafastann, er hægt að nota hvert og eitt gildi. Notum það fyrsta og stingum inn gildunum í hraðalíkanið:

 .. math::

  1,2\times 10^{-4} \text{ M/s}= k \cdot 0.100 \text{ M}\cdot (0.200 \text{ M})^2

 Endurritum þetta og þá fæst:

 .. math::

  \begin{aligned}

    k&=\frac{1,2\times 10^{-4} \text{ M/s}}{0.100 \text{ M}\cdot (0.200 \text{ M})^2}\\
     &=0,030 \text{ s}^{-1}\text{ M}^{-2}

  \end{aligned}
