# Roteiro Anatomia — Versão Final Premium

Pasta oficial:

```text
roteiro-anatomia-abas-pdf-install
```

## Inclui

- 224 cards preservados.
- Todas as estruturas do roteiro.
- Cards Premium coloridos.
- Campo de localização anatômica em cada card.
- Como identificar.
- Relações anatômicas.
- Aplicação clínica.
- Dica de prova prática.
- Som em cliques e botões usando `assets/sounds/click.mp3`.
- Zoom em cada card.
- Visualizador em alta resolução.
- Imagem sem corte.
- PDF completo.
- PWA instalável em Android e iPhone.

## Cards por aba

- Artérias do membro inferior: 39
- Veias e linfonodos do membro inferior: 37
- Nervos do membro inferior: 39
- Compartimentos, regiões e fáscias: 79
- Plexo braquial: 30

## Imagens

Agora são 224 cards. Coloque imagens em:

```text
assets/img/1.png
assets/img/2.png
...
assets/img/224.png
```

## Som

Coloque o arquivo:

```text
assets/sounds/click.mp3
```

## Rodar no PowerShell

```powershell
cd $env:USERPROFILE\Desktop\roteiro-anatomia-abas-pdf-install
python -m http.server 8000
```

Depois abra:

```text
http://localhost:8000
```


## Atualização incluída

Foram preenchidos **39 nervos do membro inferior** com:
- localização anatômica;
- como identificar;
- relações topográficas;
- aplicação clínica;
- dica de prova prática.

Mantidos todos os demais cards e recursos do PWA.
