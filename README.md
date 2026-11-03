# RANKING MUNDIAL DEFINITIVO — BETA 1.1

Site estático gratuito com um ranking brasileiro provisório de referência e acervo documental CLUBENSE 1902–1906.

- [Portal principal](https://andresantificado.github.io/ranking-mundial-definitivo/)
- [Acervo de temporadas, clubes e créditos](https://andresantificado.github.io/ranking-mundial-definitivo/acervo.html)
- [Banco versionado com rastreabilidade](data/acervo-clubense-v1.json)

## Camadas distintas

1. **Referência externa**: Top 10 com pontuações próprias do [Ranking Histórico](https://rankinghistorico.com.br/), conforme snapshot de 01/11/2026. **Provisório, não CLUBENSE.**
2. **CLUBENSE registrado**: 16 entradas do livro-razão canônico v1.6/Emenda 006, todas das três edições do Campeonato Paulista de 1902 a 1904, total exato **214475/3** (71.491,666…); não é ranking nacional completo.
3. **CLUBENSE calculado e não lançado**: 10 colocações de 1905, Paulista e Baiano, total teórico **45.975**, sem decisão 1905/1906; estes valores **nunca entram no total lançado**.
4. **1906 apenas documental**: três edições catalogadas; Paulista sob divergência e campeonatos Baiano/Carioca identificados. Nenhum crédito atribuído.
5. **Cadastro histórico**: 28 entidades, quadros ou equipes documentadas em 1905 mais Paysandu Cricket Club documentado em 1906 (29 identificadores); cadastro não equivale a pontos.

## Proteções

- Números da fonte externa não são somados aos pontos CLUBENSE.
- A fórmula canônica da calculadora não substitui lançamentos documentais.
- C07/C23 continuam HOLD; divergências 1902/1904 são preservadas.
- Pará 1908/1910, temporada 1918 e Grêmio 1919 seguem condições previamente aprovadas.
- Escudos são substituídos por monogramas neutros quando não autenticados.
- Atenção ao **Distrito Federal histórico (1905/1906)**, que não deve ser confundido com a UF DF atual.
- Homônimos de Internacional e Palmeiras são identidades históricas distintas.
- Não foram publicados os documentos privados completos da Biblioteca do usuário: apenas metadados de proveniência e lançamentos selecionados para o acervo.

## Estrutura

```
index.html
acervo.html
data/acervo-clubense-v1.json
.nojekyll
README.md
```

O acervo valida contagens, IDs e somas racionais no navegador. Não há APIs pagas, frameworks externos ou imagens protegidas obrigatórias. Hospedagem no GitHub Pages, branch `main`, pasta raiz.

**Data da revisão:** 03/11/2026.
