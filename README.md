# M490M · Input Pre Amps

Ward-Beck Systems M490M, 1988|21. Wiki page: [M490M on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M490M.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 36 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 12 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 299 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 11 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 47 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1988 - M490M - P003 - 1-1.jpg](MANUALS/1988%20-%20M490M%20-%20P003%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivity** | +10 dBm (ref. 600 ohm source) |
| **Frequency response** | +/-0.2 dB from Hz to 20 kHz |
| **Noise** | dB below the nominal operating Level, with the mixing tenuatct Sc: fcr d2 &quot;n hand&quot; 20 Hz 20 kHz) |
| **Harmonic distortion** | Less than 1% Hz to 20 kHz 20 dB above the nominal opera ting evel less |
| **Input level** | -10 dBm +10 dBm for the nominal output operating Level +21 dBm maxim mum unity gain |
| **Input impedance** | 30,000 ohms, actively balanced |
| **Source impedance** | 600 ohms or less balanced |
| **Common mode rejection ratio** | Greater than 50 dB 30 Hz to 15 kHz |
| **Common mode voltage** | 50 volts peak maximum |
| **Output level** | dBm nominal equiva ent voltage into summing networks +25 dBm maximum equivalent voltage. |
| **Output impedance** | 30,000 ohms actively balanced for program circuits_ 60,O00 ohms actively balanced for cue circuits. |
| **Load impedance** | Less than 0.5 ohm current summing nodes. |
| **Channel separations** | 55 dB from 30 Hz Input and Output terminals designated by numbers are in phase, lower number numbered Pair phase with lower number other numbered pairs |
| **Power requirements** | +/-25 volts dc 75 MA. |

## Circuit description

From [1988 - M490M - Stereo Input Module (2).pdf](MANUALS/1988%20-%20M490M%20-%20Stereo%20Input%20Module%20(2).pdf) pages 9-14 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

Input Selectors witches SWI and SW2 are mu tUll.lly interlocked and permit the selection o f one of two...v ai lab lester e o sour c.. s. add i t io na l conl...c l iss u p pl i.. don.....ch switch for control purposes.

Two b&quot;l...nc.. dins er t points a r.. provide d, one for ell c h channel, following the Input Selector s.

The SA14 ~ 12 0 Sub ll s s emb ly contains I he left and right channel pr e amplifier s. The insert returns...1 P 2 pins 6 &amp; Jan d P 2 pins 7 &amp; H Conne cl tot hep rea mp l i fie r in pu ls via 120 J l pins 1 &amp; 2 and 120 J l pins 5 &amp; 6 forth e right and left chan n e ls resp e cti v e l y.

The p r e amplifier outputs IIp pear al 120 J2 pin 1 1 for the I.. f t channel and l ZO J2 pin 12 forth e right channel. These outputs connect tot hester eo a tt e n U...l or ATT1.

Unequal input levels would b e corrected b y...d just me nt of these ns i t i v i t y trim co nl rol s - R49 (r i g h t) and Rll (l eft) located o n Ih e SA14_ 120 Pre...mpl i f i er Sub...ss e mb ly. The mixing alt e n u a tor ATTl shOuld b e p l...c ed in Ih e 15 dB &quot;in hand &quot; position to make Ih is adjustment.

The stereo e rte o o arcri nputs as mentioned above are derived from the lel1 and right channel pr e llmplifier located on Ih e SA14_ 120 SUb assembly.

Pro gram Ch...n n e l 5wit ch

Ul (right) and U4 ' (I&quot;&quot;ft l are...n.. logs o lid SI...l e switches, serving liSt h e IIc t ives witching elements of the Program c h...nn e ls. The control

voltage to op er.. te Ul...nd U4 i s d er\v ed from I he logic circuitry

within the module and i s coup led to Ul and U4 via CRT and CR3. to

switch Ihe ch...nn e lON, this con l ro l voltage i sin the order o f

+10 volts. When the control voltage drops t o 0 volts, the switch will be OFF, result ing ina signal &quot; ll e n u a t ion o f more than 100 dB.

**M49 0M STEREO INPUT. MODULE**

Follow ing Ul and UiI, I hes i g n ali s ampli Hed by integral e d c ircui l s U2, UJ (rig hl land U5, U6 (left) to II. nomin e 1 level o f 0 dBm (equivalent vo ll age). The signal i s Ih e n routed tot h e Program Assign men t switch e s SW4 and SW5.

The left and right channels con lain le vet b...la n ce controls which are f a c l o r ypres el tom atc h Ih e level oft h e left channel tot her igh t channel. These control, R I 7 (r ig hll and R54 (Iefll should require no further adjustment s.

Pro gram Out puts

The PI and P 2 Assignment switches SWiI and SW5 s i multan e o u sly assign both lett and right chan n e ls to the P Ian d/ or P 2 Program mixing buses.

The left and righl Cue channel ci rcu ils are locale don the SA1 4_ 120 P ream p l i fie.. Sub assembly. a ere.. t o Ih e SA14_ 120 circuit d e scr ipl ion for de la il.

The Cue outputs appear inge t 120 J2 pins 4 &amp; 5 fort he left channel and t 20 J2 pins 9 &amp; 10 for the right channel f.... d through their resp ecliv e summing resistors to the module conn ec lor P l.

The control voltages required 10 operate the le tt and.. i gh t solids late program and Cues w il che s are gene..a ted with thea i d of logk circ ui l r y utilizing integral e d circuits U7 through Ul0.

u ais a CMOS dual flip _flop serving as ala tch to maintain the s la l US oft hes w il c hes, once they have been set t o ettttert h eON or I he OFF position.

A number o find ivi dual inpu l functions govern I h est a t uso f Ih e dual

flip flop ua. A description of each i n p u l fun cli on follows:

Initial Reset;

When power is in H i ally applied 10 the system, Ih e combinat-. ion 01 CRI 2, CRlJ, CR1 &quot; and CD will p u l i down both &quot; clear&quot;

inputs o f UB until CJ J is fully charged, thus e ns u ring that

all solid Slates witches are driven t o I he OFF position.

WA ~ D · BECKS YSTE MS L T C.

**M4 9 0M STEREO INPUT. MODULE**

Channel On;

Moment a r y operation of I h e Channel On switch SW9 will produce &quot; nega tiYe going pulse a t u a, pin 2 &quot; n d &quot;pres et&quot; the Asection of ua. Al le r nat i Ye l y, a momentary ground e los,-&quot; r,. of th.. E.&quot;, e r&quot;l'I ('&quot;h&quot; &quot; nel 0,., con ' rol input e ' P2, p i &quot; N will result in the same condition.

Once the f li p-fl op is &quot;p r e set&quot;, u s ou lp u tet pin 15 changes from 0 to 1 (&lt;'lp pro xi mate l y ~ 1 0 yolts). This will cause the left and right Program switChes to switCh ON. Fur the r more, 0 5 will sal u rate resulting in I h e Channel On ind iC&lt;'ltor lamp DS3 t o switch on. With 05 S&lt;'ltu r &lt;'lt ed, the &quot; cont r o l common &quot; potential app ears at the emit ter s o f 0 6 &quot; &quot; d 0 7, depending on whether I n pulSe lec tOrs witCh SW\ or SW2 is depressed. Eff ecti Ye ly, 06 and 07 operate si mi l&lt;'lr l y to two AND 9a tes. The collectors oft h e two trans i s tors r epr&quot; sent the outputs oft h e AND gates. They appear a t P2, pin 13 and P. These t e r min a l s are cap &quot;ble of sin k.in g ama x imu m current o f 40 mA e&lt;'lc h from a 24 Yol l source &quot;n d m&quot;y b e used for muting purposes.

When operating the Channel On switch SW9, &quot; separate con l&lt;'lCI i s closed, accessible lOt P2, pins 15 and S. This con l act maybe used for s i mu l t &quot; neo us &quot; m&quot; chin est art &quot;.

Pin R of P 2 isis ol &quot; led I hro ugh diode CRS. When connected in parallel with the Same output of other modules, it pray ides a &quot; o rw e n i&quot; n l OR gate con fig u ration, suit &quot;b l&quot; toe e e era common Iimer each time a Channel On bull on i s depress e d.

Channel Off;

Momentary operation of the Ch &lt;'lnne l Off switch SW8 or momentary ground closure oft h e External Channel Off control input atp ~, ' pin 12 will result ina neg a ti y ego ing pulse a t u a, pin 3 and &quot;cl e a r&quot; the As e c t ion o f u a, producing 0 yo l t s

a t ua, pin 15. Consequently, the left and right solids tate

P &quot;,gr&lt;'lm switChes w i l i switch OFF. 05 wills top conducling,

causing DS3 10 extinguish, &lt;'lnd them ut ing control ou tpu lS Il t

P 2, pins 13 &quot;nd P will bed is able d.

**1-\4901-\ STEREO INPUT. MODULE**

A sep a n lt e con lac t i s available on SW8 and is accessible at P2, pin 11 and U. I t maybe used for &quot;maChine stop &quot;.

A sep ara t e Channel Off tally lamp is builtIn to SWS and Is connected to P2, pins 18 and V.

I n addition 10 the normal pUShbutton operated Channel Off function, b Ol h left and right solid state Program switches are, witChed off whenever them ixi ng a tt enu a tor i s moved tot h e &quot;infin i te &quot; position and switch 5WIO is closed. The 0 volt potential developed al U7, pin 10 i&quot; fed directly to the two programs witches and causes them 10 switch OFF. However, II'&gt;&lt;! slat uso f U8, the Channel On ind ic a tor and Ih emu ting c o..&quot; ro ls rerne in unaflected b y this operation.

The 8· sect lon of US is used to control the solid state Cues witches. The flip _f lop will changes tate each time a negative going transition takes place atp in {, 0 ' U8. Consequently, with each input pulse, the Cue channels will ene.... ale between ON and OFF.

This change of Stale can be b....... ght about by anyone of three d iffer=1 melhod s:

a) Momentary operation oft h e Cues w il c h swilch 5Wl2 101. b) Momentary ground closure o f the Exl e rn al Cue control inpul e t P2, pin II.

c) Operation o f I h e &quot;o verpre s s &quot; switCh SWII, located a l Ihe slide a llenua tor beyond Ih e &quot;inflnit e &quot; position.

The ON status of the Cue channels is indicated by 0 5 2, which is driven by 04.

Cue Off;,

Ana ddi tional feature enSureS that the Cue channels will

always, wi l Ch t o OFF whenever the slide a tte nua tor Is Il'IOved

onto o raw a y from the &quot;infini t e&quot; position, regardless oft heir

priors tate. The cont r o l signal for this action i s Initiated

by the change o f stale of the Att e n u ato r Cuts wi l c h SWIO. There sult ant level change, being either positive or negative

going, Is processed through U7, U9, and UIO.

The ou tpu l produced a t pin &quot; of U10 willa l ways bean e g a tive going pulse o f approx i mate l y 500 milliseconds du.. a lion. CRII passes this pulse to U8, pin 8, tn e..eb y &quot;clea r-i n g &quot; Ih e Bs ec lion oft he f lip_ flop, and..e s ul ting i n pin 11 o f U8 10 s wi l Ch to (or..ema i n 411) 0 vOl 15, in Iu r n s wi l chin g the Ie ': e -re i i &quot;: C::c:e&quot;,r: c;Me&lt;; ~ !'&quot; •

...11 logic conlr'O lIn puts e r-e b u ffe..ed to guard a gains l sPurious noise and s&quot;, ·iICh bounce.

Po........ Supply Oecoupl1n g

T&quot;&quot;. actIve dec: oup ling network con siSling o f 09 through 0 12 along t&quot;'&gt;:.,ei.. e asoeteree componenlS, clec oup le 0&lt;&quot;.... g u lal e t rte inc om ing -.15,,&quot;011 supply vol lege down 10 · / -20 vOl Is. CRI9 and CR20 s.... veto p..e &quot;enl amplifier damage int he.. v..... 1 o f supply voltage..e v e..sal. The decoupling n elwo.. k drops the +/-25 vol l supply..ai ls 10 a nominal vol lage of +/ _20 veus. 0 8 decoup l.. &quot; and fill e.. s lhe 20 V ODs i live supply..a il. re s u ll ing ina n out pu l o f +12 v eus 10 ope..ale the C MOS ciI&quot;'CU; I.. y.

U2, U3. US and U6 are fur the.. dec ouplt&quot;d 10 +/-18 &quot;olts. R1S, RI 9 and C 10 - ClJ decouple Iht' +18 &quot; oilS while R SS, RS6 and C23 _ C26 decouple Ih e -18 v eus. Sej)a.. ale on -boa..d powers u p ply dec oup lin g i. provided on I he 5...14-120 P..eamp lifi.... Suba s sem bl y.

W AFlC·BECK SYSTEMS LTC.

**PARTS LIST**

DESCRIPTION MFG PART NUMBER

15so/AH35/100

Cap~c ltor 2.2 uF /3S V TJ9OC225M03SAS c. t u F/ ~ 5 v t 39CA1C4MC3SAS

J3 uF /to V u F/3S V

**T39OA105M03SAS**

CS 33 uF / l O V TJ900336M01 0AS

ce 41pF Ph:.Ii P S 2222_638_34479 C7 47pF CS 33 u F/ l 0 V T3900336M010AS C9 33 u F 10 V COO 0.' u F/ l OO V Spra9u~ ICIOX7R 104MD5OB

en 0.' uF /lOO Vera 47 uF /40 V Ph:.Ii PS CU 47 uF /4D V CU 2.2 uF/3S V T39OC225M03SAS crs 0.' uF /JS V T39OAIQ4MOJSAS

JJ uF /to V uF/35 V

**T390A 1OSMOJ5AS**

C&quot; J3 uF /10 V T3900336MD10AS COO 47 pF Ph:,lips 2222-638 _34479 C20 47 pF

C20 J) u F/ l O V C22 33 u~/ I O V C2J 0.' u F/ l 00 V Sp~,a 9u~ lC IOX1R I04 MDSOB C&quot; 0.' uF / l00 V C2S 47 uF/ 40 V Philips

~ 26 47 u F/ 40 V czt, D. l uF/JS V

uF /3S V uF/3SV

CJO uF/35 V

4.7 u F/ 10V T39084 7SM0 10AS

caa uF/35 V T3 9OA10SM035A5 'JJ 47 uF/25 V T3 90 E476M0 25AS

CJ&lt; 2.2 u F/3S V T39OC22SM035 AS

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKalA5UkstS29Uc28/view?resourcekey=0-gEprVRQMdfyr-_82d5d9-A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKalA5UkstS29Uc28&resourcekey=0-gEprVRQMdfyr-_82d5d9-A" width="240" alt="1988 - M490M - 490-04-026 - STEREO INPUT MODULE MODULE LAYOUT.jpg"></a><br><sub>1988|21 · 490-04-026 - STEREO INPUT MODULE MODULE LAYOUT · <a href="MECHANICAL/1988%20-%20M490M%20-%20490-04-026%20-%20STEREO%20INPUT%20MODULE%20MODULE%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1988|21 · 490-04-026 - STEREO INPUT MODULE MODULE LAYOUT (2)](https://drive.google.com/file/d/0B0yR0b5T78SKRjl4TFRDREh1ZEE/view?resourcekey=0-NJhrcyUvvtDzDSoRVxJUCA) · [1988|21 · 490-04-026 - SWI DSI](https://drive.google.com/file/d/0B0yR0b5T78SKMnpvX0VsR0hMclk/view?resourcekey=0-GskccCE7cmQkpasWlqblzA)

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVU1Ob2Z2TEtxNlU/view?resourcekey=0-IewfUbiSpzThMwqZ2yQ87A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVU1Ob2Z2TEtxNlU&resourcekey=0-IewfUbiSpzThMwqZ2yQ87A" width="240" alt="1988 - M490M - 14-120-02-001 - COMMON COMMON SPEC IFIED LAST COMPONENT DESIGNA.jpg"></a><br><sub>1988|21 · 14-120-02-001 - COMMON COMMON SPEC IFIED LAST COMPONENT DESIGNA · <a href="SCHEMATICS/1988%20-%20M490M%20-%2014-120-02-001%20-%20COMMON%20COMMON%20SPEC%20IFIED%20LAST%20COMPONENT%20DESIGNA%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZEFTUmZuMFJad2M/view?resourcekey=0-t-HH1lFJtO4CTplL2a-x5Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZEFTUmZuMFJad2M&resourcekey=0-t-HH1lFJtO4CTplL2a-x5Q" width="240" alt="1988 - M490M - 14-120-02-001 - UNLESS OTHERWISE SPECIFIED IODES ARE.jpg"></a><br><sub>1988|21 · 14-120-02-001 - UNLESS OTHERWISE SPECIFIED IODES ARE · <a href="SCHEMATICS/1988%20-%20M490M%20-%2014-120-02-001%20-%20UNLESS%20OTHERWISE%20SPECIFIED%20IODES%20ARE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNUhOOV9Bd1lDeDQ/view?resourcekey=0--1zxF3oahF9jIqiu_yT6ng" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNUhOOV9Bd1lDeDQ&resourcekey=0--1zxF3oahF9jIqiu_yT6ng" width="240" alt="1988 - M490M - 14-120-06-001 - STEREO PREAMPLIFIER COMPONENT LAYOUT.jpg"></a><br><sub>1988|21 · 14-120-06-001 - STEREO PREAMPLIFIER COMPONENT LAYOUT · <a href="SCHEMATICS/1988%20-%20M490M%20-%2014-120-06-001%20-%20STEREO%20PREAMPLIFIER%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUjJId2t1N1RWLUE/view?resourcekey=0-gvKg2sZm4MwTgO1RP0yc0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUjJId2t1N1RWLUE&resourcekey=0-gvKg2sZm4MwTgO1RP0yc0Q" width="240" alt="1988 - M490M - 490-01-013 - OFFA ON-START TIMER RESET OFF TALLY OFF.jpg"></a><br><sub>1988|21 · 490-01-013 - OFFA ON-START TIMER RESET OFF TALLY OFF · <a href="SCHEMATICS/1988%20-%20M490M%20-%20490-01-013%20-%20OFFA%20ON-START%20TIMER%20RESET%20OFF%20TALLY%20OFF%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU3h2ZnlEMkhyd00/view?resourcekey=0-2rxK2Fy-k9lWTFGEHQedGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU3h2ZnlEMkhyd00&resourcekey=0-2rxK2Fy-k9lWTFGEHQedGw" width="240" alt="1988 - M490M - 490-01-013 - STEREO INPUT MODULE FUNCTIONAL.jpg"></a><br><sub>1988|21 · 490-01-013 - STEREO INPUT MODULE FUNCTIONAL · <a href="SCHEMATICS/1988%20-%20M490M%20-%20490-01-013%20-%20STEREO%20INPUT%20MODULE%20FUNCTIONAL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVWpBYXpOR2JZSjA/view?resourcekey=0-s0E5JPu9do6GiEe047CAIA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVWpBYXpOR2JZSjA&resourcekey=0-s0E5JPu9do6GiEe047CAIA" width="240" alt="1988 - M490M - 490-02-013 - CRIZ OFF EXT.jpg"></a><br><sub>1988|21 · 490-02-013 - CRIZ OFF EXT · <a href="SCHEMATICS/1988%20-%20M490M%20-%20490-02-013%20-%20CRIZ%20OFF%20EXT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1F6UEdneGpGZ1U/view?resourcekey=0-T2qmPnNMEyucMpEG6kYToQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1F6UEdneGpGZ1U&resourcekey=0-T2qmPnNMEyucMpEG6kYToQ" width="240" alt="1988 - M490M - 490-02-013 - LAST COMPONENT DESICMAT IONS.jpg"></a><br><sub>1988|21 · 490-02-013 - LAST COMPONENT DESICMAT IONS · <a href="SCHEMATICS/1988%20-%20M490M%20-%20490-02-013%20-%20LAST%20COMPONENT%20DESICMAT%20IONS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYU1GUEtJRGR6QTg/view?resourcekey=0-k9izlxNw2kh8qSSKxwGEbQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYU1GUEtJRGR6QTg&resourcekey=0-k9izlxNw2kh8qSSKxwGEbQ" width="240" alt="1988 - M490M - 490-06-023 - STEREO INPUT MODULE COMPONENT LAYOUT.jpg"></a><br><sub>1988|21 · 490-06-023 - STEREO INPUT MODULE COMPONENT LAYOUT · <a href="SCHEMATICS/1988%20-%20M490M%20-%20490-06-023%20-%20STEREO%20INPUT%20MODULE%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVUM3Tjl4cnh1Tkk/view?resourcekey=0-Kq01xbZNN4U-8lsdk5Iprg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVUM3Tjl4cnh1Tkk&resourcekey=0-Kq01xbZNN4U-8lsdk5Iprg" width="240" alt="1988 - M490M - 490-06-023.jpg"></a><br><sub>1988|21 · 490-06-023 · <a href="SCHEMATICS/1988%20-%20M490M%20-%20490-06-023%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M490M - RTO-144 Connections.pdf`

## RTO-144 pinout

22 contacts (P1), 22 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | LEFT PGRM 1 | audio | A3 + | high |
| 1 | MIC IN A | in | A1 + | high |
| 2 | LEFT PGRM 1 | audio | A3 - | high |
| 2 |  | unread |  | low |
| 3 | RIGHT PGRM 1 | audio | A4 + | high |
| 3 | MIC IN B | in | A2 + | high |
| 4 | RIGHT PGRM 1 | audio | A4 - | high |
| 6 | INSERT SEND | out | B1 + | high |
| 7 | INSERT RETURN | in | B2 + | high |
| 19 | -25 V | power |  | high |
| 20 | COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 |  | unread |  | low |
| 22 |  | unread |  | low |
| A | MIC IN A | in | A1 - | high |
| C | MIC IN B | in | A2 - | high |
| F | INSERT SEND | out | B1 - | high |
| H | INSERT RETURN | in | B2 - | high |

**Straps:** Insert: JMP.6.7 · Insert: JMP.F.H

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeHNTOU94RlJfQzA/view?resourcekey=0-V1UjT9wc64Teagb4hds-lg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeHNTOU94RlJfQzA&resourcekey=0-V1UjT9wc64Teagb4hds-lg" width="240" alt="1988 - M490M - P002.jpg"></a><br><sub>1988|21 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc0hoM1k0YTNmYVk/view?resourcekey=0-fziRyp5-Bhoj-f9xwBWiQw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc0hoM1k0YTNmYVk&resourcekey=0-fziRyp5-Bhoj-f9xwBWiQw" width="240" alt="1988 - M490M - P003 - 1-1.jpg"></a><br><sub>1988|21 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQmlWTy1UOUgwdEU/view?resourcekey=0-Q1fI3nSQL_FKR0BwlNw97Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQmlWTy1UOUgwdEU&resourcekey=0-Q1fI3nSQL_FKR0BwlNw97Q" width="240" alt="1988 - M490M - P004 - 1-2.jpg"></a><br><sub>1988|21 · P004 - 1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXBlMzhHd3FOVzQ/view?resourcekey=0-bLI6-qFgpxmYb-T3ywNC7g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXBlMzhHd3FOVzQ&resourcekey=0-bLI6-qFgpxmYb-T3ywNC7g" width="240" alt="1988 - M490M - P005 - 2-1.jpg"></a><br><sub>1988|21 · P005 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNTJBQjNhNXpUbzA/view?resourcekey=0-JTAImBCO9u8sb0T_qFCu6A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNTJBQjNhNXpUbzA&resourcekey=0-JTAImBCO9u8sb0T_qFCu6A" width="240" alt="1988 - M490M - P006 - 2-2.jpg"></a><br><sub>1988|21 · P006 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdmVkME1BUmNJSms/view?resourcekey=0-6NMQGFsKGJARWSDliJb6-w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdmVkME1BUmNJSms&resourcekey=0-6NMQGFsKGJARWSDliJb6-w" width="240" alt="1988 - M490M - P007 - 3-1.jpg"></a><br><sub>1988|21 · P007 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1piR0VMb2Jmcjg/view?resourcekey=0-jAW_TxBWytQgU_I95fphww" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1piR0VMb2Jmcjg&resourcekey=0-jAW_TxBWytQgU_I95fphww" width="240" alt="1988 - M490M - P008 - 3-2.jpg"></a><br><sub>1988|21 · P008 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTVpyUzB1RDFVYUU/view?resourcekey=0-Vuhh_atPWW920j1XSX_iIQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTVpyUzB1RDFVYUU&resourcekey=0-Vuhh_atPWW920j1XSX_iIQ" width="240" alt="1988 - M490M - P009 - 4-1.jpg"></a><br><sub>1988|21 · P009 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSGNxQlprcDlkVmM/view?resourcekey=0-20i1ab5efkUhZQQbm_j8mQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSGNxQlprcDlkVmM&resourcekey=0-20i1ab5efkUhZQQbm_j8mQ" width="240" alt="1988 - M490M - P010 - 4-2.jpg"></a><br><sub>1988|21 · P010 - 4-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUZDa0htZDNOQWs/view?resourcekey=0-vS3nmsFWCLxdpwqsOquqNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUZDa0htZDNOQWs&resourcekey=0-vS3nmsFWCLxdpwqsOquqNA" width="240" alt="1988 - M490M - P011 - 4-3.jpg"></a><br><sub>1988|21 · P011 - 4-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRlFza0ZLRXJnbTA/view?resourcekey=0-A96CjhHgp6_zrhB0pORCPA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRlFza0ZLRXJnbTA&resourcekey=0-A96CjhHgp6_zrhB0pORCPA" width="240" alt="1988 - M490M - P012 - 4-4.jpg"></a><br><sub>1988|21 · P012 - 4-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRWpmQldKVTN1NTQ/view?resourcekey=0-eKSK9gnzIEQlWimfY_0PEQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRWpmQldKVTN1NTQ&resourcekey=0-eKSK9gnzIEQlWimfY_0PEQ" width="240" alt="1988 - M490M - P013 - 4-5.jpg"></a><br><sub>1988|21 · P013 - 4-5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaFM5NFduU01wNVU/view?resourcekey=0-nsd14tk61xkWXCSmnwkmyA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaFM5NFduU01wNVU&resourcekey=0-nsd14tk61xkWXCSmnwkmyA" width="240" alt="1988 - M490M - P014 - 5-1.jpg"></a><br><sub>1988|21 · P014 - 5-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHc2UDcyU1N5NGM/view?resourcekey=0-LCpkGM0yog4416e0pzXeyg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHc2UDcyU1N5NGM&resourcekey=0-LCpkGM0yog4416e0pzXeyg" width="240" alt="1988 - M490M - P015 - 5-2.jpg"></a><br><sub>1988|21 · P015 - 5-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcW5EZVlTdEJIN1U/view?resourcekey=0-qKW4qUfEeuPB-XinmDBSHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcW5EZVlTdEJIN1U&resourcekey=0-qKW4qUfEeuPB-XinmDBSHQ" width="240" alt="1988 - M490M - P016 - 5-3.jpg"></a><br><sub>1988|21 · P016 - 5-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaF9IS1VoNmRyc0E/view?resourcekey=0-fta092PAqHDB5uiyBYradg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaF9IS1VoNmRyc0E&resourcekey=0-fta092PAqHDB5uiyBYradg" width="240" alt="1988 - M490M - P017 - 5-4.jpg"></a><br><sub>1988|21 · P017 - 5-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS0llT0Q4QkFtQUk/view?resourcekey=0-V6y6X5sj1-JtPOr5wkYAjw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS0llT0Q4QkFtQUk&resourcekey=0-V6y6X5sj1-JtPOr5wkYAjw" width="240" alt="1988 - M490M - P018 - 5-5.jpg"></a><br><sub>1988|21 · P018 - 5-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVm9OLXZqdi1RUDQ/view?resourcekey=0-0riFvJLibqCg6mgc70naKA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVm9OLXZqdi1RUDQ&resourcekey=0-0riFvJLibqCg6mgc70naKA" width="240" alt="1988 - M490M - P019 - 5-6.jpg"></a><br><sub>1988|21 · P019 - 5-6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQlI3aUdiOHIyQ2M/view?resourcekey=0-3GlfudkObTM8VdIIzf8hUg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQlI3aUdiOHIyQ2M&resourcekey=0-3GlfudkObTM8VdIIzf8hUg" width="240" alt="1988 - M490M - P020 - 5-7.jpg"></a><br><sub>1988|21 · P020 - 5-7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNmJ2VGdGMHJ5SW8/view?resourcekey=0-xk7A5HhqQcz74rLdVv9BtQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNmJ2VGdGMHJ5SW8&resourcekey=0-xk7A5HhqQcz74rLdVv9BtQ" width="240" alt="1988 - M490M - P021 - 5-8.jpg"></a><br><sub>1988|21 · P021 - 5-8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcDQ2NUwzbTFnVTA/view?resourcekey=0-LVGnPl2XXCyLdhjODxCvOA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcDQ2NUwzbTFnVTA&resourcekey=0-LVGnPl2XXCyLdhjODxCvOA" width="240" alt="1988 - M490M - P022 - 6-1.jpg"></a><br><sub>1988|21 · P022 - 6-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaXVLZ3N3bFJMUE0/view?resourcekey=0-CFT8kQE4a2kJg5J9nw2Dkg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaXVLZ3N3bFJMUE0&resourcekey=0-CFT8kQE4a2kJg5J9nw2Dkg" width="240" alt="1988 - M490M - P023 - 6-2.jpg"></a><br><sub>1988|21 · P023 - 6-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQmVudnVlTTNwSzQ/view?resourcekey=0-AaVPPNTW9rq2NX3KSYtLGQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQmVudnVlTTNwSzQ&resourcekey=0-AaVPPNTW9rq2NX3KSYtLGQ" width="240" alt="1988 - M490M - P028.jpg"></a><br><sub>1988|21 · P028</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRUJZaWc0OW9YeTA/view?resourcekey=0-Bx_vdNKCfzsJEWKWECrRGg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRUJZaWc0OW9YeTA&resourcekey=0-Bx_vdNKCfzsJEWKWECrRGg" width="240" alt="1988 - M490M - P029 - SA14-120.jpg"></a><br><sub>1988|21 · P029 - SA14-120</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRDBwRGlTNm93SGM/view?resourcekey=0-6PtBYZU6Znqxv1anlgw6Xg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRDBwRGlTNm93SGM&resourcekey=0-6PtBYZU6Znqxv1anlgw6Xg" width="240" alt="1988 - M490M - P030 - SA14-120 - 1-1.jpg"></a><br><sub>1988|21 · P030 - SA14-120 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbFJ5QjNZYV9CWE0/view?resourcekey=0-Qv4hAZuU7caEmnEP8H4dTg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbFJ5QjNZYV9CWE0&resourcekey=0-Qv4hAZuU7caEmnEP8H4dTg" width="240" alt="1988 - M490M - P031 - SA14-120 - 1-2.jpg"></a><br><sub>1988|21 · P031 - SA14-120 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcXU1MG4zWjNKMms/view?resourcekey=0-gfkAxzVpWQG0XsaAfS9oXQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcXU1MG4zWjNKMms&resourcekey=0-gfkAxzVpWQG0XsaAfS9oXQ" width="240" alt="1988 - M490M - P032 - SA14-120 - 2-1.jpg"></a><br><sub>1988|21 · P032 - SA14-120 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRE1oNDhjVVhHcFU/view?resourcekey=0-CSKUXJjOIRZIj8mPJAHRZw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRE1oNDhjVVhHcFU&resourcekey=0-CSKUXJjOIRZIj8mPJAHRZw" width="240" alt="1988 - M490M - P033 - SA14-120 - 2-2.jpg"></a><br><sub>1988|21 · P033 - SA14-120 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYjdTTnp3QldudDg/view?resourcekey=0-K5HLVI3wq4dy3PN7834Xlg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYjdTTnp3QldudDg&resourcekey=0-K5HLVI3wq4dy3PN7834Xlg" width="240" alt="1988 - M490M - P034 - SA14-120 - 2-3.jpg"></a><br><sub>1988|21 · P034 - SA14-120 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdGdrcV9BREZJeGM/view?resourcekey=0-OjZfzS3tXbbODizjir5Ymg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdGdrcV9BREZJeGM&resourcekey=0-OjZfzS3tXbbODizjir5Ymg" width="240" alt="1988 - M490M - P035 - SA14-120 - 2-4.jpg"></a><br><sub>1988|21 · P035 - SA14-120 - 2-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkZOYkhKM2M0R0U/view?resourcekey=0-N74H_z2508zyve58O4GZOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkZOYkhKM2M0R0U&resourcekey=0-N74H_z2508zyve58O4GZOw" width="240" alt="1988 - M490M - P036 - SA14-120 - 2-5.jpg"></a><br><sub>1988|21 · P036 - SA14-120 - 2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVjhOZnphcHlBOFk/view?resourcekey=0-MQXO_BAX7uiXRzAukoQFJw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVjhOZnphcHlBOFk&resourcekey=0-MQXO_BAX7uiXRzAukoQFJw" width="240" alt="1988 - M490M - P037 - SA14-120 - 2-6.jpg"></a><br><sub>1988|21 · P037 - SA14-120 - 2-6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMmpnNUprTEVZMmM/view?resourcekey=0-eVEtvcuY6dqgfmwMkviYjg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMmpnNUprTEVZMmM&resourcekey=0-eVEtvcuY6dqgfmwMkviYjg" width="240" alt="1988 - M490M - Stereo Input Module (2).pdf"></a><br><sub>1988|21 · Stereo Input Module (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRWtQZ3p0SGNHN0U/view?resourcekey=0-QQv1Xym5NInecwtu81Ou9A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRWtQZ3p0SGNHN0U&resourcekey=0-QQv1Xym5NInecwtu81Ou9A" width="240" alt="1988 - M490M - Stereo Input Module.pdf"></a><br><sub>1988|21 · Stereo Input Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX3NZYTBMOWZ5czA/view?resourcekey=0-JKJqYxo_tEvHPKphJnEPNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX3NZYTBMOWZ5czA&resourcekey=0-JKJqYxo_tEvHPKphJnEPNA" width="240" alt="1992 - M490M - P001 - Title Page.jpg"></a><br><sub>1992|25 · P001 - Title Page</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1988 - M490M - 14-120-02-001 - COMMON COMMON SPEC IFIED LAST COMPONENT DESIGNA.kicad_sch](KICAD/1988%20-%20M490M%20-%2014-120-02-001%20-%20COMMON%20COMMON%20SPEC%20IFIED%20LAST%20COMPONENT%20DESIGNA.kicad_sch)
- [1988 - M490M - 14-120-02-001 - UNLESS OTHERWISE SPECIFIED IODES ARE.kicad_sch](KICAD/1988%20-%20M490M%20-%2014-120-02-001%20-%20UNLESS%20OTHERWISE%20SPECIFIED%20IODES%20ARE.kicad_sch)
- [1988 - M490M - 490-01-013 - OFFA ON-START TIMER RESET OFF TALLY OFF.kicad_sch](KICAD/1988%20-%20M490M%20-%20490-01-013%20-%20OFFA%20ON-START%20TIMER%20RESET%20OFF%20TALLY%20OFF.kicad_sch)
- [1988 - M490M - 490-01-013 - STEREO INPUT MODULE FUNCTIONAL.kicad_sch](KICAD/1988%20-%20M490M%20-%20490-01-013%20-%20STEREO%20INPUT%20MODULE%20FUNCTIONAL.kicad_sch)
- [1988 - M490M - 490-02-013 - CRIZ OFF EXT.kicad_sch](KICAD/1988%20-%20M490M%20-%20490-02-013%20-%20CRIZ%20OFF%20EXT.kicad_sch)
- [1988 - M490M - 490-02-013 - LAST COMPONENT DESICMAT IONS.kicad_sch](KICAD/1988%20-%20M490M%20-%20490-02-013%20-%20LAST%20COMPONENT%20DESICMAT%20IONS.kicad_sch)
- [1988 - M490M - Stereo Input Module (2) p43.kicad_sch](KICAD/1988%20-%20M490M%20-%20Stereo%20Input%20Module%20(2)%20p43.kicad_sch)
- [1988 - M490M - Stereo Input Module p27.kicad_sch](KICAD/1988%20-%20M490M%20-%20Stereo%20Input%20Module%20p27.kicad_sch)
- [1988 - M490M - Stereo Input Module p29.kicad_sch](KICAD/1988%20-%20M490M%20-%20Stereo%20Input%20Module%20p29.kicad_sch)
- [1988 - M490M - Stereo Input Module p43.kicad_sch](KICAD/1988%20-%20M490M%20-%20Stereo%20Input%20Module%20p43.kicad_sch)
- [M490M.kicad_sym](KICAD/M490M.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
