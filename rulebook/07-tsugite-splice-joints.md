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
  - sliding slope on flare faces ≈ 1:25–1:40 over the depth (head ≈ 1–1.5 mm narrower per side at the bottom than at the top in a 105–120 mm member).
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
