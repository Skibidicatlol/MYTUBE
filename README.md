MYTUBE — DOCUMENTAÇÃO DE CONTINUIDADE

Projeto: MYTUBE
Versão atual: 1.5
Próxima versão: 1.6
Plataforma: Android
Tecnologia: Kotlin, Jetpack Compose, Gradle e Android Media3
Desenvolvimento: GitHub + GitHub Actions
Idioma do aplicativo: Português (Brasil)

---

1. SOBRE O PROJETO

MYTUBE é um aplicativo pessoal de vídeos, inspirado na experiência do YouTube.

O objetivo é construir um aplicativo Android instalável por APK, com funcionamento principalmente offline.

O aplicativo deve permitir importar vídeos do armazenamento do celular, organizar uma biblioteca pessoal, assistir vídeos, criar playlists e navegar por uma interface semelhante à de plataformas de vídeos modernas.

O projeto deve evoluir continuamente, sem perder funcionalidades existentes.

2. ESTADO ATUAL — MYTUBE 1.5

A versão 1.5 já foi compilada pelo GitHub Actions, instalada e aberta com sucesso em um Xiaomi 13C.

Funcionalidades visualmente verificadas:

- Tela inicial.
- Categorias de vídeos.
- Shorts.
- Importação de vídeos locais.
- Opção de importar como Short.
- Página Inscrições.
- Página Você.
- Biblioteca de vídeos.
- Miniaturas dos vídeos.
- Remoção de vídeos com confirmação.
- Pesquisa.
- Interface escura.
- Navegação inferior.

O aplicativo já demonstrou conseguir abrir e apresentar vídeos importados.

IMPORTANTE: não presumir que todas as funções estão completamente implementadas apenas porque aparecem na interface. Testar cada funcionalidade antes de afirmar que está pronta.

3. IDENTIDADE VISUAL

O MYTUBE utiliza:

- Preto como fundo principal no tema escuro.
- Vermelho como cor de destaque.
- Branco para textos e ícones.
- Cartões com cantos arredondados.
- Interface adaptada para dispositivos móveis.
- Barra de navegação inferior.

A navegação inferior atual deve ser preservada:

1. Início
2. Shorts
3. Enviar
4. Inscrições
5. Você

4. OBJETIVOS DA VERSÃO 1.6

A versão 1.6 deve melhorar a experiência visual e adicionar funcionalidades.

4.1. Nova página Você

Usar como referência principal a imagem enviada pelo usuário em 09/11/2026.

A página deve seguir uma organização semelhante à página de perfil do YouTube.

Elementos desejados:

- Seletor de contas.
- Ícone de mensagens, se aplicável ao funcionamento offline.
- Ícone de notificações, se aplicável.
- Pesquisa.
- Configurações.
- Foto de perfil.
- Nome do usuário.
- Identificador do perfil.
- Botão Ver canal.
- Histórico em formato horizontal.
- Biblioteca.
- Categorias da biblioteca.
- Playlists com miniaturas.
- Menus de gerenciamento das playlists.

A página não deve ficar limitada a uma única seção de biblioteca.

4.2. Sistema de conta local

O usuário escolheu explicitamente uma conta LOCAL.

Requisitos:

- Não exigir cadastro online.
- Não exigir login em servidor.
- Criar perfil diretamente no aplicativo.
- Permitir escolher uma foto da galeria.
- Permitir editar nome e descrição.
- Salvar os dados no próprio dispositivo.
- Vincular playlists e histórico ao perfil local.
- Funcionar sem internet.

Não implementar autenticação online como requisito.

Avisar que dados locais podem ser perdidos ao limpar os dados do aplicativo ou desinstalá-lo, caso não exista backup.

4.3. Playlists

Criar um sistema completo de playlists.

Funcionalidades desejadas:

- Criar playlist.
- Editar nome.
- Editar descrição.
- Escolher capa.
- Adicionar vídeos.
- Remover vídeos.
- Alterar ordem dos vídeos.
- Excluir playlist.
- Visualizar quantidade de vídeos.
- Abrir e reproduzir uma playlist.
- Mostrar playlists na página Você.

Preparar suporte a playlists privadas e, futuramente, públicas, caso exista infraestrutura online.

4.4. Reprodução de playlists

Adicionar controles:

- Repetir playlist inteira.
- Repetir somente o vídeo atual.
- Reprodução aleatória (Shuffle).
- Fila de reprodução.
- Organização manual dos vídeos.

Os modos de repetição e reprodução aleatória devem funcionar independentemente.

A reprodução deve continuar respeitando a ordem escolhida pelo usuário quando o modo aleatório estiver desativado.

4.5. Reformulação dos Shorts

Deixar a área de Shorts mais bonita e moderna.

Referências:

- Interface de Shorts do YouTube.
- Vídeo vertical ocupando melhor a tela.
- Botão de curtir.
- Botão de comentários, se houver suporte.
- Compartilhamento.
- Informações do criador.
- Navegação vertical.
- Animações suaves.

Preservar a possibilidade de importar vídeos como Shorts.

4.6. Shorts na página inicial

Permitir que a página Início apresente uma seção de Shorts.

Elementos:

- Carrossel horizontal de Shorts.
- Miniaturas.
- Títulos.
- Acesso direto à reprodução.
- Opção de ativar ou desativar essa seção nas configurações.

Também preservar categorias como Jogos, Música, Minecraft e Roblox.

4.7. Configurações

Adicionar um botão de engrenagem no canto superior direito da página principal, ao lado da lupa.

A página de configurações deve conter:

Aparência

- Tema preto.
- Tema branco.
- Tema automático, seguindo o Android.

Conta

- Editar perfil.
- Alterar foto.
- Alterar nome.
- Editar descrição.

Reprodução

- Preferências de reprodução.
- Configurações de loop.
- Preferências de reprodução automática.

Armazenamento

- Espaço utilizado.
- Dados dos vídeos.
- Cache.
- Informações sobre arquivos importados.
- Opções seguras de limpeza.

Privacidade

- Informações sobre dados locais.
- Permissões utilizadas.

Notificações

- Preferências de notificações.

Sobre

- Nome do aplicativo.
- Versão instalada.
- Informações do desenvolvedor.

Direitos

- Direitos autorais.
- Licenças de bibliotecas utilizadas.
- Créditos de recursos e componentes.

Como funciona

- Explicação resumida do aplicativo.
- Como importar vídeos.
- Como criar playlists.
- Como funciona o armazenamento local.
- Como utilizar Shorts.

Ajuda

- Perguntas frequentes.
- Informações para solucionar problemas.

5. REFERÊNCIAS VISUAIS

O usuário forneceu uma captura de tela de uma página de perfil do YouTube como referência para a nova página Você.

Essa imagem deve ser considerada uma referência de organização e experiência visual, não uma instrução para copiar marcas ou elementos proprietários.

Também foram solicitadas referências visuais da interface do próprio YouTube para:

- Shorts.
- Página Você.
- Histórico.
- Playlists.
- Reprodução.
- Configurações.

Manter a identidade própria do MYTUBE.

6. REGRAS IMPORTANTES DE DESENVOLVIMENTO

O usuário prefere:

- Scripts e projetos completos.
- Arquivos integrados.
- Preservação de todas as funções existentes.
- Não simplificar o projeto para facilitar a resposta.
- Não remover recursos sem autorização.
- Interface profissional e adaptada para celular.
- Instruções que funcionem no Android.

Antes de modificar:

1. Inspecionar todo o projeto.
2. Entender sua estrutura.
3. Identificar as funções existentes.
4. Planejar as alterações.
5. Implementar sem quebrar recursos anteriores.
6. Compilar.
7. Corrigir erros.
8. Entregar o projeto completo.

Não afirmar que uma função está pronta sem testar ou verificar sua implementação.

7. COMPILAÇÃO DO APK

O usuário utiliza GitHub pelo celular.

O processo de compilação atual utiliza GitHub Actions.

Arquivo de workflow:

".github/workflows/build-apk.yml"

O workflow atual:

1. Baixa o repositório.
2. Prepara Java 17.
3. Extrai "MYTUBE_Android_1_5.zip".
4. Localiza automaticamente "settings.gradle" ou "settings.gradle.kts".
5. Prepara Gradle.
6. Executa "assembleDebug".
7. Publica o APK como artefato "MYTUBE-APK".

O usuário conseguiu executar esse processo com sucesso.

O GitHub disponibiliza o resultado como ZIP de artefato. É necessário extrair esse ZIP para encontrar o APK.

Caminho esperado:

"app/build/outputs/apk/debug/app-debug.apk"

A estrutura real deve ser conferida antes de alterar o workflow.

8. ARQUIVOS DO PROJETO

O usuário possui:

- "MYTUBE_Android_1_5.zip" — código-fonte da versão 1.5.
- "MYTUBE-APK.zip" — artefato baixado do GitHub Actions.

O usuário pretende enviar o repositório GitHub e esses arquivos para a próxima conversa.

Utilizar o código-fonte como base para a versão 1.6.

Não reconstruir o aplicativo do zero sem necessidade.

9. DISPOSITIVO DE TESTE

Dispositivo principal:

- Xiaomi 13C.
- Android.
- Uso predominante pelo celular.

Testar a interface em telas pequenas e considerar desempenho e consumo de memória.

10. OBJETIVO FINAL

Criar a versão MYTUBE 1.6, completa, funcional e instalável.

A prioridade é evoluir a versão 1.5 sem perder funcionalidades.

O aplicativo deve continuar sendo principalmente offline, com conta local, biblioteca, Shorts, playlists e personalização visual.

PRIMEIRA TAREFA DO PRÓXIMO CHATGPT:

Receber o repositório e o ZIP da versão 1.5, inspecionar a estrutura e confirmar quais funcionalidades estão realmente implementadas. Depois, preparar a atualização completa para a versão 1.6, respeitando todas as especificações deste documento.

Não começar criando um projeto novo e simplificado.
