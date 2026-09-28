# Chapter 05 — Kikujutsu: Carpentry Geometry (規矩術 / kikujutsu)

**Scope.** This chapter covers the carpenter's layout geometry of sloped, splayed and curved work: how Japanese carpenters state a slope, name the lines of the slope triangle, and use the carpenter's square (差金 / 曲尺, *sashigane* / *kanejaku*) to lay out every cut on rafters, hips, valleys, splayed posts and boxes, and curved eaves. It gives the traditional vocabulary with exact modern formulas, worked numeric examples (4-sun and 5-sun roofs, a 3.3-sun splayed stool), and the classic training exercises. Roof *framing* (what the members are, how big they are, how they go together) is in → Ch. 11. Units, the sashigane scales and marking symbols are introduced in → Ch. 02, tools in → Ch. 04, and the historical texts in → Ch. 01.

A note on sources. Sections 4–8 give each traditional named cut with the formula it corresponds to. The formulas were derived and checked numerically for this book (three-dimensional vector geometry). Where a traditional name is attached to a formula, the attribution follows current Japanese kikujutsu textbooks as far as the author could check them. Textbooks and schools do not always agree on names, so the **formula** is the authority and the name is a label. Uncertain attributions are flagged.

## Contents

1. Concept and history
2. The sashigane as a geometric instrument
3. Slope notation (勾配 *kōbai*)
4. The slope triangle and its derived lines (勾・殳・玄, 中勾, 長玄, 短玄 …)
5. Common rafter geometry, 峠 *tōge* and 口脇 *kuchiwaki*
6. Hips and valleys on a square corner (棒隅 *bō-sumi*)
7. Worked examples: 4-sun and 5-sun hip roofs
8. Uneven-pitch hips (振れ隅 *fure-sumi*) and polygonal plans
9. Splayed members (転び *korobi*, 四方転び *shihō-korobi*)
10. Curved eaves (軒反り *nokizori*) and fan rafters (扇垂木 *ōgi-daruki*)
11. Training exercises
12. Rule index and common errors

---

## 1. Concept and history

### 1.1 What kikujutsu is

**Kikujutsu** (規矩術) means literally "the art of the compass (規 *ki*) and the square (矩 *ku*)". In carpentry it is the body of geometric methods by which a carpenter turns a roof or frame, given as a plan, a height and a slope, into cut lines on the faces of individual timbers. The same timber meets several planes at once: a hip rafter lies in two roof planes and crosses two wall-plates at 45° in plan. The carpenter cannot measure the angles of those intersections directly. Kikujutsu lets him **derive them from a few simple inputs (run, rise, plan angle) with nothing but the sashigane, a straight-edge and a line**. No protractor or trigonometric table is needed.

In practice kikujutsu is used for:

- the cuts of common rafters (垂木 *taruki*), wall-plates (桁 *keta*) and purlins (母屋 *moya*) under a slope;
- the hip (隅木 *sumigi*) and valley (谷木 *tanigi*) and the jack rafters (配付垂木 *haitsuke-daruki*) that meet them;
- mitres of fascia (鼻隠し *hanakakushi*), eave boards (茅負 *kayaoi*, 裏甲 *urakō*, 広小舞 *hirokomai*) around a corner;
- splayed posts and boards (転び *korobi*): torii, bell towers, stools, boxes, water-basin stands;
- the curved eaves of temples and shrines (軒反り *nokizori*) and fan-rafter layouts (扇垂木 *ōgi-daruki*).

### 1.2 Mathematical origin

Kikujutsu rests on the right-triangle theorem. East Asian mathematics knew it as 勾股弦 (Chinese *gōu-gǔ-xián*): 勾 is the short leg, 股 the long leg, 弦 the hypotenuse. In the Japanese carpentry tradition the same three sides are written **勾 (*kō*) – 殳 (*ko*) – 玄 (*gen*)**. 殳 is a carpenter's substitute for 股, pronounced the same; 玄 stands for 弦. Texts use both spellings, and 勾股弦 and 勾殳玄 mean the same thing.

**R05-001** — *Must.* All kikujutsu cuts are derived from the right triangle whose horizontal leg is the run (殳), whose vertical leg is the rise (勾) and whose hypotenuse is the slope length (玄). Before marking any roof member, the carpenter fixes this "base triangle" (基本図 *kihon-zu*) for the common slope. *Why:* every other line (hip, jack, mitre) is a transformation of this triangle. An error in it propagates to every member.

### 1.3 Development in the Edo period

The historical detail is handled in → Ch. 01. For practice, the essentials are these:

- **Medieval secrecy.** Before the Edo period, roof and eave layout was transmitted within carpenter lineages as secret or oral teaching (秘伝 *hiden*). The kiwari proportion books such as 『匠明』 *Shōmei* (1608, Heinouchi family; → Ch. 01, → Ch. 12) record proportions rather than layout geometry.
- **Hinagata books.** From the late 17th and 18th centuries, printed pattern books (雛形本 *hinagata-bon*) spread standard forms. Geometry for eaves and hips began to appear in print in the late Edo period.
- **Heinouchi Masaomi (平内廷臣, d. 1856; birth year given as 1791 or 1799).** Master carpenter of the shogunate. He is generally credited with putting carpentry geometry on a systematic mathematical footing, drawing on Japanese mathematics (和算 *wasan*). His 『匠家矩術要解』 *Shōka kujutsu yōkai* (1833, Tenpō 4; published under his title 平内安房) and 『矩術新書』 *Kujutsu shinsho* (1848) are the classic treatises (details and verification in → Ch. 01).
- **Other late-Edo eave treatises** exist, for example works with titles of the type 『規矩真術軒廻図解』 (*Kiku shinjutsu nokimawari zukai*, "illustrated true kikujutsu of eave work"). This book does not assign authors or dates to them. See → Ch. 01.
- **A caution on 『規矩元法』 *Kiku genpō*.** A work of this title held in Japanese collections (the National Diet Library "Edo no sūgaku" exhibition describes a copy) is a **surveying** text of the Shimizu school (清水流). It deals with measuring elevation and depression angles with a sighting instrument, not with carpentry. In the 17th–18th centuries 規矩術 also named the surveying art. Do not cite 『規矩元法』 as a carpentry-geometry source unless a specific carpentry text of that name is identified.
- **Meiji to present.** Meiji-era books such as 『建築規矩術原理図解』 recast kikujutsu in terms of descriptive geometry. Twentieth-century textbooks (for example 富樫新三『図でわかる規矩術』, Ohmsha, now in a 2nd edition, and 大工道具研究会編『図解 規矩術の基礎と実践』, Seibundō Shinkōsha) are the working references today. Kikujutsu is still examined in the national carpentry skills test (建築大工技能検定).

### 1.4 The two families of method

Carpenters and textbooks distinguish two ways to get a cut line. Both give the same answer when done correctly.

**(a) The triangle-line method (勾殳玄法 *kōkogen-hō*).** The carpenter does not draw the building. He constructs the base triangle and its named derived lines (中勾, 長玄, 短玄 …, § 4) at full size, usually on the timber itself or on a board, and transfers the needed ratio straight to the member with the sashigane: "top mitre of the fascia = 長玄 against 殳" and so on. The method is fast and portable, suited to the site and to repetitive work, and it is what most working carpenters mean by kikujutsu. Its weakness is that it is memorised. If a carpenter meets a case outside the memorised table (an uneven hip, a splayed fascia, a curved eave), the named-line recipes can be misapplied.

**(b) The drawing (projection) method (図法 *zuhō*).** The carpenter draws plan and elevation at full size (現寸図 *genzu*, on a board floor or plywood; → Ch. 04). He then finds the true shape of each face by rotating it into the drawing plane. The main techniques are:

- **展開 (*tenkai*)**, development: unfolding the faces of a member;
- **小平起こし (*kobira-okoshi*)**, "raising a small plane": rotating a sloped plane about a horizontal line until it lies flat on the drawing, to see true angles;
- **投げ墨 (*nage-zumi*)**, "thrown lines": projecting a reference plane (a wall-plate centre, a fascia face, a plumb or square plane) onto the faces of an inclined member. Current usage applies 投げ墨 above all to the lines on the side of a hip that represent a plane square to the common rafters (§ 6.7).

Drawing methods are slower but general: they solve any case, including those no named recipe covers. Late-Edo and later texts also list sub-methods such as calculation (算定法), sectioning (切断法) and ellipse methods (楕円法) for curved work.

**R05-002** — *Should.* Use the triangle-line method for standard cases (equal-pitch 45° hips, standard splays). Use a full-size drawing (現寸図) for every non-standard case: uneven pitch, non-right corners, curved eaves, fan rafters. *Why:* named recipes are valid only under the assumptions they were derived for. A drawing checks itself.

**R05-003** — *Must.* When a named-line recipe and a full-size drawing disagree, the drawing (if correctly projected) governs, and the recipe's assumptions must be re-examined. *Why:* recipes are mnemonics for particular geometric situations. The most common error is applying the equal-pitch recipe to an uneven hip (§ 8).

---

## 2. The sashigane as a geometric instrument

The sashigane is described in → Ch. 02 and → Ch. 04. Here only its geometric functions matter.

### 2.1 Scales

| Scale | Japanese | Graduation | Geometric use |
|---|---|---|---|
| Front scale | 表目 *omote-me* | ordinary sun/bu (or mm) | all normal measurement; 勾 and 殳 |
| Back "square" scale | 裏目 *ura-me*, also 角目 *kaku-me* | 表目 × √2 (one "sun" of ura-me is 1.4142 real sun) | reading a diameter gives the side of the inscribed square; laying the plan run of a 45° hip; mitres |
| Round scale | 丸目 *maru-me* (not on all squares) | 表目 ÷ π | reading a diameter gives the circumference |

The two arms are the **long arm** (長手 *nagate*, c. 1 shaku 5 sun, ≈455–500 mm) and the **short arm** (妻手 *tsumate*, c. 7.5 sun). The outside corner is the **矩 (*kane*)**, a true right angle.

**R05-004** — *Must.* Check the square for true (矩) before any kikujutsu layout. Draw a line along the long arm from a straight edge, flip the square, draw again; the two lines must coincide. *Why:* a square out by 0.5 mm over 7.5 sun puts a hip mitre visibly open. Check also that the arms are flat (not twisted).

### 2.2 Basic sashigane operations

1. **Laying a slope (勾配を引く).** Place the square on the face of the timber so that the long arm reads the run (殳, usually 10 sun) and the short arm reads the rise (勾) exactly at the **same edge** (arris) of the timber. A line drawn along the short arm is then **plumb** (立水 *tatemizu*, 垂直); a line along the long arm is **level** (陸水 *rokumizu*, 水平). Readings are taken on the outside edges of the arms by convention. Whichever edge is used, use it consistently.
2. **Square cut (直角).** Interchange the readings (勾 on the long arm, 殳 on the short arm, or equivalently use the 返し勾配, § 3.3). The line along the short arm is then square to the member's slope line.
3. **√2 multiplication (裏目).** A length read in 裏目 units is physically √2 times the same number in 表目. Laying "10 sun on 裏目" on the long arm with the rise on a 表目 scale on the short arm gives the **hip slope** (§ 6.2) directly.
4. **45° mitre (留め *tome*).** Place equal readings on both arms at the same edge (e.g. 5 and 5); the line joining the two readings, or drawn along either arm, makes 45° with the edge.
5. **Dividing a width (等分).** To divide a board of width *b* into *n* equal parts, lay the square diagonally across the board so that a number conveniently divisible by *n* (e.g. 6 sun for 3 parts) spans exactly from edge to edge. Mark the intermediate readings, then draw parallels through them.
6. **Parallel lines (平行線).** Slide the square along a straight-edge (or a line struck with the 墨壺 *sumitsubo*) without rotating it.
7. **Largest square from a log (丸太の角).** Measure the small-end diameter with the 裏目. The number read is the side of the largest square that can be sawn from it (d/√2). The same scale gives the planed "角" of a log beam (→ Ch. 03, → Ch. 11 § 10).
8. **Circumference (丸目).** A diameter read on the 丸目 gives the circumference directly (used for 丸桁, round posts, fitting round rafters of the 地円飛角 type).

**R05-005** — *Must.* Take both readings of a slope on the same arris and the same side (outside or inside) of both arms. *Why:* mixing an inside reading on one arm with an outside reading on the other changes the ratio by the arm width (15 mm) and corrupts the slope.

**R05-006** — *Should.* For layouts that must be repeated (many common rafters, many jacks), cut the slope once into a thin board as a template (型板 *kataita*, or a 勾配定規 *kōbai-jōgi*) and mark from it. The sashigane is used to make and check the template, not for every stroke. *Why:* repeated settings of the square accumulate small reading errors. → Ch. 04.

---

## 3. Slope notation (勾配 kōbai)

### 3.1 The sun-per-shaku convention

A Japanese roof slope is stated as **rise in sun for 1 shaku (10 sun) of horizontal run**:

- **4寸勾配 *yon-sun kōbai*** (4-sun slope): rises 4 sun per 10 sun of run, ratio 0.4, ≈21.8°.
- **5寸勾配** (5-sun slope): ratio 0.5, ≈26.6°.
- **矩勾配 *kane-kōbai*** ("square slope"): 10 sun per 10 sun, ratio 1.0, exactly 45°.
- Slopes steeper than 矩 are stated as 1尺2寸勾配 (12 sun, ratio 1.2) and so on. Some texts call them 矩以上 or use the reciprocal (返し, § 3.3).

The same notation works metrically (4/10, 5/10). On modern drawings it appears as a small triangle with "4" over "10" next to the roof line. Half-sun values (3.5寸, 4.5寸) are common. Finer fractions (e.g. 4寸2分) occur in temple work, where the slope is often fixed by proportion (→ Ch. 12).

### 3.2 Conversion table

The run (殳) is fixed at 10. 玄 is the slope length per 10 of run, and 玄/殳 is the factor that converts horizontal run to slope length. 中勾, 長玄 and 短玄 are defined in § 4. The last three columns belong to the 45° hip over an equal-pitch roof (§ 6).

| 勾配 (sun) | ratio *t* | angle | 玄 | 玄/殳 (length factor) | 中勾 | 長玄 | 短玄 | 返し勾配 (sun) | hip angle | 隅玄 | hip length factor 隅玄/殳 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 0.10 | 5.71° | 10.050 | 1.0050 | 0.995 | 9.950 | 0.100 | 100 | 4.04° | 14.177 | 1.4177 |
| 2 | 0.20 | 11.31° | 10.198 | 1.0198 | 1.961 | 9.806 | 0.392 | 50 | 8.05° | 14.283 | 1.4283 |
| 2.5 | 0.25 | 14.04° | 10.308 | 1.0308 | 2.425 | 9.701 | 0.606 | 40 | 10.02° | 14.361 | 1.4361 |
| 3 | 0.30 | 16.70° | 10.440 | 1.0440 | 2.873 | 9.578 | 0.862 | 33.3 | 11.98° | 14.457 | 1.4457 |
| 3.5 | 0.35 | 19.29° | 10.595 | 1.0595 | 3.304 | 9.439 | 1.156 | 28.6 | 13.90° | 14.569 | 1.4569 |
| 4 | 0.40 | 21.80° | 10.770 | 1.0770 | 3.714 | 9.285 | 1.486 | 25 | 15.79° | 14.697 | 1.4697 |
| 4.5 | 0.45 | 24.23° | 10.966 | 1.0966 | 4.104 | 9.119 | 1.847 | 22.2 | 17.65° | 14.841 | 1.4841 |
| 5 | 0.50 | 26.57° | 11.180 | 1.1180 | 4.472 | 8.944 | 2.236 | 20 | 19.47° | 15.000 | 1.5000 |
| 5.5 | 0.55 | 28.81° | 11.413 | 1.1413 | 4.819 | 8.762 | 2.651 | 18.2 | 21.25° | 15.174 | 1.5174 |
| 6 | 0.60 | 30.96° | 11.662 | 1.1662 | 5.145 | 8.575 | 3.087 | 16.7 | 22.99° | 15.362 | 1.5362 |
| 7 | 0.70 | 34.99° | 12.207 | 1.2207 | 5.735 | 8.192 | 4.014 | 14.3 | 26.33° | 15.780 | 1.5780 |
| 8 | 0.80 | 38.66° | 12.806 | 1.2806 | 6.247 | 7.809 | 4.998 | 12.5 | 29.50° | 16.248 | 1.6248 |
| 9 | 0.90 | 41.99° | 13.454 | 1.3454 | 6.690 | 7.433 | 6.021 | 11.1 | 32.47° | 16.763 | 1.6763 |
| 10 (矩) | 1.00 | 45.00° | 14.142 | 1.4142 | 7.071 | 7.071 | 7.071 | 10 | 35.26° | 17.321 | 1.7321 |
| 11 | 1.10 | 47.73° | 14.866 | 1.4866 | 7.399 | 6.727 | 8.139 | 9.1 | 37.88° | 17.916 | 1.7916 |
| 12 | 1.20 | 50.19° | 15.620 | 1.5620 | 7.682 | 6.402 | 9.219 | 8.3 | 40.32° | 18.547 | 1.8547 |

(Computed: 玄 = √(100 + h²); 中勾 = 10h/玄; 長玄 = 100/玄; 短玄 = h²/玄; hip angle = arctan(h / 10√2); 隅玄 = √(200 + h²).)

Two values in the table are worth remembering. For the **5-sun slope** the hip length factor is exactly **1.5** (隅玄 = 15.000), because 200 + 25 = 225 = 15². For **矩勾配** the three lines 中勾 = 長玄 = 短玄 are equal to 7.071 (= 10/√2).

**R05-007** — *Must.* State every slope on drawings and story-poles in the sun-per-shaku form (or its metric equivalent x/10), with the run as the reference leg. Never use degrees alone. *Why:* all sashigane layout is done with the ratio. Degrees must be converted back and invite rounding errors. Degrees may be added in brackets for information.

**R05-008** — *Must.* Distinguish a slope in sun per shaku from a slope in sun per ken or per total span. A "4-sun roof" rises 4 sun per 1 shaku of **horizontal run from the wall-plate line toward the ridge**, not per shaku of span. *Why:* confusing run with half-span or span doubles or halves the rise. The total rise of a 4-sun gable of 3 ken (18 shaku) span is 9 shaku × 0.4 = 3.6 shaku, not 7.2.

### 3.3 Derived slope names

- **返し勾配 *kaeshi-kōbai*** (return, or reciprocal, slope). The slope obtained by interchanging 勾 and 殳: *t* becomes 1/*t*. In sun per shaku it is 100/*h* (4 sun gives 25 sun, i.e. 2尺5寸勾配; 5 sun gives 20 sun). It is the complement of the original angle (21.8° becomes 68.2°). **Use:** the cut square to a sloping member (直角切り), laid out as a slope from the plumb; the face of a fascia set square to the rafters; the lean of splayed members stated from the vertical (§ 9). Some texts call the 返し勾配 of a splay the 転び勾配.
- **半勾配 *han-kōbai*** (half slope). The slope with half the rise: half of 4 sun is 2 sun. Current training material uses it in some procedures for marking the underside (下端) of a hip where it sits over the wall-plates. **Flag:** this book does not derive or verify those procedures. Use the half-slope only inside the specific textbook procedure that prescribes it, and check the result against a full-size drawing.
- **倍勾配 *bai-kōbai*** (double slope). Twice the rise (4 sun gives 8 sun). The term appears in some slope lists. **Flag:** the author has not verified a standard application in layout. Like the half-slope it is a label, not an independent geometric principle.
- **隅勾配 *sumi-kōbai*** (hip slope). The slope of the hip itself: rise 勾 over the plan run of the hip. For a 45° hip that run is 10√2, "10 sun on the 裏目" (§ 6.2).
- **隅返し勾配 *sumi-kaeshi-kōbai*.** The reciprocal of the hip slope, i.e. square to the hip in its own vertical plane.
- **中勾勾配, 長玄勾配, 短玄勾配** (and their 隅 versions): see § 4.4.

**R05-009** — *Must.* Cut a line square to a sloped member with the 返し勾配 of that member's own slope: the common slope for common rafters, the **hip slope** for hips. *Why:* using the common 返し勾配 on a hip (a frequent error) gives a cut that is not square to the hip. The hip lies at a shallower angle (15.79° against 21.80° for a 4-sun roof).

---

## 4. The slope triangle and its derived lines

### 4.1 The three sides

```
                           A (top, at ridge side)
                          /|
                         / |
               玄 gen   /  |  勾 kō  (rise, vertical)
         (slope length)/   |
                      /    |
                     /     |
                    B------C
                     殳 ko (run, horizontal = 10 sun)

    right angle at C;  angle at B = slope angle θ;  tan θ = 勾/殳 = t
```

- **勾 *kō*** — the vertical leg (rise). For an *h*-sun slope with 殳 = 10, 勾 = *h*.
- **殳 *ko*** — the horizontal leg (run), conventionally 10 sun (1 shaku).
- **玄 *gen*** — the hypotenuse (slope length) = √(殳² + 勾²).

### 4.2 中勾, 長玄, 短玄

Drop a perpendicular from the right angle C to the hypotenuse AB, meeting it at D.

```
      A
      |`.
      |  `.        短玄 tangen = AD
      |    `.
      |      D
   勾 |     / `.
      |    /    `.
      |   / 中勾   `.     長玄 chōgen = DB
      |  /  chūkō    `.
      | /              `.
      |/                 `.
      C--------------------B
                殳

   C = right angle;  D = foot of the perpendicular from C onto AB (玄)
   CD = 中勾 (chūkō)   "middle 勾": the altitude onto the hypotenuse
   DB = 長玄 (chōgen)  "long 玄": the hypotenuse segment next to 殳
   AD = 短玄 (tangen)  "short 玄": the hypotenuse segment next to 勾
```

**Definitions and formulas** (slope ratio *t* = 勾/殳, angle θ):

| Line | Definition | Formula | In terms of θ, for 殳 = 1 |
|---|---|---|---|
| 中勾 *chūkō* | perpendicular from the right angle to 玄 | 勾·殳 / 玄 | sin θ |
| 長玄 *chōgen* | part of 玄 between B (the 殳 end) and D | 殳² / 玄 | cos θ |
| 短玄 *tangen* | part of 玄 between D and A (the 勾 end) | 勾² / 玄 | sin θ · tan θ |

Identities that serve as checks: 長玄 + 短玄 = 玄; 中勾² = 長玄 × 短玄; 中勾 / 長玄 = 勾 / 殳 = *t*; 中勾 / 短玄 = 殳 / 勾 = 1/*t*.

For a 4-sun slope with 殳 = 10: 玄 = 10.770, 中勾 = 3.714, 長玄 = 9.285, 短玄 = 1.486. Check: 9.285 + 1.486 = 10.771 ≈ 10.770 (rounding), and 3.714² = 13.79 ≈ 9.285 × 1.486 = 13.80.

### 4.3 Higher-order lines

The subdivision can be repeated on the small triangles CDA and CDB, which are similar to the original. Textbooks name several further lines. The one met most often is:

- **小中勾 *shōchūkō*** ("small 中勾"). One definition circulating in current glossaries: from D (foot of 中勾) draw a line parallel to 殳 until it meets 勾; from that point drop a perpendicular to 玄. That perpendicular is 小中勾. By this definition its length is 中勾 × (勾/玄)² = 10*h*³/玄³ (0.512 sun for a 4-sun slope). It is used in some higher-order mitres of eave members (茅負, 裏甲) where two slopes compound. **Flag:** definitions and uses of 小中勾 vary between texts. Confirm against the textbook you follow.
- **欠勾 *kekkō* (reading uncertain).** This term appears in some kikujutsu terminology lists. The author could not confirm a standard definition, and the book gives none. Do not use it without a primary source.

**R05-010** — *Should.* Construct 中勾, 長玄 and 短玄 **graphically at full size** (draw the triangle with 殳 = 10 sun on a board, drop the perpendicular with the square, and read the lengths) rather than from memorised decimals, and confirm with the identity 長玄 + 短玄 = 玄. *Why:* the construction is the traditional method, needs no arithmetic, and checks itself. Memorised decimals are the usual source of transposed-digit errors.

### 4.4 Named slopes: using the derived lines as rises

In the triangle-line method each derived line is turned into a **slope** by setting it on the short arm (in the place of 勾) against 殳 = 10 on the long arm. This book uses the convention "X-勾配 means X : 殳". Most modern textbooks do the same, but check yours. For the **hip triangle** the base is the hip run 隅殳 (10 on the 裏目), so 隅中勾勾配 means 隅中勾 : 隅殳.

| Named slope | Ratio set on the square | tan of the line's angle | 4-sun value | 5-sun value |
|---|---|---|---|---|
| 勾配 (平勾配 *hira-kōbai*) | 勾 : 殳 | tan θ = *t* | 0.400 (21.80°) | 0.500 (26.57°) |
| 返し勾配 | 殳 : 勾 | 1/*t* | 2.500 (68.20°) | 2.000 (63.43°) |
| 中勾勾配 | 中勾 : 殳 | sin θ | 0.371 (20.38°) | 0.447 (24.09°) |
| 長玄勾配 | 長玄 : 殳 | cos θ | 0.928 (42.88°) | 0.894 (41.81°) |
| 短玄勾配 | 短玄 : 殳 | sin θ tan θ | 0.149 (8.45°) | 0.224 (12.60°) |
| 玄勾配 (玄 : 殳) | 玄 : 殳 | 1/cos θ | 1.077 (47.12°) | 1.118 (48.19°) |

These few ratios, together with their hip (隅) equivalents built on the hip triangle (§ 6), cover nearly all the standard cuts. What each is used for:

| Cut | Ratio (this book's derivation) | Traditional name |
|---|---|---|
| Plumb and level cuts of a common rafter | 勾 : 殳 | 勾配 |
| Cut square to a common rafter | 殳 : 勾 | 返し勾配 |
| Top (上端) cut of a jack rafter against a 45° hip | along : across = 玄 : 殳 | "玄と殳" |
| Face mitre (向こう留め) of a fascia set square to the rafters, at a 45° corner | 中勾 : 殳 | 中勾勾配 |
| Top-edge mitre (上端留め) of that fascia, top edge square to its face | along : across = 長玄 : 殳 | 長玄勾配 |
| Top-edge butt (突付け) of that fascia | along : across = 短玄 : 殳 | 短玄勾配 |
| Backing (山勾配) of a 45° hip, in its true section | 隅中勾 : 隅殳 | 隅中勾勾配 |
| Face line (胴付き) of a splayed-box side | 中勾 : 殳 of the splay triangle | 中勾勾配 |

Sections 6 and 9 show where each of these comes from.

**R05-011** — *Must.* Record, on the template or story-pole, which line (勾, 中勾, 長玄 …), **which triangle** (common or hip) and **which face** each cut belongs to. *Why:* 中勾勾配 of the common triangle and 中勾勾配 of the hip triangle are different angles (20.38° and 15.23° for a 4-sun roof). Unlabelled templates are the main source of mis-cut hips and fascia mitres.

---

## 5. Common rafter geometry, 峠 and 口脇

### 5.1 The common rafter (平垂木 *hira-daruki*)

For a common rafter of slope *t*:

- **Plumb cuts** (the ridge end against the ridge-beam side, a plumb-cut eave end): laid with 勾 : 殳 along the short arm.
- **Level (seat) cuts** (the bird's-mouth seat on a plate, where one is cut): the long-arm line of the same setting.
- **Square cut** (eave end cut square to the rafter, 直角切り): 返し勾配.
- **Length** along the rafter = horizontal run × 玄/殳. A 9-shaku run at 4 sun gives 9 × 1.0770 = 9.693 shaku (≈2,937 mm).
- **Depth on a plumb line**: a rafter of depth *d* (measured square to its slope) has a plumb depth *d* × 玄/殳. A 2-sun rafter at 4-sun slope shows 2 × 1.077 = 2.154 sun on a plumb line. This matters whenever heights are transferred with a plumb story-pole.

**R05-012** — *Must.* Measure rafter lengths along a single consistent reference line: the top arris (上端), the bottom arris (下端), or the centreline. All seats and heights must be referred to the same line. *Why:* on a sloping member the top and bottom lines are separated by the plumb depth *d* × 玄/殳, so a seat or plumb cut located from the top line sits at a different point on the member than one located from the bottom line. Measuring from a point on one line to a point on the other mislocates the cut by that offset, and does so on every rafter.

### 5.2 峠 *tōge* and 口脇 *kuchiwaki*: the reference points on the plates

On a wall-plate (軒桁 *nokigeta*) or purlin that carries rafters, kikujutsu defines two reference lines. Current textbooks use the terms as follows (the terms also apply to the hip, § 6.3).

- **峠 *tōge*** ("the pass"): the line along the **plate centreline** (桁芯) at the level of the **underside of the rafters**. It is the reference height of the roof: the height of the next purlin or of the ridge is obtained by adding run × *t* to the 峠 height (峠から峠へ).
- **口脇 *kuchiwaki*** ("the lip line"): the line on the **outer face** of the plate where the rafter underside meets it, i.e. the outer arris of the plate's bevelled top.

When the plate top is bevelled to the rafter slope (typical of temple and shrine work, and of good house work in place of a notched rafter), the 口脇 lies **below** the 峠 by (half the plate width) × *t*. For a plate 4 sun wide under a 4-sun roof that is 2 × 0.4 = 0.8 sun (≈24 mm).

```
   Section through the wall-plate, square to its length.
   Eave (outside) on the left; the roof rises to the right.

                                            __.-' inner arris
                                      __.-''
                  峠 tōge       __.-''     <- plate top bevelled to slope t;
                     *   __.-''               rafter undersides bear on it
              __.-'' :''
   口脇 *.-''         :
        |            :                        |
        |            : 桁芯 (plate centreline) |
        |            :                        |
        +-------------------------------------+
     outer face                           inner face

   口脇 lies below 峠 by (plate width / 2) × t.
```

**R05-013** — *Must.* Set out all roof heights from the 峠 of the wall-plate (the rafter underside on the plate centreline), not from the plate top arris and not from the rafter top. *Why:* the 峠 is the only point that is the same for common rafters, hips and jacks at the plate line. It lets heights be carried consistently up to the ridge and across to the hip.

**R05-014** — *Should.* In traditional work, bevel the plate and purlin tops to the rafter slope (桁の上端削り) rather than cutting deep bird's-mouths into the rafters. *Why:* the rafter keeps its full depth over the support, and the bearing is a full face contact. In small modern houses rafters are often notched (垂木欠き) over square plates. That is acceptable where the notch depth stays small (a representative limit is one-third of the rafter depth).

---

## 6. Hips and valleys on a square corner (棒隅 bō-sumi)

A **棒隅 *bō-sumi*** ("straight hip") is the standard case: a 90° plan corner, equal slopes on both sides, equal eave heights. The hip then bisects the corner at 45° in plan. The **隅木 *sumigi*** (hip rafter) runs from the corner of the wall-plates up to the ridge. The **配付垂木 *haitsuke-daruki*** (jack rafters) run from the plates or eave up to the sides of the hip. A **谷木 *tanigi*** (valley rafter) is the same geometry at a re-entrant corner (入隅 *irizumi*) (§ 6.9). The framing context is in → Ch. 11 § 8.

### 6.1 Plan geometry: 隅殳 and the 裏目

At 45° in plan, one shaku of common run (distance from the eave line) corresponds to √2 shaku of run along the hip:

- **隅殳 *sumi-ko*** (hip run) = 殳 × √2 = 14.142 sun per 10 sun of common run.
- On the sashigane, 隅殳 is simply **"10 on the 裏目"**. This is the main reason the 裏目 exists on the square.

**R05-015** — *Must.* For a 45° hip, lay the hip's horizontal run with the 裏目 (or multiply by √2 = 1.4142). Do not treat the hip as having the same run as the common rafters. *Why:* the hip is 41% longer in plan. Every hip angle depends on this.

### 6.2 Hip slope (隅勾配), 隅玄 and hip length

The hip triangle has the same rise 勾 as the common triangle but the longer run 隅殳:

- **隅勾配** (hip slope) = 勾 : 隅殳 = *h* : 14.142, so tan α = *t*/√2.
- **隅玄 *sumi-gen*** (hip hypotenuse) = √(隅殳² + 勾²) = √(200 + *h*²) per 10 sun of common run.
- **Hip length** = common run × 隅玄/殳. Use the last column of the § 3.2 table: 1.4697 for 4 sun, exactly 1.5000 for 5 sun.

**Laying the hip plumb line with the square:** set **10 on the 裏目** of the long arm and ***h* on a 表目 scale** of the short arm at the same arris. The short arm then gives the plumb (立水) line and the long arm the level line of the hip. (Most sashigane carry a 表目 scale on the back of the short arm for this purpose. If yours does not, set 14.14 sun on the 表目 of the long arm instead.)

**R05-016** — *Must.* Mark all plumb and level cuts on the **sides of the hip** with the hip slope (勾 on 表目 against 10 on 裏目), never with the common slope. *Why:* the hip side is a vertical plane containing the hip axis. Plumb and level in that plane follow the hip's own inclination.

### 6.3 The hip top: 峠, 口脇 and the backing (山勾配 *yama-kōbai*)

The hip lies at the intersection of two roof planes, so its top must be **backed** (planed to a ridge, 山 *yama*) for both halves of the top to lie in the two roof planes and carry the roof boarding. The terms are:

- **峠 *tōge*** of the hip: the centreline of the hip top, the crest of the 山, lying on the true hip line. (**Flag:** some texts use 隅木の峠 also, by analogy with § 5.2, for the hip's reference point over the plate corner. Check which sense your text uses.)
- **口脇 *kuchiwaki*** of the hip: the two lines along the side faces where the backed top meets the sides (the upper arrises). They lie in the roof planes.
- **山勾配 *yama-kōbai*** (backing slope): the slope of each half of the top relative to a line square to the hip's side faces.

**Derivation.** Take a vertical plane square to the hip in plan. In it, both roof planes fall away from the hip line at *t*/√2 per unit of horizontal distance. That is numerically the hip slope itself. The hip's true cross-section, however, is square to the inclined hip axis. In that section the vertical is foreshortened by cos α, and the backing becomes

  tan(backing) = (*t*/√2) · cos α = sin α = 勾 / 隅玄 = **隅中勾 / 隅殳**,

where **隅中勾** = 勾 × 隅殳 / 隅玄 is the 中勾 of the hip triangle. Hence the traditional statement **"the hip backing is the 中勾勾配 of the hip" (隅木山勾配は隅中勾の勾配)**. The book's three-dimensional check gives the same value to four decimals.

| Slope | 隅中勾 (sun) | backing tan = 隅中勾/隅殳 | backing angle (true section) | backing in a plumb section (= hip slope) |
|---|---|---|---|---|
| 3 sun | 2.935 | 0.2075 | 11.72° | 0.2121 (11.98°) |
| 4 sun | 3.849 | 0.2722 | 15.23° | 0.2828 (15.79°) |
| 5 sun | 4.714 | 0.3333 | 18.43° | 0.3536 (19.47°) |
| 6 sun | 5.523 | 0.3906 | 21.34° | 0.4243 (22.99°) |
| 矩 (10) | 8.165 | 0.5774 | 30.00° | 0.7071 (35.26°) |

(隅中勾 = 10√2 · *h* / √(200 + *h*²).)

**Laying the backing with the square.** On the end of the hip, cut square to its axis, set 隅中勾 (read on the 表目) on the short arm against **10 on the 裏目** on the long arm, aligned with the hip's centreline. The resulting line is the backing from the 峠 down to each 口脇.

**Height of the 山.** For a hip of width *w*:
- measured square to the hip top (in the true section): (*w*/2) · sin α;
- measured **plumb on the hip side** (the usual way to strike the 口脇 line on the side): (*w*/2) · *t*/√2 = (*w*/2) × hip slope.

For *w* = 4 sun: 4-sun roof 0.566 sun plumb (≈17.1 mm), 5-sun roof 0.707 sun plumb (≈21.4 mm).

**R05-017** — *Must.* A visible (化粧 *keshō*) hip must be backed so that its 口脇 lines lie exactly in the two roof planes, with the backing equal to the hip-triangle 中勾勾配 in the hip's true section. *Why:* an unbacked hip either holds the roof boards off the jacks (if set high) or leaves the boards bridging a gap (if set low), and the corner line of the roof shows a kink.

**R05-018** — *Variant.* A hidden hip in a concealed roof (野隅木 *no-sumigi*, → Ch. 11 § 2.7) may be left flat-topped and **dropped** instead: set so low that its top arrises lie in the roof planes, with the centre left below the hip line. *Why:* planing a backing on a rough hidden member is wasted work, and the sheathing bears on the arrises. The drop equals the plumb 山 height above.

**R05-019** — *Must.* Distinguish the backing measured in a **plumb** section (= hip slope, *t*/√2) from the backing in the hip's **true** section (= sin α). Use the plumb value when striking lines on the plumb side face, and the true-section value when making a template to lay across the hip top or on a square-cut end. *Why:* the two differ by the factor cos α (3.7% at 4 sun, 5.7% at 5 sun). Mixing them leaves a visible step at the arris.

### 6.4 Plate-centre lines on the hip sides (投げ墨 of 桁芯)

Over the plate crossing, the hip centreline passes directly above the intersection of the two plate centrelines (the corner point, 隅の芯). The hip's two **side faces** are offset *w*/2 from the centreline, so each side face crosses each plate's centre plane at a different point:

- On each side face, the plate-centre plumb line of one plate is displaced **toward the eave** and that of the other plate **toward the ridge**. The displacement is *w*/2 in plan along the hip, because at 45° a perpendicular offset of *w*/2 produces an equal offset along the hip.
- Along the sloping arris this is (*w*/2) × 隅玄/隅殳. For *w* = 4 sun: 2.078 sun (4-sun roof), 2.121 sun (5-sun roof).
- Each of these lines is a hip-slope plumb line (§ 6.2).

**R05-020** — *Must.* Strike **two** plate-centre plumb lines on each side of the hip, one per plate, displaced by ±(*w*/2) in plan from the hip-centre corner point. Do not strike a single line opposite the corner point. *Why:* the hip side faces really do cross the plates at those points. Using the corner point on the side face mislocates the plate housings by half the hip width, which is the classic reason a hip "won't sit".

### 6.5 The hip's underside over the plates

Where the hip crosses the plates it is housed (欠き込み) over them, and the plate tops at the crossing are usually cut down as well (→ Ch. 11 § 8). On the hip's **underside**, the plate faces appear as lines crossing the hip obliquely. Across the hip width, each line advances along the hip by

  along : across = **隅玄 : 隅殳** (1.0392 at 4 sun, i.e. 46.10° from square; 1.0607 at 5 sun, 46.69°).

In plan the angle is exactly 45°. The extra comes from the hip's slope. On the side faces the plate faces are hip-slope plumb lines.

**Hip height at the corner.** Because the roof planes meet on the hip line, the **top centre (峠) of the hip over the corner point is at the height of the common-rafter tops over the plate centreline**. The hip's underside at the corner point is therefore lower by (plumb 山 height) + (hip side depth × 隅玄/隅殳). Compare this with the common rafter's underside (the plate 峠), which is below the rafter top by (rafter depth × 玄/殳). The difference is the depth that must be taken up by housing the hip and cutting the plate crossing. Worked values are in § 7.

**R05-021** — *Must.* Determine the hip's vertical position from the requirement that its 口脇 lie in the roof planes (i.e. from the common-rafter top height), and then derive the housing depth over the plates. Never start from the hip's underside resting on uncut plates. *Why:* a hip set on uncut plates stands proud of the roof planes by several sun. The jacks then cannot meet it and the roof corner humps.

### 6.6 Jack rafters (配付垂木)

Jack rafters are common rafters cut short against the hip side. Their geometry:

1. **Side cut (vertical faces):** a **plumb** line with the common slope (勾配), exactly as the common rafter's ridge cut. *Why:* both the jack side and the hip side are vertical planes. Their intersection is vertical.
2. **Top cut (上端留め) and bottom cut:** on the top face (which lies in the roof plane) the cut advances along the rafter by **玄 : 殳** per unit of width, i.e. along = width × 玄/殳 (4 sun: 1.077 × width, the cut line at 42.88° to the rafter's arris; 5 sun: 1.118 × width, 41.81°). The long point is on the side toward the corner. Left- and right-hand jacks are mirror images.
3. **Positions along the hip:** jacks spaced at *s* along the plate meet the hip at spacing *s* × 隅玄/殳 along the hip's slope (4 sun, *s* = 1.5 shaku: 2.2045 shaku). In plan along the hip the spacing is *s*√2, which is *s* read on the 裏目.
4. **Lengths:** the jack at distance *n*·*s* from the corner (to its centreline) has a length, from the plate centre to the hip **centreline**, of *n*·*s* × 玄/殳. Successive jacks therefore differ by a constant **decrement** *s* × 玄/殳. For *s* = 1.5 shaku (≈455 mm): 1.6155 shaku (≈489.6 mm) at 4 sun, 1.6771 shaku (≈508.2 mm) at 5 sun.
5. **Deduction for the hip's half-width:** the jack stops at the hip **side**, not the centreline. Measured along the jack in plan the deduction is (*w*/2)·√2. Conveniently, that is **half the hip width read on the 裏目**. Along the slope it becomes (*w*/2)·√2 × 玄/殳 (for *w* = 4 sun: 3.046 sun at 4 sun, 3.162 sun at 5 sun), taken to the centre of the skew cut.

**R05-022** — *Must.* Cut jack rafters with a plumb side cut and a top cut of 玄 : 殳 (for a 45° equal-pitch hip), and measure their lengths to the centre of the skew cut after deducting half the hip width on the 裏目. *Why:* this is the only combination for which every jack meets the hip face in full contact and its top lies in the roof plane.

**R05-023** — *Should.* Lay out jack positions on the hip side from the plate-centre line of **that side** (§ 6.4), stepping the spacing *s* × 隅玄/殳 along the arris. Do not step from the corner point. *Why:* see R05-020. The two sides of the hip are staggered by the hip width.

### 6.7 The hip end (隅木の鼻) and the thrown line (投げ墨)

The end of the hip at the eave is cut to line up with the fascia or eave boards of the two sides. Three cases:

- **(a) Plumb eave end** (fascia or kayaoi front face plumb). The hip end is cut on hip-slope plumb lines on both sides, and on the backed top by two lines parallel to the two eaves (see below).
- **(b) End square to the hip** (隅返し勾配). Occasionally used when the hip end projects as an independent feature. It does not line up with a fascia set square to the common rafters.
- **(c) Eave end square to the common rafters** (the common house detail of a 鼻隠し set 直角 to the rafters). Here the hip end must lie in the two planes that are square to the common rafters. On the hip side this plane shows as the **投げ墨 *nage-zumi***. Derivation: the plane square to the common rafters leans outward at the top by *h* per 10 of height (the common 返し勾配). The hip side runs at 45° to that plane in plan, so along the hip the lean becomes **h√2 per 10 of height**, i.e. the common 返し勾配 laid with ***h* read on the 裏目** against 10 on the 表目.
    - Compare the 隅返し勾配 (a line square to the hip): only *h*/√2 per 10 of height. The 投げ墨 leans **twice as much** as the hip's own square line.
    - At 4 sun, the 投げ墨 leans 5.657 sun per 10 sun of height (29.5° from plumb). The hip's square line leans 2.828 (15.8°) and the common square cut 4.0 (21.8°).

On the **backed top** of the hip, in all cases (a) and (c), each half of the nose is cut on a line parallel to its own eave, because any fascia plane containing the eave direction meets the roof plane along the eave direction. Measured on the backed half against the hip's axis, this line advances along the hip by **殳 : 玄** per unit across (from the 口脇 toward the 峠). That is the reciprocal of the jack's top cut, and the same number as the fascia's top mitre (長玄 : 殳 = 殳 : 玄), because both lines are the eave direction seen against a different axis.

**R05-024** — *Must.* Never cut the end of a hip "square" (隅返し勾配) and expect it to meet fascias that are set square to the common rafters. Use the 投げ墨 (common 返し with 勾 on the 裏目). *Why:* the two lines differ by a factor of two in lean. This is the classic error the 投げ墨 exercise is designed to prevent.

### 6.8 Mitres of fascia and eave boards at a hip (鼻隠し・茅負の留め)

Where two fascias (鼻隠し) or eave members (茅負, 広小舞) meet at the corner above the hip, their mitre depends on how they are set:

**Plumb fascia (face vertical, top edge level):** the face mitre (向こう留め) is plumb and the top mitre (上端留め) is a plain 45°.

**Fascia set square to the rafters (face leaning outward at the common 返し勾配).** This board is geometrically a side of a **splayed box** whose lean is the roof slope (§ 9.2). Hence:

| Cut | Ratio | 4 sun | 5 sun |
|---|---|---|---|
| Face mitre (向こう留め), measured from the line square to the top edge | **中勾 : 殳** (中勾勾配) | 0.371 → 20.38° | 0.447 → 24.09° |
| Top-edge mitre (上端留め), top edge square to the face (so lying in the roof plane): offset along the edge per unit across the thickness | **長玄 : 殳** (長玄勾配) | 0.928 → 42.88° from square | 0.894 → 41.81° |
| Top-edge butt joint (突付け) instead of a mitre | **短玄 : 殳** (短玄勾配) | 0.149 → 8.45° | 0.224 → 12.60° |

**R05-025** — *Must.* Before marking a fascia or eave-board mitre, establish whether the board's face is plumb, square to the rafters, or at some other angle, and whether its top edge is level or square to the face. Then apply the corresponding rule. *Why:* each case has different mitre angles. The 中勾 / 長玄 / 短玄 triple applies only to the board set square to the rafters with its top square to its face.

**R05-026** — *Should.* For eave members whose faces are neither plumb nor square to the rafters (many 茅負 and 裏甲 in temple work), and for any **curved** eave member, solve the mitre by full-size drawing (小平起こし or development) rather than by named slopes. *Why:* the named-slope recipes assume one of the two standard settings. Real 茅負 sections are often trapezoidal, and in curved eaves the setting changes along the length (§ 10).

### 6.9 Valleys (谷木 tanigi)

A valley at a 90° re-entrant corner with equal pitches has exactly the hip's geometry with the signs reversed:

- Plan run, slope, length and plumb/level lines: identical to the hip (隅殳, 隅勾配, 隅玄).
- **Top:** the roof planes rise **away** from the valley line, so the valley top is **hollowed** (谷に削る) to a V, with the same angle as the hip backing (隅中勾勾配 in the true section). If left flat it must be set with its **centre** on the valley line, and its arrises then lie *below* the roof planes. The jacks bear on packing or on the arris.
- **Valley jacks** (配付垂木 running from the valley up to the ridge or a hip) have the same side cut (plumb) and top cut (玄 : 殳) as hip jacks, but the long point is at the **upper** side.
- Plate-centre lines on the valley sides are staggered exactly as on the hip (R05-020).

**R05-027** — *Must.* Treat the valley as a hip "upside down" for all angles, but reverse the treatment of the top (hollow, not ridge) and the direction of the jack long points. *Why:* the plane geometry is the same, but the solid-geometry consequences reverse. A valley backed like a hip holds the sheathing off the jacks along its whole length.

### 6.10 Marking sequence for a 棒隅 hip (summary)

1. Dress the hip to section (width *w*, side depth *D*). Snap the centreline on the top (峠) and the bottom.
2. From the plan, mark the corner point (plate-centre crossing) on the top centreline.
3. On each side, strike the two plate-centre plumb lines at ±(*w*/2) in plan (± (*w*/2) × 隅玄/隅殳 along the arris) with the hip slope (§ 6.4).
4. Strike the 口脇 lines on both sides, below the top arris by the plumb 山 height (*w*/2)·*t*/√2, and plane the backing (§ 6.3).
5. Mark the housing over the plates on the sides (plumb lines at the plate faces) and across the underside (隅玄 : 隅殳) (§ 6.5).
6. Mark the ridge end: the plumb cut (hip slope) and the side cheeks to meet the ridge, or the opposite hip at a hipped ridge end (→ Ch. 11 § 8).
7. Mark the jack positions along both sides, each side from its own plate-centre line (§ 6.6).
8. Mark the eave end: plumb, or 投げ墨 for fascias square to the rafters (§ 6.7). On the backed top, mark lines parallel to the eaves (殳 : 玄 against the hip axis).
9. Before cutting, check the finished marks against a full-size section and plan of the corner (現寸), and confirm the hip length with the factor 隅玄/殳 (R05-032).

---

## 7. Worked examples: 4-sun and 5-sun hip roofs

**Data.** Hip roof on a square corner. Run from plate centre to ridge centre 9 shaku (≈2,727 mm; half of a 3-ken span). Eave projection from plate centre to rafter tip 2.5 shaku (≈758 mm) in plan. Common rafters 1.5 sun (≈45 mm) wide × 1.5 sun deep, at 1.5 shaku (≈455 mm) spacing. Hip 4 sun (≈121 mm) wide × 6 sun (≈182 mm) side depth. All numbers were computed and checked for this book. Lengths are along the member's reference line (R05-012).

### 7.1 Common rafter and hip

| Quantity | Formula | 4-sun roof | 5-sun roof |
|---|---|---|---|
| Slope angle | arctan(*t*) | 21.80° | 26.57° |
| Total rise over 9 shaku run | run × *t* | 3.6 shaku (≈1,091 mm) | 4.5 shaku (≈1,364 mm) |
| 玄 per 10 | √(100+*h*²) | 10.770 | 11.180 |
| Common rafter, plate centre to ridge centre | 9 × 玄/殳 | 9.693 shaku (≈2,937 mm) | 10.062 shaku (≈3,049 mm) |
| Common rafter eave extension | 2.5 × 玄/殳 | 2.693 shaku (≈816 mm) | 2.795 shaku (≈847 mm) |
| Plumb depth of a 1.5-sun rafter | 1.5 × 玄/殳 | 1.616 sun (≈49 mm) | 1.677 sun (≈51 mm) |
| Hip plan run | 9 × √2 | 12.728 shaku | 12.728 shaku |
| Hip slope | *t*/√2 | 0.2828 (15.79°) | 0.3536 (19.47°) |
| 隅玄 per 10 of common run | √(200+*h*²) | 14.697 | 15.000 |
| Hip length, plate corner to ridge | 9 × 隅玄/殳 | 13.227 shaku (≈4,008 mm) | 13.500 shaku (≈4,091 mm) |
| Hip eave extension (along hip) | 2.5 × 隅玄/殳 | 3.674 shaku (≈1,113 mm) | 3.750 shaku (≈1,136 mm) |
| 隅中勾 | 10√2·*h*/隅玄 | 3.849 | 4.714 |
| Backing, true section | 隅中勾/隅殳 | 0.2722 (15.23°) | 0.3333 (18.43°) |
| 山 height, plumb on the side, *w* = 4 sun | 2 × *t*/√2 | 0.566 sun (≈17.1 mm) | 0.707 sun (≈21.4 mm) |
| 山 height square to the top | 2 × sin α | 0.544 sun (≈16.5 mm) | 0.667 sun (≈20.2 mm) |
| Plate-centre line offset along the arris | 2 × 隅玄/隅殳 | 2.078 sun | 2.121 sun |
| Plate-face line on the hip underside | along : across = 隅玄 : 隅殳 | 1.0392 (46.10° from square) | 1.0607 (46.69°) |
| Dihedral between the roof planes over the hip (outside) | — | 149.55° | 143.13° |

### 7.2 Hip height at the plate corner

- Common rafter top above the plate 峠 = rafter plumb depth: 1.616 sun (4 sun) / 1.677 sun (5 sun).
- Hip top centre (峠) over the corner point = the same height (roof planes meet there).
- Hip side depth plumb = 6 × 隅玄/隅殳: 6.235 sun (4 sun) / 6.364 sun (5 sun).
- Hip underside at the corner point, below the hip top centre = plumb 山 + plumb side depth: 0.566 + 6.235 = 6.801 sun (4 sun) / 0.707 + 6.364 = 7.071 sun (5 sun).
- So the hip underside lies **below the plate 峠** by 6.801 − 1.616 = **5.19 sun (≈157 mm)** at 4 sun, or 7.071 − 1.677 = **5.39 sun (≈163 mm)** at 5 sun.

This depth is shared between the hip housing and cutting down the plate crossing (and it also depends on the plate size and bevel). It shows why a deep hip always needs a deliberate crossing detail (→ Ch. 11 § 8, → Ch. 08). The numbers change directly with the chosen hip depth.

### 7.3 Jack rafters (1.5 shaku spacing, measured to jack centrelines from the corner point along the plate)

| Jack no. | Distance from corner | Length to hip **centreline** (4 sun) | (5 sun) |
|---|---|---|---|
| 1 | 1.5 shaku | 1.6155 shaku (≈489.6 mm) | 1.6771 shaku (≈508.2 mm) |
| 2 | 3.0 | 3.2311 (≈979.1 mm) | 3.3541 (≈1,016.4 mm) |
| 3 | 4.5 | 4.8466 (≈1,468.7 mm) | 5.0312 (≈1,524.6 mm) |
| 4 | 6.0 | 6.4622 (≈1,958.2 mm) | 6.7082 (≈2,032.8 mm) |
| 5 | 7.5 | 8.0777 (≈2,447.8 mm) | 8.3853 (≈2,541.0 mm) |
| decrement | 1.5 × 玄/殳 | 1.6155 shaku | 1.6771 shaku |
| deduction for half hip width | (*w*/2)·√2 × 玄/殳 | 3.046 sun (≈92 mm) | 3.162 sun (≈96 mm) |
| top cut | along = width × 玄/殳 | 1.5 × 1.077 = 1.616 sun | 1.5 × 1.118 = 1.677 sun |

(Add the eave extension, 2.693 or 2.795 shaku, to each jack that runs out to the eave.)

**R05-028** — *Should.* Compute the jack decrement once, cut and check the first two jacks against the hip, then gang-mark the rest from a story-pole (→ Ch. 04). *Why:* a constant decrement means one proven pair validates the whole run, and a story-pole prevents cumulative tape errors.

---

## 8. Uneven-pitch hips (振れ隅 fure-sumi) and polygonal plans

### 8.1 When the hip "swings"

A hip leaves the 45° bisector (振れる *fureru*, "swings") whenever the two roof planes meeting at a corner do not rise at the same rate from their eaves. This happens:

1. with **different pitches** on the two sides and equal eave heights (不等勾配 *futō-kōbai*), common where a long side and a short side must reach the same ridge height, e.g. on a rectangular hip roof whose ridge length is fixed;
2. with **different eave projections** on the two sides where the eave lines must still meet at one height, which forces different pitches;
3. with a **non-right corner** in plan (hexagon, octagon, irregular site).

### 8.2 Different pitches on a right-angled corner

Let side A have slope *t*_A and side B slope *t*_B, with the eave (or plate) lines at equal height. The hip is the line along which the heights are equal: *t*_A·*d*_A = *t*_B·*d*_B, where *d* is the distance in from each eave. Hence:

- **Plan angle of the hip from eave A:** tan φ_A = *t*_B / *t*_A. **The hip swings toward the steeper side**: the steeper face is narrower at the corner.
- **Hip plan run** per 10 sun of distance from eave A: √(10² + (10·*t*_A/*t*_B)²).
- **Hip slope** = rise / hip plan run.
- **Jack top cuts**, side A: along : across = (*t*_B/*t*_A) × 玄_A/殳. Side B: (*t*_A/*t*_B) × 玄_B/殳.
- **Backing** is **asymmetric**. In a plumb section square to the hip, side A falls at *t*_A × sin(angle between hip and eave B) and side B at *t*_B × sin(angle between hip and eave A). In the true section, multiply each by cos α.

**Worked example: side A 4 sun, side B 6 sun.**

| Quantity | Value |
|---|---|
| Hip plan angle | 56.31° from eave A, 33.69° from eave B |
| Hip plan run per 10 sun from eave A | 12.019 sun (distance from eave B at that point 6.667 sun) |
| Hip slope | 4 / 12.019 = 0.3328, i.e. 3.328 sun per shaku of hip run (18.41°) |
| Backing, true section | side A: 0.2105 (11.89°); side B: 0.4737 (25.35°) |
| Jack top cut, side A (4 sun) | along : across = 1.5 × 1.077 = 1.6155 |
| Jack top cut, side B (6 sun) | along : across = 0.6667 × 1.1662 = 0.7775 |

**R05-029** — *Must.* For an uneven-pitch hip, derive the plan angle from the pitches (tan φ_A = *t*_B/*t*_A) and lay the hip out on a full-size plan. Then compute **each side's** jack cuts and backing separately. *Why:* none of the 棒隅 shortcuts (裏目 for √2, a symmetric backing, 玄 : 殳 jack cuts) survives an uneven pitch. Applying them is the classic 振れ隅 failure (R05-003).

**R05-030** — *Should.* Where a design produces a slightly swung hip only because of unequal eave projections, consider adjusting the projections (or accepting a small difference in eave height) to restore a 棒隅. *Why:* the 棒隅 is quicker, more accurate and easier to repair. Temple and shrine plans normally keep the corner symmetrical for this reason (→ Ch. 12).

### 8.3 Polygonal plans (六角堂・八角堂)

For a regular polygon with equal pitch, each hip bisects the interior angle. Let β be half the interior angle (45° for a square, 60° for a hexagon, 67.5° for an octagon). Then, per unit of common run *r* (the distance square to the eave):

- **hip plan run** = *r* / sin β;
- **hip slope** = *t* · sin β;
- **jack top cut** along : across = cot β × 玄/殳;
- **backing** in a plumb section = *t* · cos β; in the true section, × cos α.

| Plan | β | hip plan factor 1/sin β | 4 sun: hip slope (angle) | 4 sun: jack along/across | 4 sun: backing true (angle) | 5 sun: hip slope (angle) | 5 sun: jack | 5 sun: backing |
|---|---|---|---|---|---|---|---|---|
| Square | 45° | 1.4142 | 0.2828 (15.79°) | 1.0770 | 0.2722 (15.23°) | 0.3536 (19.47°) | 1.1180 | 0.3333 (18.43°) |
| Hexagon | 60° | 1.1547 | 0.3464 (19.11°) | 0.6218 | 0.1890 (10.70°) | 0.4330 (23.41°) | 0.6455 | 0.2294 (12.92°) |
| Octagon | 67.5° | 1.0824 | 0.3696 (20.28°) | 0.4461 | 0.1436 (8.17°) | 0.4619 (24.79°) | 0.4631 | 0.1737 (9.85°) |

The 裏目 gives the √2 factor only for the square. For hexagons and octagons the factor must be constructed on the full-size plan (or computed) and transferred with a story-pole or a purpose-made scale. The famous octagonal halls (八角円堂 *hakkaku-endō*, e.g. the Yumedono of Hōryū-ji) and hexagonal halls use exactly this geometry, combined with a single apex post (→ Ch. 11 § 1).

**R05-031** — *Must.* On polygonal plans, never use the 裏目 for hip runs except on a 90° corner. Construct the hip plan factor 1/sin β on a full-size plan. *Why:* 裏目 = √2 = 1/sin 45°. For an octagon the true factor is 1.082. Using √2 would make each hip 31% too long in plan.

### 8.4 General method for any corner (drawing method)

1. Draw the **plan** at full size (or large scale): both eave lines, both plate lines, the ridge or apex.
2. Draw the **hip plan line** through the plate-corner point and the point where the two roofs reach equal height (for equal eave heights this is the ridge end, or the intersection of equal-height contours: draw one contour line on each face at a convenient height *H* from eave, at distance *H*/*t* inside each eave. The hip passes through their intersection).
3. **Raise the hip** (小平起こし): rotate the vertical plane through the hip plan line into the drawing by erecting, at each point, the rise square to the hip plan line. This gives the true hip length, the hip slope and the plumb lines.
4. For the **backing**, draw a section square to the hip plan line. The roof-plane traces give the plumb-section backing on each side. Correct it by cos α for the true section, or raise the section square to the hip axis directly.
5. For **jack top cuts**, raise each roof face about its eave line into the drawing. The hip line on the raised face gives the true angle of the jack cut on that side.
6. Transfer every angle to a template (型板). Label it by member, face and side (R05-011).

**R05-032** — *Must.* Check every computed or drawn hip length against the independent relation *L*_hip = √(plan run² + rise²) before cutting. *Why:* this single check catches most layout errors (wrong 殳, 表目/裏目 confusion, wrong rise) at no cost.

---

## 9. Splayed members (転び korobi, 四方転び shihō-korobi)

A member that leans from the vertical has **転び *korobi*** ("tumble, lean"). In this book the lean *k* is stated as **horizontal offset in sun per 1 shaku of height**: a "3-sun lean" moves 3 sun sideways per 10 sun of rise. To use the kikujutsu vocabulary, set up the **splay triangle** with **殳 = 10 (the height) and 勾 = *k* (the lean)**, and 玄 = √(100 + *k*²). Everything in § 4 then applies. (Some texts describe the same member as a very steep "roof" of slope 10/*k*, i.e. use the 返し勾配. The formulas are equivalent once the triangle is set up consistently.)

### 9.1 Lean in one direction (片転び *kata-korobi*)

This is the case of **torii** pillars (鳥居の柱の転び, which lean inward in the front elevation), of some gate posts, and of splayed legs seen in one direction only.

- On the face that shows the lean, lay **10 on the long arm and *k* on the short arm** at the post's arris, with the long arm plumb. The short arm gives the **level** lines: the top and bottom cuts, the seats of lintels (笠木 *kasagi*, 島木 *shimagi*) and the top and bottom lines of the 貫 *nuki* mortise. The long arm gives the plumb.
- On the faces that do not show the lean, level lines are simply square to the arris.
- A through-mortise for a horizontal 貫 is therefore a parallelogram on the leaning faces and a rectangle on the others. The 貫 shoulders are cut at the same angle.
- **Spread:** the bottom spacing of two posts = top spacing + 2 × height × *k*/10.

The amount of lean in torii and gates is set by the kiwari of the type (→ Ch. 12). Published figures vary, and the book does not fix a single value. As a representative order of magnitude, torii pillars often lean by a few percent of their height, up to about a tenth. **Flag:** check against the specific type and school.

**R05-033** — *Must.* Cut the top and bottom of a leaning post level (not square to the post) where it bears on a foundation stone or carries a horizontal member, with the level line taken from the splay triangle. *Why:* a square-cut end on a leaning post bears on one edge only, crushing locally and rotating the post.

### 9.2 Lean in two directions (四方転び shihō-korobi)

In **四方転び** the members lean outward (or inward) equally in both directions of the plan. It is the defining geometry of splayed boxes and trays (四方転びの箱), of splayed stools and trestles (四方転び踏み台), of water-basin stands and of many bell towers (鐘楼 *shōrō*) and some gate and pavilion structures. It is the classic trainee exercise because none of the angles is the obvious one.

**The splayed box (sides are boards).** Side A leans out by *k* per 10 of height, and so does side B at right angles to it. Let θ be the lean angle (tan θ = *k*/10). Derived and checked for this book:

| Cut | Where | Ratio | Named slope (splay triangle) |
|---|---|---|---|
| Top and bottom edge bevel, for level top/bottom | end grain of the top edge | 勾 : 殳 = *k* : 10 | 勾配 (転び勾配) |
| Corner line (胴付き *dōtsuki*) on the board's face, measured from the line square to the top edge | face | 中勾 : 殳 (tan = sin θ) | **中勾勾配** |
| Mitre (留め) on a top edge that is square to the face; offset along the edge per unit across the thickness | top edge | 長玄 : 殳 (= cos θ) | **長玄勾配** |
| Butt joint (突付け) on a top edge square to the face | top edge | 短玄 : 殳 (= sin θ tan θ) | **短玄勾配** |
| Mitre on a **level** top edge | top | 45° in plan | — |
| Blade tilt for the mitre (from the face, measured square to the corner) | end | half the (obtuse) dihedral between sides | — |

These results are the same as for the fascia set square to the rafters (§ 6.8), which is a "splayed box" whose lean equals the roof slope. That is why the same three named slopes (中勾, 長玄, 短玄) recur throughout kikujutsu.

**The splayed leg (stool, stand, bell tower).** A leg at the corner leans along the box diagonal:

- The **diagonal lean** of the leg is *k*√2 per 10 of height (the leg's plan run along the diagonal is read on the 裏目, exactly as a hip).
- Within each side plane, the leg's axis is inclined to that plane's own fall-line at tan = *k*/玄 = **中勾 : 殳**. On a leg face lying in (or parallel to) a side plane, **the rail mortise lines and rail shoulders are therefore laid with the 中勾勾配**, the same as the box's 胴付き.
- A square-section leg cannot have both outer faces in both side planes, because the side planes meet at an angle larger than 90° (95.6° at *k* = 3.3). Two practices exist: (i) the leg is **dressed to a rhombic section** (菱形) so that its two outer faces lie in the two side planes. Its level-cut end (柱木口) is then drawn by development. (ii) The leg is left square with one face in a side plane, and the small discrepancy is absorbed in the other rail's shoulder. **Flag:** which practice is standard for a given exercise or building should be confirmed against the governing textbook or test specification. Current trade-test drawings for the 四方転び踏み台 include a construction of the leg's end section (柱木口), which suggests the developed-section approach.

### 9.3 Worked example: 四方転び with a 3.3-sun lean (≈100 : 33)

A lean of about 33 per 100 is a common teaching value for the splayed stool. It is reported in trade-test material, and published tasks vary.

| Quantity | Value |
|---|---|
| Lean angle θ (each side) | arctan 0.33 = 18.26° |
| 玄 of the splay triangle | 10.530 |
| 中勾 / 長玄 / 短玄 | 3.134 / 9.497 / 1.034 |
| Face corner line (胴付き) / rail shoulder on the leg face | 中勾 : 殳 = 0.3134 → 17.40° from square |
| Mitre on a top edge square to the face | 長玄 : 殳 = 0.9497 → 43.52° from square |
| Butt on a top edge square to the face | 短玄 : 殳 = 0.1034 → 5.90° from square |
| Top-edge bevel for a level top | 18.26° (勾配 3.3 : 10) |
| Interior angle between adjacent sides (square to the corner) | 95.64° (acute complement 84.36°) |
| Mitre blade tilt from the face | 47.82° |
| Leg diagonal lean | arctan(0.33 × √2) = 25.02° |

**R05-034** — *Must.* In 四方転び work, lay the corner line on the face of a side (and the rail shoulders on a leg face lying in a side plane) with the **中勾勾配** of the splay triangle, not with the lean itself. *Why:* on the leaning face the corner line is foreshortened by the lean. Using the plain lean angle (18.26° instead of 17.40° at 3.3 sun) opens every corner joint.

**R05-035** — *Must.* Before marking a 四方転び top-edge joint, decide whether the top edge will be **level** or **square to the face**, and use 45°, 長玄 or 短玄 accordingly. *Why:* the mitre angle on the top edge differs completely between the two cases (45° against 43.52° at 3.3 sun). The decision fixes the width of the bevelled top.

**R05-036** — *Should.* For a bell tower or other building with 四方転び posts, lay out one complete post at full size (plan, both elevations and the developed faces) before cutting any joint. *Why:* the compound angles of rails, head-ties (頭貫), sills and bracket seats on splayed posts are too numerous to trust to recipes. A single full-size development checks them together.

---

## 10. Curved eaves (軒反り nokizori) and fan rafters (扇垂木 ōgi-daruki)

The upward sweep of temple and shrine eaves toward the corners is the most characteristic line of Japanese architecture. It is also the hardest kikujutsu problem: every rafter near the corner is different. This section covers the layout principles. Framing is in → Ch. 11 § 9, and style-specific proportions are in → Ch. 12. **School and period variation is large here. Everything below is general method, not a single canonical recipe.**

### 10.1 Vocabulary

- **軒反り *nokizori*** — the curve of the eave line in elevation, rising toward the corners.
- **反り上がり *sori-agari*** (also 隅の反り上がり) — the amount by which the eave line at the corner stands above the straight (unswept) eave line.
- **反り元 *sori-moto*** — the point along the eave where the curve begins. Inside it the eave is straight (level). In many wayō buildings it lies around the corner bay or at a rafter a set number of spaces in from the corner. In others the whole eave is curved from the centre (真反り).
- **茅負 *kayaoi*** — the eave member across the rafter tips (the tips of the 飛檐垂木 in a double eave, or of the single tier in a single eave; → Ch. 11 § 4). **The 茅負 carries and defines the eave curve.**
- **木負 *kioi*** — in a double eave (二軒 *futanoki*), the corresponding member across the tips of the lower rafters (地垂木 *ji-daruki*). It carries its own, related curve.
- **裏甲 *urakō*** — the board(s) laid on the 茅負, following its curve and forming the roof edge.
- **撓み定規 *tawami-jōgi*** (also 反り定規 *sori-jōgi*, or simply a *shinai*, a bending batten) — a long, clear-grained, uniformly thin batten bent to produce a fair curve.
- **扇垂木 *ōgi-daruki*** (fan rafters) and **平行垂木 *heikō-daruki*** (parallel rafters): § 10.4.

### 10.2 Laying out the eave curve

The traditional method is to **draw the curve at full size with a bent batten** on the drawing floor (現寸場 *genzu-ba*) and to take everything else from that drawing:

1. **Fix the straight eave line** in elevation and plan: the 茅負 at the centre bays, at the height and projection given by the proportions (→ Ch. 12).
2. **Fix the corner rise (反り上がり)** at the corner point (the intersection of the two 茅負 lines over the hip). The amount is a design decision set by the master carpenter or the school's kiwari. Larger halls and later periods generally show more sweep. **Flag:** representative magnitudes quoted in the literature range from a few sun on small buildings to over a shaku on large halls. Treat any single figure as school-specific.
3. **Fix the 反り元.** Clamp the batten at the 反り元 tangent to the straight line (and often at one or two points beyond it). Lift its end to the corner rise and let it take its natural curve. A batten of uniform section bent this way gives a fair curve with no kink at the 反り元, which is the aesthetic requirement.
4. **Transfer the curve** by marking the batten's height above the straight line at every rafter position (a table of ordinates, 反り割り). These ordinates set the height of each rafter tip, of the 茅負 underside and of the 裏甲.
5. **Plan curvature.** In many buildings the eave line also bows **outward** in plan toward the corner, so the corner projects further than the straight eave would. Terms for this vary by school, and the book does not fix one. It is drawn the same way, with a batten in the plan view. The combination of rise and outward swing makes the 茅負 a doubly curved member.
6. **The hip follows.** The 隅木 top is shaped to the rising corner (the hip nose rises with the sweep). The corner rafters are set so that their tips meet the curved 茅負.

**R05-037** — *Must.* Define the eave curve once, full size, with a bent batten, and derive every rafter-tip height, the 茅負 and 木負 curves and the 裏甲 from that single drawing. *Why:* independent curves for each member never agree. The eave is only fair if all members are ordinates of one curve.

**R05-038** — *Should.* Use a batten of uniform section and straight, clear grain, and let it bend naturally between its fixed points, with no intermediate forcing. *Why:* a uniform elastic batten produces a curve with continuously varying curvature and no hard point (like a spline). Forcing it at intermediate points creates the lumps that experienced eyes read immediately. Adjust the curve only by moving the end points or the 反り元.

### 10.3 Rafters under a curved eave

- **Lift (反り上げ).** Each rafter inside the corner zone is raised at its tip by the ordinate of the curve at its position. Its seat on the plate stays fixed, so each rafter's slope differs slightly.
- **Twist (捩れ *nejire*).** Where the 茅負 rises and swings, its top is no longer in one plane. The rafters near the corner, and the 茅負 itself, are therefore twisted (their tops rotate along their length). In high-quality work each such rafter is individually shaped.
- **Layout of individual rafters.** Each lifted or twisted rafter is laid out from the full-size drawing (its elevation, plan and developed faces), not from the common-rafter template.
- **Jacks against a curved hip** have cuts that vary from rafter to rafter. They are marked from the full-size drawing or by scribing to the installed hip (→ Ch. 04 on scribing, 光付け *hikari-tsuke*).

**R05-039** — *Should.* Mark every rafter within the sweep zone with its individual number and its individual ordinate (lift) from the 反り割り table, and cut it from its own layout. *Why:* no two are alike. Interchanging them spoils the fairness of the eave, which is the most visible line of the building.

### 10.4 Parallel rafters and fan rafters

**Parallel rafters (平行垂木 *heikō-daruki*).** All rafters stay square to their eave. At the corner they are cut as jacks (配付垂木) into the sides of the hip. This is the norm of the **Japanese style (和様 *wayō*)**. Its kikujutsu is that of § 6 plus the sweep of § 10.2–10.3.

**Fan rafters (扇垂木 *ōgi-daruki*).** In the corner zone the rafters **radiate** from a centre point (要 *kaname*) so that at the corner the rafters turn progressively toward the diagonal. Fan rafters are characteristic of the **Zen style (禅宗様 *zenshūyō*)**. The **Great Buddha style (大仏様 *daibutsuyō*)** uses them only at the corners (隅扇垂木 *sumi-ōgi-daruki*), e.g. at Tōdai-ji Nandaimon and Jōdo-ji Jōdo-dō (→ Ch. 12). Typical layout procedure (general method; details vary by school):

1. On the full-size **plan** of the corner, draw the eave line (the 茅負 line, including any plan swing) from the last parallel rafter to the corner.
2. Choose the **要 (kaname)**, the convergence point. It is commonly on or near the corner diagonal, inside the building: at the corner post, at the inner post line, or at a point fixed by the school's rules. The choice controls how strongly the rafters fan.
3. **Divide the eave line** between the last parallel rafter and the hip into equal spaces (equal spacing *at the eave* is the usual aim, because that is what the eye sees).
4. Draw each rafter as a line from the 要 through its division point. Each rafter now has its own **plan angle** (振れ *fure*) to the eave, which increases toward the corner.
5. For each rafter, derive its individual slope (from its plan run and the rise, including the sweep ordinate), its tip cut against the curved 茅負, its seat on the plate (which it crosses obliquely) and its heel against the adjacent rafters or the hip. Each is a separate 振れ垂木 problem solved by drawing.
6. Where the rafters crowd together toward the 要, they are cut off against one another, against the hip or on a fan-shaped block. In some traditions they also taper in width toward the inner end.

```
 Plan of a corner with fan rafters (schematic)

        eave line (茅負), equal spacing at the eave
   ─┬───┬───┬───┬───┬──┬──┬─┬─ ┐
    │   │   │    \   \  \  \ \ │ corner
    │   │   │     \   \  \  \ \│
    │   │   │      \   \  \  \ ╲  ← hip (隅木) on the diagonal
    │ parallel │     \   \  \  ╲
    │ rafters  │      \   \  \╲
    │   │   │         \   \ ╲
                        \  ╲
                         ● 要 (kaname): convergence point
```

**R05-040** — *Must.* In fan-rafter work, fix the convergence point (要) and the eave divisions on a full-size plan **before** any rafter is marked, and derive every rafter from that plan. *Why:* each fan rafter has a unique angle and cuts. The system is only consistent if all rafters come from one plan. Adjusting one rafter on site shifts all its neighbours.

**R05-041** — *Should.* Space fan rafters equally **along the eave (茅負) line**, not along the plate or at the 要. *Why:* the eave is what the viewer sees. Equal spacing there is the visual requirement, and spacing at the plate follows from the geometry.

---

## 11. Training exercises

Kikujutsu is learned by doing a fixed sequence of exercises, mostly at reduced scale in softwood (1/5 to 1/2 scale, or full size for small pieces). The national carpentry skills test (建築大工技能検定, grades 1 and 2) has long used hip-and-jack assemblies and similar compound-angle tasks. The exact tasks change from year to year and should be checked in the current test specifications. The following list is the conventional progression, with the essential steps.

### 11.1 Slope triangle and derived lines on a board

1. On a planed board draw 殳 = 10 sun and 勾 = 4 sun (then repeat for 5 and 6), square to each other.
2. Draw 玄. Drop the perpendicular from the right angle with the square to get 中勾, and read 長玄 and 短玄.
3. Check: 長玄 + 短玄 = 玄; 中勾² = 長玄 × 短玄; values as in the § 3.2 table.
4. Construct the hip triangle (10 on the 裏目 for 殳) and its 隅中勾.
*Purpose:* fluency with the vocabulary and the sashigane.

### 11.2 Common rafter and wall-plate

1. Bevel a short plate to the slope and mark the 峠 and 口脇 (§ 5.2).
2. Mark and cut a rafter: plumb cut, square cut, length along the top arris from 峠 to ridge.
3. Check the fit on the plate: full-width bearing, rafter underside through the 峠.

### 11.3 四方転び box (四方転びの箱)

1. Choose a lean (e.g. 2 or 3 sun per shaku) and set up the splay triangle.
2. Mark each side's face corner lines with the 中勾勾配 (R05-034).
3. Decide on a level or square top edge. Mark the top-edge joint with 45°, 長玄 or 短玄 accordingly (R05-035).
4. Bevel the top and bottom edges (level) with the 転び勾配.
5. Cut, assemble dry, check that the corners close and the top is level and flat.
*Purpose:* the first compound-angle exercise. It teaches the 中勾 / 長玄 / 短玄 triple.

### 11.4 四方転び stool (四方転び踏み台)

1. Set the lean (e.g. ≈33 : 100, § 9.3) and draw at full size: plan, two elevations, and the developed leg faces and leg end section (柱木口).
2. Dress the legs (square, or rhombic per the chosen practice, § 9.2).
3. Mark the level top and bottom cuts, the rail mortises (中勾勾配 on the face in the side plane) and the rail shoulders.
4. Cut the top board's corner joints or housings for the splayed legs.
5. Assemble. Check: all four feet on a flat surface, top level, equal lean each way.

### 11.5 棒隅 hip with jacks (寄棟の隅木)

1. At 1/2–1/5 scale, make two plates meeting at 90° (crossing joint, → Ch. 08) and bevel them.
2. Mark the hip per § 6.10: 峠, 口脇 and backing, the two plate-centre lines per side, the housing, and the nose (plumb or 投げ墨).
3. Mark and cut three to five jacks per side with the plumb side cut and 玄 : 殳 top cut, using the decrement and the half-hip deduction.
4. Assemble. Check with a straight-edge that the jack tops, the hip's backed faces and the common rafters lie in one plane on each side.

### 11.6 Fascia around the hip (鼻隠しの留め)

1. Set the fascia square to the rafters. Mark the face mitre (中勾勾配) and top mitre (長玄勾配). Repeat with a plumb fascia (plumb face mitre, 45° top) to feel the difference.
2. Cut the hip nose with the 投げ墨 to sit behind the square-set fascia.

### 11.7 振れ隅 (uneven-pitch hip)

1. Choose two pitches (e.g. 4 and 6 sun). Draw the full-size plan and raise the hip (§ 8.4).
2. Derive the asymmetric backing and the two different jack cuts. Compare with the § 8.2 table.
3. Cut and assemble as in 11.5.
*Purpose:* the test of whether the principles, rather than the recipes, have been learned (R05-003, R05-029).

### 11.8 Polygonal roof (六角・八角)

1. Draw a hexagonal or octagonal plan with an apex post.
2. Construct the hip plan factor (1/sin β), raise one hip, derive its backing and the jack cuts (§ 8.3).
3. Make one full facet with hip, jacks and fascia at small scale.

### 11.9 Curved eave and fan rafters (advanced)

1. On a drawing floor, lay out a corner of a double eave with 反り元 and corner rise using a bent batten (§ 10.2). Tabulate the ordinates.
2. Choose a 要 and lay out five to seven fan rafters with equal eave spacing (§ 10.4).
3. Make the 茅負 corner piece and two or three of the fan rafters at reduced scale.
*Purpose:* the level of work required for temple and shrine carpentry (宮大工 *miya-daiku*).

**R05-042** — *Should.* Trainees should complete the exercises in order (triangle, common rafter, splayed box, stool, 棒隅 hip, fascia, 振れ隅, polygon, curved eave) and should not proceed until each assembly closes without packing. *Why:* each exercise isolates one additional geometric idea. Skipping steps produces carpenters who can reproduce a 棒隅 but cannot reason about a non-standard corner.

---

## 12. Rule index and common errors

### 12.1 Consolidated rules (summary)

| Rule | Strength | Summary |
|---|---|---|
| R05-001 | Must | All cuts derive from the base triangle 勾 (rise), 殳 (run), 玄 (slope). |
| R05-002 | Should | Named-line method for standard cases; full-size drawing for non-standard. |
| R05-003 | Must | A correct drawing governs over a recipe. |
| R05-004 | Must | Check the square for true. |
| R05-005 | Must | Read both arms on the same arris and side. |
| R05-006 | Should | Make templates for repeated cuts. |
| R05-007 | Must | State slopes as sun per shaku (x/10). |
| R05-008 | Must | Slope is per unit of run, not of span. |
| R05-009 | Must | Square cuts use the member's own 返し勾配. |
| R05-010 | Should | Construct derived lines graphically and check with identities. |
| R05-011 | Must | Label templates by line, triangle and face. |
| R05-012 | Must | One consistent reference line for lengths and seats. |
| R05-013 | Must | Set heights from the plate 峠. |
| R05-014 | Should | Bevel plates rather than deeply notching rafters. |
| R05-015 | Must | Hip plan run = run × √2 (裏目). |
| R05-016 | Must | Hip side cuts use the hip slope. |
| R05-017 | Must | Visible hips are backed at the hip 中勾勾配. |
| R05-018 | Variant | Hidden hips may be dropped instead of backed. |
| R05-019 | Must | Distinguish plumb-section and true-section backing. |
| R05-020 | Must | Two staggered plate-centre lines per hip side. |
| R05-021 | Must | Position the hip from the roof planes, then derive housings. |
| R05-022 | Must | Jacks: plumb side cut, 玄 : 殳 top cut, half-hip deduction on 裏目. |
| R05-023 | Should | Step jack positions from each side's own plate-centre line. |
| R05-024 | Must | Hip nose behind square-set fascia = 投げ墨, not 隅返し. |
| R05-025 | Must | Identify the fascia setting before marking its mitre. |
| R05-026 | Should | Non-standard and curved eave members: solve by drawing. |
| R05-027 | Must | Valley = inverted hip (hollowed top, reversed long points). |
| R05-028 | Should | Prove two jacks, then gang-mark from a story-pole. |
| R05-029 | Must | 振れ隅: derive the plan angle from the pitches; each side separately. |
| R05-030 | Should | Prefer a 棒隅 where small design changes allow it. |
| R05-031 | Must | 裏目 is valid only for 90° corners. |
| R05-032 | Must | Check hip length by √(plan² + rise²). |
| R05-033 | Must | Leaning posts: level-cut ends. |
| R05-034 | Must | 四方転び face lines use the 中勾勾配. |
| R05-035 | Must | Decide level or square top edge before marking 四方転び joints. |
| R05-036 | Should | Lay out one splayed post in full development first. |
| R05-037 | Must | One full-size eave curve governs all eave members. |
| R05-038 | Should | Uniform batten, bent naturally. |
| R05-039 | Should | Number and individually lay out the rafters in the sweep zone. |
| R05-040 | Must | Fix the fan 要 and eave divisions on a full-size plan first. |
| R05-041 | Should | Space fan rafters equally at the eave. |
| R05-042 | Should | Train in the conventional order. |
| R05-043 | Must | Trial-cut every compound angle on an offcut first. |
| R05-044 | Should | Keep the layout record with the building documents. |

### 12.2 Common errors and two further rules

| Error | Consequence | Rule |
|---|---|---|
| Common slope used on hip sides | hip plumb cuts wrong; the hip does not seat | R05-016 |
| 隅返し勾配 used for a hip nose behind a square-set fascia | nose visibly out of line with the fascia | R05-024 |
| One plate-centre line per hip side, opposite the corner point | housing mislocated by *w*/2; the hip will not sit | R05-020 |
| Plumb-section backing used on a square-cut end template (or vice versa) | small step at the 口脇 | R05-019 |
| 裏目 used on hexagons or octagons | hips grossly too long | R05-031 |
| 棒隅 recipes on an uneven hip | nothing fits; backing wrong on both sides | R05-029 |
| 四方転び corner marked with the lean angle instead of the 中勾勾配 | open corners | R05-034 |
| Slope stated per span, not per run | rise doubled | R05-008 |
| Mixing inside and outside readings on the square | slope off by the arm width | R05-005 |
| Rafter lengths measured between points on different arrises | every seat or plumb cut offset by the plumb-depth offset | R05-012 |

**R05-043** — *Must.* Before cutting any compound-angle member, make a trial cut on an offcut of the same section and check it against its mating member or the full-size drawing. *Why:* errors in kikujutsu are systematic. One trial exposes them before they are repeated on every member, and the cost is one offcut.

**R05-044** — *Should.* Keep the layout record (base triangle, derived lines, templates, full-size drawings or photographs of them) with the building documents. *Why:* repair and partial replacement decades later (→ Ch. 16) need the original geometry, especially for curved eaves and fan rafters, where members cannot be reproduced by measuring the old ones alone because of distortion and sag.

### 12.3 Cross-references

- Sources and historical texts: → Ch. 01.
- Units, sashigane scales, marking symbols: → Ch. 02.
- Tools, full-size drawing floor, templates and story-poles, scribing: → Ch. 04.
- Plate crossing joints under hips: → Ch. 08.
- Roof framing, eaves assembly, hip and valley practice: → Ch. 11.
- Style-specific eave proportions, bracket sets, fan-rafter styles: → Ch. 12.
- Assembly order for roof framing: → Ch. 15.
- Repair of sagging eaves and replacement of rafters: → Ch. 16.

