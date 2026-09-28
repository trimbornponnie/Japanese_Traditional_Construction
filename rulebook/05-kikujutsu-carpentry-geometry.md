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
- **Heinouchi Masaomi (平内廷臣, 1791–1856).** Master carpenter of the shogunate. He is generally credited with putting carpentry geometry on a systematic mathematical footing, drawing on Japanese mathematics (和算 *wasan*). His 『匠家矩術要解』 *Shōka kujutsu yōkai* is the classic treatise. Library catalogues differ on its date: the Waseda University catalogue gives Tenpō 4 (1833), and other references associate him with 1848 (Kaei 1), possibly because a second work, 『矩術新書』 *Kujutsu shinsho*, is dated to that year. The attribution of dates between his works should be checked against → Ch. 01 before quoting.
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
- **半勾配 *han-kōbai*** (half slope). The slope with half the rise: half of 4 sun is 2 sun. It appears in some textbook procedures for marking the underside (下端) of a hip over the wall-plates. One widely circulated explanation says the half-slope arises when a distance taken along the plate (i.e. at 45° to the hip) is used instead of one square to the hip. **Flag:** that derivation was not verified for this book. Use the half-slope only inside the specific textbook procedure that prescribes it, and check it against a drawing.
- **倍勾配 *bai-kōbai*** (double slope). Twice the rise (4 sun gives 8 sun). It occurs in some constructions, for example stepping the ridge of a double-pitched (招き屋根 *maneki-yane*) roof. Like the half-slope it is a label, not an independent geometric principle.
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

In the triangle-line method each derived line is turned into a **slope** by setting it on the short arm (in the place of 勾) against 殳 = 10 on the long arm. This book uses the convention "X-勾配 means X : 殳". Most modern textbooks do the same, but check yours.

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

**R05-012** — *Must.* Measure rafter lengths along a single consistent reference line: the top arris (上端), the bottom arris (下端), or the centreline. All seats and heights must be referred to the same line. *Why:* the top and bottom arrises of a sloping member reach a given plumb plane at different horizontal positions, offset by *d* · sin θ. Mixing references makes every rafter too long or too short by that amount.

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

<!-- CONTINUE -->
