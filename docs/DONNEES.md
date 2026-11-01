# Structure des données (document `vision/state`, version 3)

```
{
  v: 3,
  axes:     [{ id, n (nom), k (couleur), def (objectif final) }],
  stations: [{ id, t (titre), d ("AAAA-MM"), a (id du bandeau), s (done|doing|plan|fore),
               k (st|sub|fin), g (chiffre visé), n (notes), o (id d'un objectif lié) }],
  links:    [{ id, from, to, d ("AAAA-MM"), t (fusion|corr), n (raison) }],
  obj:      [{ id, a (id du bandeau), t, u (unité), s0 (départ), v (valeur actuelle), g (cible),
               from, dl ("AAAA-MM"), r (résultat concret), det (détail des moyens),
               m: [{ id, t, d, x (fait) }], log: [{ d, v, n }] }]
}
```

Couleurs de bandeau (`k`) : bleu, rouge, violet, turquoise, magenta, indigo, ardoise, noir.

Migrations : un état sans `axes`, `links` ou `k` reçoit les valeurs par défaut. Un état ancien avec `ind` (indicateurs) est converti en `obj`.
