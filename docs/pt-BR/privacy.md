# Política de Privacidade

**Lumidepth Player VR**

- Data de vigência: 19 de outubro de 2026
- Última atualização: 28 de outubro de 2026 (inclusão dos servidores da rede doméstica)
- Fornecedor: mon neural
- Contato: [hello@monneural.dev](mailto:hello@monneural.dev)

Esta é uma tradução. Em caso de divergência, prevalece a [versão em inglês](../en/privacy.md).

## 1. Informações que coletamos

Não coletamos nenhuma informação pessoal, dados de uso ou conteúdo de vídeo. O aplicativo não se comunica com os nossos servidores e não contém publicidade nem ferramentas de análise.

## 2. Dados armazenados no seu PC

Os dados a seguir são armazenados somente no seu PC e nunca são enviados a lugar algum:

- Configurações (opções de exibição e de 3D, e os endereços das pastas compartilhadas e servidores que você cadastrar)
- Logs de diagnóstico (não contêm nomes nem locais de arquivos de vídeo)
- Dados do modelo de profundidade de IA otimizados para a sua GPU
- Miniaturas exibidas na biblioteca de vídeos

Desinstalar o aplicativo e excluir a pasta `%LOCALAPPDATA%\LumidepthPlayerVR` remove todos esses dados.

## 3. Plataforma Meta

O aplicativo é distribuído pela loja da Meta e usa a plataforma Meta para verificar a sua compra. Todas as informações envolvidas são tratadas pela Meta de acordo com a [Política de Privacidade da Meta](https://www.meta.com/legal/privacy-policy/). Nós não as recebemos.

## 4. Rede

Além da verificação de compra, o app só se conecta a:

- Unidades e pastas compartilhadas que você mesmo abrir (por exemplo, um NAS na sua rede doméstica)
- Servidores que você mesmo cadastrar (WebDAV, Jellyfin)
- Servidores de mídia (DLNA) encontrados na sua rede doméstica. Para encontrá-los, o app envia uma solicitação de descoberta (SSDP) na sua rede doméstica.

Os nomes de usuário e senhas dos servidores são lidos do que você salvou no Gerenciador de Credenciais do Windows. O app não os armazena e nunca os grava nos logs.

O app se identifica para servidores Jellyfin com um ID deste PC, para que o servidor não liste um novo dispositivo a cada vez. O ID é um hash derivado do ID do computador Windows; o ID do computador em si não é enviado.

## 5. Crianças

O aplicativo não coleta informações de crianças.

## 6. Alterações

Publicaremos nesta página quaisquer alterações a esta política.
