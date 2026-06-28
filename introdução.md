Caminho para  uma pasta: 
C:\Area de Trabalho\Maria\DCC202\Atividade01.docx
C:\nome pasta\nome subpasta\nome arquivo.extensão
Podemos manipular pastas manualmente, pelo navegador de arquivos, ou pelo Shell, por linhas de comando.

=========== Terminal da Máquina =============

Algumas operações básicas para o uso do shell no windows:
Abrir PowerShell: `Windows + R`
Qual a pasta atual: pwd 
Mudar de pasta: cd <destino> 
Ir para a pasta pessoal (Home): cd ~
Subir uma pasta: cd ..
Listar arquivos e pastas: dir 
Listar tudo (incluindo arquivos ocultos): Get-ChildItem -Force ou dir /a
Criar uma nova pasta: mkdir <nome> 
Criar um arquivo vazio: ni <nome> 
Remover um arquivo: rm <arquivo> ou del <arquivo>
Remover pasta vazia: rd <pasta> ou rmdir<pasta>
Remover pasta cheia e todo o conteúdo (Cuidado!): rm -Recurse -Force <pasta>
Copiar um arquivo ou pasta: cp <origem> <destino> 
Mover ou renomear um arquivo ou pasta: mv <origem> <destino> 
Exibir o conteúdo de um arquivo de texto: cat <arquivo> ou Get-Content <arquivo>
Limpar a tela do terminal: clear ou cls

=========== Versionamento de código ==============

Para assegurar que os arquivos sejam salvos, inclusive em diferentes versões, usamos o GitHub juntamente ao VScode para editar arquivos, salvá-los (tanto nas versões atuais quanto nas passadas), realizando o versionamento de código. Isso cria uma linha do tempo com várias versões do código, para as quais podemos retornar e inspecionar.
O github cria repositórios (como pastas), que é o repositório remoto, o qual armazena cópias do repositório local em diferentes estados.

=========== Arquivos de código ==============
O código é escrito em alguma linguagem de marcação/programação, esse arquivo é compilado para que se torne um executável (em números binários). 
Na programação web, há um padrão de decodificação de código, o `UTF-8`, garante acentos e caracteres especiais em qualquer linguagem humana e é o padrão atual. Se o leitor com um certo codificador padrão abre um arquivo com uma codificação diferente, o texto aparece com caracteres estranhos. Muitos problemas podem ser resovidos ajustando apenas o codificador.

=========== Linguagem de Marcação ==============
Cria documentos estruturados utilizando apenas texto puro. Diferente das linguagens de programação, que usam lógica ee funções, as linguagens de marcação usam tags, palavras especiais da linguagem, para especificar "o que é o que" dentro do texto para o navegador.
O maior exemplo é o HTML (HyperText Markup Language).
Etiqueta de abertura: 
<tag>
Etiqueta de fechamento:
</tag>
Estrutura:
<tag> Texto </tag>
As tags podem ter atributos, que adicionam especificações a um elemento. Esses atributos estão, sempre, na tag de abertura, nomeados por um identificador e preenchidos com valores, dessa forma:
<tag atributo="valor"> Texto </tag>











