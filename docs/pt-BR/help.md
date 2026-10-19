# Ajuda

O **Lumidepth Player VR** reproduz no seu Meta Quest vídeos VR180, VR360 e 2D armazenados no seu PC ou no NAS da sua casa. Um modelo de IA estima a profundidade de cada quadro, e assim os objetos próximos e distantes se deslocam de forma natural quando você move a cabeça.

## Requisitos

- Windows 10 / 11 (64 bits)
- NVIDIA GeForce RTX 3060 ou mais recente (séries RTX 30 / 40 / 50)
- Headset Meta Quest conectado pelo Meta Quest Link (cabo) ou Air Link
- Vídeo: MP4, MKV, MOV, WebM. H.265 (HEVC), H.264 (até 4K), AV1, VP9, ProRes
- 8 a 12 bits, 4:2:0 / 4:2:2 / 4:4:4, HDR (HDR10, HLG). Vídeos HDR são exibidos em SDR
- Nas séries RTX 30 / 40, 4:2:2 e ProRes são decodificados pela CPU, então vídeos 8K a 60 fps podem não ser reproduzidos com fluidez (a série RTX 50 os decodifica pela GPU)

## Primeiros passos

1. Abra o aplicativo Meta Quest Link no PC e conecte o seu Quest com o Link ou o Air Link.
2. Inicie o Lumidepth Player VR pela Biblioteca do seu Quest.
3. As unidades do seu PC aparecem na lista. Para navegar em uma pasta compartilhada de um NAS, mapeie-a como unidade de rede no Windows.
4. Selecione um vídeo com o gatilho direito para iniciar a reprodução. Na primeira vez que você usar o 3D, a IA é preparada para o seu PC, o que pode levar alguns minutos (depois disso, é instantâneo).

## Controles

| Botão | Biblioteca | Durante a reprodução |
|---|---|---|
| Gatilho direito | Escolher / segurar e mover para rolar | Mostrar a barra de reprodução / pressionar um botão |
| A | Subir uma pasta | Voltar à biblioteca |
| B | Subir uma pasta | Ligar/desligar o 3D |
| Y | – | Reproduzir / pausar |
| X | – | Mostrar / ocultar a linha de status |
| Analógico direito para a esquerda/direita | – | −10 s / +10 s |
| Analógico esquerdo para a esquerda/direita | – | −60 s / +60 s |
| Clique no analógico direito | – | Centrar |
| Segurar o botão de pegar direito e mover | – | Girar o vídeo |

## Barra de reprodução e ajustes

Puxe o gatilho direito durante a reprodução para mostrar a barra de reprodução no ponto para onde você aponta. Ela tem volume, zoom, 3D ligado/desligado, Centrar e Ajustes (⚙).

O painel de ajustes tem três páginas:

- **Exibição**: Brilho, Nitidez, Antisserrilhado
- **3D**: Profundidade 3D, Alinhamento de bordas, Bordas, Preenchimento de lacunas, Estabilização, Taxa de atualização, Janela, 3D para 2D/mono
- **Formato**: Projeção (180°, 360°, Plano) e Disposição (Lado a lado, Em cima/embaixo, Única). O formato é detectado automaticamente pelo nome do arquivo e pela proporção da imagem; escolha manualmente apenas se a imagem parecer errada (vale somente para o vídeo atual).

O efeito de profundidade funciona melhor com vídeos VR180 lado a lado.

## Solução de problemas

- **"Seu Meta Quest não está conectado."**: conecte o seu Quest com o Link ou o Air Link e tente novamente.
- **"Nenhuma GPU NVIDIA (GeForce RTX série 30 ou mais recente) foi encontrada."**: atualize o driver da NVIDIA. É necessária uma GPU RTX série 30 ou mais recente.
- **O 3D mostra "indisponível"**: a memória da GPU pode estar insuficiente. Feche outros aplicativos.
- **A imagem aparece duplicada ou dividida**: escolha a projeção e a disposição na página Formato dos ajustes.

Contato: [hello@monneural.dev](mailto:hello@monneural.dev)
