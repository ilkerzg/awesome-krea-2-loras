<picture>
  <source media="(prefers-color-scheme: dark)" srcset="fal-dark.png">
  <img src="fal-light.png" alt="fal" height="26">
</picture>

# Awesome Krea 2 LoRAs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of **293** style LoRAs for [Krea 2](https://huggingface.co/krea/Krea-2-Turbo), trained and served on [fal](https://fal.ai). Every entry links to a Hugging Face repo with the weights, a model card, and copy-paste fal usage.

[![Run on fal.ai](https://img.shields.io/badge/Run_on-fal.ai-FF6B35?style=flat-square)](https://fal.ai/models/fal-ai/krea-2/turbo/lora) [![Train on fal.ai](https://img.shields.io/badge/Train_on-fal.ai-FF6B35?style=flat-square)](https://fal.ai/models/fal-ai/krea-2-trainer) [![Krea 2](https://img.shields.io/badge/base-Krea_2_Turbo-7C5CFF?style=flat-square)](https://huggingface.co/krea/Krea-2-Turbo) [![HF index](https://img.shields.io/badge/%F0%9F%A4%97-Hugging_Face_index-yellow?style=flat-square)](https://huggingface.co/ilkerzgi/fal-Krea-2-Style-LoRAs)

## How to use

Pick a style, then run it on `fal-ai/krea-2/turbo/lora` with the style's **trigger added to the end** of your prompt (recommended LoRA scale `1.0`-`1.25`):

```python
import fal_client

result = fal_client.subscribe("fal-ai/krea-2/turbo/lora", arguments={
    "prompt": "a lighthouse on a rocky cliff. <trigger>",
    "loras": [{"path": "https://huggingface.co/<repo>/resolve/main/<name>.safetensors", "scale": 1.0}],
    "image_size": {"width": 1024, "height": 1280},
})
print(result["images"][0]["url"])
```

## Contents

- [3D Render](#3d-render) (18)
- [Cinematic](#cinematic) (27)
- [Drawing](#drawing) (19)
- [Graphic](#graphic) (40)
- [Illustration](#illustration) (119)
- [Painterly](#painterly) (49)
- [Photographic](#photographic) (21)

## 3D Render

| | Style | Trigger |
|:--:|---|---|
| <img src="https://v3b.fal.media/files/b/0a9f9def/S0N7VR-FWp_jd57PmabKv_QO0HOhXL.png" width="96"> | [Airy Porcelain Blue](https://huggingface.co/ilkerzgi/krea-2-airy-porcelain-blue-lora) | `airy porcelain blue style` |
| <img src="https://v3b.fal.media/files/b/0a9fcb4a/dacsCfSp7K9zIBaLaVud3_1yWURS4S.jpg" width="96"> | [Amber Ember Blue Mist](https://huggingface.co/ilkerzgi/krea-2-amber-ember-blue-mist-lora) | `amber ember blue mist style` |
| <img src="https://v3b.fal.media/files/b/0a9f9df3/4GxinBVIG0WZoR5a0jrEX_l5VobOKp.png" width="96"> | [Azure Paper Diorama](https://huggingface.co/ilkerzgi/krea-2-azure-paper-diorama-lora) | `azure paper diorama style` |
| <img src="https://v3b.fal.media/files/b/0a9fc121/HQ9j3omp3HYZT7FZngmmX_gWjlns0g.jpg" width="96"> | [Bioluminescent Voronoi Architecture](https://huggingface.co/ilkerzgi/krea-2-bioluminescent-voronoi-architecture-lora) | `bioluminescent voronoi architecture style` |
| <img src="https://v3b.fal.media/files/b/0a9fd14f/PC7gDgiVRaVBOgtf96ZBU_n4Xmusk7.jpg" width="96"> | [Blue Pink Clay Render](https://huggingface.co/ilkerzgi/krea-2-blue-pink-clay-render-lora) | `blue pink clay render style` |
| <img src="https://v3b.fal.media/files/b/0a9fcf62/z2yLYbGbBH8N_M72M74sz_9xU1qiDN.jpg" width="96"> | [Blue White Utopian Render](https://huggingface.co/ilkerzgi/krea-2-blue-white-utopian-render-lora) | `blue white utopian render style` |
| <img src="https://v3b.fal.media/files/b/0a9fcd18/pqIM1dXCmIaDxPBCUPZSP_N7PJk6aD.jpg" width="96"> | [Bold Clay Toy Render](https://huggingface.co/ilkerzgi/krea-2-bold-clay-toy-render-lora) | `bold clay toy render style` |
| <img src="https://v3b.fal.media/files/b/0a9fd186/2gSHySXnWsNbmE6sPe9Zf_qxv2TGYQ.jpg" width="96"> | [Bold Magenta Yellow Noir](https://huggingface.co/ilkerzgi/krea-2-bold-magenta-yellow-noir-lora) | `bold magenta yellow noir style` |
| <img src="https://v3b.fal.media/files/b/0a9fc269/I5D1WcCCnWuTngPcJ0WxA_Vtqp22ls.jpg" width="96"> | [Bold Stripe Pattern Render](https://huggingface.co/ilkerzgi/krea-2-bold-stripe-pattern-render-lora) | `bold stripe pattern render style` |
| <img src="https://v3b.fal.media/files/b/0a9fc13a/gELDl9o0VVGx4I9rhErKP_QkrRH8Pm.jpg" width="96"> | [Candy Harajuku Pastel Render](https://huggingface.co/ilkerzgi/krea-2-candy-harajuku-pastel-render-lora) | `candy harajuku pastel render style` |
| <img src="https://v3b.fal.media/files/b/0a9fa230/hgoI8ovPZu7CzM_JVKsBK_FpDua0xU.png" width="96"> | [Carved Ceramic Totem](https://huggingface.co/ilkerzgi/krea-2-carved-ceramic-totem-lora) | `carved ceramic totem style` |
| <img src="https://v3b.fal.media/files/b/0a9fc141/JkpqhnHMXHijJcYMztFH6_yRaGfrAW.jpg" width="96"> | [Chrome Blue Surreal](https://huggingface.co/ilkerzgi/krea-2-chrome-blue-surreal-lora) | `chrome blue surreal style` |
| <img src="https://v3b.fal.media/files/b/0a9fd016/Wvw6WDkZ49moTT9Zrpqic_Jp1TZiXV.jpg" width="96"> | [Chrome Iridescent Render](https://huggingface.co/ilkerzgi/krea-2-chrome-iridescent-render-lora) | `chrome iridescent render style` |
| <img src="https://v3b.fal.media/files/b/0a9fc276/g45yIJLQtHVq507M7BFbT_s1bnqV6q.jpg" width="96"> | [Clay Folk Miniature](https://huggingface.co/ilkerzgi/krea-2-clay-folk-miniature-lora) | `clay folk miniature style` |
| <img src="https://v3b.fal.media/files/b/0a9fd29c/fbti0V1RlrjAmRUVGrBX2_RFDClMjF.jpg" width="96"> | [Cobalt Miniature Texture](https://huggingface.co/ilkerzgi/krea-2-cobalt-miniature-texture-lora) | `cobalt miniature texture style` |
| <img src="https://v3b.fal.media/files/b/0a9fc154/rNxIgUiILr-B56SjzwkAV_gaPGoppK.jpg" width="96"> | [Cobalt White Sculptural Render](https://huggingface.co/ilkerzgi/krea-2-cobalt-white-sculptural-render-lora) | `cobalt white sculptural render style` |
| <img src="https://v3b.fal.media/files/b/0a9fcfb9/LOkowqsfcyvvzps6mWexH_WVbsg0FZ.jpg" width="96"> | [Coral Pink Midcentury Render](https://huggingface.co/ilkerzgi/krea-2-coral-pink-midcentury-render-lora) | `coral pink midcentury render style` |
| <img src="https://v3b.fal.media/files/b/0a9fcb1a/gEKgHye8jONBx7F0BornW_pGafIeTL.jpg" width="96"> | [Crimson Chrome Sculpture](https://huggingface.co/ilkerzgi/krea-2-crimson-chrome-sculpture-lora) | `crimson chrome sculpture style` |

## Cinematic

| | Style | Trigger |
|:--:|---|---|
| <img src="https://v3b.fal.media/files/b/0a9f9c87/GKdhUhuPxVY1OhPPui1tc_p2BrtnVv.png" width="96"> | [Airy Ligne Claire Scifi](https://huggingface.co/ilkerzgi/krea-2-airy-ligne-claire-scifi-lora) | `airy ligne claire scifi style` |
| <img src="https://v3b.fal.media/files/b/0a9fcba2/e84Vv-vOg2w_9IpgS38K9_XNl9FFLy.jpg" width="96"> | [Amber Fog Backlit](https://huggingface.co/ilkerzgi/krea-2-amber-fog-backlit-lora) | `amber fog backlit style` |
| <img src="https://v3b.fal.media/files/b/0a9fc121/CGOCtXOWsCYjyeX9V-qX6_PvbaWHEV.jpg" width="96"> | [Amber Fog Spotlight](https://huggingface.co/ilkerzgi/krea-2-amber-fog-spotlight-lora) | `amber fog spotlight style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0c4/RC9arsHtTbNHc9sK5ewpO_SyO4ewRy.jpg" width="96"> | [Amber Glow Dusk Architecture](https://huggingface.co/ilkerzgi/krea-2-amber-glow-dusk-architecture-lora) | `amber glow dusk architecture style` |
| <img src="https://v3b.fal.media/files/b/0a9fc887/P8jelvSLahrnV0zMTCXTc_kwKZY7lB.jpg" width="96"> | [Amber Haze Geometric Surreal](https://huggingface.co/ilkerzgi/krea-2-amber-haze-geometric-surreal-lora) | `amber haze geometric surreal style` |
| <img src="https://v3b.fal.media/files/b/0a9fca8d/1VwWXGvFV6PhNfxlSmN___dbsaUEYl.jpg" width="96"> | [Amber Haze Golden Hour](https://huggingface.co/ilkerzgi/krea-2-amber-haze-golden-hour-lora) | `amber haze golden hour style` |
| <img src="https://v3b.fal.media/files/b/0a9fcc0e/bDYIQE9zLcoZZUXbi3sBg_aUm1J06n.jpg" width="96"> | [Amber Lit Fantasy Filmset](https://huggingface.co/ilkerzgi/krea-2-amber-lit-fantasy-filmset-lora) | `amber lit fantasy filmset style` |
| <img src="https://v3b.fal.media/files/b/0a9fc80e/vpjf_-JLc9Jdr3gQM6Q0I_2eHSob7w.jpg" width="96"> | [Amber Neon Silhouette](https://huggingface.co/ilkerzgi/krea-2-amber-neon-silhouette-lora) | `amber neon silhouette style` |
| <img src="https://v3b.fal.media/files/b/0a9fcfca/1yAJ3WaEDuAo3JU2jIlp5_J7zsUgrW.jpg" width="96"> | [Amber Noir Chiaroscuro](https://huggingface.co/ilkerzgi/krea-2-amber-noir-chiaroscuro-lora) | `amber noir chiaroscuro style` |
| <img src="https://v3b.fal.media/files/b/0a9fa158/gSloCxVPSsX_mvTJ_CZLm_D9JAVkoa.png" width="96"> | [Amber Noir Contrast](https://huggingface.co/ilkerzgi/krea-2-amber-noir-contrast-lora) | `amber noir contrast style` |
| <img src="https://v3b.fal.media/files/b/0a9fc213/yD4aMkuMj_BkCiTuskxSq_XTlm5fok.jpg" width="96"> | [Analog Fantastical Surreal](https://huggingface.co/ilkerzgi/krea-2-analog-fantastical-surreal-lora) | `analog fantastical surreal style` |
| <img src="https://v3b.fal.media/files/b/0a9fc134/9TkGssFjcKqVYf1aWJuwc_DJvUGjdB.jpg" width="96"> | [Azure Surreal Collage](https://huggingface.co/ilkerzgi/krea-2-azure-surreal-collage-lora) | `azure surreal collage style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0fa/cYRIU_bmtKB5rJRYtKlIv_0piTFypI.jpg" width="96"> | [Bleached Retro Futurist](https://huggingface.co/ilkerzgi/krea-2-bleached-retro-futurist-lora) | `bleached retro futurist style` |
| <img src="https://v3b.fal.media/files/b/0a9fd009/iY2AZF4LHhulErXjBgYhX_LQ9yb9a7.jpg" width="96"> | [Bleached Surreal Uncanny](https://huggingface.co/ilkerzgi/krea-2-bleached-surreal-uncanny-lora) | `bleached surreal uncanny style` |
| <img src="https://v3b.fal.media/files/b/0a9fd15e/P8ov_uoN__2f9d4a-JgqB_tqYkeQOF.jpg" width="96"> | [Burnt Amber Silhouette](https://huggingface.co/ilkerzgi/krea-2-burnt-amber-silhouette-lora) | `burnt amber silhouette style` |
| <img src="https://v3b.fal.media/files/b/0a9fcb8d/ArlLoCOX1me7R5JfulJQ-_e0sraCxr.jpg" width="96"> | [Cold Blue Dusk Film](https://huggingface.co/ilkerzgi/krea-2-cold-blue-dusk-film-lora) | `cold blue dusk film style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0f0/fCRUPdOkwhZStG2fGdE1C_m6jrWUVu.jpg" width="96"> | [Cold Fog Surreal](https://huggingface.co/ilkerzgi/krea-2-cold-fog-surreal-lora) | `cold fog surreal style` |
| <img src="https://v3b.fal.media/files/b/0a9fc150/xNWpil-akaX1baKJRkm_L_4YKuyTBK.jpg" width="96"> | [Cool Blue Amber Bokeh](https://huggingface.co/ilkerzgi/krea-2-cool-blue-amber-bokeh-lora) | `cool blue amber bokeh style` |
| <img src="https://v3b.fal.media/files/b/0a9fa140/O385FdylOa_HCt4DX3Vdk_Rvr6VY7x.png" width="96"> | [Crimson Accent Noir](https://huggingface.co/ilkerzgi/krea-2-crimson-accent-noir-lora) | `crimson accent noir style` |
| <img src="https://v3b.fal.media/files/b/0a9f9dcb/LKEhHqtWdYfPw1cPuAQ1G_r6jKMrLG.png" width="96"> | [Crimson Circuit Noir](https://huggingface.co/ilkerzgi/krea-2-crimson-circuit-noir-lora) | `crimson circuit noir style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0f1/Z87w0WTn3_WmDadQxJth6_4xBdRj5S.jpg" width="96"> | [Crimson Indigo Nocturne](https://huggingface.co/ilkerzgi/krea-2-crimson-indigo-nocturne-lora) | `crimson indigo nocturne style` |
| <img src="https://v3b.fal.media/files/b/0a9fcd39/_FfEe-m8AmMMJYHnHBGX3_WH2YVgyG.jpg" width="96"> | [Crimson Lantern Fog](https://huggingface.co/ilkerzgi/krea-2-crimson-lantern-fog-lora) | `crimson lantern fog style` |
| <img src="https://v3b.fal.media/files/b/0a9fa223/OtBBrq0BPAZ7LOkevLU9D_RukQ92hM.png" width="96"> | [Crimson Noir Gouache](https://huggingface.co/ilkerzgi/krea-2-crimson-noir-gouache-lora) | `crimson noir gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fa211/Wnc-7qXNU21EBqKYkG_dI_KjQrtarb.png" width="96"> | [Crimson Noir Spotlight](https://huggingface.co/ilkerzgi/krea-2-crimson-noir-spotlight-lora) | `crimson noir spotlight style` |
| <img src="https://v3b.fal.media/files/b/0a9fa152/6Hing4b3NDuhsXPPbocs7_xJ8pWWHo.png" width="96"> | [Crimson Sun Noir](https://huggingface.co/ilkerzgi/krea-2-crimson-sun-noir-lora) | `crimson sun noir style` |
| <img src="https://v3b.fal.media/files/b/0a9fc84b/4r34MfArpNFTfEPpbfIEW_3vQHW3qK.jpg" width="96"> | [Crimson Void Minimalist](https://huggingface.co/ilkerzgi/krea-2-crimson-void-minimalist-lora) | `crimson void minimalist style` |
| <img src="https://v3b.fal.media/files/b/0a9fa18d/sV7spg6nx7WoBd-6pPKD8_ccGvKNjO.png" width="96"> | [Cyan Noir Inkline](https://huggingface.co/ilkerzgi/krea-2-cyan-noir-inkline-lora) | `cyan noir inkline style` |

## Drawing

| | Style | Trigger |
|:--:|---|---|
| <img src="https://v3b.fal.media/files/b/0a9f9c9c/iAp2AN5jGVJV87i1eYZps_Pfqfbg10.png" width="96"> | [Airy Blueprint Linework](https://huggingface.co/ilkerzgi/krea-2-airy-blueprint-linework-lora) | `airy blueprint linework style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1a9/hngh98yW7QG4YQcgue5Pu_Bw9CacQG.png" width="96"> | [Airy Pastel Scribble](https://huggingface.co/ilkerzgi/krea-2-airy-pastel-scribble-lora) | `airy pastel scribble style` |
| <img src="https://v3b.fal.media/files/b/0a9f9dd6/_kqVCWBp1XzuM_BPC-TVS_dctzcPA3.png" width="96"> | [Azure Inkwash Sketch](https://huggingface.co/ilkerzgi/krea-2-azure-inkwash-sketch-lora) | `azure inkwash sketch style` |
| <img src="https://v3b.fal.media/files/b/0a9fa172/6ep8asoY4HwfF8vEQCoaa_X9VaDV47.png" width="96"> | [Ballpoint Blue Crosshatch](https://huggingface.co/ilkerzgi/krea-2-ballpoint-blue-crosshatch-lora) | `ballpoint blue crosshatch style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1f7/n7khnDYAKQgzbMXUI1TuB_i4QaSChk.png" width="96"> | [Blueprint Sketch Annotation](https://huggingface.co/ilkerzgi/krea-2-blueprint-sketch-annotation-lora) | `blueprint sketch annotation style` |
| <img src="https://v3b.fal.media/files/b/0a9fa18d/KT6GaABVHiht2Fl27QteB_ryLKfobh.png" width="96"> | [Blush Inkline Storybook](https://huggingface.co/ilkerzgi/krea-2-blush-inkline-storybook-lora) | `blush inkline storybook style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0c8/kU6qpfIVa7sdwlcLUbxZB_1UsM4USQ.jpg" width="96"> | [Bold Ink Brush Sketch](https://huggingface.co/ilkerzgi/krea-2-bold-ink-brush-sketch-lora) | `bold ink brush sketch style` |
| <img src="https://v3b.fal.media/files/b/0a9fcd85/EuaUbZf0LNH5rNbicyfIO_nuAJ97ph.jpg" width="96"> | [Bold Inkwash Noir](https://huggingface.co/ilkerzgi/krea-2-bold-inkwash-noir-lora) | `bold inkwash noir style` |
| <img src="https://v3b.fal.media/files/b/0a9fa175/dKEYrxdZv-OEYkNNdkJQ2_WrOYGKC9.png" width="96"> | [Cobalt Ballpoint Sketch](https://huggingface.co/ilkerzgi/krea-2-cobalt-ballpoint-sketch-lora) | `cobalt ballpoint sketch style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0cf/VrdQk97H76GQvYy-WNXu6_yZu5i3d0.jpg" width="96"> | [Cobalt Hatched Pencil](https://huggingface.co/ilkerzgi/krea-2-cobalt-hatched-pencil-lora) | `cobalt hatched pencil style` |
| <img src="https://v3b.fal.media/files/b/0a9fd2be/s1rbdGsoevB4_uw7XH7VQ_JHxWhc4f.jpg" width="96"> | [Cobalt Linen Sketch](https://huggingface.co/ilkerzgi/krea-2-cobalt-linen-sketch-lora) | `cobalt linen sketch style` |
| <img src="https://v3b.fal.media/files/b/0a9f9ddf/TLqlDIK_H3ec6tCVLGbjQ_SxnhhWT8.png" width="96"> | [Cobalt Linework Woodcut](https://huggingface.co/ilkerzgi/krea-2-cobalt-linework-woodcut-lora) | `cobalt linework woodcut style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0e1/8NUVRnxPu26INGx0hmjBv_jWrbAUpu.jpg" width="96"> | [Crayon Scribble Childlike](https://huggingface.co/ilkerzgi/krea-2-crayon-scribble-childlike-lora) | `crayon scribble childlike style` |
| <img src="https://v3b.fal.media/files/b/0a9fd016/nWLiqsKHo26Dzt8fHQvTj_X92MnI63.jpg" width="96"> | [Cream Ground Ink Sketch](https://huggingface.co/ilkerzgi/krea-2-cream-ground-ink-sketch-lora) | `cream ground ink sketch style` |
| <img src="https://v3b.fal.media/files/b/0a9fc87b/CwIZOhzN6iwPOb2EJkhnW_IeCM8YsT.jpg" width="96"> | [Cream Ground Loose Ink](https://huggingface.co/ilkerzgi/krea-2-cream-ground-loose-ink-lora) | `cream ground loose ink style` |
| <img src="https://v3b.fal.media/files/b/0a9fa15b/rl2wg7vzWtVHVrz1zu9lc_wGbpRv1J.png" width="96"> | [Crimson Accent Charcoal](https://huggingface.co/ilkerzgi/krea-2-crimson-accent-charcoal-lora) | `crimson accent charcoal style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0ea/7VBPUZmlgEjX_c1Bc5if9_R25QCgrw.jpg" width="96"> | [Crimson Charcoal Noir](https://huggingface.co/ilkerzgi/krea-2-crimson-charcoal-noir-lora) | `crimson charcoal noir style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1ef/MZkMGCTApmVxDE03AYIrV_WiCvF8hm.png" width="96"> | [Crosshatch Sketchbook Ink](https://huggingface.co/ilkerzgi/krea-2-crosshatch-sketchbook-ink-lora) | `crosshatch sketchbook ink style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0cb/9m-KlkNHcuSMYCQa1xyVH_8SElTzRE.jpg" width="96"> | [Dark Crosshatch Surreal](https://huggingface.co/ilkerzgi/krea-2-dark-crosshatch-surreal-lora) | `dark crosshatch surreal style` |

## Graphic

| | Style | Trigger |
|:--:|---|---|
| <img src="https://v3b.fal.media/files/b/0a9fa137/s5W1vbWcQRG0WKvYnXPy4_0aZGH4pA.png" width="96"> | [Amber Geometric Collage](https://huggingface.co/ilkerzgi/krea-2-amber-geometric-collage-lora) | `amber geometric collage style` |
| <img src="https://v3b.fal.media/files/b/0a9fa162/c_-yCVx1rGKIbfou4dXmk_xO2O73zU.png" width="96"> | [Azure Pink Screenprint](https://huggingface.co/ilkerzgi/krea-2-azure-pink-screenprint-lora) | `azure pink screenprint style` |
| <img src="https://v3b.fal.media/files/b/0a9fc9da/GNvO_tYnqdaCDrdUf8W1J_Wmlx4uY1.jpg" width="96"> | [Black Grid Wireframe Spectrum](https://huggingface.co/ilkerzgi/krea-2-black-grid-wireframe-spectrum-lora) | `black grid wireframe spectrum style` |
| <img src="https://v3b.fal.media/files/b/0a9fccdb/q4q_JQTe8Q8K_FdIzIL77_aNCPns1n.jpg" width="96"> | [Blue Orange Graffiti Tag](https://huggingface.co/ilkerzgi/krea-2-blue-orange-graffiti-tag-lora) | `blue orange graffiti tag style` |
| <img src="https://v3b.fal.media/files/b/0a9fa193/vrEezxeVzUZCLIfZDCkXo_l1xSeGvk.png" width="96"> | [Blueprint Blue Concept](https://huggingface.co/ilkerzgi/krea-2-blueprint-blue-concept-lora) | `blueprint blue concept style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0ef/DvSGRcATaq_5lRyGu8lk-_YCuL8WCj.jpg" width="96"> | [Blush Pink Collage](https://huggingface.co/ilkerzgi/krea-2-blush-pink-collage-lora) | `blush pink collage style` |
| <img src="https://v3b.fal.media/files/b/0a9fcfbb/Zu_mTqoBRj6mMEpczHYS4_RHuXdW27.jpg" width="96"> | [Bold Cobalt Geometric Poster](https://huggingface.co/ilkerzgi/krea-2-bold-cobalt-geometric-poster-lora) | `bold cobalt geometric poster style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0d7/rYeJKGnw5Gw0USeNLVUzF_kghGYqMw.jpg" width="96"> | [Bold Cobalt Graphic Design](https://huggingface.co/ilkerzgi/krea-2-bold-cobalt-graphic-design-lora) | `bold cobalt graphic design style` |
| <img src="https://v3b.fal.media/files/b/0a9fa140/BSPhcgx-9_YGDaCxhcFDE_6ezaaTRr.png" width="96"> | [Bold Deco Azure](https://huggingface.co/ilkerzgi/krea-2-bold-deco-azure-lora) | `bold deco azure style` |
| <img src="https://v3b.fal.media/files/b/0a9fc13e/Y99DC8HE9OlOVZyqYgwW8_vjiweiiZ.jpg" width="96"> | [Bold Flat Sunlit Poster](https://huggingface.co/ilkerzgi/krea-2-bold-flat-sunlit-poster-lora) | `bold flat sunlit poster style` |
| <img src="https://v3b.fal.media/files/b/0a9fce21/clEvVIxzlZbu_dVX9-k03_DrShCr0S.jpg" width="96"> | [Bold Geometric Pop Mural](https://huggingface.co/ilkerzgi/krea-2-bold-geometric-pop-mural-lora) | `bold geometric pop mural style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0c3/8tXfzpZw_CUsvbT4rgCWa_8KaN0sr7.jpg" width="96"> | [Bold Green Risograph](https://huggingface.co/ilkerzgi/krea-2-bold-green-risograph-lora) | `bold green risograph style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0c6/YS7jyczFQGgq5Er_ZQaRL_KEwXKHGz.jpg" width="96"> | [Bold Halftone Popart](https://huggingface.co/ilkerzgi/krea-2-bold-halftone-popart-lora) | `bold halftone popart style` |
| <img src="https://v3b.fal.media/files/b/0a9fa236/sa__kXfvd158yXPoS6Vrj_GsosKt1h.png" width="96"> | [Bold Magenta Poster](https://huggingface.co/ilkerzgi/krea-2-bold-magenta-poster-lora) | `bold magenta poster style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1b6/dqYvnfPqg7KqxACuO9anQ_ZgfBZkpo.png" width="96"> | [Bold Orange Poster](https://huggingface.co/ilkerzgi/krea-2-bold-orange-poster-lora) | `bold orange poster style` |
| <img src="https://v3b.fal.media/files/b/0a9fd2ab/SRvCQETM4eg_F8Xgg4TJs_cG4qc5LH.jpg" width="96"> | [Bold Red Blue Screenprint](https://huggingface.co/ilkerzgi/krea-2-bold-red-blue-screenprint-lora) | `bold red blue screenprint style` |
| <img src="https://v3b.fal.media/files/b/0a9fa185/zdu5WdGaDaNs5Wf6K7Cne_yntD23Ic.png" width="96"> | [Bold Scarlet Screenprint](https://huggingface.co/ilkerzgi/krea-2-bold-scarlet-screenprint-lora) | `bold scarlet screenprint style` |
| <img src="https://v3b.fal.media/files/b/0a9fc13c/EsE9j_u7IKaik2REwKsoW_DkCeiTag.jpg" width="96"> | [Bold Spiral Linework](https://huggingface.co/ilkerzgi/krea-2-bold-spiral-linework-lora) | `bold spiral linework style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0fb/gE0ACQWNNaC_x-LpUW3UJ_20kHJSas.jpg" width="96"> | [Bold Striped Monochrome Red](https://huggingface.co/ilkerzgi/krea-2-bold-striped-monochrome-red-lora) | `bold striped monochrome red style` |
| <img src="https://v3b.fal.media/files/b/0a9fca28/5REgsE4GRx47rCtRhSsOf_Wi2ntcpG.jpg" width="96"> | [Bold Woodblock Print](https://huggingface.co/ilkerzgi/krea-2-bold-woodblock-print-lora) | `bold woodblock print style` |
| <img src="https://v3b.fal.media/files/b/0a9fc1de/VVDr1gUi_qpWQ-ADwtKB8_EIej30Dt.jpg" width="96"> | [Bold Woodcut Linocut](https://huggingface.co/ilkerzgi/krea-2-bold-woodcut-linocut-lora) | `bold woodcut linocut style` |
| <img src="https://v3b.fal.media/files/b/0a9fcc7f/d92mSfCO9ThhIP2qcZMrd_gNTAJXxs.jpg" width="96"> | [Chromatic Aura Gradient](https://huggingface.co/ilkerzgi/krea-2-chromatic-aura-gradient-lora) | `chromatic aura gradient style` |
| <img src="https://v3b.fal.media/files/b/0a9fcdae/V6fuBZedvLydFRjc8ZsKr_okI2yKkM.jpg" width="96"> | [Chromatic Glitch Anaglyph](https://huggingface.co/ilkerzgi/krea-2-chromatic-glitch-anaglyph-lora) | `chromatic glitch anaglyph style` |
| <img src="https://v3b.fal.media/files/b/0a9fc899/1pKH-6TTitdURBS7mSoBS_gbADZjgm.jpg" width="96"> | [Chunky Beaded Totem](https://huggingface.co/ilkerzgi/krea-2-chunky-beaded-totem-lora) | `chunky beaded totem style` |
| <img src="https://v3b.fal.media/files/b/0a9fc281/7tKRiGDwV3AQfexYe5tN2_PBABnUyz.jpg" width="96"> | [Clean Geometric Pop](https://huggingface.co/ilkerzgi/krea-2-clean-geometric-pop-lora) | `clean geometric pop style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1dd/x6-lCV8AuE0Vux8krkJsH_AIh5SfXt.png" width="96"> | [Cobalt Blueprint Collage](https://huggingface.co/ilkerzgi/krea-2-cobalt-blueprint-collage-lora) | `cobalt blueprint collage style` |
| <img src="https://v3b.fal.media/files/b/0a9fa21c/uNA9hyqMaBZ87PoQYrxQf_7MdltgEe.png" width="96"> | [Cobalt Halftone Riso](https://huggingface.co/ilkerzgi/krea-2-cobalt-halftone-riso-lora) | `cobalt halftone riso style` |
| <img src="https://v3b.fal.media/files/b/0a9fa148/RbwZmKFK9wG1PvxmSLL_R_S95lbF5l.png" width="96"> | [Cobalt Orange Collage](https://huggingface.co/ilkerzgi/krea-2-cobalt-orange-collage-lora) | `cobalt orange collage style` |
| <img src="https://v3b.fal.media/files/b/0a9fc1d5/iKm-iR-Y1nnBe700ccj1A_Y46FBFkF.jpg" width="96"> | [Cobalt Red Woodblock](https://huggingface.co/ilkerzgi/krea-2-cobalt-red-woodblock-lora) | `cobalt red woodblock style` |
| <img src="https://v3b.fal.media/files/b/0a9fa146/QBXpvXvLVqlE3k2NPaEjc_CW286147.png" width="96"> | [Cobalt Stipple Print](https://huggingface.co/ilkerzgi/krea-2-cobalt-stipple-print-lora) | `cobalt stipple print style` |
| <img src="https://v3b.fal.media/files/b/0a9fc146/bmNFX--w5pVm-XIxW2NJ2_i3L0Z3t0.jpg" width="96"> | [Cobalt Stripe Op Art](https://huggingface.co/ilkerzgi/krea-2-cobalt-stripe-op-art-lora) | `cobalt stripe op art style` |
| <img src="https://v3b.fal.media/files/b/0a9fc10d/YR2ZGs8ogOHfHPloZdRAc_QCgVjTQv.jpg" width="96"> | [Cobalt Woodblock Geometric](https://huggingface.co/ilkerzgi/krea-2-cobalt-woodblock-geometric-lora) | `cobalt woodblock geometric style` |
| <img src="https://v3b.fal.media/files/b/0a9fcd55/o1URyupdtsCV3IRk1IZxB_riOdYCOr.jpg" width="96"> | [Cobalt Yellow Papercut](https://huggingface.co/ilkerzgi/krea-2-cobalt-yellow-papercut-lora) | `cobalt yellow papercut style` |
| <img src="https://v3b.fal.media/files/b/0a9fd15e/b6vqP-OBIuxo2j40WZPq__GCRbwCDW.jpg" width="96"> | [Collaged Deep Teal Surreal](https://huggingface.co/ilkerzgi/krea-2-collaged-deep-teal-surreal-lora) | `collaged deep teal surreal style` |
| <img src="https://v3b.fal.media/files/b/0a9fa21a/yU8K4xIzFVqUECrCTiFGu_yzgtpXD3.png" width="96"> | [Crayon Riso Print](https://huggingface.co/ilkerzgi/krea-2-crayon-riso-print-lora) | `crayon riso print style` |
| <img src="https://v3b.fal.media/files/b/0a9fa147/O-vj5U0O1lTTPD-6g1nJr_dhVvhJFu.png" width="96"> | [Crimson Geometric Monochrome](https://huggingface.co/ilkerzgi/krea-2-crimson-geometric-monochrome-lora) | `crimson geometric monochrome style` |
| <img src="https://v3b.fal.media/files/b/0a9fc1fd/jbHZ2_B6U2AGUX49qqqC__PAjQ5d67.jpg" width="96"> | [Crimson Noir Papercut](https://huggingface.co/ilkerzgi/krea-2-crimson-noir-papercut-lora) | `crimson noir papercut style` |
| <img src="https://v3b.fal.media/files/b/0a9fca1b/Aq5ZzdqudbMkDUo2xF4yL_TRxOxbOS.jpg" width="96"> | [Crimson Orb Silhouette](https://huggingface.co/ilkerzgi/krea-2-crimson-orb-silhouette-lora) | `crimson orb silhouette style` |
| <img src="https://v3b.fal.media/files/b/0a9fa196/eherED11u2k1fFWLwSiaP_qsJkV91s.png" width="96"> | [Crimson Screenprint Poster](https://huggingface.co/ilkerzgi/krea-2-crimson-screenprint-poster-lora) | `crimson screenprint poster style` |
| <img src="https://v3b.fal.media/files/b/0a9fce84/yzotHpCGKZlDm_hOM4o3K_alCXyYjV.jpg" width="96"> | [Cyan Saturated Surreal Collage](https://huggingface.co/ilkerzgi/krea-2-cyan-saturated-surreal-collage-lora) | `cyan saturated surreal collage style` |

## Illustration

| | Style | Trigger |
|:--:|---|---|
| <img src="https://v3b.fal.media/files/b/0a9fc244/DjIgyCSj88CIFG-nJO7He_gidujaO2.jpg" width="96"> | [Acid Horror Manga](https://huggingface.co/ilkerzgi/krea-2-acid-horror-manga-lora) | `acid horror manga style` |
| <img src="https://v3b.fal.media/files/b/0a9fc90e/VrjSDtJ2disRyNPEb5kQo_hsmnQx9Q.jpg" width="96"> | [Airy Anime Watercolor](https://huggingface.co/ilkerzgi/krea-2-airy-anime-watercolor-lora) | `airy anime watercolor style` |
| <img src="https://v3b.fal.media/files/b/0a9fcf28/98lURoPfx6uumCjVcUYkx_zBgrw9Kk.jpg" width="96"> | [Airy Blush Painterly](https://huggingface.co/ilkerzgi/krea-2-airy-blush-painterly-lora) | `airy blush painterly style` |
| <img src="https://v3b.fal.media/files/b/0a9fc10b/33dFCd3Ph8XoOZU-bmEo5_07OYDrqE.jpg" width="96"> | [Airy Gouache Minimalist](https://huggingface.co/ilkerzgi/krea-2-airy-gouache-minimalist-lora) | `airy gouache minimalist style` |
| <img src="https://v3b.fal.media/files/b/0a9fa213/GTc5PacShLPhfRMDJo_bl_1gUDerqP.png" width="96"> | [Airy Minimal Monochrome](https://huggingface.co/ilkerzgi/krea-2-airy-minimal-monochrome-lora) | `airy minimal monochrome style` |
| <img src="https://v3b.fal.media/files/b/0a9fce71/ZhZUGXCwMXZbRyUn-CEkp_q6Cxxpoh.jpg" width="96"> | [Airy Watercolor Chibi](https://huggingface.co/ilkerzgi/krea-2-airy-watercolor-chibi-lora) | `airy watercolor chibi style` |
| <img src="https://v3b.fal.media/files/b/0a9fa13d/dDmt10X7MUWtNIGpCgwBd_4PL0bxBc.png" width="96"> | [Amber Dusk Anime](https://huggingface.co/ilkerzgi/krea-2-amber-dusk-anime-lora) | `amber dusk anime style` |
| <img src="https://v3b.fal.media/files/b/0a9fc265/v7NpPHKIZo87EV3R_R84f_Ot932CYM.jpg" width="96"> | [Amber Glow Deep Blue](https://huggingface.co/ilkerzgi/krea-2-amber-glow-deep-blue-lora) | `amber glow deep blue style` |
| <img src="https://v3b.fal.media/files/b/0a9fa20a/DW4tYGDcgxnyH7yl3WLPJ_eYo1Jo4W.png" width="96"> | [Amber Selective Contrast](https://huggingface.co/ilkerzgi/krea-2-amber-selective-contrast-lora) | `amber selective contrast style` |
| <img src="https://v3b.fal.media/files/b/0a9fd127/zzrTRYjiec-hkJgBxjsU6_96ueVbbQ.jpg" width="96"> | [Amber Silhouette Gothic](https://huggingface.co/ilkerzgi/krea-2-amber-silhouette-gothic-lora) | `amber silhouette gothic style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0bc/bsxRWBYw-U-XGclnwuP_g_6vyqggjY.jpg" width="96"> | [Amber Teal Urban Decay](https://huggingface.co/ilkerzgi/krea-2-amber-teal-urban-decay-lora) | `amber teal urban decay style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1e4/B3SCCJBcsqZmgzR_K5EV-_YQzAVfmN.png" width="96"> | [Amber Techno Concept](https://huggingface.co/ilkerzgi/krea-2-amber-techno-concept-lora) | `amber techno concept style` |
| <img src="https://v3b.fal.media/files/b/0a9fa161/Gv8MLSPbKsz9YQbUMpL2g_r4PIA7vF.png" width="96"> | [Azure Cel Shaded](https://huggingface.co/ilkerzgi/krea-2-azure-cel-shaded-lora) | `azure cel shaded style` |
| <img src="https://v3b.fal.media/files/b/0a9fa206/3Tz0svYPPl-43h00NtC48_fo1fTg4z.png" width="96"> | [Azure Folk Tableau](https://huggingface.co/ilkerzgi/krea-2-azure-folk-tableau-lora) | `azure folk tableau style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1fa/pcKfDlHZBPMIkqgmG3RDp_NKVvHDP8.png" width="96"> | [Azure Retrofuture Comic](https://huggingface.co/ilkerzgi/krea-2-azure-retrofuture-comic-lora) | `azure retrofuture comic style` |
| <img src="https://v3b.fal.media/files/b/0a9fa171/plNDT_oJM8DbQORPMF9eJ_VjngmWM2.png" width="96"> | [Azure Sunlit Storybook](https://huggingface.co/ilkerzgi/krea-2-azure-sunlit-storybook-lora) | `azure sunlit storybook style` |
| <img src="https://v3b.fal.media/files/b/0a9f9c9c/isEcgVB66meVzNXwjDM1n_rBLV1xEj.png" width="96"> | [Azure Tangerine Daydream](https://huggingface.co/ilkerzgi/krea-2-azure-tangerine-daydream-lora) | `azure tangerine daydream style` |
| <img src="https://v3b.fal.media/files/b/0a9fa15a/KZa8pD6RS1klTMk1sgQ-P_HiuGmrAs.png" width="96"> | [Blazing Backlit Ember](https://huggingface.co/ilkerzgi/krea-2-blazing-backlit-ember-lora) | `blazing backlit ember style` |
| <img src="https://v3b.fal.media/files/b/0a9fa22a/PMroHsn1kjpJ6IQndGtG1_G5bQGRmr.png" width="96"> | [Blue Dreamlike Surreal](https://huggingface.co/ilkerzgi/krea-2-blue-dreamlike-surreal-lora) | `blue dreamlike surreal style` |
| <img src="https://v3b.fal.media/files/b/0a9fc269/Ym3S89GwIkFLrTk3OClSW_v33i8rf2.jpg" width="96"> | [Blue Nouveau Ornate](https://huggingface.co/ilkerzgi/krea-2-blue-nouveau-ornate-lora) | `blue nouveau ornate style` |
| <img src="https://v3b.fal.media/files/b/0a9fcd83/jDDYpAb8-1NXxjICAz4QF_4ne4RuqR.jpg" width="96"> | [Blue Ochre Crayon](https://huggingface.co/ilkerzgi/krea-2-blue-ochre-crayon-lora) | `blue ochre crayon style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1b4/XRoTQhsRcAXTphoILYIw-_wtR3R0dC.png" width="96"> | [Blurred Sepia Silhouette](https://huggingface.co/ilkerzgi/krea-2-blurred-sepia-silhouette-lora) | `blurred sepia silhouette style` |
| <img src="https://v3b.fal.media/files/b/0a9fa203/dnhi82JUwQVZYiDYwN9HE_pXEzRiaO.png" width="96"> | [Blush Petal Bokeh](https://huggingface.co/ilkerzgi/krea-2-blush-petal-bokeh-lora) | `blush petal bokeh style` |
| <img src="https://v3b.fal.media/files/b/0a9fd272/8KOEHZP8c8ZtaK-Ylv5mQ_ne3uAXrR.jpg" width="96"> | [Blush Watercolor Cottage](https://huggingface.co/ilkerzgi/krea-2-blush-watercolor-cottage-lora) | `blush watercolor cottage style` |
| <img src="https://v3b.fal.media/files/b/0a9fccdb/WBKarCC8lbjGX9WX9r-KI_PnsONxC5.jpg" width="96"> | [Bold Brushy Kidlit](https://huggingface.co/ilkerzgi/krea-2-bold-brushy-kidlit-lora) | `bold brushy kidlit style` |
| <img src="https://v3b.fal.media/files/b/0a9fd1b0/pBQrAgEzFtSxP1vYcAo6V_h9PMXohx.jpg" width="96"> | [Bold Crayon Folk](https://huggingface.co/ilkerzgi/krea-2-bold-crayon-folk-lora) | `bold crayon folk style` |
| <img src="https://v3b.fal.media/files/b/0a9fa140/kvuXOjhjYPlm9AKqJ9oPH_cQcjx2vw.png" width="96"> | [Bold Crimson Toon](https://huggingface.co/ilkerzgi/krea-2-bold-crimson-toon-lora) | `bold crimson toon style` |
| <img src="https://v3b.fal.media/files/b/0a9fc11f/zJ5upQpieYyWeq64G_TDm_6eLVxgV4.jpg" width="96"> | [Bold Doodle Monster](https://huggingface.co/ilkerzgi/krea-2-bold-doodle-monster-lora) | `bold doodle monster style` |
| <img src="https://v3b.fal.media/files/b/0a9f9df2/m-vmlcTRa8Soejuxt-KRh_tS6fTIAp.png" width="96"> | [Bold Flash Tattoo](https://huggingface.co/ilkerzgi/krea-2-bold-flash-tattoo-lora) | `bold flash tattoo style` |
| <img src="https://v3b.fal.media/files/b/0a9fa225/hH61MRNAuhq3k-1Vu_z_-_PgOArlCh.png" width="96"> | [Bold Flat Color Block](https://huggingface.co/ilkerzgi/krea-2-bold-flat-color-block-lora) | `bold flat color block style` |
| <img src="https://v3b.fal.media/files/b/0a9fcc90/a_oO3KetSaeERVxelfUIO_yQuqW2ru.jpg" width="96"> | [Bold Flatcolor Cartoon](https://huggingface.co/ilkerzgi/krea-2-bold-flatcolor-cartoon-lora) | `bold flatcolor cartoon style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0b2/OXotlP2rKs6VVAwkxsev4_TaqxPFTi.jpg" width="96"> | [Bold Flatline Whimsy](https://huggingface.co/ilkerzgi/krea-2-bold-flatline-whimsy-lora) | `bold flatline whimsy style` |
| <img src="https://v3b.fal.media/files/b/0a9fd1fa/5v9jHBbopBYrfILBrt9gH_NgsnfqrK.jpg" width="96"> | [Bold Gouache Collage](https://huggingface.co/ilkerzgi/krea-2-bold-gouache-collage-lora) | `bold gouache collage style` |
| <img src="https://v3b.fal.media/files/b/0a9fd184/YZssd8R43xid17JQjbfxF_pDcApjO6.jpg" width="96"> | [Bold Gouache Folk](https://huggingface.co/ilkerzgi/krea-2-bold-gouache-folk-lora) | `bold gouache folk style` |
| <img src="https://v3b.fal.media/files/b/0a9fc124/Kn725Pji-CaYvTgL3GDxK_IXBpzKxG.jpg" width="96"> | [Bold Grainy Gouache](https://huggingface.co/ilkerzgi/krea-2-bold-grainy-gouache-lora) | `bold grainy gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fd1be/n7XcZFhTk52itk9kjsdhY_ILiRDRxc.jpg" width="96"> | [Bold Green Yellow Flat](https://huggingface.co/ilkerzgi/krea-2-bold-green-yellow-flat-lora) | `bold green yellow flat style` |
| <img src="https://v3b.fal.media/files/b/0a9fccea/PmsvFPLhEyy54yN7Us2Jt_6oBLbuW7.jpg" width="96"> | [Bold Inked Anime Realism](https://huggingface.co/ilkerzgi/krea-2-bold-inked-anime-realism-lora) | `bold inked anime realism style` |
| <img src="https://v3b.fal.media/files/b/0a9fc893/ZQA2kQ4CdYKusWuTGrmz7_4gi3dkrJ.jpg" width="96"> | [Bold Inked Superhero Comic](https://huggingface.co/ilkerzgi/krea-2-bold-inked-superhero-comic-lora) | `bold inked superhero comic style` |
| <img src="https://v3b.fal.media/files/b/0a9fc117/jX9fwrAZkh8iiolmB0tjC_WKQd08RI.jpg" width="96"> | [Bold Neon Gouache](https://huggingface.co/ilkerzgi/krea-2-bold-neon-gouache-lora) | `bold neon gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fc966/ay3BxO_3xve-kl3B5bsay_qo483C8z.jpg" width="96"> | [Bold Pink Yellow Ink](https://huggingface.co/ilkerzgi/krea-2-bold-pink-yellow-ink-lora) | `bold pink yellow ink style` |
| <img src="https://v3b.fal.media/files/b/0a9f9db9/QF14KjF5DmQYJM8vOjXNw_wp7a9vGY.png" width="96"> | [Bold Pop Comic](https://huggingface.co/ilkerzgi/krea-2-bold-pop-comic-lora) | `bold pop comic style` |
| <img src="https://v3b.fal.media/files/b/0a9fa204/VzT4z79s1eRPLaDSB4leb_dU5MsBw0.png" width="96"> | [Bold Pop Comic](https://huggingface.co/ilkerzgi/krea-2-bold-pop-comic-lora) | `bold pop comic style` |
| <img src="https://v3b.fal.media/files/b/0a9fa178/1dHZ_unxLXv119tvc3egR_DM6wyqLp.png" width="96"> | [Bold Pop Graphic](https://huggingface.co/ilkerzgi/krea-2-bold-pop-graphic-lora) | `bold pop graphic style` |
| <img src="https://v3b.fal.media/files/b/0a9fcbbe/eUvfMCgudpot8qoCm1_Gu_DeAdHqKs.jpg" width="96"> | [Bold Primary Marker](https://huggingface.co/ilkerzgi/krea-2-bold-primary-marker-lora) | `bold primary marker style` |
| <img src="https://v3b.fal.media/files/b/0a9fcf78/jrFVG7w1kz9syOnDb4ZtC_qmVsle8C.jpg" width="96"> | [Bold Primary Sketch](https://huggingface.co/ilkerzgi/krea-2-bold-primary-sketch-lora) | `bold primary sketch style` |
| <img src="https://v3b.fal.media/files/b/0a9fc227/KLrHEDKxtPoXqkXG2tyaP_k7O4B1Nq.jpg" width="96"> | [Bold Red Blue Anime](https://huggingface.co/ilkerzgi/krea-2-bold-red-blue-anime-lora) | `bold red blue anime style` |
| <img src="https://v3b.fal.media/files/b/0a9fce8a/J0D6U8WcJTFPE1cQ7KeAF_haRY45Js.jpg" width="96"> | [Bold Red Flat Korean](https://huggingface.co/ilkerzgi/krea-2-bold-red-flat-korean-lora) | `bold red flat korean style` |
| <img src="https://v3b.fal.media/files/b/0a9fd2ab/L3GPtp6QITsUOcPfQeX9D_wDvEZZjO.jpg" width="96"> | [Bold Retro Airbrush](https://huggingface.co/ilkerzgi/krea-2-bold-retro-airbrush-lora) | `bold retro airbrush style` |
| <img src="https://v3b.fal.media/files/b/0a9fc14b/S4e_F9hJul1D9lQYBhOiS_TKXEFtN9.jpg" width="96"> | [Bold Vintage Woodblock](https://huggingface.co/ilkerzgi/krea-2-bold-vintage-woodblock-lora) | `bold vintage woodblock style` |
| <img src="https://v3b.fal.media/files/b/0a9fc976/9ZzqwF-1NFJN6PrRjobXN_vyGqMOcI.jpg" width="96"> | [Botanical Gouache Miniature](https://huggingface.co/ilkerzgi/krea-2-botanical-gouache-miniature-lora) | `botanical gouache miniature style` |
| <img src="https://v3b.fal.media/files/b/0a9fc91c/ZZxnGFQ4qENyy1dMAWN1p_LBD06x3s.jpg" width="96"> | [Bright Blue Gouache](https://huggingface.co/ilkerzgi/krea-2-bright-blue-gouache-lora) | `bright blue gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fa157/ibENZ_BLwFrvVoWkHgH5p_8tMxLNDB.png" width="96"> | [Bright Crayon Storybook](https://huggingface.co/ilkerzgi/krea-2-bright-crayon-storybook-lora) | `bright crayon storybook style` |
| <img src="https://v3b.fal.media/files/b/0a9fc830/E7mBOu3F4hoeRHVZ1EpE8_24dh1wbx.jpg" width="96"> | [Bright Inkwash Urban Sketch](https://huggingface.co/ilkerzgi/krea-2-bright-inkwash-urban-sketch-lora) | `bright inkwash urban sketch style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0a7/8Aw1lEy08_qo_BhO10asM_EjWUhJDj.jpg" width="96"> | [Bright Kawaii Flatcolor](https://huggingface.co/ilkerzgi/krea-2-bright-kawaii-flatcolor-lora) | `bright kawaii flatcolor style` |
| <img src="https://v3b.fal.media/files/b/0a9fce35/-xZMyJWdVnzFmNdBZFfeu_wNBGyT2a.jpg" width="96"> | [Brushy Emerald Terracotta](https://huggingface.co/ilkerzgi/krea-2-brushy-emerald-terracotta-lora) | `brushy emerald terracotta style` |
| <img src="https://v3b.fal.media/files/b/0a9fc107/zkp0ZVJNRRYCc3kGnPmeF_tJJESGUn.jpg" width="96"> | [Brushy Pink Gouache](https://huggingface.co/ilkerzgi/krea-2-brushy-pink-gouache-lora) | `brushy pink gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1ba/Xg7kdiJyzrB93AjYSUEcD_A8KU9q0L.png" width="96"> | [Bubblegum Pop Sticker](https://huggingface.co/ilkerzgi/krea-2-bubblegum-pop-sticker-lora) | `bubblegum pop sticker style` |
| <img src="https://v3b.fal.media/files/b/0a9fc242/A4DrkhO8Ou7PvcLbJIscS_umIlNLZF.jpg" width="96"> | [Candy Gouache Flat](https://huggingface.co/ilkerzgi/krea-2-candy-gouache-flat-lora) | `candy gouache flat style` |
| <img src="https://v3b.fal.media/files/b/0a9fc140/Mg9t-ZQs0O9wor3XC9zT3_NVjodH7c.jpg" width="96"> | [Candy Gradient Lofi](https://huggingface.co/ilkerzgi/krea-2-candy-gradient-lofi-lora) | `candy gradient lofi style` |
| <img src="https://v3b.fal.media/files/b/0a9fa152/rozWE_2mO4to2fy62Rqcl_XvBrBfIb.png" width="96"> | [Candy Pop Psychedelic](https://huggingface.co/ilkerzgi/krea-2-candy-pop-psychedelic-lora) | `candy pop psychedelic style` |
| <img src="https://v3b.fal.media/files/b/0a9fc259/k_WwboO-IW5t-RV5mb4Ne_8RWubgMI.jpg" width="96"> | [Cel Shaded Daytime Anime](https://huggingface.co/ilkerzgi/krea-2-cel-shaded-daytime-anime-lora) | `cel shaded daytime anime style` |
| <img src="https://v3b.fal.media/files/b/0a9fc212/j6BMP3U6Cx5Sjy28ZZPaN_1QoM2Z9H.jpg" width="96"> | [Cerulean Open Sky](https://huggingface.co/ilkerzgi/krea-2-cerulean-open-sky-lora) | `cerulean open sky style` |
| <img src="https://v3b.fal.media/files/b/0a9fc24c/c-DKl92uC_GedAVznxo_L_TfVUImlz.jpg" width="96"> | [Chalky Blue Doodle](https://huggingface.co/ilkerzgi/krea-2-chalky-blue-doodle-lora) | `chalky blue doodle style` |
| <img src="https://v3b.fal.media/files/b/0a9fcc05/NRcNiDo4KtqZJMVWDiG5D_Z679Jlch.jpg" width="96"> | [Chalky Gouache Botanical](https://huggingface.co/ilkerzgi/krea-2-chalky-gouache-botanical-lora) | `chalky gouache botanical style` |
| <img src="https://v3b.fal.media/files/b/0a9f9df5/ObTAF_R61u98B8hnZh1kZ_61wo35Py.png" width="96"> | [Cheerful Confetti Picturebook](https://huggingface.co/ilkerzgi/krea-2-cheerful-confetti-picturebook-lora) | `cheerful confetti picturebook style` |
| <img src="https://v3b.fal.media/files/b/0a9fce08/eIrwIUOxAdFg_r7B9T6cz_IJ6ANUoV.jpg" width="96"> | [Chibi Watercolor Pastel Anime](https://huggingface.co/ilkerzgi/krea-2-chibi-watercolor-pastel-anime-lora) | `chibi watercolor pastel anime style` |
| <img src="https://v3b.fal.media/files/b/0a9fcec9/eZbNKiEygZqlVkrOMppXR_RTDZfm7Q.jpg" width="96"> | [Chinese Ink Linen Scroll](https://huggingface.co/ilkerzgi/krea-2-chinese-ink-linen-scroll-lora) | `chinese ink linen scroll style` |
| <img src="https://v3b.fal.media/files/b/0a9fc9c4/S2V9C9E0KkBfZRDQ9Oqbg_ph0kFRA3.jpg" width="96"> | [Chrome Amber Airbrush](https://huggingface.co/ilkerzgi/krea-2-chrome-amber-airbrush-lora) | `chrome amber airbrush style` |
| <img src="https://v3b.fal.media/files/b/0a9f9dd0/RgQUEIs9c6i5fd-_e8EcW_6iDKLbA5.png" width="96"> | [Chrome Cobalt Enamel](https://huggingface.co/ilkerzgi/krea-2-chrome-cobalt-enamel-lora) | `chrome cobalt enamel style` |
| <img src="https://v3b.fal.media/files/b/0a9fc8f0/fywq__hJtgQEELMBqV-_7_nyTtjCNT.jpg" width="96"> | [Chrome Cobalt Retro Futurist](https://huggingface.co/ilkerzgi/krea-2-chrome-cobalt-retro-futurist-lora) | `chrome cobalt retro futurist style` |
| <img src="https://v3b.fal.media/files/b/0a9fa14c/CmJTmtqPeXoHzAQlrldhc_fDIFw5sb.png" width="96"> | [Chrome Iridescent Vaporwave](https://huggingface.co/ilkerzgi/krea-2-chrome-iridescent-vaporwave-lora) | `chrome iridescent vaporwave style` |
| <img src="https://v3b.fal.media/files/b/0a9fd303/XN4CX7YjAWfNQPiec2NuA_DTd6nDwU.jpg" width="96"> | [Chunky Crayon Kidlit](https://huggingface.co/ilkerzgi/krea-2-chunky-crayon-kidlit-lora) | `chunky crayon kidlit style` |
| <img src="https://v3b.fal.media/files/b/0a9fc8c0/Mp-3nSoHHR-SYPDlsrF4Z_GxqHr2XN.jpg" width="96"> | [Chunky Crayon Naive](https://huggingface.co/ilkerzgi/krea-2-chunky-crayon-naive-lora) | `chunky crayon naive style` |
| <img src="https://v3b.fal.media/files/b/0a9fc868/kY87HsAmWRRUQ7j06lihj_7Kzq4a4Y.jpg" width="96"> | [Chunky Risograph Doodle](https://huggingface.co/ilkerzgi/krea-2-chunky-risograph-doodle-lora) | `chunky risograph doodle style` |
| <img src="https://v3b.fal.media/files/b/0a9fd160/2CtOttFsHQa1RKktSENCO_qXa85bGi.jpg" width="96"> | [Clean White Ground Illustration](https://huggingface.co/ilkerzgi/krea-2-clean-white-ground-illustration-lora) | `clean white ground illustration style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0bf/uFW9b7TZy5ZT0rBPggw8U_pdSv2l1z.jpg" width="96"> | [Cobalt Anime Gouache](https://huggingface.co/ilkerzgi/krea-2-cobalt-anime-gouache-lora) | `cobalt anime gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fd235/HwB7Pug8c_eWDEsJaCjSy_A7Wh4joo.jpg" width="96"> | [Cobalt Blue Linework](https://huggingface.co/ilkerzgi/krea-2-cobalt-blue-linework-lora) | `cobalt blue linework style` |
| <img src="https://v3b.fal.media/files/b/0a9fd0db/2hbmuRBhczWckds3TrDts_OhD0aW4D.jpg" width="96"> | [Cobalt Blue Whimsy](https://huggingface.co/ilkerzgi/krea-2-cobalt-blue-whimsy-lora) | `cobalt blue whimsy style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0a6/sXZwsi0kyDolqAo0uonri_1f48H5hP.jpg" width="96"> | [Cobalt Crayon Picturebook](https://huggingface.co/ilkerzgi/krea-2-cobalt-crayon-picturebook-lora) | `cobalt crayon picturebook style` |
| <img src="https://v3b.fal.media/files/b/0a9fa193/kMw_6wEqLAo2vjjaZ6Y2X_5bitzbOV.png" width="96"> | [Cobalt Dotted Craft](https://huggingface.co/ilkerzgi/krea-2-cobalt-dotted-craft-lora) | `cobalt dotted craft style` |
| <img src="https://v3b.fal.media/files/b/0a9fc269/cyYJkYJVa4AY6tc-lpj8b_aMNhPtOg.jpg" width="96"> | [Cobalt Dotted Hatching](https://huggingface.co/ilkerzgi/krea-2-cobalt-dotted-hatching-lora) | `cobalt dotted hatching style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1c6/oRGWswjnBK0i2qVIChdIZ_64dDLHCA.png" width="96"> | [Cobalt Engraved Glitch](https://huggingface.co/ilkerzgi/krea-2-cobalt-engraved-glitch-lora) | `cobalt engraved glitch style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0eb/NL-EiWVLsaVtf73Nqf9Ko_E7BsbNZH.jpg" width="96"> | [Cobalt Flat Graphic](https://huggingface.co/ilkerzgi/krea-2-cobalt-flat-graphic-lora) | `cobalt flat graphic style` |
| <img src="https://v3b.fal.media/files/b/0a9fc11d/90TCN-dl-sqeZJoZSMVGm_ZnbO54QJ.jpg" width="96"> | [Cobalt Gouache Summer](https://huggingface.co/ilkerzgi/krea-2-cobalt-gouache-summer-lora) | `cobalt gouache summer style` |
| <img src="https://v3b.fal.media/files/b/0a9fd121/3RAtvUj3laFG1H48X-pTt_CUIQQqoj.jpg" width="96"> | [Cobalt Ink Whimsy](https://huggingface.co/ilkerzgi/krea-2-cobalt-ink-whimsy-lora) | `cobalt ink whimsy style` |
| <img src="https://v3b.fal.media/files/b/0a9fc137/Q-icXy_AK6WnM0PQCEq0J_0JmgP8jY.jpg" width="96"> | [Cobalt Marker Sketch](https://huggingface.co/ilkerzgi/krea-2-cobalt-marker-sketch-lora) | `cobalt marker sketch style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0ff/h85gxtNyK7qt3DKiPuo_A_2n3l5Zuo.jpg" width="96"> | [Cobalt Sky Anime](https://huggingface.co/ilkerzgi/krea-2-cobalt-sky-anime-lora) | `cobalt sky anime style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1df/slofgvsjTiD5myDmoSh_f_Ggjwb9Ux.png" width="96"> | [Cobalt Stippled Dreamscape](https://huggingface.co/ilkerzgi/krea-2-cobalt-stippled-dreamscape-lora) | `cobalt stippled dreamscape style` |
| <img src="https://v3b.fal.media/files/b/0a9fc12b/MyM1iIiV6fnGDmWdq3UJq_bqEt0Ax3.jpg" width="96"> | [Cobalt Terracotta Risograph](https://huggingface.co/ilkerzgi/krea-2-cobalt-terracotta-risograph-lora) | `cobalt terracotta risograph style` |
| <img src="https://v3b.fal.media/files/b/0a9fc28a/wuinGl2UdhJ_Vo0s9EaM8_jJdGkd9N.jpg" width="96"> | [Cobalt Vermillion Dreamscape](https://huggingface.co/ilkerzgi/krea-2-cobalt-vermillion-dreamscape-lora) | `cobalt vermillion dreamscape style` |
| <img src="https://v3b.fal.media/files/b/0a9fa19b/2gBHgIAv2zhlE9vl_rra7_Y3U8ZbTa.png" width="96"> | [Coral Azure Retrofuturist](https://huggingface.co/ilkerzgi/krea-2-coral-azure-retrofuturist-lora) | `coral azure retrofuturist style` |
| <img src="https://v3b.fal.media/files/b/0a9fc24e/N8tWFzim9iVfJtwFWqaNf_fsEHMrrS.jpg" width="96"> | [Coral Blue Dreamlike](https://huggingface.co/ilkerzgi/krea-2-coral-blue-dreamlike-lora) | `coral blue dreamlike style` |
| <img src="https://v3b.fal.media/files/b/0a9fcca0/UL2_uTxhHeUbDc3ISbm2Q_upFgqZVr.jpg" width="96"> | [Coral Horror Inkprint](https://huggingface.co/ilkerzgi/krea-2-coral-horror-inkprint-lora) | `coral horror inkprint style` |
| <img src="https://v3b.fal.media/files/b/0a9fcea0/wbJR7clS6ec7Z-a_Trz41_FsXTpHfe.jpg" width="96"> | [Coral Navy Woodblock Folk](https://huggingface.co/ilkerzgi/krea-2-coral-navy-woodblock-folk-lora) | `coral navy woodblock folk style` |
| <img src="https://v3b.fal.media/files/b/0a9fcf10/WU3l1rAGNIX-1RF6YQeA6_JAGrSgcH.jpg" width="96"> | [Coral Surreal Flatland](https://huggingface.co/ilkerzgi/krea-2-coral-surreal-flatland-lora) | `coral surreal flatland style` |
| <img src="https://v3b.fal.media/files/b/0a9f9ca1/1pma1J8uVi8b3T8uc0TTi_kqasFhhi.png" width="96"> | [Cosmic Botanical Dreamscape](https://huggingface.co/ilkerzgi/krea-2-cosmic-botanical-dreamscape-lora) | `cosmic botanical dreamscape style` |
| <img src="https://v3b.fal.media/files/b/0a9fa222/rVQcalHXdVVBkhXMbk6jU_Zg9awoz2.png" width="96"> | [Cosmic Crimson Nightglow](https://huggingface.co/ilkerzgi/krea-2-cosmic-crimson-nightglow-lora) | `cosmic crimson nightglow style` |
| <img src="https://v3b.fal.media/files/b/0a9fa153/hAc16rlEjJ2DNW2TBjFOI_htWzsNFX.png" width="96"> | [Cosmic Prismatic Dreamscape](https://huggingface.co/ilkerzgi/krea-2-cosmic-prismatic-dreamscape-lora) | `cosmic prismatic dreamscape style` |
| <img src="https://v3b.fal.media/files/b/0a9fce4b/TTehWKVcB3sl5WBtmj8KM_RiWRdGfx.jpg" width="96"> | [Cozy Nocturnal Folk](https://huggingface.co/ilkerzgi/krea-2-cozy-nocturnal-folk-lora) | `cozy nocturnal folk style` |
| <img src="https://v3b.fal.media/files/b/0a9fcf60/hbdOKDooiZuLr1j22Ht3W_9GxsJOBl.jpg" width="96"> | [Crayon Dotted Folk](https://huggingface.co/ilkerzgi/krea-2-crayon-dotted-folk-lora) | `crayon dotted folk style` |
| <img src="https://v3b.fal.media/files/b/0a9fc122/WZBm8194mnJ3aRf-B0hw5_dt6RI7uZ.jpg" width="96"> | [Crayon Sketch Warm](https://huggingface.co/ilkerzgi/krea-2-crayon-sketch-warm-lora) | `crayon sketch warm style` |
| <img src="https://v3b.fal.media/files/b/0a9fcc4c/EY4MSpRzty_0PYHx8_KBU_meyVto79.jpg" width="96"> | [Crayon Textured Whimsy](https://huggingface.co/ilkerzgi/krea-2-crayon-textured-whimsy-lora) | `crayon textured whimsy style` |
| <img src="https://v3b.fal.media/files/b/0a9fa189/1uI8NB0Ej1xae8z5hs3yB_AmMSFop2.png" width="96"> | [Crimson Accent Monochrome](https://huggingface.co/ilkerzgi/krea-2-crimson-accent-monochrome-lora) | `crimson accent monochrome style` |
| <img src="https://v3b.fal.media/files/b/0a9fc115/h0TOLY3EFdUZxRK5wmfOQ_5lFpRVjE.jpg" width="96"> | [Crimson Blue Duotone](https://huggingface.co/ilkerzgi/krea-2-crimson-blue-duotone-lora) | `crimson blue duotone style` |
| <img src="https://v3b.fal.media/files/b/0a9fd1fa/5ATDcADeB9AHV81X7dgeP_GFoORjkg.jpg" width="96"> | [Crimson Blue Inkline Fantasy](https://huggingface.co/ilkerzgi/krea-2-crimson-blue-inkline-fantasy-lora) | `crimson blue inkline fantasy style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1cd/XR8lmHbU9RT6apr5YC-qA_Z83Kzkwx.png" width="96"> | [Crimson Bokeh Glow](https://huggingface.co/ilkerzgi/krea-2-crimson-bokeh-glow-lora) | `crimson bokeh glow style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1d1/mM5RM1tmKkOPVcWOTOTtV_XZOkZ0af.png" width="96"> | [Crimson Dusk Silhouette](https://huggingface.co/ilkerzgi/krea-2-crimson-dusk-silhouette-lora) | `crimson dusk silhouette style` |
| <img src="https://v3b.fal.media/files/b/0a9fcebb/DlCjeq9y9kbmZU_pvBZJY_5UyTqLxk.jpg" width="96"> | [Crimson Ember Linework](https://huggingface.co/ilkerzgi/krea-2-crimson-ember-linework-lora) | `crimson ember linework style` |
| <img src="https://v3b.fal.media/files/b/0a9fa18a/jtPZLVLoJxfGCPi1K0Ikb_2JcV5Iyg.png" width="96"> | [Crimson Glitch Datamosh](https://huggingface.co/ilkerzgi/krea-2-crimson-glitch-datamosh-lora) | `crimson glitch datamosh style` |
| <img src="https://v3b.fal.media/files/b/0a9fc265/KHhzeeBhVh_5J4gTkwFVr_QpJE6IbK.jpg" width="96"> | [Crimson Gold Woodblock](https://huggingface.co/ilkerzgi/krea-2-crimson-gold-woodblock-lora) | `crimson gold woodblock style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1c5/oguMwcYVZ2Dn13zP8sJkI_AxfQ8sEy.png" width="96"> | [Crimson Gothic Glow](https://huggingface.co/ilkerzgi/krea-2-crimson-gothic-glow-lora) | `crimson gothic glow style` |
| <img src="https://v3b.fal.media/files/b/0a9fd256/bM5IwfGABKUB_Kc7FPNr1_wVXhWudj.jpg" width="96"> | [Crimson Green Noir](https://huggingface.co/ilkerzgi/krea-2-crimson-green-noir-lora) | `crimson green noir style` |
| <img src="https://v3b.fal.media/files/b/0a9f9ded/Sh-6XjWwj9Q86wAO2Cx_t_d5KdplBf.png" width="96"> | [Crimson Infrared Dreamscape](https://huggingface.co/ilkerzgi/krea-2-crimson-infrared-dreamscape-lora) | `crimson infrared dreamscape style` |
| <img src="https://v3b.fal.media/files/b/0a9fcedb/5iBB4lxwYh4-VK5b2lXd7_wCQPdCJo.jpg" width="96"> | [Crimson Midnight Inkline](https://huggingface.co/ilkerzgi/krea-2-crimson-midnight-inkline-lora) | `crimson midnight inkline style` |
| <img src="https://v3b.fal.media/files/b/0a9fa18e/dcfxoY_aSDpJMHX0ss7Wc_Ntf8yMKy.png" width="96"> | [Crimson Navy Folk](https://huggingface.co/ilkerzgi/krea-2-crimson-navy-folk-lora) | `crimson navy folk style` |
| <img src="https://v3b.fal.media/files/b/0a9fd271/kHEHDQLQpfBlfrmSZYRwB_qW7sdrgz.jpg" width="96"> | [Crimson Teal Inkline](https://huggingface.co/ilkerzgi/krea-2-crimson-teal-inkline-lora) | `crimson teal inkline style` |
| <img src="https://v3b.fal.media/files/b/0a9fa22e/ZNO7yTcw8f50MkdSY8uzX_vYYc9S1q.png" width="96"> | [Crimson Woodcut Reverie](https://huggingface.co/ilkerzgi/krea-2-crimson-woodcut-reverie-lora) | `crimson woodcut reverie style` |
| <img src="https://v3b.fal.media/files/b/0a9fcd27/vXBqcl4x6lxNpAGBrDDMz_mPwMUXvy.jpg" width="96"> | [Crisp Inkwash Concept](https://huggingface.co/ilkerzgi/krea-2-crisp-inkwash-concept-lora) | `crisp inkwash concept style` |
| <img src="https://v3b.fal.media/files/b/0a9fc1fd/AntHilnSomyO_jzSTig-3_fWYt1juk.jpg" width="96"> | [Dark Ember Glow](https://huggingface.co/ilkerzgi/krea-2-dark-ember-glow-lora) | `dark ember glow style` |

## Painterly

| | Style | Trigger |
|:--:|---|---|
| <img src="https://v3b.fal.media/files/b/0a9f9c87/lrhw1fnJht1zT9vqI21ee_MUu1BiFf.png" width="96"> | [Aged Tempera Fable](https://huggingface.co/ilkerzgi/krea-2-aged-tempera-fable-lora) | `aged tempera fable style` |
| <img src="https://v3b.fal.media/files/b/0a9fca7e/VXWVcnhNfXxHvGhzP99xj_bavfd0zo.jpg" width="96"> | [Airy Brushstroke Azure](https://huggingface.co/ilkerzgi/krea-2-airy-brushstroke-azure-lora) | `airy brushstroke azure style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1d1/iGZu_nEkuEg2_ar-ZfLpb_ksqYXBYw.png" width="96"> | [Airy Mediterranean Pastel](https://huggingface.co/ilkerzgi/krea-2-airy-mediterranean-pastel-lora) | `airy mediterranean pastel style` |
| <img src="https://v3b.fal.media/files/b/0a9f9cb9/MDBfVB4EM9JO15v7Lq37__k3T9P67r.png" width="96"> | [Airy Watercolor Calm](https://huggingface.co/ilkerzgi/krea-2-airy-watercolor-calm-lora) | `airy watercolor calm style` |
| <img src="https://v3b.fal.media/files/b/0a9fa13a/ZM77lVtXyhhNae4u8GIcq_AFZUkHGA.png" width="96"> | [Amber Ink Mist](https://huggingface.co/ilkerzgi/krea-2-amber-ink-mist-lora) | `amber ink mist style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1f7/QUvNaag8_D16LSH9LVICS_eE0OPBIe.png" width="96"> | [Azure Gouache Daylight](https://huggingface.co/ilkerzgi/krea-2-azure-gouache-daylight-lora) | `azure gouache daylight style` |
| <img src="https://v3b.fal.media/files/b/0a9f9dc0/QOYQBVcLxHXZCvurtWnvk_can0y4wx.png" width="96"> | [Azure Manga Bloom](https://huggingface.co/ilkerzgi/krea-2-azure-manga-bloom-lora) | `azure manga bloom style` |
| <img src="https://v3b.fal.media/files/b/0a9f9ccf/FuBuaC9ACfR5Y3U78no-x_FrlY8DN6.png" width="96"> | [Baroque Dreamscape Oil](https://huggingface.co/ilkerzgi/krea-2-baroque-dreamscape-oil-lora) | `baroque dreamscape oil style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1bd/xTPigoc4dPp9QpaioXkPX_RoP8UR7V.png" width="96"> | [Black Ink Linocut](https://huggingface.co/ilkerzgi/krea-2-black-ink-linocut-lora) | `black ink linocut style` |
| <img src="https://v3b.fal.media/files/b/0a9fd142/dtkWk84RBsNnFXhplSNTG_VVrS0YvN.jpg" width="96"> | [Bleached Pastel Dreamscape](https://huggingface.co/ilkerzgi/krea-2-bleached-pastel-dreamscape-lora) | `bleached pastel dreamscape style` |
| <img src="https://v3b.fal.media/files/b/0a9fc806/Cuzf34ChYj87j6guNf6uM_NrMrNPEw.jpg" width="96"> | [Blue Red Grainy Haze](https://huggingface.co/ilkerzgi/krea-2-blue-red-grainy-haze-lora) | `blue red grainy haze style` |
| <img src="https://v3b.fal.media/files/b/0a9fa233/frM4VO2Klx2vO5aWOx0t9_iHKtPepj.png" width="96"> | [Blush Pastel Storybook](https://huggingface.co/ilkerzgi/krea-2-blush-pastel-storybook-lora) | `blush pastel storybook style` |
| <img src="https://v3b.fal.media/files/b/0a9fc1d1/OYnW6eAAjWvxc3HiXb52P_ypUB5End.jpg" width="96"> | [Bold Gouache Urban Sketch](https://huggingface.co/ilkerzgi/krea-2-bold-gouache-urban-sketch-lora) | `bold gouache urban sketch style` |
| <img src="https://v3b.fal.media/files/b/0a9fc22b/8J3fEj7Gtpv7mb9rueZut_TfGYmeeG.jpg" width="96"> | [Bold Impasto Retro](https://huggingface.co/ilkerzgi/krea-2-bold-impasto-retro-lora) | `bold impasto retro style` |
| <img src="https://v3b.fal.media/files/b/0a9fc881/rOCL_z3thP-RX0qnZ6Gd7_2EaNaijD.jpg" width="96"> | [Bold Impasto Sunlit](https://huggingface.co/ilkerzgi/krea-2-bold-impasto-sunlit-lora) | `bold impasto sunlit style` |
| <img src="https://v3b.fal.media/files/b/0a9fa24a/7BBpyDY2LOJC1nh4HA4Cv_BuDFHRkV.png" width="96"> | [Bold Inkbrush Silhouette](https://huggingface.co/ilkerzgi/krea-2-bold-inkbrush-silhouette-lora) | `bold inkbrush silhouette style` |
| <img src="https://v3b.fal.media/files/b/0a9fc13f/Ytq2OxozZzenBjkJTpbY1_aty3g43Y.jpg" width="96"> | [Bold Mediterranean Gouache](https://huggingface.co/ilkerzgi/krea-2-bold-mediterranean-gouache-lora) | `bold mediterranean gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1ab/jgAYVSlwit5LclNB62saS_D9kQf2Ws.png" width="96"> | [Bold Pink Pop Gouache](https://huggingface.co/ilkerzgi/krea-2-bold-pink-pop-gouache-lora) | `bold pink pop gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fa172/qmnyiIvSNefl9z-eQ45PL_nj9EFu9N.png" width="96"> | [Bold Primary Gouache](https://huggingface.co/ilkerzgi/krea-2-bold-primary-gouache-lora) | `bold primary gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fa13d/y6Fp_yOP2VXsLtWxDDGbS_cEsQK5Or.png" width="96"> | [Bold Riviera Gouache](https://huggingface.co/ilkerzgi/krea-2-bold-riviera-gouache-lora) | `bold riviera gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0e4/Ktmih8IWKdp8wVbXOMk1U_dLPfeuTh.jpg" width="96"> | [Bold Teal Yellow Plein](https://huggingface.co/ilkerzgi/krea-2-bold-teal-yellow-plein-lora) | `bold teal yellow plein style` |
| <img src="https://v3b.fal.media/files/b/0a9f9dcb/8y6MF_zv_0zPh41YjHlh1_x3Klnn91.png" width="96"> | [Botanical Teal Gouache](https://huggingface.co/ilkerzgi/krea-2-botanical-teal-gouache-lora) | `botanical teal gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fa200/rNB-7BXYb8HpY2ZZG8ae2_v1vsclXy.png" width="96"> | [Breezy Azure Impasto](https://huggingface.co/ilkerzgi/krea-2-breezy-azure-impasto-lora) | `breezy azure impasto style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1ba/VvkFRMXIFXIcsJZ4Kfgvl_FP6B7PrM.png" width="96"> | [Bright Candy Pastel](https://huggingface.co/ilkerzgi/krea-2-bright-candy-pastel-lora) | `bright candy pastel style` |
| <img src="https://v3b.fal.media/files/b/0a9fc9cc/RRKi2j3GJnH6lAQgOK--l_0QEJEmjN.jpg" width="96"> | [Bright Palette Knife](https://huggingface.co/ilkerzgi/krea-2-bright-palette-knife-lora) | `bright palette knife style` |
| <img src="https://v3b.fal.media/files/b/0a9f9cc6/KJItt79dcuizJJHdg8JQe_9SaE6Y7G.png" width="96"> | [Chrome Airbrush Retrofuture](https://huggingface.co/ilkerzgi/krea-2-chrome-airbrush-retrofuture-lora) | `chrome airbrush retrofuture style` |
| <img src="https://v3b.fal.media/files/b/0a9fd05b/f1KLE3IM7VeuNL_MvYsj8_6B6Jh2sI.jpg" width="96"> | [Chunky Impasto Pink Teal](https://huggingface.co/ilkerzgi/krea-2-chunky-impasto-pink-teal-lora) | `chunky impasto pink teal style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0ba/u2jBOc2V3LF4Ybyf32To2_mixhoRiM.jpg" width="96"> | [Cobalt Green Hyperreal Fashion](https://huggingface.co/ilkerzgi/krea-2-cobalt-green-hyperreal-fashion-lora) | `cobalt green hyperreal fashion style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1b7/n9DzIJcXgH6Y7gsjd24zm_nZneCN1P.png" width="96"> | [Cobalt Ink Dispersion](https://huggingface.co/ilkerzgi/krea-2-cobalt-ink-dispersion-lora) | `cobalt ink dispersion style` |
| <img src="https://v3b.fal.media/files/b/0a9fce62/CjUsPg07NfF8NOR_9to6q_4vtDwR5A.jpg" width="96"> | [Cobalt Magenta Dreamscape](https://huggingface.co/ilkerzgi/krea-2-cobalt-magenta-dreamscape-lora) | `cobalt magenta dreamscape style` |
| <img src="https://v3b.fal.media/files/b/0a9fd08f/pNj94Cz2H7S0OcKo0PC3Y_hhLErLRn.jpg" width="96"> | [Cobalt Nightglow Lantern](https://huggingface.co/ilkerzgi/krea-2-cobalt-nightglow-lantern-lora) | `cobalt nightglow lantern style` |
| <img src="https://v3b.fal.media/files/b/0a9fc153/jLYvBVNoUzU-CFUJXgThR_v7cQJris.jpg" width="96"> | [Cobalt Pink Gouache](https://huggingface.co/ilkerzgi/krea-2-cobalt-pink-gouache-lora) | `cobalt pink gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0f7/gSwUgE9W0PKz_YYhw5rj__jqkmqB65.jpg" width="96"> | [Cobalt Retro Realist](https://huggingface.co/ilkerzgi/krea-2-cobalt-retro-realist-lora) | `cobalt retro realist style` |
| <img src="https://v3b.fal.media/files/b/0a9fc1f1/6eLKIK9CFYslC4kSbnNI2_7TaDVKa4.jpg" width="96"> | [Coral Fauve Brushstroke](https://huggingface.co/ilkerzgi/krea-2-coral-fauve-brushstroke-lora) | `coral fauve brushstroke style` |
| <img src="https://v3b.fal.media/files/b/0a9fceae/pLMRPWSZL9H4fhQdRBuuz_X5MlLb8v.jpg" width="96"> | [Coral Mint Dreamscape](https://huggingface.co/ilkerzgi/krea-2-coral-mint-dreamscape-lora) | `coral mint dreamscape style` |
| <img src="https://v3b.fal.media/files/b/0a9f9ca2/OrPDn6xczCYfrpfrOl9Tx_Fyq7Rt9B.png" width="96"> | [Cozy Storybook Gouache](https://huggingface.co/ilkerzgi/krea-2-cozy-storybook-gouache-lora) | `cozy storybook gouache style` |
| <img src="https://v3b.fal.media/files/b/0a9f9dd9/ZX8QqO7NvjRuUvelCJsTc_PrWO3xPb.png" width="96"> | [Crimson Accent Inkwash](https://huggingface.co/ilkerzgi/krea-2-crimson-accent-inkwash-lora) | `crimson accent inkwash style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1fa/Tk2iXCIp_SZjFCgASUHxt_h9wWrRmz.png" width="96"> | [Crimson Block Inkwash](https://huggingface.co/ilkerzgi/krea-2-crimson-block-inkwash-lora) | `crimson block inkwash style` |
| <img src="https://v3b.fal.media/files/b/0a9fd227/egP-UYpAl9Dzqj3MSEjZ9_545WlINC.jpg" width="96"> | [Crimson Dark Victorian Oil](https://huggingface.co/ilkerzgi/krea-2-crimson-dark-victorian-oil-lora) | `crimson dark victorian oil style` |
| <img src="https://v3b.fal.media/files/b/0a9fd04c/FM5_9Q_WT7c9YbwOUOJh3_TEm9Qjf8.jpg" width="96"> | [Crimson Gold Leaf](https://huggingface.co/ilkerzgi/krea-2-crimson-gold-leaf-lora) | `crimson gold leaf style` |
| <img src="https://v3b.fal.media/files/b/0a9fa1d4/Qpsnj0OULt2Tp_iD3_iAs_osJH53N2.png" width="96"> | [Crimson Grotesque Oilpaint](https://huggingface.co/ilkerzgi/krea-2-crimson-grotesque-oilpaint-lora) | `crimson grotesque oilpaint style` |
| <img src="https://v3b.fal.media/files/b/0a9f9cca/EfNzM1jypnKsTf-PYDTQB_HQyw6KKA.png" width="96"> | [Crimson Ink Macabre](https://huggingface.co/ilkerzgi/krea-2-crimson-ink-macabre-lora) | `crimson ink macabre style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0b7/_LHw9YZzKcJDwddsZ5ecC_XusjdbcO.jpg" width="96"> | [Crimson Noir Drip](https://huggingface.co/ilkerzgi/krea-2-crimson-noir-drip-lora) | `crimson noir drip style` |
| <img src="https://v3b.fal.media/files/b/0a9f9de5/lQsOB5nLtnpPgQ1ozxeLR_ZFg0P8aV.png" width="96"> | [Crimson Silkscreen Ink](https://huggingface.co/ilkerzgi/krea-2-crimson-silkscreen-ink-lora) | `crimson silkscreen ink style` |
| <img src="https://v3b.fal.media/files/b/0a9fce82/rsd51nVvQgbShKb7VZvgi_383Jp5H8.jpg" width="96"> | [Crimson Violet Glow](https://huggingface.co/ilkerzgi/krea-2-crimson-violet-glow-lora) | `crimson violet glow style` |
| <img src="https://v3b.fal.media/files/b/0a9fcf7f/_Yw5bp4TbrtKKBf_9weI2_glI60NhJ.jpg" width="96"> | [Cyan Monochrome Dreamscape](https://huggingface.co/ilkerzgi/krea-2-cyan-monochrome-dreamscape-lora) | `cyan monochrome dreamscape style` |
| <img src="https://v3b.fal.media/files/b/0a9fa239/MC73xro8aNSrmLn45Ly6Z_aWGZ5D7I.png" width="96"> | [Cyan Violet Ink Splash](https://huggingface.co/ilkerzgi/krea-2-cyan-violet-ink-splash-lora) | `cyan violet ink splash style` |
| <img src="https://v3b.fal.media/files/b/0a9fd1cd/31K-aVN3Epzmaqh2kBA40_nABXTkRu.jpg" width="96"> | [Dark Academic Oil Portrait](https://huggingface.co/ilkerzgi/krea-2-dark-academic-oil-portrait-lora) | `dark academic oil portrait style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0a9/sjUnBV608UjN0fWHeTXYr_9s50YFDX.jpg" width="96"> | [Dark Chiaroscuro Nocturne](https://huggingface.co/ilkerzgi/krea-2-dark-chiaroscuro-nocturne-lora) | `dark chiaroscuro nocturne style` |

## Photographic

| | Style | Trigger |
|:--:|---|---|
| <img src="https://v3b.fal.media/files/b/0a9fc87e/qCP1wjRmcctVnuKp9uxnf_aoGvqJF9.jpg" width="96"> | [Aged Fresco Decay](https://huggingface.co/ilkerzgi/krea-2-aged-fresco-decay-lora) | `aged fresco decay style` |
| <img src="https://v3b.fal.media/files/b/0a9fce16/ofQ6vAVfDSA0R50kbFrsJ_gusN2Asm.jpg" width="96"> | [Aged Wetplate Monochrome](https://huggingface.co/ilkerzgi/krea-2-aged-wetplate-monochrome-lora) | `aged wetplate monochrome style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0d8/3vxRdv2IJHCa4Tcu2khRK_BuiQct72.jpg" width="96"> | [Airy Film Pastel](https://huggingface.co/ilkerzgi/krea-2-airy-film-pastel-lora) | `airy film pastel style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0a5/TYckufehp3VavWxBkUjEb_HShJsYb2.jpg" width="96"> | [Amber Backlit Lens Flare](https://huggingface.co/ilkerzgi/krea-2-amber-backlit-lens-flare-lora) | `amber backlit lens flare style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0aa/dTCo6hhn424WRdo8tW98G_HpScuTkj.jpg" width="96"> | [Amber Grain Nocturnal](https://huggingface.co/ilkerzgi/krea-2-amber-grain-nocturnal-lora) | `amber grain nocturnal style` |
| <img src="https://v3b.fal.media/files/b/0a9fc210/dawHr1AjnGZY5k8Xwgin-_gKhvTRDp.jpg" width="96"> | [Amber Motion Streak](https://huggingface.co/ilkerzgi/krea-2-amber-motion-streak-lora) | `amber motion streak style` |
| <img src="https://v3b.fal.media/files/b/0a9fc24e/Fh9A0IydBEGFkvuAxpuRI_6Se76Zuh.jpg" width="96"> | [Ashen Fog Surreal](https://huggingface.co/ilkerzgi/krea-2-ashen-fog-surreal-lora) | `ashen fog surreal style` |
| <img src="https://v3b.fal.media/files/b/0a9fc9f9/DWBznlDOBD0ERCVLix5PG_x2AVCgRp.jpg" width="96"> | [Bleak Monochrome Urban Melancholy](https://huggingface.co/ilkerzgi/krea-2-bleak-monochrome-urban-melancholy-lora) | `bleak monochrome urban melancholy style` |
| <img src="https://v3b.fal.media/files/b/0a9fc2a8/bTxC-L198NwKo_0tt8pIx_nfRC0wSC.jpg" width="96"> | [Blue Fog Amber Glow](https://huggingface.co/ilkerzgi/krea-2-blue-fog-amber-glow-lora) | `blue fog amber glow style` |
| <img src="https://v3b.fal.media/files/b/0a9fcb6a/VWWZqY_8jidGxKyGwVOyF_uaTJdRrw.jpg" width="96"> | [Blurred Teal Chromatic Glow](https://huggingface.co/ilkerzgi/krea-2-blurred-teal-chromatic-glow-lora) | `blurred teal chromatic glow style` |
| <img src="https://v3b.fal.media/files/b/0a9fc13e/AjvVm_4XQc5_9aASZKtj5_xhJELvN7.jpg" width="96"> | [Bold Orange Geometric Shadow](https://huggingface.co/ilkerzgi/krea-2-bold-orange-geometric-shadow-lora) | `bold orange geometric shadow style` |
| <img src="https://v3b.fal.media/files/b/0a9fcf9e/afjVNY1Oi8tRXDTsaMWLW_M6Hy78RS.jpg" width="96"> | [Burnt Orange Motion Blur](https://huggingface.co/ilkerzgi/krea-2-burnt-orange-motion-blur-lora) | `burnt orange motion blur style` |
| <img src="https://v3b.fal.media/files/b/0a9fc1cd/D9HMAobfpPiVMRoKNjWfT_I65A2IIV.jpg" width="96"> | [Chromatic Glitch Thermal](https://huggingface.co/ilkerzgi/krea-2-chromatic-glitch-thermal-lora) | `chromatic glitch thermal style` |
| <img src="https://v3b.fal.media/files/b/0a9fc9e8/cq5Q690cqesS3p5k1iBpD_JodoQG5u.jpg" width="96"> | [Cold Blue Fog](https://huggingface.co/ilkerzgi/krea-2-cold-blue-fog-lora) | `cold blue fog style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0c2/w2yT62dDxhw8T05V4N3aY_yL4od28A.jpg" width="96"> | [Cool Blue Film Grain](https://huggingface.co/ilkerzgi/krea-2-cool-blue-film-grain-lora) | `cool blue film grain style` |
| <img src="https://v3b.fal.media/files/b/0a9fce33/DpzYKaoEuNUIoLZAmEjKA_hfizidCe.jpg" width="96"> | [Cool Bokeh Dusk](https://huggingface.co/ilkerzgi/krea-2-cool-bokeh-dusk-lora) | `cool bokeh dusk style` |
| <img src="https://v3b.fal.media/files/b/0a9fcb4b/Wozyg53Lb-lr8_YcqzSri_5JNmUXIO.jpg" width="96"> | [Crimson Fog Dreamscape](https://huggingface.co/ilkerzgi/krea-2-crimson-fog-dreamscape-lora) | `crimson fog dreamscape style` |
| <img src="https://v3b.fal.media/files/b/0a9fd0f9/eVjqGzqlUdH0C5xaHMFnb_Xlqh8S8m.jpg" width="96"> | [Cyan Amber Slide Film](https://huggingface.co/ilkerzgi/krea-2-cyan-amber-slide-film-lora) | `cyan amber slide film style` |
| <img src="https://v3b.fal.media/files/b/0a9fca9a/FoSzJo6zFXtMo8imhbCi0_BZZCtIxi.jpg" width="96"> | [Cyan Fog Orange Surreal](https://huggingface.co/ilkerzgi/krea-2-cyan-fog-orange-surreal-lora) | `cyan fog orange surreal style` |
| <img src="https://v3b.fal.media/files/b/0a9fd0f9/GZS5XqxaH_ZujmRTV0Iou_cfCGvQQW.jpg" width="96"> | [Cyan Red Motion Blur](https://huggingface.co/ilkerzgi/krea-2-cyan-red-motion-blur-lora) | `cyan red motion blur style` |
| <img src="https://v3b.fal.media/files/b/0a9fc0aa/hzQsLNfg9PlRABGFjwj_h_2ih8OOEs.jpg" width="96"> | [Cyan Yellow Duochrome](https://huggingface.co/ilkerzgi/krea-2-cyan-yellow-duochrome-lora) | `cyan yellow duochrome style` |

## License

The LoRA weights are licensed under the [Krea 2 Community License](https://huggingface.co/krea/Krea-2-LoRA-impressionist/blob/main/LICENSE.pdf). This list is released under [CC0](https://creativecommons.org/publicdomain/zero/1.0/). Built on Krea 2, trained and served on [fal](https://fal.ai).
