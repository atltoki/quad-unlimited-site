# Quad Unlimited — Prompts UGC IA (sans te filmer)

> Guide complet + 10 idées vidéo prêtes à produire. Tous les prompts copiables sont dans des blocs de code. Avatars UGC en français, prompts text-to-video en anglais, voix off FR via ElevenLabs.

---

# Guide UGC IA — Quad Unlimited

## 1. Comment faire de l'UGC sans te filmer ni montrer ton stock

Tu n'as pas besoin d'apparaître à l'écran, ni de filmer ton atelier ou ton stock, pour produire du contenu vertical qui claque. Trois routes, à mixer selon le format et le temps que t'as.

### Route A — Avatar IA qui parle (talking-head sans toi)
Un personnage généré par IA dit ton script face caméra. C'est l'UGC "tête qui parle" classique, sauf que c'est pas ta tête.
- **Avantages** : ultra rapide, format "conseil pote" qui convertit, parfait pour les hooks parlés et les tops/comparatifs, scalable (plusieurs vidéos/jour).
- **Limites** : risque de "fake" si l'avatar est trop lisse ou la voix robotique ; varie les avatars et soigne la voix FR. Ne JAMAIS faire dire à l'avatar un claim technique non prouvé sur du freinage ou de la perf — il reste sur "j'ai trié / j'ai testé la confiance du vendeur / voilà ce que je garde".

### Route B — Faceless cinématique + voix off FR
Des plans cinématiques de quad/MX générés en text-to-video, montés ensemble, avec une voix off française par-dessus. Zéro visage, zéro stock, que de l'action et de la belle image.
- **Avantages** : très haut plafond esthétique (beauty shots Banshee, Raptor, YFZ qui roulent), aucune contrainte de tournage, image de marque "média de passion" forte.
- **Limites** : ne montre pas de produit réel précis (l'IA invente les machines) — donc à utiliser pour l'ambiance/le hook/le storytelling, pas pour prouver une référence exacte. Surveille les détails incohérents (roues, logos déformés).

### Route C — Hybride (le meilleur des deux)
Avatar IA en intro/outro pour le hook parlé et le call-to-action, plans cinématiques au milieu pour l'énergie et la preuve d'ambiance. C'est le format le plus solide pour Quad Unlimited.
- **Avantages** : crédibilité du discours (avatar) + spectacle (cinématique), rythme dynamique, lisible "passion + curation".
- **Limites** : un peu plus de montage. Garde la cohérence visuelle (même grade couleur, même voix off si tu enchaînes avatar → off).

---

## 2. Quel outil pour quoi

| Besoin | Outils recommandés |
|---|---|
| **Avatar parlant** (talking-head sans filmer le fondateur) | Arcads, Creatify, HeyGen, Captions (AI Avatars), Higgsfield (avatar/UGC), Veo 3 (personnage qui parle avec dialogue) |
| **Text-to-video cinématique** (plans quad/MX, action, beauty shots) | Google Veo 3 / 3.1, OpenAI Sora 2, Runway Gen-4, Kling 2.x, Higgsfield, Luma Dream Machine, Pika, Hailuo/MiniMax |
| **Image-to-video** (animer une photo produit/quad statique) | Kling, Runway, Higgsfield, Veo |
| **Voix off FR naturelle** (faceless) | ElevenLabs (voix française naturelle) |
| **Montage + sous-titres** | CapCut, Captions |

**Raccourci pratique** : pour un hook parlé rapide → Arcads/Creatify/HeyGen. Pour un beau plan d'action → Veo 3 ou Kling. Pour animer UNE photo (quad statique, pièce) → Kling ou Runway en image-to-video. Voix off systématiquement ElevenLabs. Assemblage et sous-titres sur CapCut.

---

## 3. Workflow "0 tournage" en 5 étapes

1. **Idée + hook (FR)** — Choisis un angle (top 3, "le piège à éviter", "ce que je garde / ce que je jette") et écris le hook des 2 premières secondes en français. Le hook d'abord, tout le reste sert le hook.
2. **Script + voix off (FR)** — Rédige le script complet en français (20-45s), ton direct et brut. Génère la voix off sur **ElevenLabs** (voix FR naturelle), ou fais-le porter par un **avatar IA** (Arcads/HeyGen/Creatify).
3. **Génération visuelle** — Plans cinématiques en text-to-video (**Veo 3 / Kling / Sora 2**) avec des prompts EN ANGLAIS, ou anime une photo via image-to-video (**Kling/Runway**). Garde un grade couleur cohérent sur tous les plans.
4. **Montage + sous-titres (FR)** — Assemble sur **CapCut**, cale les plans sur la voix off, ajoute des sous-titres FR punchy (mots clés en gros), un son qui tape, format 9:16.
5. **Export + post** — Export vertical 9:16, vérifie le hook à 2s, ajoute la légende + CTA en FR, poste. Décline le même script en 2-3 variantes de hook pour tester.

---

## 4. Master prompts réutilisables (à copier)

### MASTER PROMPT — Plan cinématique quad/MX (text-to-video, EN)
> À coller dans Veo 3 / Kling / Sora 2 / Runway. Remplis les `[...]`. Prompt en anglais ; les textes à l'écran restent en français au montage.

```
Cinematic vertical 9:16 short-form shot, [DURÉE ex: 5s], high-energy motocross / ATV sport mood.
Subject: [MACHINE ex: Yamaha Banshee 350 / Raptor 700 / YFZ 450 / Honda TRX] [ACTION ex: ripping across a dirt track, kicking up dust / drifting through a berm / launching off a jump].
Setting: [LIEU ex: dusty motocross track at golden hour / forest trail / open desert dunes].
Camera: [MOUVEMENT ex: low-angle tracking shot / fast whip pan / slow-motion close-up on the rear wheel spinning], dynamic, handheld energy.
Lighting & grade: [AMBIANCE ex: warm golden-hour backlight, punchy contrast, slightly gritty color grade, cinematic].
Details: flying dirt and dust particles, sharp focus on the machine, sense of speed and power, no on-screen text, no logos, no visible rider face.
Style: gritty, authentic, passionate moto/MX brand energy, premium but raw. No watermark.
```

### MASTER PROMPT — Avatar UGC parlant (FR)
> À coller dans Arcads / Creatify / HeyGen / Captions / Veo 3. Le script parlé est en FRANÇAIS.

```
Format: vertical 9:16 UGC talking-head, [DURÉE ex: 30s], style selfie authentique, lumière naturelle.
Avatar: [PROFIL ex: homme 25-35 ans, look rider décontracté, casquette/sweat, ambiance garage neutre ou extérieur flou], énergie passionnée et directe, pas commerciale.
Langue: FRANÇAIS, ton accessible et brut, débit naturel de passionné qui parle à un pote.

SCRIPT (FR) à dire :
"[HOOK 2s ex: Arrête d'acheter ce kit les yeux fermés.]
[CORPS ex: Sur une [MACHINE], y'a 3 trucs que je regarde avant de valider un vendeur...]
[POINT 1] [POINT 2] [POINT 3]
[CTA ex: Je te trie le bon matos, abonne-toi pour la suite.]"

Contraintes: sous-titres FR à ajouter au montage, mots clés en gros. Rester sur curation/sélection/confiance — AUCUN claim d'ingénierie maison ni de performance/sécurité non prouvée, surtout sur le freinage.
```

---

## 5. Les 5 règles d'or (rester authentique, pas une pub IA cheap)

1. **Le hook avant tout.** Les 2 premières secondes décident de tout : une phrase qui pique, pas une intro lente. "Arrête de…", "Le piège c'est…", "3 trucs que personne te dit…".
2. **Parle comme un rider, pas comme une marque.** Ton direct, brut, un peu imparfait. La voix off FR doit respirer la passion, pas le script lu. Évite l'avatar trop lisse et la voix robotique.
3. **Reste honnête sur ton rôle.** Tu sélectionnes, tu source, tu tries le bon matos — tu ne conçois pas. JAMAIS de claim d'ingénierie maison ni de perf/sécurité non prouvée sur des pièces de freinage. La sincérité, c'est ton positionnement.
4. **Soigne la cohérence visuelle.** Même grade couleur, même rythme, même énergie MX sur tous les plans. Surveille les défauts IA (logos déformés, roues incohérentes, mains bizarres) et coupe-les.
5. **Décline et teste.** Un même script = 2-3 variantes de hook. Poste, regarde la rétention à 2s, garde ce qui marche. L'UGC authentique se construit au volume, pas à la perfection.

---
---

# Les 10 vidéos

---

## Vidéo 1 — Pourquoi la Yamaha Banshee 350 est une légende (2-stroke culte)

**Format :** Vertical 9:16, TikTok / Instagram Reels / YouTube Shorts. Durée cible 28-34s (sweet spot 30s). Hook sonore + visuel dans les 2 premières secondes.

**Hook :** PARLE (frame 1, sec 0): "Y'a des quads... et y'a la Banshee." / TEXTE ECRAN (gros, centré, fond noir 0,4s puis incrusté sur l'image): "POURQUOI ELLE FAIT ENCORE FLIPPER TOUT LE MONDE ?" — le son d'un moteur 2-temps qui monte dans les tours démarre AVANT la voix, dès la frame 1, c'est le vrai hook.

**Approche recommandée :** HYBRIDE, faceless cinématique dominant + variante avatar pour A/B test. Sujet 100% sensoriel et patrimonial: le mythe se vend par le b-roll cinématique et le son 2-temps, pas par un visage — ce qui colle parfaitement aux deux contraintes créateur (zéro fondateur, zéro stockage). Le format principal est donc faceless (b-roll IA + VO ElevenLabs). On fournit EN PLUS un avatar UGC talking-head, créateur IA générique explicitement NON-fondateur, dans un décor extérieur neutre (piste/champ/studio), pour tester un hook "recommandation perso". Dans les deux variantes, moteur émotionnel identique: le son, la fumée bleue, le caractère brut du 2-temps. Contenu strictement éditorial/culture: aucun claim d'ingénierie maison, aucune perf/sécurité — uniquement des faits vérifiables (bicylindre 2-temps 350, production fin années 80 au milieu des années 2000, statut culte) et le ton "fan qui kiffe et qui sait de quoi il parle". Note IP: on évite de nommer "Yamaha" DANS les prompts génératifs (risque de logo de marque / filtre), la marque reste citée uniquement dans le texte parlé et les textes écran (usage éditorial légitime).

**Outils avatar :** Arcads (avatar UGC qui parle, script FR collé tel quel) · HeyGen (avatar réaliste + voix FR clonée, export 9:16) · Captions AI Avatars (export 9:16 + sous-titres mot-à-mot auto) · Creatify (variante UGC ad-style A/B) · Veo 3.1 (si besoin d'un rendu plus cinématique avec lip-sync)

### Prompt avatar UGC

```
Vertical 9:16 UGC talking-head video, ~28 seconds, handheld-selfie energy. Subject: a generic 28-35 year old male motorsport enthusiast and content creator (he is NOT a business owner, NOT a brand founder, NOT a shop owner). Short modern haircut, light stubble, wearing a plain casual motocross-style graphic t-shirt or a worn enduro hoodie with NO readable brand logos and NO real company names. Setting: a neutral outdoor 'rider lifestyle' location — the sandy edge of a dirt track at golden hour, OR an open field with a softly blurred dirt berm behind him, OR a clean neutral concrete-and-light studio backdrop. ABSOLUTELY NO warehouse, NO shelves, NO racks of parts, NO storage room, NO personal garage, NO inventory, NO stockroom of any kind anywhere in frame or background. Lighting: natural daylight or soft golden-hour rim light, shallow depth of field, slightly desaturated cinematic look with crisp natural skin tones. Camera: chest-up framing, subtle handheld micro-movement, occasional small zoom-in punch on emphasis. Performance: he speaks with passion and conviction, expressive hands, leaning in slightly on the key lines, hyping a legendary machine to a friend — authentic, energetic, raw but likeable. Clean dry audio, no background music in the avatar plate (music added later). He lip-syncs the provided French script exactly.
```

### Script parlé FR (avatar)

> Y'a des quads... et y'a la Banshee. Un bicylindre 2-temps de 350, un son que tu reconnais à des kilomètres. Yamaha l'a produite de la fin des années 80 jusqu'au milieu des années 2000, et encore aujourd'hui les passionnés s'arrachent les bons modèles. Pourquoi elle est culte ? Parce qu'elle est brute, légère, et qu'elle te demande de savoir piloter. Elle pardonne pas tout — mais elle te récompense. Une légende, ça se respecte. Et toi, tu kiffes la Banshee ? Dis-le en commentaire.

### Prompts B-roll (text-to-video)

**Plan 1 — Réveil moteur (hook sonore)** — *0-4s* — Outils: Veo 3.1 (meilleur rendu + son moteur synthétisé), Kling 2.x, Runway Gen-4

```
Vertical 9:16 cinematic extreme close-up of a vintage 1990s two-stroke sport ATV twin-cylinder engine with two parallel exhaust pipes, retro blue-and-white plastic bodywork softly out of focus behind it (generic design, NO visible brand name, NO logo, NO badge). Cold early-morning air, faint blue-tinted two-stroke exhaust haze curling from the twin pipes as the engine revs. Dramatic low-key lighting, a single hard rim light catching the chrome pipes and the engine cooling fins. Shallow depth of field, slow dolly-in toward the exhaust tips, subtle heat shimmer. Gritty, moody, premium automotive ad look, slight film grain, high detail. No text, no people, no warehouse, no shelves, no garage.
```

**Plan 2 — Profil héroïque de la machine** — *4-9s* — Outils: Veo 3.1, Sora 2, Higgsfield

```
Vertical 9:16 cinematic hero shot of a classic late-1990s blue-and-white two-stroke sport quad / ATV (twin pipes, aggressive vintage racing stance, generic unbranded bodywork with NO logos or brand names) parked in profile on a sandy desert dirt track at golden hour. Wide low-angle, the machine fills the lower third, dramatic warm backlight, a long shadow stretching across the sand, fine dust drifting through the light beams. The camera slowly orbits a few degrees, a soft lens flare catches the handlebars. Aggressive, legendary, poster-worthy framing. Cinematic color grade, high dynamic range, crisp detail, light film grain. No riders, no text, no buildings, no warehouse, no storage.
```

**Plan 3 — Action piste / power slide** — *9-16s* — Outils: Veo 3.1, Kling 2.x, Sora 2, Runway Gen-4

```
Vertical 9:16 high-energy action shot of a blue-and-white vintage two-stroke sport quad (twin pipes, unbranded bodywork, NO logos) ripping a power slide on a sandy motocross track, a huge rooster-tail of sand spraying behind the rear wheels, dynamic motion blur, dust cloud catching golden afternoon light. Tracking side shot moving with the machine, brief slow-motion on the sand spray then snap back to real time. The rider is fully helmeted with a tinted visor and plain generic riding gear, framed so NO face is visible and NO real brand logos appear; focus is entirely on the machine and the flying sand. Adrenaline, raw motorsport energy, cinematic grade, gritty texture. No on-screen text, no logos, no warehouse, no garage.
```

**Plan 4 — Détails culte (textures qui racontent l'histoire)** — *16-22s* — Outils: Veo 3.1, Runway Gen-4, Kling 2.x (image-to-video si photo réelle dispo)

```
Vertical 9:16 macro detail montage with cinematic shallow depth of field, extreme close-ups of the same vintage blue-and-white two-stroke quad (generic, NO brand names, NO logos): the twin exhaust tips with faint blue smoke, the worn knurled hand grip and the thumb throttle, the analog handlebar details, sunlight raking across scratched-but-loved blue plastics and brushed aluminum. Slow rack-focus pulls between each detail, warm golden light, dust motes floating in the air. Nostalgic, soulful, premium product-film texture, fine film grain. No people, no text, no shelves, no storage room, no warehouse.
```

**Plan 5 — Plan final iconique (silhouette + poussière)** — *22-30s* — Outils: Veo 3.1, Sora 2, Luma Dream Machine

```
Vertical 9:16 closing cinematic shot of the same blue-and-white vintage two-stroke sport quad (twin pipes, unbranded, NO logos) silhouetted against a dramatic dusty golden sunset on an empty dirt track. Low camera angle looking slightly up, thick warm dust and faint two-stroke haze drifting through strong backlight, deep lens flare. The machine sits still, heroic and timeless, like the last frame of a legend's tribute. Very slow push-in. Epic, emotional, premium cinematic grade, fine film grain. Keep clean negative space in the upper third for a text overlay added later. No riders, no baked-in text, no buildings, no warehouse.
```

### Script parlé FR (version faceless — voix off)

> Y'a des quads... et y'a la Banshee. (beat) Bicylindre 2-temps de 350, un son que tu reconnais à l'oreille avant même de la voir. Produite par Yamaha de la fin des années 80 jusqu'au milieu des années 2000 — et toujours adulée aujourd'hui. Pourquoi elle est devenue une légende ? Parce qu'elle est brute. Légère. Vivante. Une machine qui pardonne pas tout, mais qui te récompense quand tu sais la piloter. Le 2-temps, la fumée bleue, ce caractère que plus aucun quad moderne n'ose avoir. La Banshee, c'est pas une machine. C'est un mythe sur quatre roues. Et toi, tu kiffes la Banshee ? Dis-le en commentaire.

### Textes à l'écran

- POURQUOI ELLE FAIT ENCORE FLIPPER TOUT LE MONDE ?
- BANSHEE 350 — BICYLINDRE 2-TEMPS
- UN SON QUE TU RECONNAIS À L'OREILLE
- BRUTE. LÉGÈRE. VIVANTE.
- ELLE TE RÉCOMPENSE QUAND TU SAIS PILOTER
- PAS UNE MACHINE. UN MYTHE.
- Tu kiffes la Banshee ? 👇

### CTA

"Tu kiffes la Banshee toi aussi ? Dis-le en commentaire — et abonne-toi à Quad Unlimited pour le vrai contenu de passionnés." (overlay bouton "S'ABONNER" sur le dernier plan, plan 5)

### Musique / son

Son 2-temps en VEDETTE: ouvre sur le bruit réel d'un moteur Banshee qui monte dans les tours dès la frame 1, AVANT la voix — c'est le hook sonore. Dessous, musique trap/phonk énergique à BPM moyen-haut, montée jusqu'à un drop calé sur le power slide (plan 3). Layering SFX: whoosh sur chaque cut, gros impact sur le drop, crépitement d'échappement 2-temps sur les plans détails (plan 4). Sur le plan final, baisse la musique et laisse respirer un dernier coup de gaz + reverb. VO FR: ElevenLabs, voix française masculine naturelle, ton passionné et un peu brut, légèrement compressée pour percer au-dessus de la musique (viser ~30s, débit oral, pas de lecture mécanique). Sous-titres mot-à-mot punchy via CapCut ou Captions.

---

## Vidéo 2 — Raptor 700 vs YFZ 450 : c'est quoi la vraie différence ?

**Format :** TikTok / Instagram Reels / YouTube Shorts — vertical 9:16 (1080x1920) — durée cible 30 à 35s

**Hook :** PARLÉ (0-2s): "Raptor 700 ou YFZ 450 ? Arrête de croire que c'est juste la cylindrée." | TEXTE ÉCRAN: "700 vs 450 🤔 (pas ce que tu crois)"

**Approche recommandée :** HYBRIDE. Sujet comparatif et technique: un avatar IA talking-head pose le cadre et la "vraie différence" (autorité + visage humain qui crédibilise sans filmer le fondateur), tandis que les plans b-roll text-to-video des deux machines en action portent l'émotion et le rythme MX. L'avatar prend le hook + la conclusion/CTA, le b-roll illustre chaque point (couple vs régime, balade vs piste). On respecte les contraintes (jamais le fondateur, jamais le lieu de stockage): l'avatar est un rider générique distinct du fondateur, filmé en extérieur. Le positionnement reste curation/conseil ("on trie l'info, on te dit ce qui colle à ton usage") — jamais test maison ni claim d'ingénierie. Une version 100% faceless (VO ElevenLabs + b-roll seul) est fournie en repli. Note de calibrage: le script a été raccourci pour tenir réellement en 30-35s à débit oral naturel (le texte d'origine dépassait 60s).

**Outils avatar :** Arcads · Creatify · HeyGen · Captions (AI Avatars) · Higgsfield (avatar/UGC) · Veo 3 (personnage qui parle)

### Prompt avatar UGC

```
Vertical 9:16 UGC talking-head, single shot. A generic, relatable male ATV/motocross enthusiast in his late 20s, NOT a polished spokesperson — looks like a real rider/fan, an everyman. Short messy hair or a simple dark cap, light stubble, wearing a worn motocross/enduro jersey or a plain dark hoodie, casual energetic vibe. He is filmed outdoors at the edge of a dirt motocross track at golden hour, with blurred dirt berms and a light dust haze in the soft background (shallow depth of field). STRICTLY no indoor setting: NOT a warehouse, NOT a parts/storage room, NOT a garage, NOT a workshop. Handheld selfie-style framing, chest-up, eyes locked to camera, talking directly and energetically to the viewer with natural hand gestures and an occasional excited eyebrow raise. Authentic UGC look: slightly imperfect natural lighting, real skin texture, real phone-camera feel, subtle ambient wind. Confident, passionate, friendly, a bit raw — a genuine fan who actually rides, not a fake expert or engineer. Lip-sync precisely to the provided French audio. Clean dialogue audio, no background music baked in. Total duration about 30-35 seconds.
```

### Script parlé FR (avatar)

> Raptor 700 ou YFZ 450 ? Arrête de croire que c'est juste la cylindrée. La vraie différence elle est pas dans le chiffre. Le 700, c'est le couple: t'appuies, ça part tout seul. Génial en balade, dans le sable, sur les chemins. Le YFZ 450, c'est une bête de piste: il vit dans les tours, faut le pousser, jouer avec la boîte... mais sur un circuit MX, il réveille direct. Donc la vraie question c'est pas 'lequel est le plus fort'. C'est: tu roules pour quoi ? Fun et balade, c'est le 700. Compét et pilotage agressif, c'est le 450. Nous on trie l'info et on te dit ce qui colle à TON usage. Team 700 ou team 450 ? Dis-le en commentaire.

### Prompts B-roll (text-to-video)

**Plan 1 — Ouverture impact : quad sport jaune qui sort fort d'un virage, roue avant qui se lève** — *3-4s* — Outils: Google Veo 3.1, OpenAI Sora 2, Kling 2.x, Runway Gen-4

```
Vertical 9:16 cinematic slow-motion shot of a yellow-and-black sport quad (four-wheel ATV, single-rider quad bike — NOT a motorcycle) launching hard out of a dirt corner on an outdoor motocross track, front wheels lifting slightly off the ground, rear tires throwing a thick rooster-tail of dirt and dust, golden-hour backlight catching the airborne particles. Low aggressive ground-level tracking camera, shallow depth of field, dust haze, heat shimmer. Rider in full gear and a closed-visor helmet (face fully hidden). High-energy motocross color grade, crisp shadows, 24fps cinematic motion blur. No on-screen text, no brand logos, no indoor space, no warehouse, no garage — outdoor dirt track only.
```

**Plan 2 — Couple bas régime : gros plan roue arrière qui mord dans le sable d'une dune** — *3s* — Outils: Kling 2.x, Higgsfield, Luma Dream Machine, Veo 3

```
Vertical 9:16 cinematic extreme close-up, slow-motion, of a sport quad's rear knobby tire digging into soft sand on a desert dune at sunset, sand spraying in slow glowing arcs, rear suspension compressing under load, conveying strong low-end torque and grip. Warm golden light, backlit sand grains, shallow focus, gritty texture. Camera low and close with slight handheld energy. Motocross documentary look. Rider's face never visible (closed-visor helmet only if any rider is shown). No on-screen text, no brand logos, outdoor dune environment, never indoors.
```

**Plan 3 — Haut régime piste : quad sport bleu qui enchaîne des virages serrés sur circuit MX** — *3-4s* — Outils: OpenAI Sora 2, Google Veo 3.1, Runway Gen-4, Kling 2.x

```
Vertical 9:16 cinematic high-speed tracking shot of a blue-and-white racing sport quad (four-wheel ATV, NOT a motorcycle) carving aggressively through tight motocross berms, leaning hard, kicking up dirt, conveying a high-revving nervous riding style, fast and precise. Dynamic side-tracking drone-style follow camera, motion blur, dust trails, overcast-to-golden outdoor track lighting. Rider in full race gear and a closed-visor helmet (face hidden). Punchy contrasty MX color grade. No on-screen text, no brand logos, no buildings, outdoor track only.
```

**Plan 4 — Comparatif duo : les deux quads côte à côte au ralenti pour overlay split** — *3s* — Outils: Google Veo 3.1, OpenAI Sora 2, Higgsfield, Kling 2.x

```
Vertical 9:16 cinematic shot of two sport quads side by side on an outdoor dirt motocross track at golden hour — one yellow sport quad on the left, one blue race quad on the right — both idling then accelerating forward together in slow motion, dust rising symmetrically behind them, dramatic backlight separating them from the background. Centered heroic symmetrical composition suitable for a vertical split-screen or comparison overlay, shallow depth of field. Riders in full gear and closed-visor helmets, faces hidden. Epic motocross hero color grade. No on-screen text, no brand logos, no indoor space, outdoor dirt track only.
```

**Plan 5 — Beauty shot final : quad arrêté sur une butte, poussière qui retombe, crépuscule** — *3s* — Outils: Luma Dream Machine, Veo 3, Runway Gen-4, Higgsfield

```
Vertical 9:16 cinematic static-to-slow-push beauty shot of a single sport quad (four-wheel ATV) parked on a dirt berm outdoors at dusk, its silhouette set against a deep orange and purple sky, light dust and gentle exhaust haze drifting through warm rim light, knobby tires and front grille catching the last sunlight. Calm, premium, end-card energy with clear negative space at the top of the frame for a caption overlay. Subtle slow dolly-in. No rider, no on-screen text, no brand logos, no garage, no workshop, no storage — fully outdoor with a dramatic sky.
```

### Script parlé FR (version faceless — voix off)

> Raptor 700 ou YFZ 450 ? Tout le monde regarde la cylindrée... et tout le monde se trompe. Le 700, c'est le couple: ça pousse fort en bas, t'accélères et ça part tout seul. Parfait pour la balade, le sable, les chemins. Le YFZ 450, c'est une machine de piste: il vit dans les tours, faut le pousser, jouer avec la boîte... mais sur un circuit MX, il réveille direct. Donc la vraie question c'est pas 'lequel est le plus fort'. C'est: tu roules pour quoi ? Fun et polyvalence, le 700. Compét et pilotage agressif, le 450. Nous, on trie l'info et on te dit ce qui colle à TON usage. Team 700 ou team 450 ? Réponds en commentaire.

### Textes à l'écran

- 700 vs 450 🤔 (pas ce que tu crois)
- Spoiler: c'est PAS la cylindrée
- RAPTOR 700 = COUPLE 🟡
- Pousse fort en bas → balade / dune / chemins
- YFZ 450 = RÉGIME 🔵
- Vit dans les tours → piste / MX / compét
- La vraie question: tu roules pour QUOI ?
- Fun & polyvalence → 700
- Compét & agressif → 450
- Team 700 ou team 450 ? 👇

### CTA

"Team 700 ou team 450 ? Dis-le en commentaire — et abonne-toi à Quad Unlimited, on trie le bon matos pour les vrais riders."

### Musique / son

Musique: trap/phonk MX énergique, BPM 140-150, basse lourde, montée d'intensité sur le hook puis drop synchronisé au premier plan d'action (le quad jaune qui part). Baisser le volume musique de -8 à -10 dB sous la voix pendant toutes les parties parlées. SFX: vrombissement moteur quad punchy calé sur l'accélération du plan 1, whoosh/transition sur chaque cut entre le 700 et le 450, léger 'dust impact' sur le beauty shot final. Version faceless: VO ElevenLabs voix française masculine naturelle, énergique mais claire, légèrement grave (style passionné moto), débit calibré pour tenir en 30-35s. Sous-titres animés mot-à-mot façon CapCut/Captions, police bold condensée, surlignage jaune sur les mots clés (COUPLE, RÉGIME, PISTE, BALADE).

---

## Vidéo 3 — Le frein 6 pistons, ça sert à quoi exactement ? (vulgarisation freinage quad/ATV)

**Format :** TikTok / Instagram Reels / YouTube Shorts — vertical 9:16 (1080x1920) — durée cible 30-35s

**Hook :** PARLE (0-2s): "Un étrier 6 pistons sur un quad, c'est juste pour faire joli ?" | ECRAN: "6 PISTONS = ? 🔧" en gros, sur un plan macro d'étrier rouge qui mord un disque ventilé. Enchaînement immédiat: "Franchement non. Mais c'est pas magique non plus."

**Approche recommandée :** Hybride recommandé, mais la version 100% faceless est tout aussi solide ici. Le sujet est pédagogique: un avatar IA talking-head (créateur générique, JAMAIS le fondateur) donne le rythme parlé et la crédibilité humaine, pendant que le b-roll cinématique text-to-video (macros d'étrier, coupe technique, disque qui chauffe, action piste, comparaison 2 vs 6) illustre chaque notion. C'est l'option la plus sûre vu les contraintes: zéro fondateur à l'écran, zéro lieu de stockage. La version faceless (b-roll IA + VO ElevenLabs) tient parfaitement seule pour ce format vulgarisation et reste la plus rapide à produire. Angle strictement confiance/curation: on explique le principe physique GÉNÉRIQUE (plus de pistons = répartition de pression plus régulière sur la plaquette, en théorie), JAMAIS "nos freins sont plus sûrs/plus puissants". Aucune revendication d'ingénierie ou de test maison.

**Outils avatar :** Arcads · Creatify · HeyGen · Captions (AI Avatars) · Veo 3.1 (personnage qui parle) · Higgsfield (UGC avatar)

### Prompt avatar UGC

```
Vertical 9:16 UGC talking-head video, single continuous shot, ~30 seconds. A generic, relatable male content creator in his late 20s to mid 30s, casual motorsport-enthusiast style: plain dark t-shirt or a neutral hoodie, short modern haircut, light stubble, friendly and energetic but down-to-earth expression — NOT a polished corporate spokesperson, more like a passionate hobbyist filming himself on his phone. He is outdoors in a fully neutral, anonymous setting: an open grassy/dirt field with a softly blurred natural bokeh background in soft overcast daylight. Absolutely no buildings, no shelves, no warehouse, no garage interior, no boxes, no stored parts, no signage, no logos. Handheld selfie framing, eye level, head-and-shoulders, he looks directly into the camera and talks naturally with relaxed hand gestures, occasionally pointing toward the camera to emphasize a point. Natural skin texture, realistic lighting, shallow depth of field, authentic phone-camera UGC aesthetic, slight ambient handheld motion. He speaks French. Calm, confident, friendly-teacher energy with small smiles. No on-screen text baked in. Lip-sync to French audio.
```

### Script parlé FR (avatar)

> Un étrier 6 pistons sur un quad, c'est juste pour faire joli ? Franchement non. Mais c'est pas magique non plus. Un étrier, c'est la pince qui serre les plaquettes contre le disque pour te ralentir. Les pistons, eux, ils poussent les plaquettes. Et plus t'as de pistons, plus la pression se répartit régulièrement sur toute la plaquette. Donc en théorie: un freinage plus progressif, plus constant quand ça chauffe. Mais attention: 6 pistons, ça veut PAS dire que tu freines deux fois plus court. Le frein, c'est un système complet — disque, plaquettes, maître-cylindre. Nous chez Quad Unlimited, on conçoit rien, on teste rien en labo. On trie, on source, on te sort le matos sérieux. C'est tout. Donc avant de craquer pour du 6 pistons parce que ça claque sur la photo: demande-toi d'abord pour quel usage. Ta machine, c'est quoi ? Dis-le en commentaire.

### Prompts B-roll (text-to-video)

**Plan 1 — Macro étrier 6 pistons qui mord le disque** — *3-4s* — Outils: Google Veo 3.1, OpenAI Sora 2, Runway Gen-4, Kling 2.x

```
Vertical 9:16 cinematic macro shot, ~3-4 seconds. Extreme close-up of a red 6-piston brake caliper clamping onto a vented, drilled brake disc on a sport ATV/quad. Slow dolly-in, very shallow depth of field, dramatic side rim lighting, fine anodized-metal detail, tiny dust particles floating in a shaft of light, subtle heat shimmer near the disc. Premium automotive-commercial look, dark moody background, high contrast, crisp reflections on the caliper. Slow motion, photorealistic. No text, no people, no warehouse, no shelves, no boxes, no garage.
```

**Plan 2 — Coupe technique animée: les 6 pistons poussent les plaquettes** — *4-5s* — Outils: Google Veo 3.1, Runway Gen-4, Kling 2.x, Higgsfield

```
Vertical 9:16 cinematic engineering cutaway / cross-section shot, ~4-5 seconds, of a brake caliper interior. Six small hydraulic pistons slowly extend in unison and press two brake pads evenly against a spinning brake disc. Clean engineering-visualization aesthetic, brushed metal with red accents, soft studio lighting on a seamless dark gradient background, subtle glowing motion lines highlighting even pressure distribution across the full pad surface. Smooth slow camera orbit, photorealistic CGI look. No text, no people, neutral studio, no shelves, no stored parts.
```

**Plan 3 — Disque qui chauffe / léger glow rouge (usage intensif)** — *3-4s* — Outils: OpenAI Sora 2, Google Veo 3.1, Kling 2.x, Luma Dream Machine

```
Vertical 9:16 cinematic close-up, ~3-4 seconds, of a quad brake disc glowing faint orange-red from heavy braking, fine sparks and heat haze rising, slow motion. Dark dramatic background, strong contrast, ember particles drifting upward, realistic incandescent metal glow on the disc edge, the red caliper visible at the side. Moody motorsport commercial grade, photorealistic, shallow depth of field. No text, no people, no warehouse, no shelves, outdoor track ambience implied only by lighting.
```

**Plan 4 — Action piste: quad qui freine fort en virage (poussière)** — *3-4s* — Outils: Google Veo 3.1, OpenAI Sora 2, Kling 2.x, Higgsfield

```
Vertical 9:16 cinematic action shot, ~3-4 seconds, of a sport quad/ATV braking hard into a dirt corner on an outdoor motocross track, front suspension compressing, a burst of dust kicked up. Low tracking camera following the front wheel and brake disc. Golden-hour backlight, dust glittering in the light, motion blur on the wheels, sharp focus on the brake assembly. Rider wears generic plain motocross gear with a full-face helmet and tinted visor down — face fully hidden, no recognizable identity, no readable logos or numbers. High-energy motorsport film look, slow-mo accent on the dust, photorealistic. No text, no warehouse, no shelves, no stored parts.
```

**Plan 5 — Comparaison: étrier 2 pistons vs 6 pistons côte à côte** — *3-4s* — Outils: Runway Gen-4, Google Veo 3.1, Kling 2.x

```
Vertical 9:16 clean product-comparison shot, ~3-4 seconds, on a seamless dark studio background: on the left a small simple 2-piston brake caliper, on the right a larger red 6-piston brake caliper, both rotating slowly on invisible turntables. Even soft key lighting with crisp specular highlights, subtle reflective floor. Engineering-commercial aesthetic, photorealistic, generous negative space at top and bottom for captions. No baked-in text, no people, neutral studio, no shelves, no boxes, no warehouse.
```

**Plan 6 — Étrier seul en hero shot (parallaxe, reflets, particules) — clôture** — *3s* — Outils: Kling 2.x (image-to-video ou text-to-video), Runway Gen-4 (image-to-video), Higgsfield, Google Veo 3.1

```
Vertical 9:16 cinematic hero product shot, ~3 seconds, of a single red multi-piston brake caliper floating centered on a dark neutral studio background. Slow 3D parallax push-in with a gentle rotation, animated specular reflections sweeping across the polished and anodized metal, soft drifting dust particles and a faint light flare passing across the frame. Premium commercial feel, photorealistic, shallow depth of field. No text, no people, no warehouse, no shelves, no boxes.
```
> (Peut aussi être produit en image-to-video en partant d'une photo produit neutre d'étrier sur fond sombre.)

### Script parlé FR (version faceless — voix off)

> (Hook, sur macro étrier) Un étrier 6 pistons sur un quad, ça sert à quoi exactement ? (Base, sur coupe animée) L'étrier, c'est la pince qui serre les plaquettes contre le disque pour te ralentir. Les pistons, eux, ils poussent ces plaquettes. (Principe, sur pistons qui poussent) Plus t'as de pistons, plus la pression se répartit régulièrement sur toute la plaquette. En théorie: un freinage plus progressif et plus constant quand ça chauffe. (Nuance, sur disque qui glow + action piste) Mais attention à l'arnaque marketing: six pistons, ça veut pas dire que tu freines deux fois plus court. Le frein, c'est un système entier — disque, plaquettes, maître-cylindre, liquide. (Position, sur comparaison 2 vs 6) Nous chez Quad Unlimited, on conçoit rien, on invente aucun test. On trie, on source, on te sort le matos sérieux. Point. (CTA, sur hero étrier) Donc avant de craquer pour du 6 pistons juste parce que ça en jette: demande-toi d'abord pour quel usage. Ta machine, c'est quoi ? Dis-le en commentaire.

### Textes à l'écran

- 6 PISTONS = ? 🔧
- L'étrier = la pince qui serre
- Les pistons poussent les plaquettes
- + de pistons = pression + régulière
- ➡️ freinage + progressif (en théorie)
- STOP à l'arnaque marketing
- 6 pistons ≠ tu freines 2x plus court
- Le frein = un SYSTÈME complet
- Disque • plaquettes • maître-cylindre
- Nous: on trie, on source. On invente rien.
- C'est quoi ta machine ? 👇

### CTA

"Avant d'acheter du 6 pistons parce que ça claque sur la photo, demande-toi pour quel usage. Ta machine c'est quoi ? Dis-le en commentaire — et abonne-toi pour la suite sur le matos qui vaut vraiment le coup."

### Musique / son

Musique: bed hip-hop / trap instrumental sobre et énergique, BPM modéré (~90-100), basse présente mais pas envahissante pour laisser passer la voix — type "garage / motorsport edit". Petit drop sur le hook et sur la punchline anti-arnaque marketing. SFX: whoosh sur chaque transition de b-roll; un "click/clamp" métallique synchronisé quand les pistons serrent les plaquettes; un léger souffle/hiss sur le plan du disque qui chauffe; un impact grave sur l'apparition du texte "STOP à l'arnaque marketing". Ducking automatique de la musique sous la voix. Voix off FR via ElevenLabs (voix masculine française naturelle, ton passionné et direct). Garder un mix qui privilégie l'intelligibilité de la voix (format pédagogique).

---

## Vidéo 4 — Réaction/analyse d'un build de quad de fou — commentaire passionné (faceless-friendly)

**Format :** TikTok / Instagram Reels / YouTube Shorts — vertical 9:16 (1080x1920) — durée cible 30-36s

**Hook :** Texte parlé (0-2s): "Arrête tout. Regarde CE quad deux secondes." — Texte écran plein cadre: "CE BUILD EST ILLÉGAL DE PROPRETÉ 🔥" sur un plan macro d'un YFZ 450 customisé qui se révèle. Impact bass hit synchronisé sur la révélation.

**Approche recommandée :** HYBRIDE, avec la version 100% FACELESS comme livraison par défaut/sûre. Sur une vidéo de réaction/analyse de build, la star c'est la MACHINE: on maximise le temps écran sur des plans cinématiques du quad (b-roll text-to-video) avec un commentaire passionné par-dessus. Deux livraisons à partir du même script: (1) FACELESS = b-roll IA + voix off ElevenLabs FR + sous-titres animés Captions/CapCut. C'est le plus rapide, le plus crédible "vrai fan", et 100% conforme (aucun fondateur, aucun stock/atelier filmé). (2) AVATAR = on insère un avatar IA générique (Arcads/Creatify/HeyGen) 5-7s en intro pour incarner la réaction, le reste reste en b-roll. Recommandation: publier la version faceless en priorité; n'ajouter l'avatar que si on veut un visage récurrent pour la marque. Dans les deux cas le fondateur n'apparaît jamais et aucun lieu de stockage/garage/atelier n'est montré. Le ton reste "fan qui repère le bon taf", jamais "expert qui conçoit".

**Outils avatar :** Arcads · Creatify · HeyGen · Captions (AI Avatars) · Higgsfield (UGC/avatar) · Veo 3.1 (personnage qui parle, lip-sync)

### Prompt avatar UGC

```
Vertical 9:16 UGC talking-head clip, about 7 seconds. A generic male content creator, late 20s, athletic motocross/ATV enthusiast look: short dark messy hair, light stubble, wearing a plain matte-black motocross-style hoodie with NO visible logos or brand marks. Energetic, passionate fan energy, leaning slightly toward the camera, one hand gesturing with excitement as if reacting to something amazing off-screen. Neutral OUTDOOR setting: an open dirt motocross track at golden hour, soft bokeh of berms and tire tracks far in the background. NO warehouse, NO shelves, NO parts storage, NO garage interior, NO building, ONLY open sky and a blurred outdoor track. Handheld selfie-style framing, slight natural camera shake, eye-level, face filling the upper third, vertical phone-shot aesthetic, shallow depth of field, warm natural sunlight, realistic skin texture, authentic creator-style color grade. The creator speaks directly to camera with high energy and a big grin. Clean accurate lip-sync to French audio. No on-screen text baked in.
```

### Script parlé FR (avatar)

> Frérot, ce build, je peux pas le laisser passer. Regarde-moi ce YFZ deux secondes... c'est trop propre. Reste là, je te montre.

### Prompts B-roll (text-to-video)

**Plan 1 — Hook : plan macro qui révèle le quad** — *0-4s* — Outils: Google Veo 3.1, OpenAI Sora 2, Runway Gen-4, Kling 2.x

```
Vertical 9:16 cinematic macro shot, extreme close-up slowly pulling back to reveal a clean custom YFZ 450 sport ATV parked on an open dirt motocross track at golden hour. Start tight on the bright anodized aluminum A-arm and a knobby front tire, then a smooth slow dolly-back revealing the full sculpted plastics and graphics kit. Sun flares, warm rim light catching the frame, fine dust floating in the air, shallow depth of field, glossy reflections on the tank. No people, no riders, no buildings, no shelves, no warehouse, no garage interior, only open track and sky. High dynamic range, premium automotive commercial look, 35mm cinematic, crisp detail, slow motion 60fps feel.
```

**Plan 2 — Détail #1 : orbite sur les triangles / suspension avant** — *4-9s* — Outils: Runway Gen-4, Kling 2.x, Higgsfield, Google Veo 3.1

```
Vertical 9:16 cinematic detail shot, slow orbiting camera around the front suspension of a sport ATV: polished aluminum A-arms, a coilover shock with a colored spring, a billet hub. Crisp metallic textures, tiny points of light reflecting off machined surfaces, soft golden-hour backlight, blurred dirt-track background with bokeh. Camera arcs smoothly 90 degrees around the component. No people, no logos, no buildings, no garage, no interior storage or shelving, outdoor track setting only. Shot on a cinema lens, shallow depth of field, premium product-film aesthetic, ultra sharp, slow motion.
```

**Plan 3 — Détail #2 : travelling latéral le long du châssis / déco** — *9-15s* — Outils: Google Veo 3.1, OpenAI Sora 2, Luma Dream Machine, Pika

```
Vertical 9:16 cinematic tracking shot gliding slowly along the side of a custom sport ATV, following the graphics kit and the welded tubular steel frame from front to rear. Smooth lateral dolly move, warm low-angle sunlight raking across the bodywork, vibrant graphics, sharp panel gaps, subtle heat-haze. Outdoor dirt track at golden hour, distant berms blurred in the background. No riders, no people, no buildings, no garage, no parts shelves. 35mm anamorphic look, shallow depth of field, glossy highlights, cinematic color grade, slow and deliberate.
```

**Plan 4 — Détail #3 : gros plan moteur/échappement (beauty shot statique, AUCUN claim perf)** — *15-20s* — Outils: Kling 2.x, Runway Gen-4, Higgsfield, Google Veo 3.1

```
Vertical 9:16 cinematic close-up of a sport ATV engine bay and exhaust header, a static beauty shot: machined cooling fins, a polished aftermarket exhaust pipe, clean cable routing, subtle reflections. Gentle slow push-in, warm directional light, fine dust particles drifting in sunbeams, shallow depth of field, premium mechanical detail. Outdoor track environment, soft bokeh background. No flames, no smoke, no exhaust fire, no riding, no people, no warehouse, no garage, no storage. Hyper-detailed, automotive commercial grade, slow motion, 35mm cinematic.
```

**Plan 5 — Money shot : le quad en action sur la piste (rider anonyme)** — *20-28s* — Outils: OpenAI Sora 2, Google Veo 3.1, Kling 2.x, Runway Gen-4

```
Vertical 9:16 high-energy cinematic action shot of a sport ATV ripping across a dirt motocross track, kicking up a dramatic rooster-tail of dust, hitting a berm at golden hour. The rider is fully anonymous: full plain riding gear and a tinted full-face helmet with the visor down, face NEVER visible, no logos or identifiable marks on the gear. Dynamic low tracking shot, motion blur, sun flares through the dust, knobby tires biting into the dirt. Fast, punchy, adrenaline-filled. Open outdoor track only, no buildings, no shelves, no warehouse, no garage. Cinematic 35mm, high frame rate slow-mo on the dust spray, vivid contrast, premium MX film look.
```

**Plan 6 — Outro : hero shot statique, espace CTA** — *28-34s* — Outils: Google Veo 3.1, Runway Gen-4, Luma Dream Machine, Higgsfield

```
Vertical 9:16 cinematic hero shot, the custom sport ATV parked center-frame on an open dirt track, silhouetted against a warm golden-hour sky with a soft sun flare, slow gentle push-in. Clean negative space in the lower third for on-screen text. Dust settling, calm epic mood, glossy reflections, premium commercial finish. No people, no buildings, no garage, no storage, outdoor only. 35mm cinematic, shallow depth of field, rich warm grade, slow motion.
```

### Script parlé FR (version faceless — voix off)

> (VO FR faceless, ~32s, ton passionné/direct, débit énergique, à générer dans ElevenLabs voix FR naturelle) "Arrête tout. Regarde CE quad deux secondes. Franchement, ce build, c'est une claque. [détail 1] Les triangles d'abord : finition propre, alignée, zéro bavure. [détail 2] Ensuite le châssis et la déco : tout est raccord, les lignes, les couleurs. Le gars a pris son temps. [détail 3] Côté moteur, je te baratine pas sur des chiffres que j'ai pas testés. Ce que je regarde, c'est le taf : le câblage clean, le choix des pièces. Et là, c'est carré. [action] Et en piste... ça parle tout seul. Moi je vends pas du rêve, je repère le bon matos et le bon boulot. Et CE build, c'est validé. Toi, c'est quoi ton build de rêve : YFZ, Raptor ou Banshee ?"

### Textes à l'écran

- CE BUILD EST ILLÉGAL DE PROPRETÉ 🔥
- Détail #1 : les triangles 👀
- Finition = zéro bavure ✅
- Détail #2 : châssis + déco raccord
- Détail #3 : le taf, pas les promesses
- Zéro chiffre bidon. Juste du bon boulot.
- En piste ça parle tout seul 💨
- YFZ ? Raptor ? Banshee ? 👇

### CTA

"Dis-moi en commentaire ton build de rêve : YFZ, Raptor ou Banshee 👇 — abonne-toi, on repère le bon matos ensemble."

### Musique / son

Musique: instru hip-hop/trap énergique mid-tempo (≈140 BPM) avec une basse qui claque, type "MX edit", libre de droits (CapCut Commercial Music ou Epidemic Sound). Drop musical synchronisé sur le money shot d'action (20-28s). SFX: petit "whoosh" sur chaque transition de détail, un "impact bass hit" sur le hook (0-1s) et sur la révélation du quad, un son léger d'admission/moteur UNIQUEMENT en ambiance discrète sur le plan action (jamais utilisé comme preuve sonore de performance). VO FR mixée au-dessus de la musique (ducking -8 dB sous la voix). Sous-titres animés mot-à-mot façon Captions/CapCut, gros, contrastés, jaune/blanc, contour noir.

---

## Vidéo 5 — Top 5 des quads sport de tous les temps

**Format :** TikTok / Reels / Shorts — vertical 9:16 — durée cible 32-36s

**Hook :** Texte parlé (FR, 0-2s, sec et rapide): "Top 5 des quads sport de tous les temps. Le numéro 1 fait l'unanimité." | Texte écran (apparaît dès 0s, gros): "TOP 5 QUADS SPORT 🏁 le #1 est culte"

**Approche recommandée :** HYBRIDE à dominante FACELESS cinématique. Un "Top 5" se regarde — il vit par le b-roll d'action et les machines, pas par une tête qui parle. La colonne vertébrale reste donc une suite de plans text-to-video cinématiques (un par quad) + voix off FR + textes écran rythmés mot-à-mot. On garde une OPTION avatar IA (créateur IA générique, JAMAIS le fondateur) uniquement pour le hook (~2s) et l'outro (~3s), pour créer un lien "créateur" sans jamais filmer le fondateur ni montrer le stockage/atelier. La vidéo est 100% publiable en pur faceless si on retire l'avatar. Correction clé apportée: le #1 est désormais NOMMÉ (Banshee placé en #1, sa vraie place de légende culte) pour ne pas frustrer le viewer ni l'algo, et le classement est réordonné pour rester cohérent (du moderne accessible vers la légende). Idée #5 ne touche ni aux freins (#3) ni à AliExpress (#8): on reste sur de l'opinion de fan ("mythique", "culte", "ma sélection perso"), jamais sur de la perf chiffrée non vérifiée ou un claim sécurité.

**Outils avatar :** Arcads · Creatify · HeyGen · Captions (AI Avatars) · Higgsfield (avatar/UGC) · Veo 3 (personnage qui parle)

### Prompt avatar UGC

```
Vertical 9:16 UGC talking-head, ~3 seconds. A generic, likable male content creator in his late 20s to early 30s — NOT a brand owner, NOT a shop owner — athletic-casual style: a plain black brand-neutral hoodie or a fitted dark tee, short modern haircut, light stubble, energetic and genuine vibe, like a passionate amateur rider who reviews gear for fun. Neutral OUTDOOR setting that reads as 'standing near a dirt track / motocross paddock at golden hour': soft heavily-blurred background of an open sandy field with faint dirt berms far in the distance, warm late-afternoon light, shallow depth of field. ABSOLUTELY NO warehouse, NO shelves, NO parts storage, NO stockroom, NO garage interior, NO workshop, NO boxes, NO indoor scene. Handheld phone-selfie energy with subtle natural camera shake, framed chest-up, eyes locked to lens, talking directly and excitedly to the viewer, expressive hand gestures, briefly counting on his fingers. Natural skin texture, realistic French lip-sync, crisp daylight, punchy contrasty social-media color grade, clean ambient outdoor sound. The creator speaks French. No on-screen text, no logos, no brand markings.
```

### Script parlé FR (avatar)

> HOOK (0-2s, débit rapide, ton de pote passionné): "Top 5 des quads sport de tous les temps — le numéro 1 fait l'unanimité."
> OUTRO (à coller en toute fin, ~3s): "Pas d'accord avec mon classement ? Balance ton numéro 1 en commentaire, et abonne-toi pour la suite."

### Prompts B-roll (text-to-video)

**Plan 1 — #5 Honda TRX (la fiabilité légende)** — *4-5s* — Outils: OpenAI Sora 2, Google Veo 3.1, Kling 2.x, Runway Gen-4

```
Vertical 9:16 cinematic action shot. A red sport ATV (quad), generic classic sport-quad silhouette with no brand badges and no readable text on the bodywork, carving hard through a hard-packed dirt motocross corner, throwing a clean rooster-tail of dust. Low chase-cam following close behind at wheel height, motion blur on the spinning rear wheels, late-afternoon sun raking across the track, backlit dust particles. Dynamic fast tracking, slow-motion 120fps feel, cinematic punchy contrast, anamorphic look, ultra sharp, 9:16. Rider in full generic motocross gear and a plain helmet, face not visible. No text, no logos, no badges, no brand markings, no buildings, no warehouse, no shelves.
```

**Plan 2 — #4 Yamaha YFZ 450 (la racing pure)** — *4-5s* — Outils: OpenAI Sora 2, Google Veo 3.1, Higgsfield, Kling 2.x

```
Vertical 9:16 cinematic action shot. A race-prepped white-and-blue sport ATV (quad), generic racing sport-quad silhouette with no brand badges and no readable text, launching off a dirt jump against a dramatic sky, frozen mid-air at the apex of the jump, dirt clods trailing behind. Low hero angle shooting up toward the machine, strong backlight from the sun creating a rim-lit silhouette and a clean lens flare. Epic slow-motion, crisp suspended dust, high dynamic range, cinematic film look, 9:16. Rider in full generic motocross gear and a plain helmet, face not visible. No text, no logos, no badges, no brand markings, no buildings.
```

**Plan 3 — #3 Yamaha Raptor 700 (le best-seller moderne)** — *4-5s* — Outils: Google Veo 3.1, Runway Gen-4, Kling 2.x, Luma Dream Machine

```
Vertical 9:16 cinematic beauty shot. A modern aggressive blue-and-black sport ATV (quad), generic modern sport-quad silhouette with no brand badges and no readable text, parked three-quarter front on wet asphalt in a moody open-air environment at blue hour, soft rim lighting outlining the bodywork, glistening reflections on the fuel tank and headlights, subtle drifting fog. Smooth orbital camera move arcing around the front of the machine, shallow depth of field, cinematic teal-and-orange grade, glossy reflections, ultra detailed, 9:16. No rider, no text, no logos, no badges, no brand markings, no shelves, no storage, no warehouse.
```

**Plan 4 — #2 Le challenger (machine sport sous projecteur, teaser)** — *4-5s* — Outils: Google Veo 3.1, Runway Gen-4, Kling 2.x, Luma Dream Machine

```
Vertical 9:16 cinematic teaser shot. A sleek modern sport ATV (quad), generic sport-quad silhouette with no brand badges and no readable text, sitting three-quarter on a dark reflective floor with two crossing colored stage lights (cool blue and warm amber) sweeping over the glossy bodywork, faint atmospheric haze, deep dark background. Slow dramatic lateral dolly revealing the profile of the machine, premium high-contrast look, rich blacks, sharp specular highlights, ultra cinematic, 9:16. No rider, no text, no logos, no badges, no brand markings, no shelves, no warehouse, no garage.
```

**Plan 5 — #1 Yamaha Banshee 350 (le 2-temps culte, GRAND reveal)** — *5-6s* — Outils: Google Veo 3.1, Runway Gen-4, Kling 2.x, Luma Dream Machine

```
Vertical 9:16 cinematic reveal shot. A vintage-style two-stroke sport ATV (quad), classic late-80s sport-quad silhouette with glossy purple-and-white bodywork and twin chrome exhaust pipes, no brand badges and no readable text on the bodywork, sitting alone on a dark stage under a single dramatic top spotlight. Volumetric light beam cutting through faint atmospheric haze, the chrome pipes and bodywork glowing as the camera slowly cranes down and pushes in for a grand hall-of-fame reveal, deep black background, faint heat-haze trembling near the engine as if idling. Ultra cinematic, high contrast, rich blacks, anamorphic film grain, sharp detail, 9:16. No rider, no text, no logos, no badges, no brand markings, no shelves, no warehouse, no garage.
```

**Plan 6 — Transition / texture entre les rangs (whip-pan poussière)** — *1s* — Outils: Runway Gen-4, Kling 2.x, Pika, Higgsfield

```
Vertical 9:16 fast transition shot, about 1 second. Extreme close-up of a sport ATV knobby tire spinning and biting into loose dirt, an explosive burst of dust and small rocks flying toward camera, then an ultra-fast whip-pan smearing into a wall of golden backlit dust. Designed as a punchy 1-second cut transition between segments. High frame rate, dramatic backlight, cinematic film grain, 9:16. No text, no logos, no badges, no people.
```

### Script parlé FR (version faceless — voix off)

> [Ton: passionné, direct, énergie MX, débit rapide mais clair — voix FR naturelle ElevenLabs, ducking -6dB sous la VO.]
> (0-2s, HOOK) "Top 5 des quads sport de tous les temps — le numéro 1 fait l'unanimité."
> (2-8s, #5) "Cinquième : le Honda TRX. La fiabilité légende. Le genre de machine qui démarre toujours et qui en redemande."
> (8-14s, #4) "Quatrième : le Yamaha YFZ 450. Là on passe en racing pur. Du vrai caractère sur la piste."
> (14-20s, #3) "Troisième : le Raptor 700. Le best-seller moderne — polyvalent, accessible, t'en croises partout, et c'est mérité."
> (20-25s, #2) "Deuxième... un sacré morceau, mais il se fait souffler la place."
> (25-32s, #1, reveal) "Et numéro un : le Yamaha Banshee 350. Le 2-temps culte. Le son, le mythe, toute une génération a grandi avec. Pour moi, LA légende."
> (32-36s, CTA) "Ça c'est mon classement de fan. Le tien, ton numéro un c'est quoi ? Balance-le en commentaire."

### Textes à l'écran

- TOP 5 QUADS SPORT 🏁 le #1 est culte
- #5 — HONDA TRX 🔧 la fiabilité légende
- #4 — YFZ 450 🏆 racing pure
- #3 — RAPTOR 700 🔥 le best-seller
- #2 — le challenger… 👀
- #1 — BANSHEE 350 ⚡ le 2-temps culte 👑
- Mon top de FAN, pas un classement officiel
- TON #1 EN COMMENTAIRE 👇

### CTA

"C'est mon classement de fan — toi, ton top 1 c'est quoi ? Balance-le en commentaire et abonne-toi pour la suite. 👇"

### Musique / son

Musique: instru hip-hop/trap énergique, grosse 808 et hi-hats rapides, montée en intensité jusqu'au reveal du #1 — le drop est calé PILE sur l'apparition du Banshee sous le projecteur. Sur le #1, court SFX de moteur 2-temps qui monte dans les tours sous la VO (signature sonore du Banshee). SFX: whoosh/whip sur chaque transition entre les rangs (calés sur le plan whip-pan poussière), et un 'impact' grave (boum + sub) au moment exact du reveal #1. Ducking musique -6dB sous la voix off pour l'intelligibilité. Montage + sous-titres animés mot-à-mot sur CapCut ou Captions.

---

## Vidéo 6 — J'apprends à reconnaître les pièces d'un quad (série pédago) — Épisode 1

**Format :** TikTok / Instagram Reels / YouTube Shorts — vertical 9:16 (1080x1920) — durée cible 32-38s

**Hook :** Texte parlé (0-2s): "Tu sais pas nommer 5 pièces de ton quad ? Moi non plus y'a six mois." | Texte écran: "POV: t'achètes des pièces sans savoir comment ça s'appelle 😅"

**Approche recommandée :** HYBRIDE. Un avatar IA (créateur générique, PAS le fondateur) ouvre et ferme la vidéo en talking-head pour incarner la posture "le fan qui apprend avec toi" (sincérité, complicité, forte rétention sur le hook), et le coeur pédago passe en b-roll cinématique IA de pièces de quad (gros plans macro) avec annotations textuelles à l'écran. Cette structure respecte toutes les contraintes: zéro fondateur à l'écran (avatar IA), zéro stockage/atelier/garage montré (décor neutre extérieur/piste + plans macro produits sur fonds studio neutres), et l'angle "j'apprends, je ne suis pas un faux-expert" est tenu de bout en bout. Une version 100% faceless (VO ElevenLabs + b-roll seul) est fournie en alternative sans avatar. Tous les claims sur le freinage restent en posture CONFIANCE/CURATION (sélection du bon matos), jamais de performance ni de conception maison.

**Outils avatar :** Arcads · Creatify · HeyGen · Captions (AI Avatars) · Google Veo 3.1 (dialogue + lip-sync) · Higgsfield (UGC avatar)

### Prompt avatar UGC

```
Vertical 9:16 UGC talking-head selfie video, ~8-10 seconds. A generic, relatable male AI creator in his late 20s with a casual ATV / motocross enthusiast vibe — short messy hair, light stubble, wearing a worn plain black enduro hoodie or a dark unbranded graphic tee, absolutely no visible logos. He is clearly NOT a mechanic and NOT in any workshop. Setting: a neutral OUTDOOR location beside an empty dirt track / open gravel area at golden hour, soft natural backlight, heavily blurred bokeh background of an open field and distant trackside fencing — strictly NO shelves, NO cardboard boxes, NO stored or stacked parts, NO garage interior, NO workshop, NO warehouse. He holds the phone at arm's length at a slight high selfie angle with subtle handheld micro-shake for authenticity, and speaks directly and energetically to camera with friendly, humble, motivated body language, small natural hand gestures, a genuine smile and raised eyebrows on the opening hook. Natural daylight skin tones, shallow depth of field, 35mm phone-selfie look, crisp face, clean accurate lip-sync. Energetic but approachable street / MX tone. Keep generous headroom and a clear lower third empty for on-screen captions.
```

### Script parlé FR (avatar)

> OUVERTURE (0-8s, avatar): "Tu sais pas nommer 5 pièces de ton quad ? Franchement, moi non plus y'a six mois. Alors on apprend ensemble — épisode 1, c'est parti."
> FERMETURE (30-37s, avatar de retour): "Et voilà : déjà cinq pièces que tu sais nommer. Moi je suis pas méca, je suis juste un passionné qui trie le bon matos avec vous. Dis en commentaire celle que tu connaissais pas, et abonne-toi — l'épisode 2 arrive."

### Prompts B-roll (text-to-video)

**Plan 1 — Macro étrier de frein + disque (angle curation, aucune promesse de perf)** — *4-5s* — Outils: Google Veo 3.1, Runway Gen-4, Kling 2.x, Higgsfield

```
Vertical 9:16 cinematic macro shot, 4-5 seconds. Extreme close-up of a sport ATV front brake caliper and brake rotor, mounted on a clean knobby off-road wheel, isolated on a neutral matte concrete studio floor lit by a single soft key light from the left. Slow dolly-in with shallow depth of field, brushed-metal and anodized textures catching the light, fine dust motes drifting in the air, moody trackside ambiance. No people, no hands, no shelving, no boxes, no garage, no warehouse. Premium product-film look, high detail, subtle reflections, slightly desaturated teal-orange color grade. Camera slowly racks focus across the caliper body.
```

**Plan 2 — Macro amortisseur + triangle de suspension avant** — *4-5s* — Outils: Google Veo 3.1, Sora 2, Kling 2.x, Runway Gen-4

```
Vertical 9:16 cinematic macro shot, 4-5 seconds, of a sport quad front shock absorber and A-arm suspension assembly, with the spring coil and piggyback reservoir clearly visible, mounted on a matte black studio surface with dramatic rim lighting. Slow vertical tilt revealing the full length of the shock, shallow depth of field, oily metallic sheen, fine micro-detail on the threaded preload collar, neutral dark studio backdrop. No humans, no hands, no storage racks, no garage, no warehouse. Cinematic product cinematography, crisp focus, teal-orange grade, gentle floating camera move.
```

**Plan 3 — Macro pneu cranté + jante alu** — *4-5s* — Outils: Kling 2.x, Runway Gen-4, Google Veo 3.1, Luma Dream Machine

```
Vertical 9:16 cinematic macro, 4-5 seconds, of an aggressive ATV knobby off-road tire and aluminum rim, with dirt and dried mud flecks in the deep tread blocks, rotating slowly on a turntable against a clean neutral grey seamless studio background lit by a soft top light. Extreme texture detail on the rubber lugs, shallow depth of field, slow continuous rotation, subtle dust particles in the air. No people, no hands, no shelves, no garage, no warehouse. High-end commercial product look, dynamic but minimal, slightly contrasty color grade.
```

**Plan 4 — Macro guidon + leviers + poignée d'accélérateur au pouce** — *4-5s* — Outils: Google Veo 3.1, Runway Gen-4, Higgsfield, Pika

```
Vertical 9:16 cinematic macro tracking shot, 4-5 seconds, gliding along a sport ATV handlebar — grips, brake lever, thumb throttle and clutch perch coming into sharp focus one after another — set against a softly blurred outdoor dirt-track background at dusk. Smooth lateral dolly, shallow depth of field, warm practical highlights catching the metal levers. No rider, no hands, no garage interior, no workshop, no warehouse. Premium automotive-style detail film, cinematic motion blur on the background, refined teal-orange color grade.
```

**Plan 5 — Macro moteur + cylindre + radiateur (clôture pédago)** — *4-5s* — Outils: Sora 2, Google Veo 3.1, Kling 2.x, Runway Gen-4

```
Vertical 9:16 cinematic macro, 4-5 seconds, of a sport quad engine block with the cooling fins of the cylinder and an aluminum radiator core in the foreground, beads of light reflecting off the metal, set on a neutral dark studio floor with a single dramatic side light and gentle atmospheric haze. Slow push-in revealing engineering texture and bolt detail, shallow depth of field. No people, no hands, no inventory, no shelves, no garage, no warehouse. High-end mechanical beauty shot, moody teal-orange cinema grade, fine particulate floating in the light beam.
```

**Plan 6 — Plan d'ambiance d'ouverture / transition : quad sport seul sur piste, lumière dorée** — *4-5s* — Outils: Google Veo 3.1, Sora 2, Kling 2.x, Luma Dream Machine

```
Vertical 9:16 cinematic establishing shot, 4-5 seconds, of a sport ATV quad parked alone on an empty dirt motocross track at golden hour, shot from a low hero angle, dust gently drifting in warm backlight, distant blurred berms and track fencing behind it. No rider, no people, no buildings, no shelves, no garage, no storage. Slow orbital camera move around the machine, subtle anamorphic flares, shallow depth of field, epic MX commercial energy, rich teal-orange color grade.
```

### Script parlé FR (version faceless — voix off)

> VERSION 100% FACELESS (VO ElevenLabs, voix française masculine naturelle, énergie passionnée, débit dynamique mais clair — calée sur ~33-37s de b-roll) : "Tu roules en quad, mais tu sais pas nommer les pièces ? Pas de stress, on apprend ensemble. (plan étrier) Ça, c'est l'étrier de frein, avec son disque — sur ce genre de pièce, je trie au millimètre, je prends que du matos en qui j'ai confiance. (plan amorto) Là, l'amortisseur et le triangle de suspension — c'est ce qui encaisse les bosses. (plan pneu) Le pneu cranté et sa jante — voilà d'où vient l'accroche. (plan guidon) Le guidon, les leviers, la poignée d'accélérateur au pouce — tes commandes. (plan moteur) Et le coeur de la bête : le moteur et son radiateur. Voilà — déjà cinq pièces que tu connais. Moi je suis pas méca, juste un passionné qui sélectionne le bon matos. Abonne-toi, l'épisode 2 arrive."

### Textes à l'écran

- POV: t'achètes des pièces sans savoir comment ça s'appelle 😅
- ÉPISODE 1 — Apprends avec moi
- 1️⃣ L'ÉTRIER DE FREIN (+ disque)
- 2️⃣ L'AMORTISSEUR + TRIANGLE
- 3️⃣ LE PNEU CRANTÉ + JANTE
- 4️⃣ GUIDON / LEVIERS / POIGNÉE
- 5️⃣ MOTEUR + RADIATEUR
- Tu en connaissais combien ? 👇
- Pas méca — juste passionné. On trie le bon matos ensemble
- Abonne-toi → Épisode 2

### CTA

"Dis en commentaire la pièce que tu connaissais pas — et abonne-toi, l'épisode 2 (zoom sur le système de freinage) arrive cette semaine."

### Musique / son

Musique : instru hybride MX / trap-rock énergique, BPM ~120-130, kick punchy, légère montée sur le hook, drop discret au premier plan macro. SFX : petit "whoosh" à chaque transition entre pièces, léger "click" mécanique sur l'apparition de chaque numéro à l'écran, sub-boom sur le plan moteur final. Garder la musique nettement sous la VO (-12 à -15 dB) pour la clarté du français. Montage et sous-titres animés word-by-word dans CapCut ou Captions.

---

## Vidéo 7 — L'histoire des éditions commémoratives Banshee — le quad 2-temps devenu un mythe

**Format :** TikTok / Instagram Reels / YouTube Shorts — vertical 9:16, 1080x1920 — durée cible 32-36s

**Hook :** Texte parlé (0-2s, sur le brap du démarrage 2-temps): "La Banshee, c'est le seul quad qu'on collectionne comme une voiture de sport." | Texte écran (gros, en haut, qui claque à l'image): "POURQUOI ON LA COLLECTIONNE ?" sur un gros plan moteur 2-temps qui s'allume.

**Approche recommandée :** HYBRIDE à dominante FACELESS. Le sujet est historique et narratif (éditions spéciales, années, livrées) — l'émotion vient des PLANS de quads (livrées, beauty shots, fumée 2-temps), pas d'un visage. La vidéo principale est donc 100% faceless: b-roll text-to-video cinématique + voix off FR (ElevenLabs) + textes écran rythmés. On fournit AUSSI un prompt d'avatar IA générique (créateur lambda, décor extérieur neutre) en option d'ouverture/fermeture, pour ceux qui veulent un visage qui parle SANS jamais filmer le fondateur ni le stock. Contraintes absolues respectées: zéro fondateur à l'écran, zéro atelier/stockage/entrepôt/garage. Aucune pièce détachée montrée — uniquement des quads entiers en studio neutre ou en nature. Le seul humain possible (plan action) est un pilote 100% casqué et non identifiable, en équipement générique: ce n'est pas le fondateur et ce n'est pas du stock.

**Outils avatar :** Arcads · Creatify · HeyGen · Captions (AI Avatars) · Higgsfield

### Prompt avatar UGC

```
Vertical 9:16 UGC talking-head, handheld phone-camera look. A generic, authentic-looking male motorsport fan in his late 20s, NOT a polished TV presenter: short slightly messy hair, light stubble, wearing a plain dark enduro/motocross-style hoodie or a neutral graphic tee with NO readable brand logos. He is filmed OUTDOORS in a clean, NEUTRAL location: the edge of an open dirt track or an empty paddock at golden hour, with softly blurred dunes or distant trees in the deep background. ABSOLUTELY NO warehouse, NO shelves, NO spare parts, NO garage or workshop interior anywhere in frame. Eye-level selfie framing, head-and-shoulders, shallow depth of field, natural warm daylight with soft rim light. He talks straight to camera with genuine passion and energy, slight smile, expressive hand gestures, like a real enthusiast sharing something he loves. Authentic UGC texture: natural skin detail, light film grain, ambient outdoor sound. Lip-sync must match French speech. Keep the background clean, generic and free of any storage at all times.
```

### Script parlé FR (avatar)

> La Yamaha Banshee 350, c'est LE quad qu'on collectionne comme une voiture de sport. Pourquoi ? Parce que pendant presque vingt ans, Yamaha a multiplié les éditions spéciales: des livrées qui changeaient quasiment chaque année, des coloris collector, certaines en toute petite quantité. Du coup, les plus rares, dans leur jus, c'est devenu des pièces de passionnés. Une machine 2-temps, brute, bruyante, devenue un vrai mythe. Nous, on ne fabrique rien — on adore juste décortiquer cette culture. Tu connaissais ? Abonne-toi à Quad Unlimited.

### Prompts B-roll (text-to-video)

**Plan 1 — Hook : réveil du monstre 2-temps** — *0-3s* — Outils: Google Veo 3.1, OpenAI Sora 2, Runway Gen-4, Kling 2.x

```
Vertical 9:16 cinematic close-up. Extreme close-up of a vintage-style 2-stroke twin-cylinder sport ATV engine in a clean dark studio with soft dramatic side lighting. The engine fires up: faint blue-white two-stroke exhaust haze curls out of dual pipes, subtle heat shimmer, chrome and aluminium reflections gleaming. Slow push-in dolly, very shallow depth of field, moody automotive-commercial look, crisp detail, high contrast, fine film grain. No people, no text, no shelves, no parts, no storage — neutral studio only.
```

**Plan 2 — Galerie des livrées commémoratives (beauty rotation)** — *3-12s* — Outils: Google Veo 3.1, Runway Gen-4, Kling 2.x, Higgsfield

```
Vertical 9:16 cinematic studio shot. A complete classic-style blue-and-white two-stroke racing sport quad (ATV) sits on a clean dark reflective floor under a soft spotlight. Slow smooth 180-degree orbit camera move revealing its bodywork and graphics. The livery smoothly morphs between several special-edition color schemes: deep blue and white, then black and gold, then red and silver. Premium car-commercial lighting, glossy plastics, subtle lens flare, shallow depth of field, dramatic rim light, cinematic color grade, film grain. No humans, no readable logos or text, neutral empty studio — absolutely no warehouse, garage or parts shelving.
```

**Plan 3 — Action piste : la légende en mouvement** — *12-22s* — Outils: Google Veo 3.1, OpenAI Sora 2, Kling 2.x, Luma Dream Machine

```
Vertical 9:16 cinematic action shot. A blue-and-white two-stroke sport quad rips across desert sand dunes at golden hour, throwing a rooster tail of sand, faint blue two-stroke smoke trailing behind, motion-blurred background, dynamic low tracking shot moving alongside it. Warm backlight, dust particles in the air, fast-shutter feel, adrenaline energy, cinematic motocross-commercial style, high detail, film grain. The rider wears a FULL helmet and full gear with face completely covered and unidentifiable, plain generic gear with no readable logos. Wide open natural landscape, no buildings, no shelves, no storage of any kind.
```

**Plan 4 — Détail collector : la patine d'une légende** — *22-29s* — Outils: Runway Gen-4, Kling 2.x, Higgsfield, Pika

```
Vertical 9:16 cinematic macro shot. A slow gliding close-up travels across the tank graphics and a small generic commemorative-style edition badge on a glossy quad fuel tank. Warm golden light rakes across the metallic paint flake, tiny dust motes float in the beam, very shallow depth of field with creamy bokeh, luxury-product reveal feel, slow motion, cinematic grade, film grain. No baked-in text overlay, no people, neutral dark studio backdrop only — no shelves, no parts, no storage.
```

**Plan 5 — Outro : silhouette mythique** — *29-36s* — Outils: Google Veo 3.1, Luma Dream Machine, Runway Gen-4

```
Vertical 9:16 cinematic hero shot. A single complete sport quad stands silhouetted against a dramatic dusk sky on a hilltop dirt ridge, warm orange-and-purple gradient sky, faint mist low to the ground, soft backlight tracing a rim of light around the bodywork, slow cinematic push-in, epic legendary mood, gentle lens flare, film grain. Empty natural landscape, no people, no buildings, no storage. Clean composition with generous headroom at the top for an end-card text overlay.
```

### Script parlé FR (version faceless — voix off)

> La Yamaha Banshee 350. Pour beaucoup, c'est LE quad qu'on collectionne comme une voiture de sport. Et il y a une vraie raison. Pendant près de vingt ans, Yamaha a sorti des éditions spéciales: des livrées qui changeaient quasiment chaque année, des coloris collector, certaines séries en toute petite quantité. Résultat, les Banshee les plus rares, dans leur jus, c'est devenu des pièces que les passionnés s'arrachent. Une machine 2-temps, brute, bruyante, devenue un vrai mythe. Nous, on ne fabrique rien — on adore juste décortiquer cette culture et trier ce qui mérite vraiment qu'on en parle. Si l'histoire du quad te parle, abonne-toi: on continue ensemble.

### Textes à l'écran

- POURQUOI ON LA COLLECTIONNE ?
- Yamaha Banshee 350 — 2-temps culte
- ~20 ans d'éditions spéciales
- Des livrées différentes presque chaque année
- Les séries rares, très recherchées
- Une machine devenue un mythe
- Abonne-toi — la culture quad expliquée

### CTA

"Tu connaissais l'histoire des éditions Banshee ? Dis-moi ta livrée préférée en commentaire — et abonne-toi à Quad Unlimited, on décortique la culture quad ensemble."

### Musique / son

Musique: instru hip-hop / trap cinématique, sombre et lente au début (sous le hook moteur), puis montée d'énergie quand le quad part sur les dunes (drop rythmé, BPM medium-haut, vibe MX/edit), retour plus posé sur l'outro silhouette. SFX: démarrage 2-temps réel + brap caractéristique (banque de sons moteur 2T) calé pile sur le hook, whoosh sur chaque transition de livrée, swell de basse sur l'outro. Voix off FR générée sur ElevenLabs (voix masculine française naturelle, énergique mais posée, légère réverbe). Mix: VO nettement au-dessus de la musique, ducking de la musique sous la voix. Montage et sous-titres animés mot-à-mot sur CapCut ou Captions.

---

## Vidéo 8 — AliExpress vs pièce sérieuse : la différence qui peut te coûter cher (angle confiance/curation)

**Format :** Vertical 9:16 (1080x1920), TikTok / Instagram Reels / YouTube Shorts, durée cible 30-34s, hook dans les 2 premières secondes.

**Hook :** Texte parlé : "Cette pièce à 8 balles et celle à 40, sur la photo c'est exactement la même. En vrai, c'est là que tu te fais avoir." | Texte écran (gros, contrasté, en haut) : "MÊME PHOTO. PAS LE MÊME TRUC."

**Approche recommandée :** Route recommandée : HYBRIDE. Le sujet "confiance/curation" gagne à avoir un visage humain qui parle (crédibilité + rétention), mais comme le fondateur ne veut PAS apparaître, on utilise un avatar IA générique (créateur lambda, PAS le fondateur) pour le talking-head, intercalé avec du b-roll text-to-video très cinématique de deux pièces côte à côte. Ce mix garde la sincérité du discours porté par une voix/visage tout en montrant visuellement l'écart de finition, SANS jamais filmer le fondateur ni montrer de stock/atelier/garage. Une version 100% faceless (VO ElevenLabs + b-roll uniquement) est fournie en repli si tu veux zéro avatar. Garde-fou intégrité : aucune pièce de freinage mise en avant, aucun claim de durabilité/sécurité chiffré ou prouvé — on reste sur le principe général de curation/sourcing/confiance, et le discours assume explicitement "je ne suis pas ingénieur".

**Outils avatar :** Arcads · Creatify · HeyGen · Captions (AI Avatars) · Higgsfield (avatar/UGC) · Veo 3 / 3.1 (personnage qui parle, lip-sync FR)

### Prompt avatar UGC

```
Vertical 9:16 UGC talking-head video, authentic phone-camera look. A casual male amateur ATV / motocross enthusiast in his late 20s to mid 30s, clearly NOT a professional and NOT a mechanic in uniform. Short slightly messy hair, light stubble, wearing a plain dark t-shirt or a lightly worn black motocross hoodie. He is filmed outdoors in a fully neutral location: a sunlit open dirt area or an empty plain concrete lane, soft natural daylight, shallow depth of field, smoothly blurred neutral background. ABSOLUTELY NO warehouse, NO shelves, NO storage racks, NO cardboard boxes of parts, NO garage interior, NO workshop, NO stockpile of any kind visible anywhere in frame or background. Handheld selfie-style framing, eye-level, head-and-shoulders, subtle natural camera shake, realistic skin texture, no beauty smoothing. He speaks directly and energetically to the camera with confident, sincere, slightly raw friend-to-friend energy, small natural hand gestures, genuine micro-expressions. Lip-sync must match French speech precisely. Natural ambient outdoor sound. No on-screen text baked in (captions added later in edit). Realistic, not glossy, high-retention UGC aesthetic.
```

### Script parlé FR (avatar)

> Franchement, je suis pas ingénieur, je te raconte pas de salades. Mais à force de commander, j'ai compris un truc : sur la photo, la pièce à 8 euros et celle à 40, c'est la même. En vrai, pas du tout. Le métal, les finitions... y'a des trucs où t'as juste pas envie de jouer. Mon délire c'est pas de te dire 'achète cher'. C'est de trier pour toi le matos en qui j'ai confiance, et de te dire honnêtement quand le pas cher suffit. C'est tout.

### Prompts B-roll (text-to-video)

**Plan 1 — Ouverture : deux pièces quasi identiques côte à côte (hook visuel)** — *0-4s* — Outils: Google Veo 3 / 3.1, OpenAI Sora 2, Runway Gen-4, Kling 2.x

```
Vertical 9:16 cinematic close-up product shot. Two visually near-identical small aftermarket ATV / motorcycle metal parts (a generic aluminium drive sprocket and, alternatively, a non-brake clutch lever) placed side by side on a clean matte dark slate surface under a single soft studio key light. Slow push-in dolly move. The left part has a subtly rougher cast finish with faint surface irregularities and a dull sheen; the right part is precisely machined, smooth, evenly anodized. Shallow depth of field, crisp macro detail on the metal grain and edges, cool cinematic color grade with a hint of teal. Dust-free neutral studio backdrop. No people, no hands, no logos, no readable text, no shelves, no warehouse. Photoreal, high-end commercial lighting.
```

**Plan 2 — Macro comparatif : glissé sur les finitions du métal (texture vs propreté)** — *4-9s* — Outils: Runway Gen-4, Kling 2.x, Google Veo 3 / 3.1, Higgsfield

```
Vertical 9:16 extreme macro tracking shot gliding slowly across the edge of a machined aluminium ATV sprocket. Reveal fine surface detail: on the first piece subtle uneven edges and a dull matte sheen with faint surface texture; then a smooth transition to a second piece with clean, precise CNC-machined edges and a uniform finish. Dramatic raking side light to emphasize texture, sparkling micro-highlights, slow rack focus, very shallow depth of field, cinematic teal-and-amber grade. Pure black neutral background. No people, no hands, no readable text, no environment, no warehouse, no shelves. Photoreal, premium tech-product aesthetic.
```

**Plan 3 — Plan symbolique 'écart de prix' : étiquettes prix abstraites qui s'affichent** — *9-14s* — Outils: Google Veo 3 / 3.1, Higgsfield, Luma Dream Machine, Pika

```
Vertical 9:16 stylized cinematic shot of two near-identical aluminium ATV parts on a dark reflective surface, a soft spotlight on each. Two clean minimalist motion-graphic price tags drift down and settle next to the parts, one lower and one higher, rendered as abstract floating label shapes with no specific currency symbols and no readable numbers baked in. Subtle particle dust floating in the light beams, slow parallax camera drift, moody high-contrast studio lighting, cinematic depth of field. No people, no hands, no warehouse, no shelves, no readable text baked in. Photoreal product with a tasteful motion-graphic overlay feel.
```

**Plan 4 — B-roll ambiance rider : quad sport en action sur piste MX (énergie)** — *14-19s* — Outils: Google Veo 3 / 3.1, OpenAI Sora 2, Kling 2.x, Runway Gen-4

```
Vertical 9:16 cinematic action shot of a sport ATV quad ripping across a dusty motocross dirt track at golden hour, kicking up a dramatic plume of dust behind the rear wheels. Low dynamic tracking camera following alongside, motion blur, fast-shutter texture, warm backlight rim glowing through the dust, deep cinematic color grade, high-energy motocross atmosphere. The rider wears full gear and a closed helmet so the face is not identifiable. No text, no brand logos, no warehouse, no static parts. Photoreal, high-octane, premium sports cinematography.
```

**Plan 5 — Plan 'curation/confiance' : deux pièces sur fond studio, une mise en avant par la lumière (tri symbolique, SANS opérateur)** — *19-26s* — Outils: Runway Gen-4, Kling 2.x, Higgsfield, Google Veo 3 / 3.1 (image-to-video from a product photo)

```
Vertical 9:16 cinematic studio shot on a clean dark tabletop. Two small aluminium ATV parts sit on a neutral matte surface: one is gently lit and slowly pushed into a soft pool of key light (the 'chosen' part), while the second drifts slightly out of focus into shadow at the edge of frame (the 'set-aside' part). A slow, contemplative camera drift and a gradual rack focus convey careful selection and trust, purely through light and composition. NO hands, NO gloves, NO people, NO body, NO warehouse, NO shelves, NO stockpile, NO garage — only the two parts on a clean surface with cinematic lighting. Shallow depth of field, intimate premium curation mood, soft volumetric beams. Photoreal.
```

**Plan 6 — Clôture : la pièce 'sérieuse' héroïsée pour le CTA** — *26-32s* — Outils: Google Veo 3 / 3.1, Higgsfield, Luma Dream Machine, Runway Gen-4

```
Vertical 9:16 hero product beauty shot of a single well-machined aluminium ATV part rotating slowly on a dark pedestal under cinematic studio lighting, soft volumetric light beams and a gentle lens flare, clean reflective floor, slow orbit camera move, premium teal-and-warm color grade, shallow depth of field. Empty negative space at the bottom of the frame reserved for a caption / CTA overlay added later in edit. No people, no hands, no text baked in, no warehouse, no shelves. Photoreal, aspirational commercial finish.
```

### Script parlé FR (version faceless — voix off)

> Cette pièce à 8 euros, et celle à 40... sur la photo, c'est la même. En vrai ? Pas du tout. Je vais être clair : je suis pas ingénieur, et je vais pas t'inventer des tests que j'ai pas faits. Mais à force de commander un peu partout, t'apprends à voir la différence. Le métal, les finitions... parfois ça saute aux yeux, parfois non. Et y'a des pièces où le pas cher passe sans souci. D'autres où, perso, je préfère pas tenter. Mon truc, c'est pas de te pousser à payer plus. C'est de trier pour toi le matos en qui j'ai confiance, et de te dire quand l'AliExpress suffit largement... et quand ça vaut le coup de mettre un peu plus. Le reste, tu décides. Mais au moins, en connaissance de cause.

### Textes à l'écran

- MÊME PHOTO. PAS LE MÊME TRUC.
- 8€ ou 40€ : tu vois la diff ?
- Je suis pas ingénieur (et je te le dis)
- Parfois le pas cher suffit
- Parfois... je préfère pas tenter
- Mon job : trier le matos de confiance
- Tu décides — mais en connaissance de cause
- Quad Unlimited

### CTA

"Abonne-toi à Quad Unlimited : à chaque vidéo, je trie le bon matos pour que tu commandes sans te faire avoir. Dis-moi en commentaire la pire pièce AliExpress que t'as reçue."

### Musique / son

Musique : instru hip-hop / trap modéré, basse présente mais pas écrasante, tempo qui donne de l'énergie sans couvrir la voix (style 'urban garage'). Drop léger calé sur le hook visuel des deux pièces (0-4s) et sur le plan quad en action (14s). SFX : petit 'whoosh' métallique sur l'apparition des étiquettes prix (9-14s), 'ding' discret sur le plan de tri/curation (19-26s). Sur la version avatar, baisser la musique de 6-8 dB sous la voix. Montage et sous-titres animés (mot-à-mot, couleur d'accent contrastée) sur CapCut ou Captions. Voix off FR via ElevenLabs (voix masculine française naturelle, ton posé-direct, légèrement brut, pas radio-commercial).

---

## Vidéo 9 — Coulisses : "Je construis une marque quad de zéro, suis-moi" — version 100% FACELESS

**Format :** TikTok / Instagram Reels / YouTube Shorts — vertical 9:16 (1080x1920) — durée cible 30-36s

**Hook :** Texte parlé (2 premières sec) : "Zéro quad, zéro stock, zéro budget. Et je lance quand même une marque quad. Jour 1." | Texte écran plein cadre : "MARQUE QUAD — JOUR 1 / 0€ EN POCHE"

**Approche recommandée :** Route recommandée : 100% FACELESS cinématique + voix off.

**Outils avatar :** Arcads · Creatify · HeyGen · Captions (AI Avatars) · Higgsfield (avatar/UGC) · Veo 3 (personnage qui parle)

### Prompt avatar UGC

```
Vertical 9:16 UGC talking-head, ~25s. A generic French-looking male content creator in his late 20s, NOT a celebrity and NOT based on any real person, casual passionate enthusiast vibe: dark moto/MX-style hoodie or a plain black tee, short tousled hair, light stubble, authentic slightly raw energy like a fan filming himself on his phone. Handheld selfie-style, eye-level, natural daylight. SETTING (pick ONE, never both): outdoors at the edge of an empty motocross dirt track during golden hour, with packed earth, distant berms, faint tire marks, soft bokeh of trees and a warm sky. ABSOLUTELY NO warehouse, NO shelves, NO parts on shelves, NO garage, NO workshop, NO boxes, NO stock, NO storage room, NO indoor industrial space of any kind. He speaks directly to camera with genuine, motivated, direct delivery, small natural hand gestures, warm skin tones, subtle ambient outdoor noise. Realistic micro-expressions, natural blinking, accurate French lip-sync. Crisp 9:16 framing, head and upper chest in frame, shallow depth of field, modern UGC look.
```

### Script parlé FR (avatar)

> Zéro quad, zéro stock, zéro budget. Et je lance quand même une marque quad. Jour 1. Mon truc, c'est pas de jouer l'expert qui sait tout — c'est d'apprendre devant vous. Je teste des idées, je compare, je partage ce qui me parle, sans mytho. Une marque média de passion, construite en public. Si t'aimes le quad sport et le MX, reste : tu suis tout depuis le tout début. On y va.

### Prompts B-roll (text-to-video)

**Plan 1 — Hook : quad sport plein cadre, démarrage explosif** — *3-4s* — Outils: Google Veo 3 / 3.1, OpenAI Sora 2, Kling 2.x, Runway Gen-4, Higgsfield

```
Vertical 9:16 cinematic slow-motion. An empty motocross dirt track at golden hour. Low ground-level tracking shot of a generic sport ATV quad bike (raptor/YFZ-style silhouette, NO readable logos, NO brand text) launching forward, rear wheels spinning, a thick cloud of dust and dirt clods exploding behind it, backlit by a warm low sun. Shallow depth of field, lens flare, gritty energetic motocross atmosphere, ultra sharp, photoreal, 60fps slow-motion feel. No people visible, no rider, no text, no logos. Anamorphic look, high contrast, dramatic.
```

**Plan 2 — Détail produit : gros plan étrier de frein doré qui tourne (beauty shot, objet générique)** — *3s* — Outils: Kling 2.x (image-to-video sur photo produit), Runway Gen-4, Higgsfield, Google Veo 3

```
Vertical 9:16 macro beauty shot. A premium gold-anodized multi-piston ATV brake caliper and a wave brake disc, isolated on a clean dark reflective surface with dramatic studio rim lighting and slow rotating turntable motion. Cinematic product cinematography, crisp metallic reflections, shallow depth of field, soft moving highlights catching the machined edges, subtle floating dust particles in the light beams, premium high-end automotive-parts advertising look. Photoreal. No text, no readable logos, no hands, no people. Plain neutral seamless studio background — NOT a warehouse, NOT a garage, NO shelves, NO boxes.
```

**Plan 3 — Action piste : quad qui prend un virage en envoyant la terre (pilote anonyme casqué)** — *3-4s* — Outils: Google Veo 3 / 3.1, OpenAI Sora 2, Kling 2.x, Luma Dream Machine

```
Vertical 9:16 cinematic, dynamic side tracking shot of a single generic sport ATV quad carving hard through a banked dirt corner on a motocross track, spraying a fan of dirt and dust into warm afternoon light. The rider wears full opaque MX gear and a full-face helmet with the tinted visor down, seen only from behind and the side so NO face is ever visible or identifiable. Motion blur on the background, sharp on the machine, adrenaline-fueled, photoreal, gritty MX energy, golden dust haze. No readable logos, no text, no recognizable person.
```

**Plan 4 — Symbole du build : site/réseaux CONCEPT qui s'assemble (screen-recording stylisé, mockup)** — *3-4s* — Outils: CapCut (mockup + motion), Higgsfield, Runway Gen-4, Captions

```
Vertical 9:16 stylized screen-recording aesthetic. A sleek modern dark-themed CONCEPT website and social-media profile mockup for a quad/ATV passion media brand, scrolled smoothly on a phone held against a clean neutral blurred OUTDOOR background. Animated UI elements gently sliding and assembling in: a bold placeholder logo, a follower count ticking up, content cards, a glowing 'Suivre' button. Soft motion graphics, premium app-promo look, shallow depth of field, warm rim light on the phone edges. Photoreal hand holding the phone from behind only — NO face. NO warehouse, NO shelves, NO garage, NO physical products or stock visible. Pure on-screen interface only.
```

**Plan 5 — Ambiance culture : quad 2-temps au ralenti, fumée et chrome** — *3s* — Outils: Google Veo 3 / 3.1, Kling 2.x, Runway Gen-4, Pika, Hailuo/MiniMax

```
Vertical 9:16 moody cinematic. A classic 2-stroke sport ATV quad (twin-pipe Banshee-style silhouette, NO readable logos, NO brand text) idling at dusk, faint exhaust haze drifting through cold-blue-to-warm light. Extreme close-ups of chrome exhaust pipes, finned engine and knobby tire treads, dramatic low-key lighting with deep shadows, nostalgic motocross-culture mood, slow drifting camera. Photoreal, film grain. No people, no text, no logos. Outdoor dusk setting — NOT a garage, NOT a workshop, NO shelves.
```

**Plan 6 — Closing : quad qui s'éloigne vers l'horizon, espace CTA** — *3-4s* — Outils: Google Veo 3 / 3.1, OpenAI Sora 2, Luma Dream Machine, Kling 2.x

```
Vertical 9:16 cinematic wide shot. A generic sport ATV quad riding away from camera down an open dirt track toward a glowing sunset horizon, a long dust trail rising behind it and catching golden backlight. Epic, hopeful, start-of-a-journey feeling, lens flare, slow push-in, photoreal, warm color grade. Composition leaves clear empty space at the top and bottom for text overlay. No readable logos, no text baked in, no people in the foreground, no rider face visible.
```

### Script parlé FR (version faceless — voix off)

> Zéro quad. Zéro stock. Zéro budget. Et pourtant, aujourd'hui, je lance une marque quad. Jour un. Mon idée, c'est pas de jouer l'expert qui sait tout — c'est l'inverse : j'apprends devant vous. Je me renseigne, je compare, et je partage ce qui me parle, honnêtement. Étriers, disques, plaquettes... je ne prétends pas concevoir ni garantir quoi que ce soit — je sélectionne et je vous montre ce que je trouve intéressant. Une marque média de passion, construite en public, sans mytho. Pas de promesse magique : juste de la confiance, du tri, et de l'énergie quad et MX. Si t'es là pour la passion, abonne-toi. Tu vas voir grandir tout le projet depuis le tout premier jour. On y va.

### Textes à l'écran

- MARQUE QUAD — JOUR 1
- 0€ • 0 stock • 0 quad
- Je construis en public 👀
- PAS faux expert. Juste un passionné.
- Je compare, je sélectionne 🔧
- Confiance > prix
- Abonne-toi, suis tout depuis le début 🏁

### CTA

Abonne-toi pour suivre la construction de Quad Unlimited depuis le jour 1 — dis en commentaire la machine que tu roules (Banshee, Raptor, YFZ, TRX) 🏁

### Musique / son

Beat hip-hop / trap instrumental énergique mais pas saturé (BPM ~90-100), montée sur le hook, drop léger sur le plan d'action piste. SFX : whoosh sur chaque coupe, rugissement moteur sourd sous les plans quad, petit "ding" UI sur le screen-recording (follower count qui grimpe). Baisser la musique de -8 dB sous la voix off pour garder la VO ElevenLabs (voix française masculine naturelle, chaleureuse, débit posé mais motivé) parfaitement intelligible. Fin sur un dernier whoosh + court silence avant le CTA écran.

---

## Vidéo 10 — 3 erreurs de débutant sur un quad — Pack UGC IA (9:16)

**Format :** TikTok / Instagram Reels / YouTube Shorts — vertical 9:16 (1080x1920) — durée cible 30-36s

**Hook :** PARLE (0-2s): "3 réflexes de débutant flinguent ton quad... et le numéro 2, tout le monde le fait." | TEXTE ECRAN: "3 ERREURS DE DÉBUTANT 🏁 (la n°2 fait mal)"

**Approche recommandée :** HYBRIDE. On ouvre sur un avatar IA talking-head (créateur générique, JAMAIS le fondateur) qui balance le hook et crée le lien humain/le rythme, puis on bascule sur du b-roll cinématique IA quad/MX pour illustrer chaque erreur, avec sous-titres punchy. Pourquoi: le format "3 erreurs" est très pédagogique — un visage qui parle installe la confiance et donne du tempo au hook, mais ce sont les plans d'action (roue qui patine à froid, doigts qui serrent le levier, manomètre sur le pneu) qui rendent chaque point concret et scrollable. L'hybride respecte les 2 contraintes créateur: aucun fondateur filmé (avatar IA générique), aucun lieu de stockage/atelier montré (décors exclusivement piste de terre / gravier extérieur / golden hour, explicitement interdits dans chaque prompt). Une version 100% faceless (VO FR + b-roll seul) est fournie en repli si le fondateur ne veut aucun visage du tout. Intégrité respectée: aucun claim de freinage/perf sur une pièce — le conseil reste du pilotage générique, le positionnement reste "on trie / on source le bon matos avec toi", jamais "on conçoit".

**Outils avatar :** Arcads · Creatify · HeyGen · Captions (AI Avatars) · Higgsfield (Speak) · Veo 3.1 (talking character)

### Prompt avatar UGC

```
Vertical 9:16 UGC talking-head, handheld phone-selfie look. A generic, likeable male content creator in his late 20s to early 30s, athletic build, short tousled brown hair, light stubble, friendly confident energy. He wears a casual fitted plain dark-grey or black t-shirt or hoodie with a subtle racing vibe — strictly NO readable logos, NO brand names, NO text on clothing. He stands outdoors at the edge of an open dirt motocross track / gravel pit at golden hour, soft warm backlight, blurred berms and tire tracks behind him with heavy bokeh (shallow depth of field) — NEVER a warehouse, NEVER shelves of parts, NEVER a garage, workshop or storage room, NEVER any interior. Chest-up framing, slight natural handheld camera movement, authentic UGC aesthetic, direct eye contact with the lens, expressive hand gestures, he counts the points on his fingers. Natural daylight, realistic skin texture, crisp 4K, shallow depth of field. He speaks directly and energetically to camera. Lip-sync to the provided French audio. Tone: passionate, direct, a real rider sharing tips — never a salesman.
```

### Script parlé FR (avatar)

> (0-2s, hook) 3 réflexes de débutant qui flinguent ton quad. Et le numéro 2, franchement, tout le monde le fait.
> (2-11s, erreur 1) Un : pleins gaz à froid. Le moteur a pas chauffé, l'huile circule pas encore — laisse-le respirer trente secondes avant d'attaquer.
> (11-22s, erreur 2 ; marquer un micro-silence de 0,3s avant 'et c'est le pire') Deux, et c'est le pire : tu serres tout au levier droit, d'un coup, brutal. Sur un quad faut doser, anticiper, répartir — sinon ça part en vrille direct.
> (22-31s, erreur 3) Trois : tu négliges la pression des pneus. Trop gonflés ça glisse, pas assez ça rippe en virage. Vérifie avant chaque session, ça change tout.
> (31-35s, CTA) Abonne-toi — on trie le bon matos ensemble, que du concret.

### Prompts B-roll (text-to-video)

**Plan 1 — Plan d'ouverture / B-roll hero (sous le hook, 0-2s)** — *3-4s* — Outils: Google Veo 3.1, OpenAI Sora 2, Higgsfield, Kling 2.x

```
Vertical 9:16 cinematic hero shot. An unbranded sport ATV quad bike ripping across an open dirt motocross track at golden hour, kicking up a long trail of backlit dust, dynamic tracking drone-style shot following from behind and slightly to the side, knobby tires gripping the berms, dramatic warm sunlight, lens flare, slow motion 60-120fps, epic energetic motocross film look, shallow depth of field, 4K. No readable logos or brand names anywhere. No human faces in focus. No garage, no warehouse, no parts shelves, no interior — outdoor dirt track only.
```

**Plan 2 — Erreur 1 : démarrage à froid / coup de gaz** — *4-6s* — Outils: Google Veo 3.1, OpenAI Sora 2, Runway Gen-4, Kling 2.x

```
Vertical 9:16 cinematic macro shot. Extreme close-up of an unbranded sport ATV quad engine and exhaust pipe at cold dawn, a thin wisp of cold morning vapor near the exhaust, dewy dirt ground. A rider's gloved hand twists the throttle grip aggressively; the rear knobby tire suddenly spins and throws a burst of dirt and gravel. Shallow depth of field, slow-motion 120fps feel, cold blue morning light with subtle golden rim light, gritty dramatic, dust particles backlit in the air. Outdoor dirt track only. No readable logos. No human faces. No shelves, no garage, no warehouse, no interior.
```

**Plan 3 — Erreur 2 : freinage brutal / dosage** — *5-7s* — Outils: OpenAI Sora 2, Google Veo 3.1, Kling 2.x, Higgsfield

```
Vertical 9:16 cinematic action shot. An unbranded sport ATV quad riding fast on a dirt motocross track kicks up dust; the rider grabs the right-hand brake lever hard and abruptly — extreme close-up of gloved fingers clamping the brake lever — then cut to the front knobby tire locking and skidding forward, the quad's nose diving down under hard braking, body weight pitching forward. Slow motion, dynamic low-angle, golden-hour dust haze, tense energy, shallow depth of field, gritty and realistic. Outdoor dirt track only. No readable logos. No human faces visible. No garage, no storage, no interior.
```

**Plan 4 — Erreur 3 : pression des pneus** — *4-6s* — Outils: Runway Gen-4, Kling 2.x, Google Veo 3.1, Luma Dream Machine

```
Vertical 9:16 cinematic detail shot. Macro close-up of a digital tire-pressure gauge being pressed onto the valve of a chunky knobby ATV tire, an unbranded sport quad parked on dirt at golden hour, a finger pressing the valve; then a quick cut to the same quad leaning hard into a dirt corner, the tire flexing and gripping, a spray of dust. Crisp product-style lighting on the gauge, warm natural backlight, shallow depth of field, premium gritty motocross aesthetic, 4K slow motion. Outdoor only. No readable logos. No faces. No shelves, no warehouse, no garage, no interior.
```

**Plan 5 — Plan de clôture / CTA** — *3-4s* — Outils: Kling 2.x, Runway Gen-4, Google Veo 3.1, Luma Dream Machine

```
Vertical 9:16 cinematic closing shot. An unbranded sport ATV quad parked side-on at the edge of a dirt track at golden hour, engine off, dust slowly settling in warm backlight, a slow cinematic dolly-in toward the machine, clean negative space at the top of the frame for an end-card text overlay. Calm, premium, satisfying mood, shallow depth of field, 4K, motocross brand aesthetic. Outdoor only. No readable logos. No people, no faces. No shelves, no storage, no warehouse, no interior.
```

### Script parlé FR (version faceless — voix off)

> (Version 100% FACELESS — narration ElevenLabs, voix française masculine naturelle, énergique, calée sur le b-roll, ~33s) Trois erreurs de débutant qui flinguent ton quad. Le numéro 2, franchement, tout le monde le fait. [b-roll hero] Erreur une : pleins gaz à froid. Le moteur a pas chauffé, l'huile circule pas encore — laisse-le respirer trente secondes avant d'attaquer. [b-roll erreur 1] Erreur deux, la pire : tu serres tout au levier droit, d'un coup, en panique. Sur un quad faut doser et anticiper, sinon ça part en vrille. [b-roll erreur 2] Erreur trois : tu négliges la pression des pneus. Trop gonflés ça glisse, pas assez ça rippe en virage. Vérifie avant chaque session. [b-roll erreur 3] Nous, on trie le bon matos avec toi, sans blabla. Abonne-toi. [b-roll clôture]

### Textes à l'écran

- 3 ERREURS DE DÉBUTANT 🏁
- (la n°2 fait mal)
- ❌ N°1 : PLEINS GAZ À FROID
- Laisse chauffer 30s ⏱️
- ❌ N°2 : FREIN BRUTAL AU LEVIER
- Dose. Anticipe. Répartis.
- ❌ N°3 : PNEUS MAL GONFLÉS
- Vérifie AVANT chaque session
- On trie le bon matos avec toi 🔧
- ABONNE-TOI 👊

### CTA

"Abonne-toi — on trie le bon matos ensemble, pas de blabla, que du concret. 👊" (overlay fin + bouton abonnement sur le plan de clôture)

### Musique / son

Musique : instru hip-hop/trap énergique ou rock électro motocross, BPM ~90-110, léger drop sur le hook et à chaque révélation d'erreur. SFX : vrombissement moteur quad sur le plan hero, crissement/dérapage sur l'erreur 2 (freinage), petit ding/woosh sur l'apparition de chaque numéro, micro-silence de 0,3s juste avant "la pire" pour le suspense. Mix : VO devant, musique -8 à -10 dB sous la voix, SFX ponctuels. Sous-titres animés style CapCut/Captions, mots-clés surlignés (jaune/rouge MX).