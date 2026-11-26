# Escalação · Sport Clube Ribeira Bote

## Estrutura
```
escalacao/
├── index.html      a app (interface, animação, gravação de vídeo)
├── server.js       servidor (guarda os dados no projeto)
├── package.json
├── iniciar.bat     duplo clique no Windows para arrancar
├── img/
│   └── emblema-ribeira-bote.png   <- COLOCA AQUI o emblema (PNG transparente)
├── fotos/                         <- fotos opcionais: 1.png, 2.png ... (número do jogador)
└── data/
    ├── state.json                 <- criado sozinho: jogadores, tática, banco, dados do jogo
    └── state.json.bak             <- cópia da gravação anterior
```

## Arrancar
1. Instala o Node.js (nodejs.org), só uma vez.
2. Na pasta do projeto: `node server.js` (ou duplo clique em `iniciar.bat`).
3. Abre http://localhost:3000. Noutros aparelhos da mesma rede, usa o endereço que aparece na consola.

## Dados
Tudo o que crias (jogadores, fotos, banco, dados do jogo, emblema do adversário) fica em `data/state.json`.
Copia a pasta `data/` para levar os dados para outro PC. Na 1.ª vez, os dados já guardados neste navegador são enviados para o servidor.
Se editares em dois aparelhos ao mesmo tempo, a última gravação ganha.

## Vídeo Reels
Marca "Gravar vídeo Reels", põe o navegador em ecrã inteiro (F11) e clica em "Iniciar animação".
Escolhe "Este separador". O vídeo sai a 60 fps em MP4 (H.264) com 50 a 80 Mbps. A nitidez depende da altura do ecrã: ecrã 1440p/4K dá mais resolução.
