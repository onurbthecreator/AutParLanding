# AutPar Irrigação

Landing page do monitoramento de pivô central da AutPar. Leva para o sistema do pivô (login e dashboard).

Página estática: um único `index.html`, sem build. Para ver local:

```
python -m http.server 8765
```

e abrir http://127.0.0.1:8765

## Pendências

- Trocar os degradês do topo e dos 3 blocos pelas imagens geradas por IA (`hero.jpg`, `bloco1.jpg`, `bloco2.jpg`, `bloco3.jpg`)
- Conferir a licença de uso comercial das imagens de satélite da Esri usadas nos cards de mapa
- Apontar os botões "Acessar o sistema" para o subdomínio do pivô quando ele existir
