# Keybindings

keybinding (custom) | Vim Modes | Utility
---|---|---
gc | Normal, Visual | Comenta a linha onde o cursor está
K | Normal | Mostra o hover do VS Code (só funcionarão em arquivos de código que têm suporte a LSP)
gd | Normal | Vai à definição do trecho de código onde o cursor está
gy | Normal | Copia o caminho do arquivo
leader | Visual | Mostra a lista de which keys definidas (o leader é representado pela tecla space)
&lt; | Visual | Indenta a linha para esquerda
&gt; | Visual | Indenta a linha para direita
jk | Insert | Sai do modo Insert e volta para o Normal
jj | Insert | Sai do modo Insert e volta para o Normal
ctrl + / | All | Exibe e oculta a Primary Side Bar
a | Explorer | Cria um novo arquivo no Explorer
f | Explorer | Cria uma nova pasta no Explorer
s | Explorer | Abre um arquivo do Explorer no modo split
c | Explorer | Copia um arquivo no Explorer
x | Explorer | Corta um arquivo no Explorer
p | Explorer | Cola um arquivo anteriormente copiado/cortado no Explorer
d | Explorer | Deleta um arquivo no Explorer
r | Explorer | Renomeia um arquivo no Explorer
gy | Explorer | Copia o caminho de um arquivo no Explorer
ctrl + n | Normal, Visual | Seleciona a próxima ocorrência de um caractere ou cadeia de caractere selecionada
ctrl + ~ | Normal, Insert | Executa um código elegível para o Code Runner (necessita da extensão Code Runner instalada)
ctrl + shift + down | All | Copia uma linha ou bloco para baixo
ctrl + ] | All | Abre e fecha o terminal
ctrl + shift + up | All | Copia uma linha ou bloco para cima
Space c f | Normal | Formata um determinado documento
Space m p | Normal | Abre o Preview de um arquivo Markdown
Space m s | Normal | Abre o Preview de um arquivo Markdown no modo split
Space g l | Normal | Vai para uma determinada linha
Space g r | Normal | Abre o hover com todas as referências ao determinado trecho do código onde o cursor está
Space g i | Normal | Vai à implementação do trecho de código onde o cursor está
Space / | Normal | Pesquisa todas as ocorrências de um caractere ou cadeia de caractere no arquivo
Space f n | Normal | Abre um novo arquivo sem título
Space w s | Normal | Faz com que o arquivo atual seja aberto ao lado direito (modo split)
Space Space | Normal | Abre o quickOpen do VS Code
Space b s | Normal | Mostra cada configuração definida no arquivo atual no formato de símbolos
Space b q | Normal | Abre o quickOpenView do VS Code (o que permite navegar pela Activity Bar quando a mesma está oculta)
Space b d | Normal | Fecha o arquivo atual
Space b o | Normal | Fecha os outros arquivos
Space b w | Normal | Fecha todos os arquivos do grupo
Space b c | Normal | Fecha todos os arquivos de outros grupos que não o atual
ctrl + h | Normal, Visual | Muda o foco para um arquivo a esquerda (quando tem vários grupos diferentes aberto em split)
ctrl + l | Normal, Visual | Muda o foco para um arquivo a direita (quando tem vários grupos diferentes aberto em split)
ctrl + k | Normal, Visual | Muda o foco para um arquivo acima (quando tem vários grupos diferentes abertos em modo split)
ctrl + j | Normal, Visual | Muda o foco para um arquivo abaixo (quando tem vários grupos diferentes abertos em modo split)
Space a | Normal | Adiciona o arquivo atual ao harpoon no próximo slot vago
Space h m | Normal | Abre o arquivo que contém todos os outros arquivos adicionados ao harpoon, permitindo que a ordem seja alterada ou mesmo que um slot seja liberado
ctrl + {1-9} | Normal | Muda para o arquivo presente no slot especificado pelo número após o ctrl

<br>

Alguns keybindings acima usam o padrão WhichKey (Space * *). Abaixo está uma tabela que serve como um guia semântico para fácil identificação do contexto em que cada um desses padrões atalhos se aplica:

Word | Context
--- | ---
Space c * | Code
Space f * | File
Space w * | Window
Space m * | Markdown
Space g * | Goto
Space b * | Buffers
Space h * | Harpoon

<br>
<br>
<br>

keybinding (vs code) | Utility
---|---
ctrl + shift + p | Abre o input de pesquisa por arquivos do VS Code
ctrl + shift + e | Redireciona a Primary Side Bar para a aba de Explorer
ctrl + shift + f | Redireciona a Primary Side Bar para a aba de Search
ctrl + shift + g | Redireciona a Primary Side Bar para a aba de Source Control (Git)
ctrl + shift + d | Redireciona a Primary Side Bar para a aba de Debug
ctrl + shift + x | Redireciona a Primary Side Bar para a aba de Extensions
ctrl + shift + h | Substituição de caractere ou cadeia de caracteres em um arquivo
ctrl + shift + n | Abre uma nova janela do VS Code
ctrl + , | Abre as configurações
ctrl + shift + u | Abre o Output do VS Code
ctrl + Page Down | Muda o foco do arquivo atual para o logo a direita (não funciona se o arquivo atual estiver no modo Insert)
ctrl + Page Up | Muda o foco do arquivo atual para o logo a esquerda (não funciona se o arquivo atual estiver no modo Insert)
alt + click | Permite utilizar multi seleção com o cursor
ctrl + shift + l | Seleciona todas as ocorrências de uma palavra
ctrl + shift + k | Deleta a linha onde o cursor está
ctrl + alt + seta para cima/baixo | Selecione todas as linhas de uma mesma coluna
alt + seta para cima/baixo | Move a linha atual para cima ou para baixo
ctrl + s | Salva o arquivo atual
F5 | Inicia o Debugging
shift + F5 | Para o Debugging
F10 | Passa para o próximo passo de execução do código
F9 | Define um breakpoint na linha em que o cursor está
ctrl + . | Mostra as opções de correção rápida do VS Code (quickFix)
shift + F8 | Pula para o Erro, Aviso ou Informação de código anterior
alt + F8 | Pula para o próximo Erro, Aviso ou Informação de código

<br>
<br>
<br>

# Extensions

Extensions |
---|
Better Comments
Brazilian Portuguese - Code Spell Checker
Code Runner
Code Spell Checker
Color Highlight
Comment Anchors
Container Tools
Database Client
Database Client JDBC
Dev Containers
EditorConfig for VS Code
Error Lens
fuzzy-search
GitHub Markdown Preview
GitLens — Git supercharged
Go
Kubernetes
Material Icon Theme
One Dark Pro Monokai Darker Theme
Reload
Theme by language
Vim
VSCode Harpoon
Which Key
WSL
YAML
