# Randy’s Vehicle Locator

Localizador de fã dos carros da lista do Randy em GTA VI. Não afiliado à Rockstar Games.

Site estático: `index.html` + `assets/leonida.jpg`. Sem build, sem back-end. Progresso salvo no `localStorage`.

## Publicar

**GitHub:** crie um repositório, envie a pasta inteira (`index.html`, `assets/`, `README.md`).

**Vercel:** em vercel.com, "Add New > Project", importe o repositório e clique em Deploy. Não precisa de nenhuma configuração (Framework Preset: Other).

## Posições no mapa

Os 42 locais estão cadastrados com fonte e confiança, mas nenhum tem posição ainda: o mapa não tem rótulos nem escala, e posição não foi inventada.

1. Abra o carro e toque em "Posicionar" no local; toque no ponto certo do mapa.
2. Quando terminar, use "Copiar posições do mapa (JSON)".
3. Cole o JSON dentro de `const POS={}` no script (ou me envie) para fixar as posições para todos os visitantes.
