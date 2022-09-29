---
theme: ./
---

# slidev-theme-teal

XX XX


---

# あのイーハトーヴォのすきとおった風
> 夏でも底に冷たさをもつ青いそら、うつくしい森で飾られたモリーオ市、郊外のぎらぎらひかる草の波。 またそのなかでいっしょになったたくさんのひとたち、ファゼーロとロザーロ、羊飼のミーロや、顔の赤いこどもたち、地主のテーモ、山猫博士のボーガント・デストゥパーゴなど、いまこの暗い巨きな石の建物のなかで考えていると、みんなむかし風のなつかしい青い幻燈のように思われます。では、わたくしはいつかの小さなみだしをつけながら、しずかにあの年のイーハトーヴォの五月から十月までを書きつけましょう。

<div class="absolute bottom-10">
<Ref
  n="1"
  content="
Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A., Kaiser, ., & Polosukhin, I. (2017). Attention is all you need. Advances in neural information processing systems, 30.
"
  url="https://arxiv.org/pdf/1706.03762.pdf"
/>
<Ref
  n="2"
  content="
Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A., Kaiser, ., & Polosukhin, I. (2017). Attention is all you need. Advances in neural information processing systems, 30.
"
  url="https://arxiv.org/pdf/1706.03762.pdf"
/>
</div>

---

# PKE
## Model
$\Pi = (\mathrm{Gen}, \mathrm{Enc}, \mathrm{Dec})$

- keygen: $(\mathrm{pk}, \mathrm{sk}) \gets \mathrm{Gen}(1^{\kappa})$
- enc: $m \in \mathcal{M}, c \gets \mathrm{Enc}_{\mathrm{pk}}(m)$
- dec: $c \in \mathcal{C}, m' \mid \bot \gets \mathrm{Dec}_{\mathrm{sk}}(c)$

## Correctness
$$
\mathrm{Dec}_{\mathrm{sk}}(\mathrm{Enc}_{\mathrm{pk}}(m)) = m
$$

---

# Code

`Rust`: A language empowering everyone to build reliable and efficient software.

```rust
use anyhow::Result;

fn main() -> Result<()> {
    let mut a = 2;
    match a {
        2 => println!("{}", 3),
        _ => panic!()
    };
    Ok(())
}
```

---

# 化物語
## 概要
『化物語』は21世紀初頭で日本の田舎町を舞台に高校生の阿良々木暦が「怪異（かいい）」に関わった少女達と出会い、その怪異にまつわる事件を解決していく物語。

> 「助けるんじゃない。君が勝手に助かるんだ。ボクは力を貸すだけだ」

## 後日談というか今回のオチ

<div class="flex">
<div class="flex-1">

刃の下に心あり。彼女(図1)らしい、いい名前だろう？苗字は僕のをそのまま流用させてもらった。

</div>

<div class="flex-1">
  <div class="w-40 mx-auto">
    <Fig n="1" title="忍野忍" src="https://i.gyazo.com/891661286b491b5844e901f1fea9974e.png" />
  </div>
</div>

</div>

---

# H1
## h2
あのイーハトーヴォのすきとおった風、夏でも底に冷たさをもつ青いそら、うつくしい森で飾られたモリーオ市、郊外のぎらぎらひかる草の波。 またそのなかでいっしょになったたくさんのひとたち、ファゼーロとロザーロ、羊飼のミーロや、顔の赤いこどもたち、地主のテーモ、山猫博士のボーガント・デストゥパーゴなど、いまこの暗い巨きな石の建物のなかで考えていると、みんなむかし風のなつかしい青い幻燈のように思われます。では、わたくしはいつかの小さなみだしをつけながら、しずかにあの年のイーハトーヴォの五月から十月までを書きつけましょう。

## h2
あのイーハトーヴォのすきとおった風、夏でも底に冷たさをもつ青いそら、うつくしい森で飾られたモリーオ市、郊外のぎらぎらひかる草の波。 またそのなかでいっしょになったたくさんのひとたち、ファゼーロとロザーロ、羊飼のミーロや、顔の赤いこどもたち、地主のテーモ、山猫博士のボーガント・デストゥパーゴなど、いまこの暗い巨きな石の建物のなかで考えていると、みんなむかし風のなつかしい青い幻燈のように思われます。では、わたくしはいつかの小さなみだしをつけながら、しずかにあの年のイーハトーヴォの五月から十月までを書きつけましょう。