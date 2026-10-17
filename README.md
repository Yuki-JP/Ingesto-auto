# Ingesto Projetos

Canal público de distribuição e atualizações do Ingesto Projetos para Windows 10/11 de 64 bits.

Adaptação do [Ingesto](https://github.com/noar-justedit/ingesto), de Arnaud Augst / Just Edit, sob GPL-3.0-or-later. Não é uma edição oficial do projeto original.

## Instalação

[Baixar o instalador mais recente](https://github.com/Yuki-JP/Ingesto-auto/releases/latest). As edições antigas precisam receber o novo instalador uma vez para habilitar a consulta de futuras atualizações pelo aplicativo.

Feche o Ingesto somente após terminar as cópias. Abra o instalador na conta do Windows que utilizará o programa, sem executar como administrador. Preferências e importações locais são preservadas; a instalação anterior fica guardada como backup.

## Atualizações

O aplicativo consulta `releases/latest/download/latest.json`. A publicação usa manifesto assinado Ed25519, tamanho e SHA256 do instalador. Download e aplicação exigem ação do usuário; não há instalação silenciosa durante backups.

Os instaladores não têm assinatura Authenticode do Windows. A assinatura do manifesto é verificada pelo aplicativo e não substitui um certificado de editor reconhecido pelo Windows.

## Código-fonte e licenças

Cada instalador inclui `FONTES-IngestoProjetos.zip` com as fontes correspondentes da adaptação, instalador, detector e ferramentas, além das licenças do aplicativo e dependências. Nenhuma mídia, preferência pessoal ou chave privada de publicação deve ser enviada a este repositório.

## Estado do canal

Primeira Release publicada em 17/10/2026: [Ingesto Projetos 2026-10-17.1](https://github.com/Yuki-JP/Ingesto-auto/releases/tag/projetos-2026-10-17.1). Manifesto público, assinatura, tamanho e SHA256 conferidos; consulta online testada com edição atual e edição anterior. A instalação e o detector em outras máquinas ainda precisam ser validados no ambiente de uso.
