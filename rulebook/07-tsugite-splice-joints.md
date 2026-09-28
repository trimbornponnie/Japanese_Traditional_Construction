# Chapter 07 — Catalogue of Splice Joints (継手 / *tsugite*)

**Scope.** This chapter catalogues the splice joints (継手, *tsugite*) of Japanese carpentry — joints that unite two members end to end along a common axis. Each joint is described with the standard entry template of the rulebook (class, typical use, load behaviour, proportions, orientation, marking, cutting sequence, assembly, rules, common errors, variants, sketch). The general principles on which the catalogue relies — male/female roles, placement near supports, staggering, cross-section loss, kigoroshi and fit — are set out in → Ch. 06 and are referred to rather than repeated. Connections at an angle (shiguchi) are in → Ch. 08; pins, wedges, keys and shachi in → Ch. 09; board edge joints in → Ch. 14; repair uses of splices (netsugi, kaitai-shūri) in → Ch. 16; structural verification and code requirements in → Ch. 17.

**Status of the figures.** All proportions and dimensions in this chapter are **representative**. Proportions in Japanese carpentry are transmitted by schools, regions and individual masters and vary considerably; precut machines use their own standard dimensions. Where a range is given, it spans commonly published or taught values. Do not treat a single number as a code requirement. Where a description of a joint's geometry is uncertain or disputed, this is stated in the entry.

## Contents

1. Conventions, family tree and general rules for splices
2. Simple splices: butt, lap, hooked lap, scarf, seat, mechigai
   - 2.1 突付け継ぎ *tsukitsuke-tsugi* (butt)
   - 2.2 相欠き継ぎ *aikaki-tsugi* (half-lap)
   - 2.3 布継ぎ *nuno-tsugi* and 略鎌 *ryaku-kama* (hooked half-laps)
   - 2.4 殺ぎ継ぎ *sogi-tsugi* (bevelled scarf)
   - 2.5 台持ち継ぎ *daimochi-tsugi* (splice on a support)
   - 2.6 目違い継ぎ *mechigai-tsugi* (tongued butt)
   - 2.7 箱目違い継ぎ *hako-mechigai-tsugi* (box-tongued butt)
3. Hook splices: dovetail and gooseneck
   - 3.1 蟻継ぎ *ari-tsugi* (plain dovetail)
   - 3.2 腰掛け蟻継ぎ *koshikake-ari-tsugi* (seated dovetail)
   - 3.3 鎌継ぎ *kama-tsugi* (plain gooseneck), 目違い鎌, 箱目違い鎌
   - 3.4 腰掛け鎌継ぎ *koshikake-kama-tsugi* (seated gooseneck)
   - 3.5 隠し鎌・隠し蟻 *kakushi-kama / kakushi-ari* (hidden variants)
4. Bending-capable stepped scarfs
   - 4.1 追掛け大栓継ぎ *okkake-daisen-tsugi*
   - 4.2 金輪継ぎ *kanawa-tsugi*
   - 4.3 尻挟み継ぎ *shiribasami-tsugi*
   - 4.4 Pins and keys in splices: 大栓 *daisen*, 栓 *sen*
5. Tenon-and-key splices
   - 5.1 竿継ぎ *sao-tsugi*
   - 5.2 竿車知継ぎ *sao-shachi-tsugi*
   - 5.3 腰掛け竿車知継ぎ *koshikake-sao-shachi-tsugi*
   - 5.4 雇い竿・雇い実 *yatoi-sao / yatoi-zane* (loose-tongue splices)
   - 5.5 千切り *chigiri* (butterfly key)
6. Splices by member and special-purpose splices
   - 6.1 Nuki splices (貫の継手)
   - 6.2 宮島継ぎ *miyajima-tsugi*
   - 6.3 いすか継ぎ *isuka-tsugi*
   - 6.4 Sills (土台) — splice practice
   - 6.5 Plates and girders (桁・胴差) including kyōro-gumi and orioki-gumi practice
   - 6.6 Purlins and ridge (母屋・棟木)
   - 6.7 Rafters (垂木)
   - 6.8 Floor beams and joists (大引・根太)
   - 6.9 Post splices — root splices (根継ぎ *netsugi*)
   - 6.10 Boards (cross-reference to Ch. 14)
7. Summary comparison table
8. Typical dimensions (representative)
9. Rule index for this chapter
10. Notes on sources and uncertainties

---

## 1. Conventions, family tree and general rules for splices

### 1.1 Notation

| Symbol | Meaning |
|---|---|
| **W** | member width (幅, *haba*) — horizontal dimension of the cross-section of a horizontal member |
| **D** | member depth (成, *sei*) — vertical dimension of the cross-section |
| **L** | total length of the joint (from the tip of one piece to the tip of the other) |
| **ogi / megi** | male (男木) / female (女木) — see → Ch. 06 §5 |
| **uwaki / shitaki** | upper piece (上木) / lower piece (下木) in seated or lapped splices |
| **s** | seat length (腰掛けの出) |
| **b_n** | neck width (首幅) of a dovetail or kama |
| **b_h** | head width (頭幅) at its widest |

Plans are top views; elevations are side views. ASCII sketches are schematic and not to scale.

### 1.2 Family tree

```
                               TSUGITE (splices)
                                      |
   +---------------+-----------------+------------------+------------------+
   |               |                 |                  |                  |
 BUTT            LAP              HOOK (on seat)     STEPPED SCARF     TENON + KEY
 tsukitsuke      aikaki           ari / kama         okkake-daisen     sao-tsugi
 mechigai        nuno / ryaku-    koshikake-ari      kanawa            sao-shachi
 hako-mechigai   kama             koshikake-kama     shiribasami       koshikake-sao-shachi
 (juji-mechigai) sogi (scarf)     mechigai-kama      (okkake-kanawa)   yatoi-sao / chigiri
                 daimochi         kakushi-kama/ari
   compression   support needed   hinge near support  bending/tension  last-member, repair,
   & alignment   below            shear + some tension capable         through-post splices
```

### 1.3 General rules for all splices

The following rules apply to every splice in this chapter in addition to → Ch. 06.

**R07-001** — **Must.** Every splice is either (a) placed on or immediately beside a support that carries its shear, or (b) of a bending-capable type (okkake-daisen, kanawa, shiribasami) placed and proportioned for the moment it must carry. *Why:* a splice that is neither supported nor bending-capable is a hinge in mid-air (→ R06-023, R06-024).

**R07-002** — **Must.** In seated splices, the female (下木) is continuous over the support and the male (上木) rests on the female's seat; the female is erected first (→ R06-016, R06-017).

**R07-003** — **Must.** Splices in parallel members are staggered (千鳥), normally by at least one bay; splices in the same member are spaced so that every piece spans at least two supports (→ R06-028, R06-029).

**R07-004** — **Must.** No splice is placed over an opening, under a post, or in the same short length as a major mortise in the same member (→ R06-025, R06-026, R06-034).

**R07-005** — **Should.** The seated splice offset from the support centre is ≈ 150 mm (≈ 5 sun), within ≈ 100–250 mm or ≈ 1–1.5 × D. Larger offsets are used only for the bending-capable splices (§4).

**R07-006** — **Should.** Match the two halves of a splice in species, moisture content, grain orientation and *kiomote/kiura* orientation (→ R06-011).

**R07-007** — **Must.** Mark both halves of a splice from the **same reference lines** (centre line 芯墨 *shinzumi*, level line 陸墨 *rokuzumi* or reference face), with the joint's key points transferred with the same sashigane and the same template where one is used. *Why:* two halves marked from different references will not meet on the same centre line.

**R07-008** — **Should.** Use a template (型板, *kataita*) for the outline of the head of a kama or dovetail and for the profile of stepped scarfs when more than one or two joints of the same size are to be cut, and mark male and female from the same template (one side of it for the male, with an allowance for the line convention, → R06-046). *Why:* guarantees interchangeability and consistent fit.

---

## 2. Simple splices

### 2.1 Butt splice — 突付け継ぎ (*tsukitsuke-tsugi*)

- **Class:** tsugite, butt family.
- **Typical use:** rafters (垂木, *taruki*) butted over a purlin or plate; floor joists (根太, *neda*) butted over a floor beam; battens, ceiling joists (野縁, *nobuchi*); floorboards (end joints over joists, → Ch. 14); minor members in concealed work; temporary work. Also, in compression, stacked posts or struts with a separate alignment device (see mechigai, §2.6).
- **Load behaviour:** compression only (end grain to end grain). No tension, no bending, no shear capacity of its own; all of these come from the support below and from nails, cramps (鎹, *kasugai*), straps or splines.
- **Proportions:** the bearing on the support should allow each piece at least about half the support width, and not less than ≈ 30–45 mm for rafters and joists on a 90–120 mm purlin/beam.
- **Orientation rules:** centred on the support; both ends cut square and true. On sloping rafters the butt is cut plumb (垂直) or square to the rafter according to the workshop's custom; whichever, both ends must match.
- **Marking:** a single square line around the member at the joint position (from the rafter or joist layout, → Ch. 11, Ch. 14).
- **Cutting sequence:** 1. mark the cut line; 2. crosscut with the saw leaving or taking the line per convention; 3. check squareness; 4. ease the arrises if the joint is visible.
- **Assembly:** place both pieces on the support, close the joint, nail each piece to the support (skew-nailed where the ends are close), or clamp with a kasugai across the joint on a concealed face.
- **Rules:**
  - **R07-009** — **Must.** A butt splice is made only directly over a support, with both pieces bearing on it and fixed to it. *Why:* it has no capacity of its own.
  - **R07-010** — **Should.** Stagger butt splices of adjacent rafters or joists so that no two neighbouring members are spliced over the same support; common practice is to alternate supports. *Why:* avoids a line of weakness in the roof or floor plane.
- **Common errors:** splice between supports; nails driven too close to the end, splitting it (leave ≥ ≈ 10 × nail diameter end distance where possible or pre-drill); rafters butted with a gap that collects water under the roofing.
- **Variants:** butt with a spline or loose tongue (雇い実); butt with mechigai (§2.6); butt with kasugai.

### 2.2 Half-lap splice — 相欠き継ぎ (*aikaki-tsugi*)

- **Class:** tsugite, lap family.
- **Typical use:** secondary horizontal members (sleepers, ties, battens, 胴縁 *dōbuchi*), temporary members, members supported continuously along their length (e.g. a plate on a wall head), some nuki splices (inside the post, §6.1), historical minor framing.
- **Load behaviour:** the halves overlap; compression and shear are passed by bearing if the lap is on a support; tension and bending only through pins, nails or bolts crossing the lap plane. Without fasteners it has no tension capacity. Each half has only half the section at the joint.
- **Proportions:** lap depth = ½ D (or ½ W if the lap is vertical); lap length ≈ 1.0–2.0 × D (commonly ≈ 1.5 D); 2 pins or nails/bolts spaced along the lap, each ≥ ≈ 4 pin diameters from the ends of the laps.
- **Orientation rules:** for vertical load the lap plane is horizontal and the joint is placed on a support; the **upper piece (上木) is the one which, if unsupported, would be carried by the lower** — in practice the piece placed second. When the lap plane is vertical (lap seen from above), the joint resists vertical bending better (each half keeps full depth) but offers no bearing between the halves; it then relies entirely on the fasteners.
- **Marking:** centre line or mid-depth line on both side faces; shoulder lines square around; end lines.
- **Cutting sequence:** 1. saw the shoulder to the half-depth line; 2. rip (縦挽き) along the half-depth line from the end, or remove the waste by multiple kerfs and chisel; 3. pare the lap face flat and true; 4. check with a straightedge; 5. bore the pin holes after trial assembly (for draw, → Ch. 09).
- **Assembly:** lower piece in place; upper piece laid on; pins or nails driven.
- **Rules:**
  - **R07-011** — **Must.** A plain half-lap splice carries no tension or bending of its own; use it only on a support or in members where these forces are negligible, and always fix it with pins, nails or bolts. *Why:* the geometry provides no interlock.
- **Common errors:** lap faces not flat (the joint rocks); lap too short for the pins' end distances; plain half-lap used for a wall plate between posts.
- **Variants:** hooked half-laps (布継ぎ, 略鎌, §2.3); half-lap with mechigai; bevelled half-lap (殺ぎ相欠き); the half-lap as the basis of daimochi (§2.5), okkake and kanawa (§4).

### 2.3 Hooked half-laps — 布継ぎ (*nuno-tsugi*) and 略鎌継ぎ (*ryaku-kama-tsugi*)

- **Class:** tsugite, lap family with hook.
- **Typical use:** nuki (splices inside posts, §6.1), tie-members and secondary members in tension, members where the joint can be assembled by lowering or lateral movement; historically in daibutsuyō nuki.
- **Load behaviour:** the ends of the laps are cut as hooks (steps) that engage one another, so the joint resists tension by bearing between the hooks (with shear along the grain behind them). Bending and shear only with a support or fasteners.
- **Description:** 布継ぎ (*nuno-tsugi*) is described as a half-lap in which each member's lap is cut to a hook (鉤型, *kagi-gata*) — symmetrically top-and-bottom or side-to-side — so that the two hook into each other and the joined member behaves "like one piece". 略鎌 (*ryaku-kama*, "abbreviated kama") is the analogous form in which a small projection (a short hook) is left at the tip of each lap to resist pulling apart; it was used notably for nuki in the Great Buddha style and is regarded as the ancestor of the okkake splice (→ Ch. 06 §3.4). Usage of these two names overlaps in the literature.
- **Proportions:** lap length ≈ 1.5–2.5 × D; hook (step) height ≈ 1/6–1/4 of the lap depth; length of wood beyond each hook ≥ ≈ 6 × hook height (shear, → R06-007).
- **Orientation rules:** the hook faces must face so that tension brings them into bearing; the piece placed second is lowered (or slid) so that its hooks drop behind the hooks of the first.
- **Marking:** mid-depth line, hook lines, shoulder lines; mark both halves from a single template.
- **Cutting sequence:** as for aikaki, then cut the hook steps with saw and chisel; pare hook faces square to the axis (or with a very slight undercut so that they pull tight).
- **Assembly:** lower first piece; lower/slide second so hooks engage; drive pins or, in nuki, drive the wedge (§6.1).
- **Rules:**
  - **R07-012** — **Should.** Give hooked laps a length behind each hook of at least ≈ 6 times the hook height, and never less than ≈ 1 × D. *Why:* the hook transfers tension into the member by shear along the grain behind it.
- **Common errors:** hooks too short (they shear off); hooks cut with the faces sloping the wrong way (they ride over each other under tension).
- **Variants:** 略鎌 in nuki; 追掛け大栓 (§4.1) is its developed form.

```
 ELEVATION, hooked half-lap (schematic)
 ======================+                         
    piece A            |_________________        
                       |         _______|__________________
 ======================+________|  hook |      piece B
                                |_______|__________________
```

### 2.4 Bevelled scarf — 殺ぎ継ぎ (*sogi-tsugi*)

- **Class:** tsugite, scarf family.
- **Typical use:** rafters (垂木) over a purlin or plate; ceiling battens (竿縁 *saobuchi*, 野縁 *nobuchi*); fascia and eaves boards (鼻隠し *hanakakushi*, 広小舞 *hirokomai*); roof sheathing battens; handrails; other light members where a butt would show an open end-grain line or where the members must be nailed together over a support.
- **Load behaviour:** the long sloping faces give a large glue/nail area and a joint line that closes rather than gapping; compression and some bending when nailed over a support. No inherent tension capacity.
- **Proportions:** slope of the scarf ≈ 1:2 to 1:4 in rafters and light members (length of scarf ≈ 2–4 × D); longer scarfs (≈ 1:6–1:8) for fascia boards and handrails where appearance matters.
- **Orientation rules:** on rafters the scarf is cut in elevation so that the **upper piece's bevel lies on top of the lower piece's bevel** and both are nailed down into the support; on fascia boards the scarf is cut in plan (visible edge) with the lap oriented so that rain runs off the joint, i.e. the outer (visible) lip belongs to the piece higher up the slope or nearer the weather.
- **Marking:** two parallel sloped lines on both side faces, from the same template or sashigane setting.
- **Cutting sequence:** 1. mark; 2. saw both bevels with the same saw setting; 3. plane the bevels flat; 4. trial fit.
- **Assembly:** place lower piece; lay upper piece; nail through both into the support (for rafters), or glue and nail (finish members).
- **Rules:**
  - **R07-013** — **Must.** A sogi-tsugi in a structural member (rafter, batten) lies over a support and both pieces are nailed to it. *Why:* the scarf has no tension capacity and bending capacity only from the nails.
  - **R07-014** — **Should.** On exterior boards orient the scarf so that the visible outer lip sheds water away from the joint. *Why:* water drawn into an end-grain scarf rots it quickly.
- **Common errors:** bevel angles mismatched (a gap opens at one end); scarf too short, leaving a thin feather edge that splits under nails.
- **Variants:** 殺ぎ相欠き (scarf with a small step at each end); 腰掛け殺ぎ (scarf with a seat); いすか継ぎ (§6.3) as a finish scarf.

### 2.5 Splice on a support — 台持ち継ぎ (*daimochi-tsugi*)

- **Class:** tsugite, lap/seat family (splice made **on** a support).
- **Typical use:** round-log roof beams (丸太梁, *marutabari*) and roof tie-beams (小屋梁 *koyabari*) spliced over a post, an interior girder (敷梁 *shikibari*) or a wall plate; beams in wagoya roofs; heavy timbers where a long cantilever is impossible; post root splices (台持ち根継ぎ, §6.9).
- **Load behaviour:** made directly over a support; the lower piece (下木) sits on the support and the upper piece (上木) sits on the lower piece, so vertical load passes straight down through bearing. Tension capacity comes from small steps (目違い/顎) at the ends of the laps and from dowels (太枘, *dabo*) or bolts. Bending continuity is limited but, because the joint is over a support, the negative moment is shared by the support.
- **Proportions:** lap length ≈ 1.5–2.5 × D (for log beams, ≈ 1.5–2 × the diameter at the joint); lap depth ≈ ½ D; small end steps ≈ 15–30 mm to locate the pieces; 2 dabo (≈ 1 sun, ≈ 30 mm square or round hardwood dowels, ≈ 2–3 sun long) set in the lap face, or 2 bolts; commonly the joint length is arranged so that the **support is at the centre** of the lap.
- **Orientation rules:** the joint is centred on the support. The lower piece is the one whose end would otherwise be the more heavily loaded (commonly the longer span's member, or the one set first in erection sequence). The lap plane is horizontal. The dabo are placed so that neither lies directly over the post tenon.
- **Marking:** on log beams, a horizontal level line (陸墨) and centre line (芯墨) are struck along the log first (→ Ch. 02, Ch. 11); the lap plane is marked from the level line, not from the irregular log surface.
- **Cutting sequence:** 1. establish level and centre lines on both logs; 2. mark lap plane, steps, dabo positions; 3. saw shoulders and steps; 4. remove waste (saw kerfs and chōna/chisel, or rip saw); 5. plane lap faces flat; 6. bore dabo holes in the lower piece; 7. trial fit and transfer dabo positions to the upper piece.
- **Assembly:** lower piece set on the support (usually with the post tenon passing into it); dabo inserted; upper piece lowered on; bolt or cramp added where required.
- **Rules:**
  - **R07-015** — **Must.** A daimochi splice is made directly over a support, with the lap bearing fully on it. *Why:* the joint is designed to pass load down into the support; it has little capacity away from it.
  - **R07-016** — **Must.** On log beams, cut the lap plane from struck level and centre lines, not from the natural surface. *Why:* otherwise the upper piece will twist and not seat.
  - **R07-017** — **Should.** Keep dabo holes and the post tenon mortise apart by at least ≈ 1 × dabo size of solid wood. *Why:* combined holes split the lower piece over the support.
- **Common errors:** splice located off the support; lap faces not flat and not level (the upper beam rocks); dabo so close to the ends that the steps split.
- **Variants:** daimochi with bolts; daimochi with kama on the lap (台持ち鎌); daimochi netsugi (§6.9).

```
 ELEVATION, daimochi-tsugi over a post (schematic)
      upper piece (上木)
   ______________________________
  |                     _________|_______________________
  |____________________|  dabo  o   lap   o dabo  |      lower piece (下木)
                       |________________________|_______
                                  |  post  |
                                  |        |
```

### 2.6 Tongued butt — 目違い継ぎ (*mechigai-tsugi*)

- **Class:** tsugite, butt family with alignment tongue.
- **Typical use:** members in compression that need only to be kept in line: post root splices (as part of netsugi, §6.9), struts, sills bedded on a continuous foundation, finish members (長押 *nageshi*, 敷居 *shikii* on a continuous support, 回り縁 *mawaribuchi*) where one face must stay flush with the next.
- **Load behaviour:** compression by end bearing; the tongue (目違い) resists lateral offset (shear) in the direction(s) it spans; no tension.
- **Proportions:** tongue thickness ≈ 1/4–1/3 of the dimension across which it acts (e.g. 25–35 mm in a 105 mm member); tongue length ≈ 15–30 mm (5 bu–1 sun); set in from the visible face by at least ≈ 1/4 of the member width so it is not seen.
- **Orientation rules:** the tongue belongs to the piece placed second (male); for a post root splice the tongue is usually on the **new** piece, so that the old post only needs a mortise cut from below.
- **Marking:** centre lines on the end faces; tongue outline from the centre line.
- **Cutting sequence:** 1. square the ends; 2. saw tongue cheeks; 3. chop mortise/groove in the female; 4. trial fit.
- **Assembly:** male lowered/raised into female; end faces must bear fully.
- **Rules:**
  - **R07-018** — **Must.** In compression splices the **end faces bear**, not the tongue: the tongue is cut ≈ 1 mm shorter than its mortise. *Why:* if the tongue bottoms out, the load passes through the small tongue and splits the female.
- **Common errors:** tongue too long (end faces open); tongue on the visible face edge.
- **Variants:** 一方目違い (one-direction tongue), 二方目違い (two), 十字目違い (*jūji-mechigai*, cross-shaped tongue acting in both directions, used in post splices), 箱目違い (§2.7).

### 2.7 Box-tongued butt — 箱目違い継ぎ (*hako-mechigai-tsugi*)

- **Class:** tsugite, butt family with box-shaped tongue.
- **Typical use:** post root splices (根継ぎ) where the post is replaced below a wall or under a sill; compression members exposed on several faces where a clean square joint line is wanted all round; as a component combined with kama in 箱目違い鎌 (§3.3).
- **Load behaviour:** compression; the box (a central rectangular tongue with shoulders on all four sides) resists lateral displacement in both horizontal directions and resists twisting better than a single-direction tongue. No tension.
- **Proportions:** box ≈ 1/3–1/2 of W in each direction, length ≈ 1–1.5 sun (30–45 mm); shoulders ≥ ≈ 1/4 W each side.
- **Orientation rules:** as for 目違い; for netsugi the male box is usually on the new lower piece.
- **Assembly:** requires insertion along the axis — for a post root splice the post must be jacked up by at least the box length plus clearance (揚げ前, *agemae*, → Ch. 16).
- **Rules:**
  - **R07-019** — **Should.** Use hako-mechigai (or jūji-mechigai) only where the post can be raised by the tongue length; otherwise choose a laterally assembled splice (kanawa, shiribasami, daimochi). *Why:* the box cannot be inserted sideways.
- **Common errors:** attempting to insert a box tongue by forcing the post sideways; box too large (shoulders too narrow to bear).
- **Variants:** 十字目違い (cross), 四方目違い; 箱目違い鎌 (combined with a kama for tension).

---

## 3. Hook splices: dovetail and gooseneck

### 3.1 Plain dovetail splice — 蟻継ぎ (*ari-tsugi*)

- **Class:** tsugite, dovetail family (without seat).
- **Typical use:** light secondary members bearing continuously or near a support: sleepers (大引 *ōbiki*) over a post-strut (床束 *tsuka*), ledgers (根太掛け *nedakake*), wall girts, members of low importance; historically in some sills. In fine joinery, board-end splices.
- **Load behaviour:** resists tension only moderately (the short dovetail head bears on the socket's flared faces and splits the female jaws); no bending; shear only if supported below. Among structural splices it is the **weakest in tension**, but it needs only a short length and removes relatively little of the female.
- **Proportions:** neck width b_n ≈ 1/3 W (0.28–0.35 W); head width b_h ≈ 0.45–0.55 W; flare per side ≈ 1:3–1:6; dovetail length ≈ 0.6–1.0 W (e.g. 60–100 mm in 105–120 mm members). Full depth unless hidden (§3.5).
- **Orientation rules:** female continuous over or immediately beside the support; male dropped from above.
- **Marking:** centre line (芯墨) on top and bottom faces; shoulder line square round; head outline from template on top face and, reduced by the sliding slope, on the bottom face.
- **Cutting sequence (male):** 1. saw the shoulder cheeks down to the neck lines; 2. rip the cheeks of the dovetail along the flare lines (top-to-bottom marks); 3. remove waste; 4. pare the flare faces to the lines. **(female):** 1. saw the socket sides; 2. chop out the socket (through); 3. pare flared faces.
- **Assembly:** female placed; male lowered; kigoroshi on the male's flare faces (→ R06-041); drive down until top faces are flush.
- **Rules:**
  - **R07-020** — **Must.** Use the plain dovetail splice only for secondary members and only on or immediately next to a support; never for plates, girders, sills carrying posts or any member in which tension is expected. *Why:* its tension capacity is limited by the splitting of the female jaws and is low.
- **Common errors:** neck too narrow (neck breaks); head too wide (jaws split); flare too steep.
- **Variants:** 腰掛け蟻 (§3.2); 隠し蟻 (§3.5); 四方蟻 (§6.9).

### 3.2 Seated dovetail splice — 腰掛け蟻継ぎ (*koshikake-ari-tsugi*)

- **Class:** tsugite, dovetail family with seat.
- **Typical use:** sills (土台) in secondary positions (interior sill lines, short sill runs), sleepers (大引), purlins (母屋) and ridge (棟木) near struts in modest buildings, floor beams, and generally where a cheap, short, reliable splice near a support is wanted. Standard in precut. Precut/house-building literature often describes it as the most basic splice: adequate for sills, unsuitable for plates and girders that carry significant tension.
- **Load behaviour:** the seat (腰掛け) carries the male's end shear by bearing on the female; the dovetail resists modest tension (keeps the pieces from drawing apart); it acts as a **hinge** — no significant bending capacity; little torsional resistance.
- **Proportions (representative):**
  - neck width b_n ≈ 1/3 W (e.g. 30 mm in 105, 33–36 mm in 120, 40–45 mm in 150);
  - head width b_h ≈ 0.45–0.5 W (45–50 / 50–55 / 60–70 mm);
  - dovetail length (from the male's upper shoulder to tip) ≈ 0.6–0.8 W (60–75 / 70–90 / 90–110 mm);
  - seat length s ≈ 15–30 mm (5 bu–1 sun), up to ≈ 45 mm in large members;
  - seat height: the seat is the lower part of the female's end; commonly ≈ ½ D (range ≈ 1/3–1/2 D by school);
  - sliding slope on flare faces ≈ 1:25–1:40 over the depth (i.e. of the order of 3–4.5 mm over a 105–120 mm depth; schools differ on whether this is applied to each flare face or split between them).
- **Geometry (description):** the **female** end has, over the length s, its upper part removed down to seat height, leaving the seat (the ledge) at the bottom; behind the seat a flared socket is cut right through the depth, and the neck slot continues through the seat. The **male** end has its lower part cut back by s up to seat height on both sides of the neck, so that its upper part overhangs and rests on the female's seat; the dovetail (neck and head) projects from the male full depth and drops into the socket.
- **Orientation rules:**
  - female (下木) is continuous over the support and cantilevers ≈ 150 mm past the support centre (→ R07-005); male (上木) rests on the seat;
  - in sills, the anchor bolt is placed near the male's end so that tightening it clamps the male on the female's seat (→ R06-019); posts are not placed on the joint;
  - direction along the run follows the erection plan and moto/sue custom (→ R06-020).
- **Marking (墨付け):** centre lines on top and bottom faces of both pieces; shoulder line (胴付き墨) square around both; seat line; seat height line on the side faces; neck lines at ±b_n/2 from centre; head outline from template on top face; the same outline reduced by the sliding slope on the bottom face; assembly marks (合印).
- **Cutting sequence (male):**
  1. saw down the upper shoulder lines on either side of the neck to the neck lines (full depth, but only to the seat line for the lower part — see step 2);
  2. saw the lower shoulder (seat notch) — cut the seat notch on both sides of the neck to seat height by length s;
  3. rip the dovetail flare faces from top-face line to bottom-face line (the sliding slope is thereby built in);
  4. remove waste; pare all faces; check the seat notch surface is flat and square.
- **Cutting sequence (female):**
  1. saw the seat: cut down on the shoulder line to seat height, rip along seat height from the end, remove the upper waste;
  2. saw the socket sides and neck slot through the full depth;
  3. chop and pare the socket (bore out waste with an auger if convenient), keeping flared faces to the lines at top and bottom;
  4. check the seat is flat and at the correct height from the reference (bottom) face.
- **Assembly:** set and fix the female; apply kigoroshi to the male's flare faces and to the leading arrises of the head; lower the male, align, and drive home with the gennō (through a protective block) until the top faces are flush and the male's overhang sits hard on the seat. In sills, fit the anchor washer and nut after the frame is squared.
- **Rules:**
  - **R07-021** — **Must.** In a koshikake-ari splice the seat bears the shear: the male's overhang must sit hard on the seat, and the dovetail must not bottom out. *Why:* if the seat is open, the dovetail's thin head carries the shear and splits.
  - **R07-022** — **Should.** Use koshikake-ari in preference to plain ari wherever a dovetail splice is chosen, and prefer koshikake-kama over koshikake-ari wherever tension is expected (outer sill lines, plates, girders). *Why:* the kama's longer neck and barbed head resist pull-out much better.
  - **R07-023** — **Must.** Each female jaw (口脇) beside the socket must be at least ≈ 1/4 W wide at the narrowest point. *Why:* narrower jaws split under the wedge action of the head.
- **Common errors:** seat cut at different heights on the two pieces (the top faces do not come flush); socket cut vertically while the head was cut with sliding slope (the joint binds at the top and is loose at the bottom); dovetail too long relative to the socket (shoulder open); anchor bolt placed in the female only.
- **Variants:** 腰掛け蟻 with mechigai; 隠し蟻 (§3.5); ari with a long seat in large purlins.

```
 PLAN (top face), assembled koshikake-ari (schematic)
   male (上木, ogi)             female (下木, megi)
 -----------------------+-----------------------------
                        |     ______
                        |____/      |
                 neck ->|____       |  <- dovetail head in socket
                        |    \______|
                        |
 -----------------------+-----------------------------
                        ^ shoulder of male's upper part

 SIDE FACE, assembled (the only visible line is a step)
 -----------------------+-----------------------------
          male          |               female
                   +----+   <- male rests on the seat
                   |  seat (koshikake), length s
 ------------------+----------------------------------
```

### 3.3 Plain gooseneck splice — 鎌継ぎ (*kama-tsugi*), with 目違い鎌 and 箱目違い鎌

- **Class:** tsugite, kama family (without seat).
- **Typical use:** members supported continuously or at close intervals: sills on a continuous foundation (in some older and regional practice), plates lying on a wall or on a beam head, sleepers, ledgers; and as the tension element inside compound splices (daimochi-kama, mechigai-kama). The kama is reported in Japanese buildings from an early date (Nara period in some accounts) and is one of the oldest named hook splices.
- **Load behaviour:** the long neck and the barbed head (with shoulders facing back toward the neck) resist tension better than a dovetail of the same width, because the head's bearing faces are nearly square to the axis rather than flared, which reduces the splitting action on the female jaws. No bending; shear only with support; torsion only with mechigai.
- **Proportions (representative):** neck width b_n ≈ 1/3 W; head width b_h ≈ 0.5–0.6 W; neck length ≈ 0.5–0.8 D; head length ≈ 0.6–0.8 D; total kama length ≈ 1.2–2.0 D; sliding slope on the head's bearing faces ≈ 1:25–1:40 (a published example: about 1.5 bu over a kama 4 sun deep, i.e. ≈ 4.5 mm over ≈ 120 mm). A frequently quoted example for a plate is the "6-sun kama" (六寸鎌): head 3 sun + neck 3 sun; deeper members may take an 8-sun kama.
- **Head shape:** from the neck the head widens abruptly to its full width at the "shoulders" (the bearing faces, square or very slightly undercut to the axis), then tapers toward its tip. The tip is slightly narrower than the full width to ease entry. Proportions of the taper vary by school; use a template.
- **Orientation rules:** female continuous over/near support; male dropped from above.
- **Rules:**
  - **R07-024** — **Must.** The bearing faces of a kama head must be **square (or very slightly undercut) to the axis**, not flared like a dovetail. *Why:* square bearing faces transmit tension along the grain without prying the female jaws apart; a flared kama is a dovetail in disguise.
  - **R07-025** — **Must.** Leave a clearance of ≈ 1 mm between the tip of the kama head and the end of the socket. *Why:* the joint must close at the shoulder and bear on the head's bearing faces, not at the tip (→ R06-044).
- **Variants:**
  - **目違い鎌継ぎ** (*mechigai-kama-tsugi*) — a kama splice with an added mechigai (small tongue and groove) along one or both faces (commonly on the upper face or the side), preventing the two members from rotating or shifting relative to one another about the axis; used where the member is exposed to twisting or where a flush face must be guaranteed (e.g. exposed plates).
  - **箱目違い鎌継ぎ** (*hako-mechigai-kama-tsugi*) — a kama whose shoulders are surrounded by a box-shaped mechigai (a small housing of the male's end into the female on several faces). It resists twisting and lateral displacement in both directions and hides the kama's outline on the faces covered by the box. It requires more careful cutting and is used on better-quality work and exposed members.
- **Common errors:** head bearing faces flared; kama too short (neck breaks before the jaws engage fully); kama used without support in a spanning member.

### 3.4 Seated gooseneck splice — 腰掛け鎌継ぎ (*koshikake-kama-tsugi*)

- **Class:** tsugite, kama family with seat. The standard splice of Japanese post-and-beam house framing, both hand-cut and precut.
- **Typical use:** sills (土台) — the standard sill splice; girders (胴差 *dōsashi*), wall plates (軒桁 *nokigeta*), interior plates (敷桁 *shikigeta*), purlins (母屋), ridge (棟木), floor beams (大引). Everywhere near a support.
- **Load behaviour:** seat carries shear; kama carries tension (moderate — better than koshikake-ari but well below the solid member); acts as a hinge (no significant bending); little torsion resistance unless combined with mechigai. Tests typically show failure by splitting of the female jaws, shear of the male head, or fracture at the neck; the joint's tension capacity is a fraction of the member's (→ Ch. 06 §9.1, Ch. 17).
- **Proportions (representative):**
  - neck width b_n ≈ 1/3 W (30 mm in 105; 33–36 mm in 120; 40–45 mm in 150);
  - head width b_h ≈ 0.5–0.6 W (50–60 / 60–70 / 75–90 mm);
  - total kama length ≈ 1.2–1.8 D (≈ 120–160 mm in 105; ≈ 150–180 mm in 120; ≈ 180–240 mm in 150);
  - seat length s ≈ 15–30 mm (a published example gives 5 bu ≈ 15 mm for the seat), up to ≈ 45 mm in large members;
  - seat height ≈ 1/3–1/2 D by school; where D is large (≥ ≈ 150 mm) some carpenters cut the seat with an additional step or mechigai;
  - sliding slope on the kama's bearing faces ≈ 1:25–1:40 over D.
- **Geometry (description):** as for the seated dovetail (§3.2), with the dovetail replaced by the kama. The female has a seat at the lower part of its end and a kama socket cut through the full depth behind it, with the neck slot through the seat; the male's upper part overhangs and rests on the seat; its kama (neck and head, full depth) drops into the socket.
- **Orientation rules:**
  - female continuous over the support, projecting ≈ 150 mm past the support centre (→ R07-005); male on the seat;
  - **sills (土台):** the female is placed so that it passes over the foundation at a post or anchor position; the anchor bolt is placed near the end of the **male** (上木) so that it presses the male down onto the female (押さえ勝手) (→ R06-019); a common precut recommendation places the anchor bolt around 300 mm from the post centre on the male side for kama splices — follow the current specification (→ Ch. 17); posts are never set on the joint; the joint is not placed at a doorway;
  - **plates and girders:** the female passes over the post (the post's tenon enters the female, not the male); the male hangs on the female's seat; the joint is on the side of the post away from where the next member (beam, brace) frames in, where possible;
  - **purlins, ridge:** female over the strut (束), male on the seat; joints of adjacent purlins staggered;
  - **direction:** the female faces the direction from which the next member will arrive in erection (→ R06-020).
- **Marking (墨付け):**
  1. centre lines on top and bottom faces of both pieces;
  2. shoulder line of the male's upper part (胴付き) square around; seat-length line s behind it;
  3. seat height line on both side faces (from the bottom reference face);
  4. kama outline on the top face from the template, centred on the centre line;
  5. on the bottom face, the same outline reduced by the sliding slope on the bearing faces;
  6. neck lines through the seat;
  7. female: identical lines from the same template, the socket outline equal to the head plus the line allowance per the workshop's convention (→ R06-046).
- **Cutting sequence (male):**
  1. saw the upper shoulders either side of the neck (down to seat height);
  2. saw the lower shoulders (seat notch) either side of the neck, and remove the notch waste by ripping along the seat-height line;
  3. saw the neck and head cheeks full depth (top line to bottom line, building in the slope);
  4. saw the head's bearing faces (across the neck-to-head transition) with a narrow saw or chisel;
  5. remove waste; pare all faces; chamfer the leading arrises lightly.
- **Cutting sequence (female):**
  1. cut the seat (saw down on the shoulder line to seat height, rip along seat height, remove waste);
  2. bore out the bulk of the socket with an auger; saw the socket sides where possible;
  3. chop the socket through the full depth, paring the bearing faces square (with the slope) and the sides to the lines;
  4. check depth of seat from bottom reference and flatness.
- **Assembly:**
  1. set and fix the female (sills: onto the foundation; plates: onto the post tenons);
  2. kigoroshi on the male's head bearing faces, neck cheeks and leading arrises;
  3. lower the male so the kama enters the socket; drive with the gennō (using a striking block) until the top faces are flush and the overhang bears on the seat;
  4. check the shoulder line is closed on the side faces; drive the post tenons, pins and anchor nuts after squaring the frame.
- **Rules:**
  - **R07-026** — **Must.** In sills, the post must never stand over any part of the koshikake-kama joint, and the post tenon must enter the solid female at least ≈ 1 × D from the joint. *Why:* the joint's section is already reduced by the socket and seat.
  - **R07-027** — **Must.** In plates and girders, the post tenon must enter the **female**, and the joint must be on the far side of the post from any beam or brace framing into the plate at the same place. *Why:* the female carries the cantilever and the male's reaction; putting additional mortises into the male's thin end or into the female's jaws weakens both.
  - **R07-028** — **Should.** Where the member is exposed to twisting (plates carrying eccentric roof load, sills with offset posts) or where top faces must stay flush, add a mechigai (目違い付き腰掛け鎌) on the top face or sides. *Why:* the plain kama offers little resistance to rotation about the axis.
  - **R07-029** — **Should.** Do not rely on the koshikake-kama for tension in primary lateral-load paths; where tension is expected (e.g. plates tying frames, sills at hold-down posts), add a strap (短冊金物 *tanzaku kanamono*) or choose okkake-daisen or kanawa. *Why:* the joint's tension capacity is a fraction of the member's; modern practice in Japan (→ Ch. 17) specifies straps for plate and girder splices in many cases.
  - **R07-030** — **Must.** The kama socket in the female is cut through the full depth, and the female's end beyond the socket (the part carrying the head's bearing load) is at least ≈ 1 × the head length long before any other mortise. *Why:* shear-out along the grain behind the head.
- **Common errors:** female and male swapped (male over the post); seat not in contact; kama socket cut square while the head was sloped (binding); post placed on the male end; anchor bolt placed in the female only; kama over-long, making the jaws of the female long and weak; kigoroshi overdone so that the female jaws split during driving.
- **Variants:** 目違い付き腰掛け鎌 (with mechigai); 箱目違い腰掛け鎌; 腰掛け鎌 with a strap or bolt (modern); 隠し鎌 (§3.5); 台持ち鎌 (kama on a daimochi splice).

```
 PLAN (top face), male end of koshikake-kama (schematic)
                  shoulder (upper part)
                      |
  male (ogi)          |<-neck->|<-------- head -------->|
 _____________________|         ________________________
                      |________|  <- bearing face       \
                      |                                   >  tip
                      |________    <- bearing face       /
 _____________________|        |________________________/
                      ^
     lower part of male is cut back by s behind this line (seat notch)

 SIDE FACE (assembled): simple step, kama hidden
 ------------------------------+----------------------------
    male (上木)                 |           female (下木)
                         +-----+
                         | seat |
 ------------------------+----------------------------------
                                          ^ post ≈ 150 mm beyond
```

### 3.5 Hidden kama and hidden dovetail — 隠し鎌・隠し蟻 (*kakushi-kama / kakushi-ari*)

- **Class:** tsugite, hidden variants of the kama and dovetail families.
- **Typical use:** exposed plates, beams, sills and finish members (e.g. exposed 敷桁, 化粧梁, 地覆 *jifuku*, 長押 in some forms) where the kama or dovetail outline must not show on the visible faces (usually the top face is concealed by the floor or roof, but the underside and the sides are seen, or vice versa).
- **Load behaviour:** as the corresponding visible form, but with a reduced depth of kama/dovetail (typically the kama occupies only part of the depth); the tension capacity is correspondingly lower (→ R06-057).
- **Description:** in the common form, the kama (or dovetail) is cut over only part of the depth — for example the lower part — while the upper part of the joint is a plain butt with a shoulder (or a housing, 被せ *kabuse*), so that the visible face shows only a straight line. Other forms hide the kama within a mechigai or box. Exact forms differ between workshops; the name "隠し鎌" is used for several of these.
- **Proportions:** hidden kama depth ≈ 1/2–2/3 D; neck and head widths as in §3.3.
- **Orientation rules:** the concealed face (on which the kama or dovetail would show) is placed on the hidden side; the male is inserted from the hidden side (usually from above, the covering part lying on top).
- **Rules:**
  - **R07-031** — **Should.** Use a hidden kama only where the reduced tension capacity is acceptable, or relocate it to a less-loaded position; do not use a hidden variant simply because it looks better in a place where a full kama is structurally needed (→ R06-057). *Why:* concealment removes part of the head.
- **Common errors:** covering part cut too thin (it splits off); hidden part cut too shallow to engage.
- **Variants:** 隠し蟻 (hidden dovetail), 隠し目違い, 箱目違い鎌 (§3.3).

---

## 4. Bending-capable stepped scarfs

The okkake-daisen, kanawa and shiribasami splices share a common idea: each piece is cut down to a long lap of roughly half the section, the laps are **stepped** at mid-length so that they hook each other (the jaw, 顎/腮 *ago*), the tips carry **small tongues (目違い)** into the other piece's shoulder to prevent lateral displacement, and the joint is **locked by pins or a key** that bring the pieces into firm contact. They transmit tension, shear and a meaningful share of bending moment — among Japanese splices they have the highest bending efficiency — and they can be placed away from the immediate vicinity of a support. They are still weaker than the solid member.

**R07-032** — **Must.** Do not assume that a stepped scarf restores the full bending strength or stiffness of the member. Place it where the moment is moderate (near a support or near the inflection zone, commonly within about 1/4 span of a support) and, for primary members, verify by test-based values (→ Ch. 17). *Why:* the lap section at the joint is roughly half the member and the joint rotates by embedment of pins and jaws.

**R07-033** — **Should.** Make stepped scarfs about **3 × D** long (okkake-daisen ≈ 3–3.5 D; kanawa and shiribasami ≈ 2.5–3 D). *Why:* this is the length at which the lap sections and shear planes behind the steps become adequate; shorter joints lose strength quickly (it is commonly stated that ≈ 3 × D gives the best performance).

### 4.1 Chasing splice with large pins — 追掛け大栓継ぎ (*okkake-daisen-tsugi*)

- **Class:** tsugite, stepped scarf with pins (略鎌-derived).
- **Typical use:** plates (軒桁, 敷桁), girders (胴差), beams (梁), purlins (母屋), ridge (棟木) and sills (土台) in hand-cut traditional work where tension and bending continuity are wanted; members spliced away from a post (e.g. in long spans with intermediate supports), exposed members in minka and temples. Standard for good-quality hand-cut plates in many regions.
- **Load behaviour:** resists tension (commonly cited as having the highest tensile capacity among traditional splices), shear, and bending moment (one of the highest bending efficiencies among traditional splices); moderate torsion resistance by virtue of the tip mechigai. Behaviour is governed by embedment at the jaws and pins and by shear along the grain behind the jaws.
- **Proportions (representative):**
  - total length L ≈ 3–3.5 × D (e.g. ≈ 315–370 mm in 105; ≈ 360–420 mm in 120; ≈ 450–525 mm in 150);
  - lap thickness ≈ ½ of the section at each side of the jaw;
  - jaw (顎) height ≈ D/10–D/8 (≈ 10–20 mm), at mid-length;
  - sliding slope (滑り勾配) of the sliding faces ≈ 1:10;
  - tip mechigai / eriwa (襟輪): ≈ 1/3 W wide (or a lip of ≈ 10–15 mm), ≈ 15–25 mm long;
  - daisen: usually **2**, hardwood (kashi, keyaki), square ≈ 15–18 mm in 105, ≈ 18–21 mm in 120, ≈ 21–24 mm in 150 (round daisen of similar diameter are also used); one on each side of the jaw, each ≥ ≈ 4–5 pin sizes from the jaw and from the tip of the lap it passes through. Published tests are reported to show no gain in capacity from 4 daisen over 2.
- **Geometry (description):** the two pieces have the **same shape** (the joint is sometimes said to have no male/female distinction), one rotated 180° relative to the other. Each end is cut down to a long lap which is stepped at mid-length by the jaw so that the lap is thinner near its root and thicker toward its tip; the two laps interlock at the jaws so that pulling the pieces apart brings the jaw faces into bearing. The sliding faces are given a slope of about 1/10 so that, as the second piece is driven along the axis ("chased", 追い掛ける) the two pieces are drawn together and the shoulders (胴付き) at both tips close tight. Small mechigai/eriwa at the tips keep the faces aligned. The two daisen are driven **through the side of the joint**, through material of both pieces, and lock it. **Uncertainty:** published drawings differ in whether the stepped profile is shown in the side elevation or in plan and in the exact form of the eriwa; the rules below hold for either orientation.
- **Orientation rules:**
  - the piece set first is called the lower piece (下木) and the piece slid in second the upper piece (上木); the second piece is **not dropped from above but slid along the axis** into the first — ensure axial room for this movement during erection (→ R06-037);
  - place the joint near a support where possible (≈ 150 mm from post centre on the cantilever side as for other splices), or away from the post at a moderate-moment position when a post position is not available; never at mid-span of a long unsupported member;
  - where the joint is visible, place the side on which the daisen show and the profile show according to the building's aesthetic custom (e.g. daisen on the inner, less prominent face);
  - orient so that the jaw bearing faces are loaded by the expected tension, and so that gravity load on the upper piece presses it onto the lower piece's lap.
- **Marking (墨付け):**
  1. centre lines and reference faces on both pieces;
  2. overall joint length L, tips and shoulders;
  3. jaw position (mid-length) and jaw height;
  4. sliding-face lines at the specified slope from template;
  5. mechigai/eriwa outlines at the tips;
  6. daisen centres (transfer later after trial fit for draw);
  7. mark both pieces from one template, turned end-for-end.
- **Cutting sequence:**
  1. saw the shoulders at both tips (with mechigai outline);
  2. rip the long sliding faces with the slope (rip saw, or a series of kerfs and chisel); take great care to keep them flat and true in both directions;
  3. saw and chop the jaw step;
  4. cut the mechigai/eriwa tongues and their grooves;
  5. pare all faces; check with straightedge and square;
  6. trial fit (仮組) — slide the pieces together, check shoulders close, mark daisen holes through both pieces (bore after trial fit, with a slight offset for draw if the workshop uses it, → Ch. 09);
  7. bore/chop daisen holes (square daisen holes are chopped; round are bored).
- **Assembly:**
  1. set the lower piece (下木);
  2. set the upper piece in position offset along the axis as needed to clear the jaw and tips;
  3. drive the upper piece along the axis (with a heavy mallet, 掛矢 *kakeya*, via a block) — the 1/10 slope draws the pieces together until both tip shoulders close;
  4. drive the two daisen (hardwood, dry, slightly tapered at the leading end) through; trim flush or leave a uniform projection per custom;
  5. do not drive daisen until the frame is plumbed (→ R06-040).
- **Rules:**
  - **R07-034** — **Must.** Okkake-daisen splices are about 3 × D long (≥ 2.5 × D absolute minimum; 3–3.5 × D preferred) (→ R07-033).
  - **R07-035** — **Must.** The daisen must pass through **material of both pieces** and be placed on either side of the jaw with adequate end distance (≥ ≈ 4–5 pin sizes to the jaw and to the lap tip). *Why:* each daisen transfers force between the pieces in shear and embedment; a pin through only one piece does nothing, a pin near a tip shears out.
  - **R07-036** — **Must.** Provide the axial clearance needed to slide the second piece home during erection; plan the erection sequence accordingly. *Why:* the joint cannot be assembled by dropping; a member captured at its other end cannot be chased in.
  - **R07-037** — **Should.** Use dry, dense hardwood (kashi, keyaki) for daisen, and bore the holes only after trial assembly. *Why:* pins must not shrink loose; holes bored separately in each piece rarely align.
  - **R07-038** — **Should.** Keep the sliding faces flat and the slope exact; test with a straightedge along and across. *Why:* the drawing action depends on uniform contact; a hollow face lets the joint rock and loosen.
- **Common errors:** joint too short; slopes cut in the wrong sense (the joint opens instead of closing when driven); jaw too high (thin lap roots) or too low (jaw shears); daisen near the tips or through a drying check; forgetting that the joint must be slid (erection sequence fails); tip mechigai cut too tight so shoulders do not close.
- **Variants:** 追掛け金輪 (*okkake-kanawa*, a hybrid of okkake and kanawa, used by some workshops for plates); 追掛け with bolts in place of daisen (modern); okkake cut by precut machines (modern CNC lines can produce it).

```
 SCHEMATIC PROFILE, okkake-daisen (not to scale; jaw exaggerated)
      piece A (下木)                                          piece B (上木)
 ===========+------------------------------------------------+=============
            |mechigai   B's lap (thicker toward its tip) ___/|
            +--_________________________o__________________/  |
            |                            | <- jaw (顎)         |
            |  \________________o________|_______________ ____+
            |   A's lap (thicker toward its tip)       mechigai|
 ===========+------------------------------------------------+=============
            |<-------------------- L ≈ 3 D ------------------->|
   o = daisen (2), driven through both pieces, one each side of the jaw
   sliding faces sloped ≈ 1:10 ; B is slid along the axis toward A to draw tight
```

### 4.2 Iron-ring splice — 金輪継ぎ (*kanawa-tsugi*)

- **Class:** tsugite, stepped scarf with a key (sen).
- **Typical use:** plates (桁), girders, beams, sills, and **post root splices** (根継ぎ, §6.9); a standard repair splice (→ Ch. 16) because it can be **assembled laterally**, i.e. by bringing the pieces together from the side, without moving either piece along its axis; exposed members where strength in all directions is wanted.
- **Load behaviour:** resists tension, compression, shear and bending in all directions (it is often described as strong "in every direction"); torsion resisted by the tip mechigai. The key (栓) pre-stresses the joint: the tips are driven into bearing against the opposite shoulders, and the jaws bear on the key under tension.
- **Proportions (representative):**
  - total length L ≈ 2.5–3 × D (≈ 260–315 mm in 105; ≈ 300–360 mm in 120; ≈ 375–450 mm in 150);
  - lap thickness ≈ ½ section;
  - central step (jaw) height ≈ D/6–D/8 (≈ 15–20 mm in 120);
  - key (栓, sometimes 金輪栓) hardwood, rectangular: thickness ≈ 15–18 mm (105), ≈ 18 mm (120), ≈ 21–24 mm (150); width ≈ the jaw band plus embedment into each lap — commonly ≈ 30–45 mm; very slight taper (≈ 1:30–1:50) along its length; length = full thickness of the member;
  - tip mechigai: T-shaped tongues ≈ 1/4–1/3 of the thickness, ≈ 15–25 mm long.
- **Geometry (description):** both pieces are of the **same shape**. Each is cut to a lap stepped at mid-length (as in okkake, but with the lap faces **parallel** to the axis rather than sloped). At each tip a **T-shaped mechigai** engages a matching groove in the other piece's shoulder; these tongues run through the member, so they show on the outer faces, and they make it impossible to assemble the joint by dropping one piece onto the other — it is assembled by sliding one piece **sideways** (perpendicular to the face that shows the profile). When assembled, a slot remains at the central step, of the key's thickness; the key driven into this slot pushes the two step faces apart, forcing each tip hard against the opposite shoulder. **Uncertainty:** sources differ on the face from which the key is driven: it is driven perpendicular to the face on which the profile shows; several sources describe it as driven "from above" (縦から) for plates, others show it from the side face. Follow the workshop drawing.
- **Orientation rules:**
  - designation of male/female is by erection order (the piece placed first is female);
  - for plates and beams, choose the lap orientation (profile seen from the side or from above) so that the **lateral assembly direction is available** in the erection sequence and the key can be driven; for netsugi the lap plane is vertical and the new piece is slid in horizontally;
  - place near a support where possible; kanawa may be placed away from supports at moderate-moment positions (→ R07-032);
  - on visible faces, orient the side showing the T-mechigai to the less prominent side, or use shiribasami (§4.3).
- **Marking:** as okkake, with parallel lap faces; T-mechigai outlines at the tips on both outer faces; key slot at the central step (its width, marked on both pieces so that when assembled the slot is exactly the key's thickness less a small draw allowance).
- **Cutting sequence:**
  1. saw shoulders and T-mechigai outlines at the tips;
  2. rip the lap faces (parallel to the axis) and cut the central step;
  3. chop the T-mechigai tongues and grooves;
  4. cut the key slot halves at the central step;
  5. pare flat; trial assemble laterally; check shoulders and slot;
  6. make the key from dry hardwood, fitted to the slot with slight taper.
- **Assembly:**
  1. set the first piece (for netsugi: the existing post, jacked slightly and braced);
  2. slide the second piece in laterally until faces are flush;
  3. drive the key (栓) through the slot until tight — the tips close hard onto the shoulders;
  4. trim the key; optionally add nails or a pin to stop the key backing out.
- **Rules:**
  - **R07-039** — **Must.** The key slot must be sized so that the key, when driven, **forces the tips against the shoulders** (pre-stressing the joint); a key that merely fills a gap without driving the joint tight is inadequate. *Why:* kanawa's stiffness depends on the pre-compression set up by the key.
  - **R07-040** — **Should.** Use kanawa where a strong splice must be assembled **laterally** — post root splices, repairs of plates and beams in place, and last members between fixed pieces. *Why:* lateral assembly is its distinctive advantage over okkake.
  - **R07-041** — **Must.** The key is of dry dense hardwood, with its grain running along its length (i.e. across the member), and its end distances respected (≥ ≈ 6–8 × key thickness of solid lap on each side). *Why:* the key bears across the grain of both pieces and shears along the grain behind it.
- **Common errors:** lap faces not parallel (pieces cannot slide in); key slot too wide (key cannot pre-stress) or too narrow (key splits the laps); T-mechigai too tight laterally; jaws too thin.
- **Variants:** shiribasami (§4.3); okkake-kanawa hybrid; kanawa netsugi (§6.9); kanawa with bolts (modern).

```
 SCHEMATIC PROFILE, kanawa (face showing the profile; not to scale)
      piece A                                           piece B
 ===========+-----------------------------------------+============
            T-mechigai          B's lap          ______|
            +_____________________________[K]_____|    |
            |                         [K]              |
            |      A's lap        ____[K]______________+
            |_____________________|         T-mechigai
 ===========+-----------------------------------------+============
            |<------------- L ≈ 2.5-3 D -------------->|
   [K] = key (sen) in the slot at the central step, driven perpendicular to this face;
   B is slid in laterally (perpendicular to this face) before the key is driven.
```

### 4.3 Tail-clasp splice — 尻挟み継ぎ (*shiribasami-tsugi*)

- **Class:** tsugite, stepped scarf with a key; close relative of kanawa.
- **Typical use:** as kanawa, especially for **exposed** plates, beams and posts (netsugi) where the kanawa's T-mechigai showing on the outer faces is considered unsightly.
- **Load behaviour:** comparable to kanawa; a commonly quoted comparison says the bending strength is equivalent to kanawa even though the outer face looks like a plain straight joint.
- **Description:** the connecting geometry (stepped laps, key at the central step) is shared with kanawa; the difference lies in the tips: the mechigai is placed **inside** — the tip of each lap is clasped (挟む) between cheeks of the other piece — so that it does not appear on the outer faces, which show only straight joint lines. Because the tongues do not run through, the pieces cannot necessarily be slid together laterally as in kanawa; the assembly direction follows the orientation of the hidden tongues (descriptions vary; follow the workshop drawing).
- **Proportions:** as kanawa (L ≈ 2.5–3 D; key and step similar); clasping cheeks each ≥ ≈ 1/4 of the thickness.
- **Rules:**
  - **R07-042** — **Should.** Prefer shiribasami to kanawa on prominent exposed faces, provided the assembly direction it requires is available. *Why:* equivalent strength with a cleaner appearance.
- **Common errors:** cheeks too thin (they split during keying); assembly direction not checked against the erection sequence.
- **Variants:** kanawa; shiribasami netsugi.

### 4.4 Pins and keys in splices — 大栓 (*daisen*), 栓 (*sen*), 込み栓 (*komisen*)

This section summarizes how pins and keys are used **in splices**; their general design, species and manufacture are in → Ch. 09.

| Device | Where used in splices | Section (house scale) | Direction | Function |
|---|---|---|---|---|
| 大栓 *daisen* | okkake-daisen (2 per joint), some daimochi | 15–24 mm square or round | through the side, perpendicular to the laps, through both pieces | shear transfer between laps, locking |
| 栓 / 金輪栓 *sen* | kanawa, shiribasami (1 per joint) | ≈ 15–24 × 30–45 mm, slightly tapered | into slot at central step | pre-stress, bearing at the jaws |
| 込み栓 *komisen* | sao-tsugi, yatoi-sao, some laps | 12–18 mm square | through tenon/sao and female | lock; draw if offset |
| 車知栓 *shachi-sen* | sao-shachi, koshikake-sao-shachi, yatoi-sao | ≈ 10–15 × 30–45 mm, tapered | across tenon and female slot, often in pairs | draw tight and lock |
| 太枘 *dabo* | daimochi, netsugi | ≈ 20–30 mm | across the lap plane | location, shear |
| 千切り *chigiri* | board and shallow splices, keys across butts | per board | inlaid in face | holds butts/edges together |

**R07-043** — **Must.** Pins and keys in splices are of dry, dense, straight-grained hardwood, with their grain running along their length; keys and shachi are rived or sawn along the grain, never with short grain. *Why:* short-grained keys snap; wet keys shrink loose.

**R07-044** — **Should.** Where a splice is visible, set its pins or keys consistently (same face, same line, same projection) across the building (→ R06-056).

---

## 5. Tenon-and-key splices

These splices use a long, slender tongue (竿, *sao*) on one piece — or a separate loose tongue (雇い, *yatoi*) in both — inserted into a slot and locked by pins (込み栓) or tapered keys (車知, *shachi*). Their great practical virtue is that the tongue can be **slid in horizontally along the axis**, so they can pass **through a post** or close **between two members already fixed**, and the shachi can **draw the shoulders tight** and be re-driven later.

### 5.1 Rod-tenon splice — 竿継ぎ (*sao-tsugi*)

- **Class:** tsugite, tenon family.
- **Typical use:** girders (胴差) meeting from opposite sides of a through-post (通し柱), where the sao of one passes through the post into the other; plates and sills where one piece must be slid in horizontally; secondary members; the basis of sao-shachi (§5.2).
- **Load behaviour:** shear (via the sao in bending and the female's slot — weak unless seated or supported); tension via pins through the sao; bending small. Pinned sao splices are relatively flexible.
- **Proportions:** sao thickness ≈ 1/4–1/3 W (27–36 mm in 105–120); sao depth ≈ D less any housings (often the full depth, or D minus ≈ 10–15 mm); sao length ≈ 1.5–2.5 D; komisen 12–18 mm, usually 2, placed ≥ ≈ 2.5–3 pin sizes from the sao tip (→ R06-007).
- **Orientation rules:** the sao is on the member that moves (the one inserted last); the slot is in the member fixed first; where passing through a post, the post mortise is sized to the sao alone and the girder ends are housed (大入れ) into the post faces to carry shear (→ Ch. 08).
- **Marking / cutting:** centre lines; sao cheeks sawn and pared; slot chopped (often through, open at the far end for through-post use); pin holes bored after trial fit, with draw offset (→ Ch. 09).
- **Assembly:** female/fixed piece in place; male slid in along the axis; pins driven.
- **Rules:**
  - **R07-045** — **Should.** A plain sao splice is locked with at least two pins or with shachi; a single pin permits rotation. *Why:* one pin is a hinge in the plane of the sao.
- **Common errors:** sao too thin (breaks in bending at the shoulder); pins too close to the tip; slot cut with insufficient cheeks.
- **Variants:** sao-shachi (§5.2), koshikake-sao-shachi (§5.3), yatoi-sao (§5.4).

### 5.2 Rod-tenon splice with shachi keys — 竿車知継ぎ (*sao-shachi-tsugi*)

- **Class:** tsugite, tenon family with tapered keys.
- **Typical use:** sills (土台), especially the **last piece** closing a loop, or sill pieces that must be slid in between posts or other fixed sills; girders (胴差) joined **through a through-post**; plates (桁) in positions where dropping in is impossible; any splice where the shoulder (胴付き) must be drawn tight and kept tight, since the shachi can be re-driven after drying.
- **Load behaviour:** good tension (the shachi draw the sao into the female and bear in the slots); moderate shear (needs a seat or support for heavy loads); limited bending. The drawing action of the shachi keeps the shoulders closed.
- **Proportions (representative):**
  - sao thickness ≈ 1/4–1/3 W (27–33 mm in 105; 30–40 mm in 120; 40–50 mm in 150);
  - sao length ≈ 1.5–2 D (150–210 / 180–240 / 225–300 mm);
  - shachi: hardwood (kashi), section ≈ 10–12 × 30–36 mm (105), 12–15 × 36–45 mm (120), 15–18 × 45–55 mm (150); taper ≈ 1:10–1:15 along the length; usually one **pair** per joint driven from opposite faces (top and bottom, or the two sides), a second pair in long sao;
  - draw: the shachi slot in the sao is offset ≈ 1–2 mm toward the male's shoulder relative to the slot in the female, so that driving the shachi pulls the sao in.
- **Geometry (description):** the male carries a sao; the female has a matching slot. Rectangular slots for the shachi are cut **across** the joint, partly in the female's cheeks and partly through the sao; a tapered shachi driven into each slot bears on the far face of the sao-slot and the near face of the female-slot and, because of the offset, draws the two members together.
- **Orientation rules:** the male is the piece slid in last; the female is fixed first. For sills: female continuous over the foundation anchor point; the shachi pair driven from the top and bottom faces (bottom driven before the sill is set, or from the sides where the bottom is inaccessible). For girders through a post: the sao of one girder passes through the post and into the other girder (which is the female), shachi on the far side of the post.
- **Marking:** centre lines; sao outline; shachi slot positions on both pieces (with offset for draw); assembly marks.
- **Cutting sequence:** 1. saw and pare the sao; 2. chop the slot in the female; 3. chop the shachi slots through the female cheeks; 4. trial-fit the sao; 5. mark the shachi slot on the sao through the female's slots, then shift the mark by the draw offset; 6. chop the sao's shachi slot; 7. make shachi to fit, with taper.
- **Assembly:** slide the sao home; drive the shachi pair alternately (a little each) so that the joint draws evenly; stop when the shoulder is closed; trim.
- **Rules:**
  - **R07-046** — **Must.** Drive paired shachi **alternately and equally** from opposite faces. *Why:* driving one fully before the other twists the sao and splits the female cheek.
  - **R07-047** — **Should.** Use sao-shachi (or yatoi-sao) as the splice of the **last member** in a closed loop of sills or plates, where a dropped-in kama is impossible (→ R06-038). *Why:* the sao can be slid in horizontally and locked afterwards.
  - **R07-048** — **Should.** Where shachi will be accessible later, leave them slightly proud (or mark them) so that they can be re-driven after the frame has dried. *Why:* the joint's great advantage is that it can be re-tightened.
- **Common errors:** draw offset too large (shachi cannot be driven; female splits) or reversed (the joint is pushed apart); shachi of weak or short-grained wood; slots too close to the female's end.
- **Variants:** koshikake-sao-shachi (§5.3); 雇い竿車知 (§5.4); 竿車知 netsugi.

```
 PLAN, sao-shachi (schematic)
   male                                female
 ------------------+=================+-------------------
                   |     sao         |
                   |======[S]========|    [S] = shachi slot (driven vertically,
                   |                 |          pairs from top & bottom);
 ------------------+=================+-------------------   slot in sao offset 1-2 mm
                   ^ shoulder (胴付き) drawn tight           toward the male's shoulder
```

### 5.3 Seated rod-tenon splice with shachi — 腰掛け竿車知継ぎ (*koshikake-sao-shachi-tsugi*)

- **Class:** tsugite, tenon family with seat and tapered keys.
- **Typical use:** plates, girders and sills near a post where shear must be carried by a seat and tension by keys; an upgrade of koshikake-kama with re-tightenable draw; also where the male is dropped onto the seat with the sao entering an open-topped slot.
- **Load behaviour:** seat carries shear (as in koshikake-kama); sao and shachi carry tension (generally better and more reliably tight than a kama); limited bending.
- **Proportions:** seat as koshikake-kama (s ≈ 15–30 mm, seat height ≈ 1/3–1/2 D); sao and shachi as §5.2.
- **Orientation rules:** female over the support, ≈ 150 mm cantilever (→ R07-005); male on the seat; shachi driven from the faces accessible after erection (commonly from the sides or top). **Uncertainty:** workshops differ as to whether the sao is dropped into an open-topped slot (with shachi from the sides) or slid in (with shachi from top/bottom); both forms are described.
- **Rules:**
  - **R07-049** — **Should.** Where a seated splice must carry tension reliably and remain tight through drying, prefer koshikake-sao-shachi to koshikake-kama. *Why:* the shachi draw and can be re-driven; the kama cannot.
- **Common errors:** as for §5.2; in addition, seat not bearing.
- **Variants:** koshikake-kama with shachi; 目違い付き腰掛け竿車知.

### 5.4 Loose-tongue splices — 雇い竿 (*yatoi-sao*) and 雇い実 (*yatoi-zane*)

- **Class:** tsugite, loose-tenon family (雇い = "hired", a separate piece).
- **Typical use:**
  - **yatoi-sao** (雇い竿, a separate rod-tenon let into both members) with shachi (雇い竿車知) or pins (雇いほぞ胴栓止め): girders on either side of a through-post; sills between fixed posts; **repair** of plates and beams in place; any junction where **both members are already fixed** and neither can move;
  - **yatoi-zane** (雇い実, loose spline): butt splices and edge joints in boards, finish members (敷居, 鴨居, 長押), ceiling boards; alignment rather than strength (→ Ch. 14).
- **Load behaviour:** yatoi-sao: tension through the keys at both ends, shear through the sao and the housings; every yatoi joint is effectively **two** joints in series, and its capacity is that of the weaker end. Yatoi-zane: alignment and small shear; no tension.
- **Proportions:** yatoi-sao section ≈ as a sao (≈ 1/4–1/3 W thick, depth ≈ D less housings); length ≈ 2 × (1.2–2 D); hardwood or the same species of good quality; shachi or pins at both ends as §5.2. Yatoi-zane: thickness ≈ 1/4–1/3 of board thickness, width ≈ 2–3 × thickness, grain along the spline's length (or cross-grain plywood-like spline in modern work).
- **Orientation rules:** slots are cut in both members; the loose tongue is inserted into one, the other member brought against it (or, where both are fixed, the tongue is slid in from a side opening and then keyed). In through-post girders, the yatoi-sao passes through the post.
- **Rules:**
  - **R07-050** — **Should.** Use yatoi-sao where both members are already fixed (repair, last member, through-post) and a strong splice is needed; lock both ends with shachi or at least two pins each. *Why:* the loose tongue avoids moving either member.
  - **R07-051** — **Must.** The yatoi-sao is of timber at least as strong and as dry as the members, straight-grained, with no knots in the sao's length between the keys. *Why:* the whole tension passes through the yatoi.
- **Common errors:** one end keyed, the other merely glued or friction-fit; yatoi of weak species; slot too deep for the member (excessive section loss).
- **Variants:** 雇い竿車知, 雇いほぞ, 雇い実矧ぎ, 雇い目違い.

### 5.5 Butterfly key — 千切り (*chigiri*)

- **Class:** key (inlaid), used as a splice key across butt joints and as an edge key.
- **Typical use:** holding together the butted ends or edges of **thick boards** (tokonoma boards 床板 *tokoita*, 地板 *jiita*, thick shelves, 式台 *shikidai*, stair treads, counter and table tops, 一枚板 slabs), arresting the growth of end checks in slabs and thick members; in some traditional work across the butt of two members lying on a continuous support. Not a primary structural splice for framing members.
- **Load behaviour:** holds the two parts together against small tension across the joint and keeps faces flush; it relies on the flared ends bearing on the sockets. Capacity limited by the key's neck and by shear of the socket ends.
- **Proportions (representative):** hardwood (keyaki, kashi, shitan, ebony-like woods, or a contrasting species); length ≈ 3–5 × waist width; end width ≈ 2–2.5 × waist; flare per side ≈ 1:4–1:6; depth ≈ 1/3–1/2 of board thickness (through keys are possible in thin boards but weaken them); grain of the key runs along its length, i.e. **across** the joint.
- **Orientation rules:** set on the concealed face where strength is the aim, on the visible face as a deliberate ornament in sukiya and craft work; centred on the joint line; keys spaced along the joint at ≈ 150–300 mm.
- **Cutting sequence:** 1. make the key and plane its sides with a very slight taper (narrower at the bottom); 2. place the key on the joint and knife its outline; 3. saw/chop the socket to the knife line to the key's depth; 4. glue or dry-fit and drive; 5. plane flush.
- **Rules:**
  - **R07-052** — **Must.** The grain of a chigiri runs along the key (across the joint). *Why:* a key with grain parallel to the joint breaks at the waist.
  - **R07-053** — **Should.** Do not rely on chigiri to hold boards whose shrinkage across the grain is restrained by other means; allow the boards to move (chigiri across an **end** butt of boards are unaffected by width shrinkage; chigiri across an **edge** joint resist movement and can split the boards if too many or too long). *Why:* the key's length is stable, the boards' width is not.
- **Common errors:** key too deep (weakens the board); grain orientation wrong; sockets too loose (key only glued).
- **Variants:** 契り (alternative spelling), 蟻型の千切り, double chigiri.

---

## 6. Splices by member and special-purpose splices

### 6.1 Nuki splices — 貫の継手 (*nuki no tsugite*)

- **Class:** tsugite in a penetrating tie; made **inside a post**.
- **Typical use:** structural nuki (足固め貫 *ashigatame-nuki*, 胴貫 *dō-nuki*, 内法貫 *uchinori-nuki*, 頭貫 *kashira-nuki* in temples) and wall nuki (壁貫 for komai walls, → Ch. 14) where a single nuki cannot run the full length of the wall.
- **Load behaviour:** in the lateral frame, nuki act by embedment in the post mortises; the splice must pass tension (and some bending) across the post so that the nuki line continues to tie the posts together. The splice is located inside the post because there it is confined, supported and wedged.
- **Forms:**
  - **略鎌 (*ryaku-kama*) inside the post**: the two nuki ends meet within the post's through-mortise, each cut to a half-lap (the lap plane usually horizontal, across the nuki's height) with a small hook at the tip; the hooks engage, and a wedge is driven into the mortise to clamp the lap. This is the classic structural form.
  - **相欠き (*aikaki*) with pins or wedge**: a plain half-lap inside the post, locked by wedges and sometimes a pin through post and nuki.
  - **Butt inside the post with wedges (突付け + 楔締め)**: for thin wall nuki (小貫), simply butted in the post and wedged or nailed.
  - **竿・車知 forms**: in some heavy temple and minka work, the nuki ends are joined with a sao and shachi or with a kama inside the post.
- **Proportions:** structural nuki (house scale) ≈ 1 sun thick × 3.5–4 sun high (≈ 27–30 × 105–120 mm); temple nuki much larger; lap length = the post width (the whole splice lies inside the post) — the hook height ≈ 1/6–1/4 of nuki height; wedges (kusabi) of hardwood in pairs (相楔 *ai-kusabi*, opposing wedges) driven above (or below) the nuki from both faces of the post (→ Ch. 09).
- **Orientation rules:** the post mortise is cut high enough for nuki plus wedge; the nuki is threaded through posts in the erection sequence (→ Ch. 15); the wedges are driven from both sides of the post so that they meet; the hook faces are oriented so that tension brings them into bearing.
- **Rules:**
  - **R07-054** — **Must.** Nuki are spliced only **inside a post** (or, in heavy work, over a support designed for it), never between posts. *Why:* the confinement of the mortise and the wedges is what makes the lap work; a free nuki lap in a bay has no capacity.
  - **R07-055** — **Must.** Stagger nuki splices so that splices in vertically adjacent nuki tiers fall in **different posts**, and do not splice nuki at a corner post or at a post that also receives a girder splice. *Why:* each post can tolerate only limited cross-section loss (→ R06-031) and a line of splices becomes a line of weakness.
  - **R07-056** — **Should.** Drive nuki wedges from **both faces** of the post, meeting inside, and re-drive them after the frame has dried (増し締め). *Why:* single-sided wedging pushes the nuki off-centre; drying loosens wedges (→ Ch. 06 §4.4).
- **Common errors:** splice falling half outside the post; wedges too steep (spring out); mortise too high (nuki slack even after wedging); all nuki spliced in the same post line.
- **Variants:** as listed under Forms.

```
 ELEVATION through a post, nuki spliced inside (schematic)
               |<-- post -->|
     nuki A    |  ____      |    nuki B
 ==============|_|    |_____|==============
 ==============|______|  |__|==============    hooked half-lap (略鎌) inside the post
               |  wedge  >< |   <- opposing wedges driven from both faces
               |            |
```

### 6.2 Miyajima splice — 宮島継ぎ (*miyajima-tsugi*)

- **Class:** tsugite, finish (化粧) splice.
- **Typical use:** members visible on **three faces**, such as ceiling battens (竿縁 *saobuchi*) and similar exposed thin members; the name is said to come from its frequent use in buildings at Miyajima (Itsukushima).
- **Load behaviour:** light; alignment and a small amount of compression/tension; the member is supported and nailed or hung.
- **Description:** the splice is arranged so that the three visible faces (the two sides and the underside) show a clean, simple joint line, and the interlocking part is on the concealed top face. **Uncertainty:** published descriptions of the exact geometry are scarce and vary; practitioners should follow a workshop's drawing. This entry records use and intent rather than a definitive shape.
- **Rules:**
  - **R07-057** — **Should.** In finish members visible on three faces (竿縁, 回り縁 lengths), use a splice whose mechanism is confined to the concealed face (miyajima, isuka, hidden mechigai) and locate it at a hanger or support. *Why:* the joint must neither show nor sag.

### 6.3 Crossbill splice — いすか継ぎ (*isuka-tsugi*)

- **Class:** tsugite, finish (化粧) scarf.
- **Typical use:** ceiling battens (竿縁), in compression; other thin finish members where a neat appearance is required; the four-sided form 四方いすか継ぎ (*shihō-isuka-tsugi*) shows the characteristic inclined lines on all faces.
- **Load behaviour:** mainly compression and alignment; little tension.
- **Description:** named after the crossbill (鶍, *isuka*), whose mandibles cross; the two ends are cut obliquely so that they bite into each other like crossed beaks, giving a neat slanted line on the visible faces instead of a butt. It is regarded as a "finish splice" (化粧継手) chosen where a clean appearance matters. It is increasingly rare because long members are used instead, avoiding the splice altogether.
- **Orientation rules:** place over or immediately beside a hanger/support; orient the slanted lines consistently across a ceiling.
- **Rules:**
  - **R07-058** — **Should.** In fine ceilings, avoid splices in saobuchi altogether by using full-length members where possible; where a splice is unavoidable, use isuka or miyajima at a support and align splices in adjacent battens deliberately (either on one line or regularly staggered, per design). *Why:* splices in visible battens are read as part of the ceiling's composition (→ R06-055).

### 6.4 Sills — 土台 (*dodai*) splice practice

Summary of rules for sill splices (sill framing overall: → Ch. 10; anchor bolts and code: → Ch. 17).

| Situation | Splice | Notes |
|---|---|---|
| Ordinary sill run (outer walls) | 腰掛け鎌継ぎ | standard; ≈ 150 mm from post; anchor bolt near male end |
| Interior sill lines, short runs | 腰掛け蟻継ぎ or 腰掛け鎌継ぎ | ari acceptable where tension is small |
| Last piece closing a loop / between fixed posts | 竿車知継ぎ, 腰掛け竿車知, 雇い竿 | slid in horizontally, locked by shachi |
| High-quality hand-cut work / continuity wanted | 追掛け大栓継ぎ, 金輪継ぎ | need sliding or lateral assembly room |
| Repair of a sill length in place | 金輪継ぎ, 雇い竿車知, 台持ち (if supported) | lateral assembly |

- **R07-059** — **Must.** Sill splices are never under a post, never under a door or opening where the sill is not continuously supported, never directly over a foundation vent opening (床下換気口) or other gap in the bearing, and never at a hold-down or anchor position unless the anchor is on the male end as intended. *Why:* the sill must be continuously supported at the splice and not concentrated-loaded there.
- **R07-060** — **Should.** Stagger sill splices on opposite and parallel walls, and keep sill pieces as long as available (commonly 4 m). *Why:* fewer, staggered splices keep the sill ring continuous.
- **R07-061** — **Should.** Treat the end grain and the joint surfaces of sill splices with preservative where the species is not naturally durable, and make sill splices of durable species (hinoki, hiba, kuri) where possible. *Why:* sill joints are the most decay-prone joints in the building (→ Ch. 03, Ch. 16).

### 6.5 Plates and girders — 桁・胴差 (*keta, dōsashi*), with kyōro-gumi and orioki-gumi practice

- **Kyōro-gumi** (京呂組): roof beams (小屋梁) rest **on top of** the wall plate, which is carried by posts. The plate is spliced ≈ 150 mm from a post, female over the post (post tenon in the female), male on the seat. The roof beams cross the plate with 渡り腮 or 兜蟻掛け (→ Ch. 08).
- **Orioki-gumi** (折置組): roof beams rest **directly on the posts** and the plate rests on the beam ends. The plate is then supported at every beam end, and its splices are commonly placed **over a beam end/post**, using a daimochi- or kama-type splice on the support, or near it with a seated splice. Practice varies regionally.
- **Girders (胴差)** at the second-floor level, especially at through-posts: either spliced ≈ 150 mm from a post (koshikake-kama with strap, or okkake-daisen), or joined **through** the through-post with sao-shachi or yatoi-sao, with the girder ends housed into the post faces.

- **R07-062** — **Must.** In kyōro-gumi, a roof beam must not cross the plate over any part of the plate's splice; keep crossings on the solid female or over the post. *Why:* the splice's reduced section cannot also receive the notch of the crossing.
- **R07-063** — **Should.** For plates carrying heavy roofs or tying frames in lateral load, use okkake-daisen or kanawa (or koshikake-kama with a strap) rather than koshikake-ari. *Why:* plates must pass tension along the wall line.
- **R07-064** — **Should.** At through-posts receiving girders from two or more directions, avoid splicing the girder in the post unless the post is enlarged (≥ ≈ 5 sun / 150 mm) or the heights are staggered (→ R06-031); prefer splicing ≈ 150 mm away from the post. *Why:* cross-section loss in the post at a single height.

### 6.6 Purlins and ridge — 母屋・棟木 (*moya, munagi*)

- Purlins and ridge are spliced ≈ 150 mm from a strut (束, *tsuka*) or post, female over the strut, male on the seat, with koshikake-kama (standard) or koshikake-ari (light roofs); okkake-daisen or kanawa where the roof is heavy, the bay long, or the ridge exposed.
- **R07-065** — **Must.** Splices of adjacent purlins are staggered (not in the same bay line), and a purlin splice is not placed where the rafters' own splices fall. *Why:* coincident splices create a hinge line across the roof plane.
- **R07-066** — **Should.** Keep ridge splices out of the central bay(s) where possible, place the ridge's female toward the direction from which the ridge is erected, and in exposed roofs use okkake-daisen or kanawa. *Why:* the ridge is the ceremonial and visual spine of the roof (上棟), and the central bay usually carries the heaviest roof load; custom in many workshops is to avoid a joint there (a variant, not universal).

### 6.7 Rafters — 垂木 (*taruki*)

- Rafters are spliced **only over a support** (purlin, plate), by butt (突付け) or bevelled scarf (殺ぎ継ぎ), nailed to the support; adjacent rafters alternate their splice positions.
- **R07-067** — **Must.** Never splice a rafter within the eaves overhang or within about one purlin spacing inside the wall plate; the eaves cantilever must be the continuous extension of a rafter with a full back-span. *Why:* the cantilever is held down by the back-span; a splice at or beyond the plate leaves the eaves unsupported (→ Ch. 11).
- **R07-068** — **Should.** Do not splice exposed (化粧) rafters; use full-length members. Where hidden rafters (野垂木) are spliced, stagger them alternately over the purlins. *Why:* visible rafter splices are considered poor work; hidden splices must not align.

### 6.8 Floor beams and joists — 大引・根太 (*ōbiki, neda*)

- Floor beams (大引) are spliced over a floor strut (床束) or a sill with koshikake-ari (standard), koshikake-kama, or a butt on a seat with nails/cramps; joists (根太) are butted over a floor beam and nailed, staggered.
- **R07-069** — **Should.** Splice floor beams ≈ 150 mm from a floor strut on the cantilever side (as for other seated splices) or directly over a strut with a half-lap/butt that bears fully on it; stagger joist butts so that adjacent joists are not spliced on the same beam. *Why:* avoids soft lines in the floor.

### 6.9 Post splices — root splices (根継ぎ, *netsugi*)

When the base of a post has decayed (the usual cause: water at the foot of the post, termite, or contact with earth), the decayed part is cut away and a new foot is spliced on. This is the most common structural repair in Japanese buildings (→ Ch. 16).

| Netsugi type | Assembly | Strength | Appearance | Use |
|---|---|---|---|---|
| 金輪継ぎ *kanawa* | lateral (slid in sideways), keyed | high in all directions | T-mechigai visible on two faces | standard high-quality netsugi |
| 尻挟み継ぎ *shiribasami* | as described §4.3 | high | clean straight lines on faces | exposed posts |
| 台持ち継ぎ *daimochi* | lateral; dabo or bolts | moderate | lap line visible | simpler work, hidden posts |
| 箱目違い / 十字目違い (*hako- / jūji-mechigai*) | axial (post must be jacked up by tongue length) | compression and shear only | clean square line | posts in pure compression, where jacking is possible |
| 四方蟻 *shihō-ari* (four-way dovetail) | diagonal (slid in along the diagonal of the section) | moderate; mainly compression and alignment | dovetails appear on all four faces | display of skill; rare in structural practice |
| 四方鎌 *shihō-kama* (four-way kama) | diagonal | as shihō-ari | kama outlines on four faces | display of skill; rare |
| 竿車知 / 雇い竿 | axial or with loose tongue | moderate | lines visible | specific cases |

- **Proportions:** the netsugi length (from the old post's cut to the joint's far end) is chosen so that the joint lies wholly in sound wood — commonly the joint's upper end ≥ ≈ 1 × W above the highest decay; joint lengths as §4 (kanawa ≈ 2.5–3 W).
- **Orientation rules:**
  - the new foot is set with its **butt (moto) down**, as the tree grew (→ Ch. 03, sakabashira taboo);
  - its faces (kiomote/kiura, marking faces) match the old post;
  - the joint does not coincide with any mortise (nuki, ashigatame, sill, 地覆) — keep ≥ ≈ 1 × W clear;
  - the lap plane is oriented so that the lateral assembly direction is free (away from walls, toward the room or the exterior as access permits).
- **Procedure outline (→ Ch. 16):** 1. shore and jack the load off the post (揚げ前 *agemae*); 2. strike plumb reference lines on all faces of the old post and a level reference line; 3. cut away the decayed foot; 4. mark and cut the joint on the old post in situ; 5. make the new foot, marking from the same references (transfer by story stick); 6. trial fit; 7. slide in, key/pin; 8. fit the new foot to the foundation stone (光付け *hikaritsuke*) or sill; 9. lower the load.
- **Rules:**
  - **R07-070** — **Must.** A root splice lies wholly in sound wood and clear of all mortises; its new foot is set moto-down with matching face orientation. *Why:* splicing into partly decayed wood or into a mortise zone produces a weak joint; an inverted foot violates both custom and durability practice.
  - **R07-071** — **Must.** Choose the netsugi type by the **assembly direction available**: lateral (kanawa, shiribasami, daimochi) when the post cannot be raised, axial (mechigai types) only when it can be jacked by the tongue length. *Why:* the post is part of a standing frame.
  - **R07-072** — **Should.** Use a new foot of the same species or a more durable one (hinoki, hiba, kuri), well seasoned, and protect the new end grain at the base. *Why:* the base is the most decay-exposed part of the post.
- **Note on terms:** 地獄枘 (*jigoku-hozo*, "hell tenon", a blind fox-wedged tenon that cannot be withdrawn) is a connection, not a splice (→ Ch. 08, Ch. 09).

### 6.10 Boards — end and edge joining (cross-reference)

Boards are joined edge to edge (矧ぎ, *hagi*) and end to end in floors, ceilings, walls and fittings. Their techniques — 本実 (*hon-zane*, tongue-and-groove), 相決り (*aijakuri*, shiplap/rebated), 雇い実 (*yatoi-zane*, loose spline), 突付け (butt) end joints over joists, 乱継ぎ (*ranzugi*, random/staggered end joints), 目透かし (*mesukashi*, deliberate shadow gaps) — are covered in → Ch. 14.

- **R07-073** — **Must.** End joints of floor and ceiling boards fall over a joist or support and are staggered (乱継ぎ) so that no two adjacent boards have end joints on the same joist; the usual minimum stagger is two joist spacings. *Why:* aligned end joints make a hinge line and a visible stripe.
- **R07-074** — **Should.** Lay tongue-and-groove boards so that the tongue leads in the direction of laying and so that blind nails through the tongue are hidden by the next board (→ Ch. 14). *Why:* standard sequence for concealed fixing.

---

## 7. Summary comparison table

Ratings are qualitative (●●● good, ●● moderate, ● poor, — none) and assume correct proportions and placement. "Support below" = whether the splice must be at or beside a support.

| Joint | Tension | Bending | Torsion | Shear (own) | Difficulty | Typical members | Support below? | Assembly | Visible appearance |
|---|---|---|---|---|---|---|---|---|---|
| 突付け tsukitsuke | — | — | — | — | very easy | rafters, joists, boards | **yes, on it** | laid | single line |
| 相欠き aikaki | ● (pins only) | ● | ● | ●● if on support | easy | secondary, ties | yes | drop | line + lap line |
| 布継ぎ / 略鎌 | ●● | ● | ● | ●● | moderate | nuki, ties | yes (nuki: in post) | drop / slide | stepped line |
| 殺ぎ sogi | — (nails) | ● | ● | ● | easy | rafters, battens, fascia | **yes, on it** | laid | sloping line |
| 台持ち daimochi | ●● (dabo/bolts) | ●● over support | ●● | ●●● | moderate | log beams, roof beams, netsugi | **yes, on it** | drop / lateral | lap line |
| 目違い mechigai | — | — | ● | ●● (lateral) | easy | posts, finish members | continuous bearing | axial | single line |
| 箱目違い hako-mechigai | — | — | ●● | ●●● (lateral) | moderate | posts (netsugi), finish | continuous bearing | axial | single square line |
| 蟻 ari | ● | — | — | — | easy | secondary | yes | drop | dovetail outline (top) |
| 腰掛け蟻 koshikake-ari | ● | — | ● | ●●● (seat) | easy | sills (interior), sleepers, purlins | yes, ≈150 mm | drop | step (side), dovetail (top) |
| 鎌 kama | ●● | — | — | — | moderate | continuously supported members | yes | drop | kama outline (top) |
| 腰掛け鎌 koshikake-kama | ●● | — | ● | ●●● (seat) | moderate | sills, plates, girders, purlins | yes, ≈150 mm | drop | step (side), kama (top) |
| 目違い/箱目違い腰掛け鎌 | ●● | — | ●● | ●●● | moderate–hard | exposed plates, sills | yes, ≈150 mm | drop | cleaner faces |
| 隠し鎌/隠し蟻 | ● | — | ●● | ●● | hard | exposed members | yes | drop | straight line |
| 追掛け大栓 okkake-daisen | ●●● | ●●● (best of traditional) | ●● | ●●● | hard | plates, girders, beams, ridge, sills | preferably near | **axial slide** | long stepped line + 2 pins |
| 金輪 kanawa | ●●● | ●●● | ●●● | ●●● | hard | plates, beams, sills, **netsugi** | preferably near | **lateral** + key | stepped line, T-mechigai, key |
| 尻挟み shiribasami | ●●● | ●●● | ●●● | ●●● | hard | exposed plates, posts | preferably near | per drawing + key | straight lines + key |
| 竿 sao | ●● (pins) | ● | ● | ● | moderate | girders through posts | yes | axial | line |
| 竿車知 sao-shachi | ●●● | ● | ●● | ●● | moderate–hard | sills (last piece), girders through posts | yes | axial + shachi | line + shachi heads |
| 腰掛け竿車知 | ●●● | ● | ●● | ●●● | hard | plates, girders, sills | yes, ≈150 mm | drop/axial + shachi | step + shachi |
| 雇い竿 yatoi-sao | ●● – ●●● | ● | ●● | ●● | moderate–hard | repairs, through-posts | yes | loose tongue + keys | line + keys |
| 千切り chigiri | ● | — | — | — | moderate | thick boards, slabs | continuous | inlaid | bow-tie (if on face) |
| 貫の継手 (in post) | ●● | ●● (confined) | ● | ●● | moderate | nuki | **inside post** | threaded + wedges | hidden in post |
| 宮島 miyajima | ● | — | ● | ● | moderate | saobuchi, finish | yes | per drawing | clean on three faces |
| いすか isuka | ● | — | ● | ● | moderate | saobuchi, finish | yes | laid | slanted line |
| 四方蟻 / 四方鎌 | ●● | ● | ●● | ●● | very hard | netsugi (display) | column | diagonal | four-face outlines |

---

## 8. Typical dimensions (representative)

The following figures are **representative** values drawn from the proportional rules given in the entries; they are intended as a starting point for workshop templates, **not** as specifications. Precut manufacturers, regional schools and individual masters use their own values. For code-governed structural members verify with test-based data (→ Ch. 17).

### 8.1 Metric members: 105, 120 and 150 mm square (D = W)

| Joint / element | 105 mm | 120 mm | 150 mm |
|---|---|---|---|
| **腰掛け蟻 koshikake-ari** — neck width | 30 | 33–40 | 40–50 |
| head width (max) | 45–55 | 55–65 | 65–80 |
| dovetail length (shoulder to tip) | 60–80 | 70–95 | 90–120 |
| seat length s | 15–30 | 20–30 | 30–45 |
| seat height (from bottom) | 35–55 | 40–60 | 50–75 |
| **腰掛け鎌 koshikake-kama** — neck width | 30–35 | 35–40 | 45–50 |
| head width (max) | 55–63 | 60–72 | 75–90 |
| total kama length | 120–160 | 150–190 | 180–240 |
| seat length s | 15–30 | 20–30 | 30–45 |
| sliding slope on bearing faces | ≈ 1:25–1:40 | ≈ 1:25–1:40 | ≈ 1:25–1:40 |
| offset of joint from post centre | ≈ 150 | ≈ 150 | ≈ 150–200 |
| **追掛け大栓 okkake-daisen** — total length L | 315–370 | 360–420 | 450–525 |
| jaw (顎) height | 10–15 | 12–18 | 15–20 |
| sliding slope | ≈ 1:10 | ≈ 1:10 | ≈ 1:10 |
| tip mechigai/eriwa length | 15–20 | 15–25 | 20–30 |
| daisen (2 pcs, square) | 15–18 | 18–21 | 21–24 |
| **金輪 kanawa** — total length L | 260–315 | 300–360 | 375–450 |
| central step height | 15–18 | 15–20 | 20–25 |
| key (栓) thickness × width | 15–18 × 30–40 | 18 × 36–45 | 21–24 × 45–55 |
| T-mechigai length | 15–20 | 15–25 | 20–30 |
| **竿車知 sao-shachi** — sao thickness | 27–33 | 30–40 | 40–50 |
| sao length | 150–210 | 180–240 | 225–300 |
| shachi section (at head) | 10–12 × 30–36 | 12–15 × 36–45 | 15–18 × 45–55 |
| shachi per joint | 1 pair | 1 pair | 1–2 pairs |
| draw offset | 1–1.5 | 1–2 | 1.5–2 |

All values in mm.

### 8.2 Traditional members: 4 sun (≈ 121 mm) and 5 sun (≈ 152 mm) square

1 sun = 10 bu ≈ 30.3 mm; 1 bu ≈ 3.03 mm; 1 shaku = 10 sun ≈ 303 mm.

| Joint / element | 4 sun (≈ 121 mm) | 5 sun (≈ 152 mm) |
|---|---|---|
| **腰掛け蟻** — neck width | 1.1–1.3 sun (33–39 mm) | 1.4–1.6 sun (42–48 mm) |
| head width | 1.8–2.1 sun (55–64 mm) | 2.2–2.6 sun (67–79 mm) |
| dovetail length | 2.3–3.0 sun (70–91 mm) | 3.0–3.8 sun (91–115 mm) |
| seat length | 7 bu–1 sun (21–30 mm) | 1–1.5 sun (30–45 mm) |
| **腰掛け鎌** — neck width | 1.2–1.3 sun (36–39 mm) | 1.5–1.6 sun (45–48 mm) |
| head width | 2.0–2.4 sun (61–73 mm) | 2.5–3.0 sun (76–91 mm) |
| total kama length ("6-sun kama" etc.) | 5–6 sun (152–182 mm) | 6–8 sun (182–242 mm) |
| seat length | 5 bu–1 sun (15–30 mm) | 1–1.5 sun (30–45 mm) |
| sliding slope (example) | ≈ 1–1.5 bu over the depth | ≈ 1.5–2 bu over the depth |
| **追掛け大栓** — total length | 1.2–1.4 shaku (364–424 mm) | 1.5–1.75 shaku (455–530 mm) |
| jaw height | 4–6 bu (12–18 mm) | 5–7 bu (15–21 mm) |
| daisen (2 pcs) | 6–7 bu square (18–21 mm) | 7–8 bu square (21–24 mm) |
| **金輪** — total length | 1.0–1.2 shaku (303–364 mm) | 1.25–1.5 shaku (379–455 mm) |
| central step | 5–6 bu (15–18 mm) | 6–8 bu (18–24 mm) |
| key thickness × width | 6 bu × 1.2–1.5 sun (18 × 36–45 mm) | 7–8 bu × 1.5–1.8 sun (21–24 × 45–55 mm) |
| **竿車知** — sao thickness | 1.0–1.3 sun (30–39 mm) | 1.3–1.6 sun (39–48 mm) |
| sao length | 6–8 sun (182–242 mm) | 7.5–10 sun (227–303 mm) |
| shachi section | 4–5 bu × 1.2–1.5 sun (12–15 × 36–45 mm) | 5–6 bu × 1.5–1.8 sun (15–18 × 45–55 mm) |

**R07-075** — **Should.** Derive each workshop's joint dimensions from the member size by stated proportions (recorded on templates), check them against the end-distance and jaw-width rules of → Ch. 06 §4.3 and §9, and use the same template for male and female. *Why:* proportional templates keep joints balanced across member sizes; ad hoc dimensions produce weak necks or narrow jaws.

**R07-076** — **Must.** For members deeper than they are wide (e.g. 120 × 240 mm plates and girders), take neck and head widths from **W** and joint lengths (kama length, okkake/kanawa length) from **D**; do not scale all dimensions from one of the two. *Why:* widths govern the neck/jaw balance in plan; lengths govern shear planes and lap sections in elevation.

---

## 9. Rule index for this chapter

| Rule | Strength | Subject |
|---|---|---|
| R07-001 | Must | splice on support or bending-capable |
| R07-002 | Must | female continuous; female first |
| R07-003 | Must | stagger; each piece spans two supports |
| R07-004 | Must | no splice over opening/under post/at mortise |
| R07-005 | Should | seated splice ≈150 mm from support |
| R07-006 | Should | match halves |
| R07-007 | Must | mark both halves from same references |
| R07-008 | Should | templates |
| R07-009 | Must | butt only on support |
| R07-010 | Should | stagger butts |
| R07-011 | Must | half-lap needs support + fasteners |
| R07-012 | Should | length behind hooks |
| R07-013 | Must | sogi over support, nailed |
| R07-014 | Should | exterior scarf sheds water |
| R07-015 | Must | daimochi on the support |
| R07-016 | Must | log laps from struck lines |
| R07-017 | Should | dabo away from tenon mortise |
| R07-018 | Must | end faces bear, tongue short |
| R07-019 | Should | hako-mechigai only if post can be raised |
| R07-020 | Must | plain ari only secondary |
| R07-021 | Must | seat bears in koshikake-ari |
| R07-022 | Should | prefer koshikake-kama for tension |
| R07-023 | Must | jaw width ≥ ¼ W |
| R07-024 | Must | kama bearing faces square |
| R07-025 | Must | clearance at kama tip |
| R07-026 | Must | no post on sill kama joint |
| R07-027 | Must | post tenon into female |
| R07-028 | Should | mechigai against twist |
| R07-029 | Should | no reliance on koshikake-kama for tension |
| R07-030 | Must | socket through; shear length behind head |
| R07-031 | Should | hidden kama only where capacity allows |
| R07-032 | Must | stepped scarf ≠ full strength |
| R07-033 | Should | stepped scarf ≈ 3 D |
| R07-034 | Must | okkake length |
| R07-035 | Must | daisen through both pieces, end distances |
| R07-036 | Must | axial room for okkake |
| R07-037 | Should | hardwood daisen; bore after trial fit |
| R07-038 | Should | flat sliding faces |
| R07-039 | Must | kanawa key pre-stresses |
| R07-040 | Should | kanawa for lateral assembly |
| R07-041 | Must | kanawa key grain and end distance |
| R07-042 | Should | shiribasami on exposed faces |
| R07-043 | Must | pins/keys dry hardwood, long grain |
| R07-044 | Should | consistent visible pins |
| R07-045 | Should | sao with ≥ 2 pins or shachi |
| R07-046 | Must | drive paired shachi alternately |
| R07-047 | Should | sao-shachi for last member |
| R07-048 | Should | leave shachi re-drivable |
| R07-049 | Should | koshikake-sao-shachi for reliable tension |
| R07-050 | Should | yatoi-sao when both fixed |
| R07-051 | Must | yatoi quality |
| R07-052 | Must | chigiri grain across joint |
| R07-053 | Should | chigiri and board movement |
| R07-054 | Must | nuki spliced inside posts only |
| R07-055 | Must | stagger nuki splices |
| R07-056 | Should | wedge from both faces; re-drive |
| R07-057 | Should | three-face-visible finish splices |
| R07-058 | Should | avoid saobuchi splices |
| R07-059 | Must | sill splice exclusions |
| R07-060 | Should | stagger sill splices |
| R07-061 | Should | protect sill splices from decay |
| R07-062 | Must | no beam crossing on plate splice |
| R07-063 | Should | plates: okkake/kanawa/strap |
| R07-064 | Should | girders at through-posts |
| R07-065 | Must | stagger purlin splices |
| R07-066 | Should | ridge splice placement |
| R07-067 | Must | no rafter splice in eaves |
| R07-068 | Should | no exposed rafter splices |
| R07-069 | Should | floor beam and joist splices |
| R07-070 | Must | netsugi in sound wood, moto down |
| R07-071 | Must | netsugi type by assembly direction |
| R07-072 | Should | durable species for netsugi |
| R07-073 | Must | board end joints staggered over supports |
| R07-074 | Should | T&G laying direction |
| R07-075 | Should | proportional templates |
| R07-076 | Must | widths from W, lengths from D |

---

## 10. Notes on sources and uncertainties

The descriptions above synthesize commonly taught Japanese practice, published glossaries of carpentry terms, the Japan Housing Finance Agency's *Wooden Housing Construction Specification* (木造住宅工事仕様書) for mainstream sill and plate practice, and general references such as Kiyosi Seike, *The Art of Japanese Joinery* (1977), Yasuo Nakahara, *Japanese Joinery* (English ed. 1983), and Torashichi Sumiyoshi & Gengo Matsui, *Wood Joints in Classical Japanese Architecture* (c. 1989–1991); see → Ch. 01. Experimental data on the tensile and bending performance of traditional splices (koshikake-ari, koshikake-kama, okkake-daisen, kanawa and others) have been published by Japanese research institutes and collected in databases of traditional-construction joint tests; use those, not the qualitative ratings of §7, for design (→ Ch. 17).

**Flagged uncertainties in this chapter:**

1. **Okkake-daisen geometry:** sources agree on the essentials (stepped lap about 3 × D long, jaw at mid-length, ≈ 1:10 sliding slope, assembly by sliding rather than dropping, two daisen driven from the side), but published drawings differ on whether the stepped profile lies in elevation or in plan and on the exact form of the tip mechigai/eriwa. The sketch in §4.1 is schematic.
2. **Kanawa key direction:** sources variously describe the key as driven "vertically" (縦から) or from the side face; it is in all cases perpendicular to the face showing the profile.
3. **Shiribasami:** described as kanawa with the mechigai placed internally; its assembly direction is not uniformly described.
4. **Nuno-tsugi vs ryaku-kama:** the names overlap in the literature.
5. **Miyajima-tsugi and isuka-tsugi:** use (finish members such as saobuchi) is well attested; exact geometry varies and published descriptions are scarce.
6. **Koshikake-sao-shachi:** both "dropped with open-topped slot" and "slid-in" forms are described.
7. **Moto/sue custom for splice direction** (→ Ch. 06 §5.3) and ridge-splice customs (R07-066) are variants, not universal.
8. **All dimensions** in §8 are representative, derived from proportional rules and a small number of published examples (e.g. a 15 mm seat for koshikake-kama, a "6-sun kama" of 3 sun head + 3 sun neck, a sliding slope of ≈ 1.5 bu over 4 sun, okkake length ≈ 3 × D with ≈ 1:10 slope). They should be replaced by the workshop's own templates.
9. **Anchor-bolt position** for sill splices follows current mainstream specification logic (bolt on the male/upper piece); exact distances are code- and specification-dependent (→ Ch. 17).
