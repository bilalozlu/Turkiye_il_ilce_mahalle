# Turkiye_il_ilce_mahalle
Türkiye'deki il ilçe mahalle verileri JSONları

format1 --> object(il) -> object(ilçe) -> array(mahalle/köy)
{
  "il": {
    "ilçe": [
      "mahalle/köy",
    ],
  },
}

format2 --> array of objects(il) -> array of objects(ilçe) -> array(mahalle/köy)
[
  {
    "il": [
      {
        "ilçe": [
          "mahalle/köy",
        ]
      },
    ]
  },
]
