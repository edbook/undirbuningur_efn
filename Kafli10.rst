Efnajafnvægi
============

Fram að þessu hefur verið áætlað að efnahvörf gerast einungis í aðra áttina, þ.e. :math:`\require{mhchem}` :math:`\require{cancel}`

.. math::

	\ce{A + B -> C +D} \quad \quad 	\text{hraði}=k[\ce{A}]^m[\ce{B}]^n

Það sem getur einnig gerst er að hvarfið fari í *öfuga átt*

.. math::

  \ce{C + D -> A+ B}

Hraðalíkan fyrir þetta hvarf í hina áttina væri þá:

.. math::

	\text{hraði}=k`[\ce{C}]^k[\ce{D}]^l

Ef hvörfin eru hvorug núllta stigs *eykst* hraðinn á afturábak hvarfinu þegar líður á upprunalega hvarfið, enda eykst styrkur :math:`[\ce{C}]` og :math:`[\ce{D}]`. Að sama leyti *minnkar* hraðinn á upprunalega hvarfinu þar sem :math:`\ce{[A]}` og :math:`\ce{[B]}` minnkar. Þegar þessir tveir hraðar jafnast út,
nær hvarfið *jafnvægi* (e. equilibrium).

Þegar efnahvarf nær jafnvægi má segja að það sé hætt, en það er ekki alveg rétt. Bæði efnahvörfin eru enn í fullu gangi, bara fara jafnhratt. Það *myndast því jafn mikið efni og hvarfast aftur.*

Fyrir þetta efnahvarf væri myndun :math:`\ce{C}` og :math:`\ce{D}` kallað að "efnahvarfið gangi til hægri" og afturábak hvarfið væri að "ganga til vinstri".

Fyrir hvörf þar sem hvarfefnin hvarfast ekki að öllu leyti, og það nær jafnvægi, er notað örvar í báðar áttir í efnajöfnunni. Þ.e. í stað :math:`\ce{->}` er notað :math:`\ce{<=>}` . Hér má athuga að öll hvörf ná jafnvægi, en stundum má nálga að hvarf gangi alveg til hægri, og nota þá venjulega ör.

Jafnvægisfasti
--------------

Hvert hvarf hefur einkennandi *jafnvægisfasta* (e. equilibrium constant) fyrir ákveðið hitastig. Jafnvægisfastinn er táknaður með :math:`K` og er einingarlaus.

.. math::

  \ce{aA +bB+ \dots <=> nN + mM + \dots}

Jafnan fyrir jafnvægisfasta þessa hvarfs væri:

.. math::

  K=\frac{[\ce{N}]^n[\ce M]^m \dots }{[\ce A]^a[\ce B]^b \dots }

Þessi jafna er einnig gjarnan kölluð *jafnvægislíking* til aðgreiningar, og segir til um hlutfall styrks við jafnvægi. Jafnvægisfastinn er tölulega gildið á :math:`K` og er hægt að fletta upp fyrir flest hvörf við algeng hitastig s.s. stofuhita.

.. tip::

 **Á Íslandi stofnaði CRI fyrstu verksmiðju heims sem umbreytir koldíoxíð í útblæstri í nothæft metanól. Þetta er gert samkvæmt efnaformúlunni:**

  .. math::

  	\ce{CO2 + 3H_2 <=> CH_3OH + H_2O}

 **Hver er jafnvægislíking hvarfsins?**

 Jafnvægislíking hvarfsins er:

 .. math::

   K=\frac{ [\ce{CH_3OH}][\ce{H_2O}] }{ [\ce{CO_2}][\ce{H_2}]^3}

Jafnvægisfasti tekur gildi á breiðu bili, en t.d. er jafnvægisfasti bruna vetnis með stærðargráðu :math:`~10^{80}`, en jafnvægisfasti fyrir bruna niturs í lofti er með stærðargráðu :math:`10^{-31}` við stofuhita. Þessi munur myndi útskýra af hverju það er ekkert vetni í andrúmsloftinu, en nitur og loft getur lifað í samlyndi þar.

Jafnvægi fyrir gös
------------------

Fyrir efnahvörf sem eiga sér stað á gasfasa er oft ekki notaður styrkur, heldur *hlutþrýstingur* (e. partial pressure) efna. Þá er ekki notað styrkur í hornklofa, :math:`[\ce{A}]`, heldur :math:`P_A` í jafnvægislíkingunni. Til aðgreiningar er notað :math:`K_c` fyrir jafnvægi í lausn en
:math:`K_p` fyrir jafnvægi í gasfasa.

.. math::

  \ce{aA(g) +bB(g)+ \dots <=> nN(g) + mM(g) + \dots}

Fyrir þetta efnahvarf væri jafnvægisfastinn í gasfasa:

.. math::

  K=\frac{P_N^n P_M^m \dots }{P_A^a P_B^b \dots }

:math:`K_p` er ekki endilega sama talan og :math:`K_c` en jafnan til að breyta á milli þeirra er

.. math::

  K_p=(RT)^{\Delta n} K_c

Þar sem :math:`R` er gasfastinn :math:`0,083145 \,\frac{\text{bar L}}{\text{K mól}}` og :math:`T` er hitastigið í kelvin. Að lokum er :math:`\Delta n` mismunur á mólum fyrir og eftir hvarfið, þ.e.

.. math::

  \Delta n = \ce{(n + m + \dots) - (a + b + \dots)}

Ef það eru jafnmörg mól af efnum fyrir og eftir hvarfið, þá gildir :math:`(RT)^0=1` og :math:`K_p=K_c`.

.. tip::

 **Gefið er efnahvarfið:**

 .. math::

    \ce{2SO_2(g) +O_2(g) <=> 2SO_3(g)} \quad \quad \quad \quad K_p=3,4 \text{ fyrir } 1000 \text{ K}

 **Hvað er** :math:`K_c` **fyrir hvarfið við 1000 K?**

 Nú er jafnan:

 .. math::

  K_p=(RT)^{\Delta n} K_c

 Þar sem:

 .. math::

  \Delta n =2 -(2+1) =-1

 Nú er hægt að einangra :math:`K_c` og stinga inn gildum:

 .. math::

  \begin{aligned}

  K_c &= \frac{ K_p}{(RT)^ {\Delta n} }\\
      &= \frac{3,4} { \left(0,083145\,\frac{\text{bar L}}{\text{K mól}} \cdot 1000\text{ K}\right)^{-1}}\\
      &=280

  \end{aligned}

.. note::

  *Hvert fóru einingarnar í dæminu að ofan?*

  Jafnvægisfastinn, :math:`K` er upphaflega skilgreindur út frá *virkni* (e. activity) og er því einingslaus. Ef :math:`\Delta n \neq 0` eru jafnvægisfastarnir :math:`K_c` og :math:`K_p` tæknilega séð ekki einingarlausir.
  Þessum einingum er þó almennt sleppt að þessu sinni.

  Það verður ekki farið nánar út í virkni hér.

Jafnvægi fyrir vökva og fast efni
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Fyrir hvörf þar sem annað hvort myndefni eða hvarfefni eru ekki í lausn eða í gasi, þ.e. vökvi eða fast efni, koma þau efni **ekki** fram í jafnvægislíkingunni.

.. tip::

 **Til að útbúa sement fyrir steypu þarf að byrja á því að brjóta niður kalsíum karbónat skv. formúlunni:**

 .. math::

    \ce{CaCO_3(s) <=> CaO(s) +CO_2(g)}

 **en þetta efnahvarf er talið vera allt að 5% af koldíoxíð útblæstri mannkynsins. Hver er jafnvægisfasti,** :math:`K_p` **, fyrir hvarfið sem og** :math:`\Delta n`?

 Hér liggur beint við að koldíoxíð er eina efnið sem er ekki á föstu- né vökvaformi. Þá er:

 .. math::

   \begin{aligned}
   K_p&=P_{\ce{CO_2}} 	& \Delta n=(1)-(0)=1
   \end{aligned}

Jafnvægisfasti fyrir sameinuð hvörf
-----------------------------------

Hægt er að sameina efnaformúlu í heildarformúlu. Þegar það er gert, er hægt að finna jafnvægisfasta fyrir heildarhvarfið, út frá jafnvægisföstum efnaformúlunna sem hvarfið var smíðað úr.

- Þegar lagt er saman tvö efnahvörf, eru jafnvægisfastarnir *margfaldaðir.*

  .. math::

    \begin{array}{c|c}
    \text{Efnahvarf}& \text{Jafnvægisfasti}\\
      \hline
    \ce{A -> B} & K \\
    \ce{B -> C} & K` \\
      \hline
    \ce{A -> C} & K \cdot K`\\
    \end{array}


- Þegar hvarf með jafnvægisfasta :math:`K` er snúið við, er nýji jafnvægisfastinn :math:`1/K`.

  .. math::

    \begin{array}{c|c}
    \text{Efnahvarf}& \text{Jafnvægisfasti}\\
      \hline
    \ce{A -> B} & K \\
    \ce{B -> A} & 1/K \\
    \end{array}

- Þegar efnahvarf er margfaldað með :math:`x`, fer jafnvægisfastinn *í* :math:`x`-ta *veldi*.

  .. math::

    \begin{array}{c|c}
    \text{Efnahvarf}& \text{Jafnvægisfasti}\\
      \hline
    \ce{ A -> B} & K \\
    \ce{2A -> 2B} & K^2 \\
    \frac{1}{2}\ce{A} \rightarrow \frac 12 \ce{B} &\sqrt{K}\\
    \end{array}

Hvarfkvóti
----------

*Hvarfkvóti* (e. reaction quotient) fyrir hvarfið:

.. math::

  \ce{aA + bB -> cC + dD}

Hefur sömu jöfnu og jafnvægisfastinn:

.. math::

  Q_c=\frac{[\ce{C}]^c[\ce{D}]^d}{[\ce{A}]^a[\ce{B}]^b}

Munurinn á hvarfkvótanum og jafnvægisfastanum er sá að hvarfkvóti er fyrir ákveðinn tíma, ekki þegar hvarfið hefur náð jafnvægi. Hvarfkvótinn er því ekki fasti, heldur breytist hann með tíma. Hann byrjar oft í 0 og endar í jafnvægisfastanum.

.. figure:: ./myndir/equi/hvarfkvoti.svg
  :width: 40%
  :align: center

Hvarfkvóti nýtist til að spá fyrir um hvert hvarfið stefnir:


:math:`Q<K`
  Hvarfið stefnir til hægri.

:math:`Q=K`
  Hvarfið hefur náð jafnvægi.

:math:`Q>K`
  Hvarfið stefnir til vinstri.

.. tip::

 **Ammóníak myndast með efnahvarfinu:**

 .. math::

    \begin{aligned}
    \ce{N_2(g) +3H_2(g) &<=> 2NH_3(g)} & K&=152 \text{ við } 500 \text{ K}
    \end{aligned}

 **Á ákveðnum tíma er styrkur efnanna:** :math:`[\ce{N_2}]=0,800\text{ M}`, :math:`[\ce{H_2}]= 0,070 \text{ M}` **og** :math:`[\ce{NH_3}]=0,350 \text{ M}`. **Hvert stefnir hvarfið?**

 .. math::

  \begin{aligned}
   Q_c&=\frac{[\ce{NH_3}]^2}{[\ce{N_2}][\ce{H_2}]^3}\\
      &=\frac{0,350 ^2}{0.800\cdot 0,070^3}\\
      &=446
  \end{aligned}

 Sjáum að :math:`Q>K` og hvarfið stefnir því til *vinstri* og myndar meira af hvarfefnunum.

Jafnvægisreikningar
-------------------

Klassísk dæmi er að reikna styrk við jafnvægi. Til þess þarf að setja upp jöfnu þar sem styrknum er lýst með t.d. breytunni :math:`x` og leyst er fyrir :math:`x` með algebru.

.. math::

	\ce{A + 2B -> C}

Fyrir þetta efnahvarf væri styrkur :math:`\ce{A}` við jafnvægi :math:`[\ce{A}]_0-x`, :math:`\ce{B}` væri :math:`[\ce{B}]_0-2x` og :math:`\ce{C}` væri :math:`[\ce{C}]_0+x`. Í þessu tilfelli er :math:`x` *mól hvörfuð/mynduð við jafnvægi*. Þá getur verið gott að setja upp í töflu til að halda utan um styrkinn.

.. tip::

 .. math::

   \ce{ A -> B} \quad \quad\quad K_c=3,4

 **Ef byrjað er með 3,00 mól af A, í 2,00 L af vatni, hver er styrkur B við jafnvægi?**

 Hér þarf að byrja á því að finna upphafsstyrk A:

 .. math::

    [\ce{A}]_0=\frac{3,00 \text{ mól}}{2,00 \text{ L}} = 1,50 \text{ M}

 Þá er hægt að setja upp í töflu:

 .. math::

    \begin{array}{c|c|c}
    \text{Efni}&\ce{A}&\ce{B}\\
      \hline
    \text{Upphafsstyrkur}&1,50\text{ M} & 0 \\
    \text{Hvarf}&-x & +x\\
      \hline
    \text{Jafnvægisstyrkur} &1,50-x&  x\\
    \end{array}

 Jafnvægisfastinn er þá:

 .. math::

  K=\frac{[\ce{B}]}{[\ce{A}]} =\frac{x}{1,50-x}=3,4

 Fyrir jafnvægisreikninga eru einingar oft geymdar í bili. Þá fæst með því að einangra :math:`x`:

 .. math::

  \begin{aligned}
  & \quad \, \,\frac x{1,50-x}=3,4\\
  &\Leftrightarrow x=3,4(1,50-x)\\
  &\Leftrightarrow x+3,4x = 5,1\\
  &\Leftrightarrow x= \frac{5,1}{4,4}\\
  &\Leftrightarrow x= 1,16
  \end{aligned}

 Þá er :math:`[\ce{B}]=x=1,16 \text{ M}`.

Algebran flækist hratt þegar fleiri en tvö efni eru í hvarfinu. Þá er mikilvægt að geta rifjað upp gamla stærðfræðitakta og leyst fyrir annars stigs margliðu. Fyrir enn flóknari dæmi, þarf að nálga eða beita enn flóknari aðferðum sem ekki verður farið í hér.

.. begin-toggle::
  :label: Leysa annars stigs margliðu
  :starthidden: True

Margliðan

.. math::

  ax^2 + bx + c =0

hefur rætur (lausnir):

.. math::

  x= \frac{-b +\sqrt{b^2-4ac}}{2a} \quad \text{eða} \quad x= \frac{-b -\sqrt{b^2-4ac}}{2a}

Margliðan hefur því oftast *tvær* lausnir en oft er hægt að útiloka aðra þeirra, út frá rökhugsun. T.d. getur styrkur efnis ekki orðið neikvæður.

.. end-toggle::

.. tip::

 **Díniturtetraoxíð brotnar niður í niturdíoxíð skv. efnaformúlunni:**

 .. math::

  \ce{N_2O_4(g) <=> 2 NO_2(g)} \quad \quad \quad K_c=4,6 \times 10^{-3} \, \text{ við } 25°C

 **Ef gefið er að** :math:`[\ce{N_2O_4}]_0=0.450 \text {M}`, **hver er styrkur** :math:`\ce{NO_2}` **við jafnvægi?**

 Gott er að byrja á að setja upp töflu:

  .. math::

    \begin{array}{c|c|c}
    \text{Efni}&\ce{N_2O_4} & \ce{NO_2}\\
      \hline
    \text{Upphafsstyrkur}&0,450\text{ M} & 0 \\
    \text{Hvarf}&-x & +2x\\
        \hline
    \text{Jafnvægisstyrkur} &0,450-x&  2x\\
    \end{array}

 Jafnvægisfastinn er þá:

  .. math::

    K=\frac{[\ce{NO_2}]^2}{[\ce{N_2O_4}]}=\frac{(2x)^2}{0,450-x}= 4,6\times 10^{-3}

 Þá er hægt að setja upp og einfalda annars stigs jöfnuna:

 .. math::

  \begin{aligned}
  \frac{4x^2}{0,450-x}&= 4,6\times 10^{-3}\\
  4x^2 &=4,6\times 10^{-3}(0,450 -x)\\
  4x^2 +4,6\times 10^{-3}x -2,07 \times 10^{-3}&=0\\
  \end{aligned}

 Þessi jafna hefur lausnir:

 .. math::

  \begin{aligned}
  x&= \frac{-b +\sqrt{b^2-4ac}}{2a}\\
  &= \frac{-4,6\times 10^{-3} +\sqrt{(4,6\times 10^{-3})^2-4\cdot 4\cdot(- 2,07\times10^{-3})}}{2\cdot 4}\\
  &= 0,02333
  \end{aligned}

 Sambærilega fæst hin lausnin:

 .. math::

  \begin{aligned}
  x&= \frac{-b -\sqrt{b^2-4ac}}{2a}\\
  &= -0,02218
  \end{aligned}

 Sjá má að seinni lausnin er ekki gild, þar sem styrkur :math:`\ce{NO_2}` getur ekki verið neikvæður. Fyrri lausnin er því svarið, en þá fæst að lokum, með þremur markverðum tölustöfum:

 .. math::

   [\ce{NO_2}]=2x= 0,0467 \text{ M}


Nálgun
~~~~~~

Til þess að spara tíma í þessum útreikningum, eða einfaldlega gera jöfnur leysanlegar, getur þurft að *nálga* lausnirnar. Þá eru tekin út atriði sem skipta litla sem engu máli, til að einfalda jöfnuna.
Sem dæmi um þetta má nefna af ef jafnvægisfastinn er lítill, er :math:`x` lítið. Ef upphafstyrkurinn er ekki mjög lítill er oft hægt að nálga t.d. :math:`[\ce{A}]_0-x\approx [\ce{A}]_0`.

Nálgunin :math:`[\ce{A}]_0-x\approx [\ce{A}]_0` getur haft tvenns konar áhrif. Ef :math:`x` breytir einungis ómarkverðum tölustöfum, hefur það engin áhrif og er næstum alltaf góð hugmynd. Ef :math:`x` breytir markverðum tölustafi  í upphafsgildi, þá getur ennþá verið góð hugmynd að nálga, og fer það eftir nákvæmni sem þarf að hverju sinni.

Oft er notað 5% sem hámark leyfilegrar skekkju, en það er ekki fastákveðið.

Ef :math:`x` er lítið er hægt að nálga í samlagninu, en **aldrei** í margföldun.

.. tip::

 **Hvað fengist úr dæminu fyrir ofan með nálgun, og hversu mikil væri skekkjan?**

 Jafnvægisfastinn úr dæminu að ofan var:

 .. math::

    K=\frac{[\ce{NO_2}]^2}{[\ce{N_2O_4}]}=\frac{(2x)^2}{0,450-x}= 4,6\times 10^{-3}

 Með nálgun að :math:`0,450-x\approx 0,450` einfaldast jafnan og verður:

 .. math::

  \begin{aligned}
  4x^2&=4,6\times 10^{-3} \cdot 0,450\\
  \Rightarrow x &=\sqrt{\frac{2,07\times 10^{-3}}{4}}\\
   &=0,0227
   \end{aligned}

 Þá fæst:

  .. math::

    [\ce{NO_2}]=2x= 0,0455 \text{ M}

 Með því að bera saman svörin fæst að :math:`\frac{0,0455}{0,0467}=0,974`. Það þýðir að nálgunin gefur  :math:`2,6 \%` skekkju.

Regla Le Châtelier
------------------

Regla Le Châtelier gefur til kynna að ef aðstæðum efnahvarfs er breytt við jafnvægi, *leitast efnahvarfið að vinna gegn breytingunni*.

Nú er hægt að líta aftur á efnahvarfið:

.. math::

	\ce{N2O4(g) <=> 2NO2(g)} \quad \quad \quad K_c=4,6 \times 10^{-3} \text{ við } 25\ °\text{C}

Hér er hægt að gera nokkra hluti til að stýra hvarfinu:

Breyting á styrk
~~~~~~~~~~~~~~~~

Ef styrkur efni er aukinn reynir hvarfið að draga úr þeirri breytingu með því að stefna í átt *frá* viðbættum styrk. Ef styrkur :math:`\ce{NO2}` væri aukinn, myndi hvarfið fara til *vinstri*. Sambærilega myndi hvarfið fara til *hægri* ef
styrkur :math:`\ce{N2O4}` væri aukinn.

Við jafnvægi gildir:

.. math::

	Q_c=\frac{\ce{[NO2(g)]}^2}{\ce{[N2O4(g)]}} =K_c

Ef litið er á hvarfkvótann þegar styrkur :math:`\ce{N2O}` er aukinn um :math:`x`:

.. math::

		Q_c=\frac{(\ce{[NO2(g)]}+x)^2}{\ce{[N2O4(g)]}} >K_c

Þetta gefur til kynna að hvarfið fer til vinstri. Hvarfið mun þó aldrei ná að losa sig við eða bæta upp fyrir alla breytinguna, enda þarf teljarinn og nefnarinn í jafnvægislíkingunni að ná nýju jafnvægi.

Breyting á rúmmáli og þrýsting
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Ef efnahvarf hefur mismunandi fjölda móla við örina, er hægt að stjórna hvarfinu með þessum hætti. Þrýstingur er háður rúmmáli, sem og mólum. Þegar rúmmál er minnkað, leitast hvarfið við að draga úr þrýstingsaukningunni. Hvarfið stefnir þá í átt að *færri* mólum.
Sambærilega ef rúmmál er aukið, leitast hvarfið við að viðhalda
þrýstingnum og stefnir í átt að *fleiri* mólum.

Efnahvarfið fyrir ofan hefur mismunandi fjölda af móla. Þá er hægt að leiða út:

.. math::

		\begin{aligned}
		K_c &= \frac{\ce{[NO2(g)]}^2}{\ce{[N2O4(g)]}}\\
				&= \frac{n_{\ce{NO2(g)}} ^2/V^\bcancel{2}}{n_{\ce{N2O4(g)}}/\bcancel{V}}\\
				&= \frac{n_{\ce{NO2(g)}} ^2}{n_{\ce{N2O4(g)}}} \cdot \frac{1}V
		\end{aligned}

Ef :math:`V` er t.d. tvöfaldað, þarf :math:`\frac{n_{\ce{NO2(g)}} ^2}{n_{\ce{N2O4(g)}}}` einnig að tvöfaldast. Þetta næst þegar hvarfið fer til hægri.

Hvorugar af þessum breytingum breyta þó jafnvægisfastanum, :math:`K`, en hann breytist einungis með hitastigi.

Breyting á hitastigi
~~~~~~~~~~~~~~~~~~~~

Jafnvægisfastinn breytist með hitastigi, en fyrir útvermin efnahvörf *eykst* hann en *minnkar* fyrir innvermin efnahvörf. Þetta er annað dæmi um að hvarfið sporni við breytingum.

- Við heitari aðstæður leitar hvarfið að því að framleiða minni hita, til að takmarka hitastigsaukninguna.
- Við kaldari aðstæður leitar það að því að framleiða meiri hita, til að takmarka hitastigslækkunina.

Ef efnahvarf er útvermið gefur það frá sér hita er hægt að skrifa hitann sem myndefni:

.. math::

	\ce{A -> B } + \Delta H

Ef efnahvarf er innvermið tekur það til sín hita og þá er hægt að hugsa sér hitann sem hvarfefni:

.. math::

	\ce{A} + \Delta H \ce{ -> B}

Þá er hægt að hugsa sér þetta alveg eins og þegar bætt er við myndefnum og hvarfefnum. Ef hitinn er aukinn, þ.e. :math:`\Delta H \uparrow` þá leitar hvarfið að því að losa sig við hluta af honum. Ef hitinn er lækkaður, þ.e. :math:`\Delta H \downarrow`, þá leitar hvarfið að því að mynda hita.

Regla Le Châtelier er góð til að spá fyrir hvernig jafnvægið breytist, en þegar á að nota hana er nóg að spurja sig eftirfarandi spurningar: *Hvað breytist og hvernig er hægt að sporna við því?*

.. tip::

 **Gefið er útvermið efnahvarf við jafnvægi:**

 .. math::

 		\ce{A <=> B + C } \quad \quad \quad \Delta H <0

 **Hvernig breytist styrkurinn þegar gerðar eru breytingar á styrk efna, rúmmáli og hitastigi? Fylltu inn í töfluna.**

 .. math::

 	\begin{array}{c||c|c|c}
	 &[\ce{A}]&[\ce{B}]&[\ce{C}]\\
				\hline
			[\ce{A}] \uparrow& & & \\
			[\ce{B}] \downarrow &&& \\
		 	V \downarrow \! \!&&& \\
			T \uparrow \! \!&&& \\
		 	T \downarrow \! \!&&& \\
   \end{array}

 Nú fæst með Le Châtelier:

 .. math::

 			\begin{array}{c||c|c|c|c}
	   	&[\ce{A}]&[\ce{B}]&[\ce{C}]&\\
				\hline
			[\ce{A}] \uparrow& \uparrow& \uparrow & \uparrow & (1)\\
			\hline
			[\ce{B}] \downarrow &\downarrow&\downarrow&\uparrow& (2) \\
			\hline
		 	V \downarrow \! \!&\uparrow&\downarrow& \downarrow& (3) \\
			\hline
			T \uparrow \! \!&\uparrow&\downarrow&\downarrow & (4) \\
			\hline
		 	T \downarrow \! \!&\downarrow&\uparrow&\uparrow & (5)\\
	 		\end{array}

 1. Styrkur hvarfefnis er aukinn, og efnahvarfið fer því til hægri. Viðbættur styrk A hvarfast ekki allur og því eykst allir styrkir.
 2. Styrkur myndefnis er minnkaður, svo efnahvarfið fer til hægri. Styrkur B nær þó ekki sömu hæðum.
 3. Rúmmál er minnkað og þrýstingur eykst. Efnahvarfið vill því losna við mól og fer til vinstri.
 4. Hitastig er hækkað og útvermið efnahvarf fer þá til vinstri, til að minnka hitann.
 5. Hitastig er lækkað og útvermið efnahvarf fer þá til hægri, til að auka hitann.
