# super-trunfo
comparação entre cartas
🧭 1. Pré-requisitos

Para compilar programas em C, você precisa de um compilador C instalado no computador.
As opções mais comuns são:

🔹 No Windows

Instalar o MinGW (que vem com o compilador gcc).
👉 Download oficial: https://www.mingw-w64.org/

Durante a instalação, marque a opção para adicionar o MinGW ao PATH do sistema.

Depois, confirme a instalação abrindo o Prompt de Comando e digitando:

gcc --version


Se aparecer algo como gcc (MinGW-W64) ..., está tudo certo ✅

🔹 No Linux (Ubuntu, Debian, Fedora etc.)

O GCC geralmente já vem instalado.
Se não estiver, instale com:

sudo apt update
sudo apt install build-essential


ou no Fedora:

sudo dnf install gcc

🔹 No macOS

Use o compilador que vem com o Xcode Command Line Tools:

xcode-select --install


Depois, teste com:

gcc --version

🧱 2. Salvando o código

Abra um editor de texto simples, como:

Notepad++ (Windows)

VS Code

Geany

Gedit (Linux)

Copie todo o código do programa (o que enviei anteriormente).

Salve o arquivo com o nome:

super_trunfo_avancado.c


⚠️ Atenção:
Certifique-se de que a extensão do arquivo é .c, não .txt.
Exemplo correto: ✅ super_trunfo_avancado.c
Exemplo errado: ❌ super_trunfo_avancado.c.txt

⚙️ 3. Compilando o programa

Abra o terminal (ou Prompt de Comando) e navegue até a pasta onde você salvou o arquivo.

Exemplo no Windows:

cd C:\Users\SeuNome\Desktop


Exemplo no Linux/macOS:

cd ~/Área\ de\ Trabalho


Agora compile o programa com o comando:

gcc super_trunfo_avancado.c -o super_trunfo


gcc → é o compilador C.

super_trunfo_avancado.c → é o nome do seu arquivo-fonte.

-o super_trunfo → cria o executável com o nome “super_trunfo”.

Se nenhum erro aparecer, o programa foi compilado com sucesso ✅

Você verá um novo arquivo:

No Windows: super_trunfo.exe

No Linux/macOS: super_trunfo

▶️ 4. Executando o programa

Agora rode o programa:

🔹 No Windows:
super_trunfo

🔹 No Linux/macOS:
./super_trunfo

🧠 5. Exemplo de execução completa

Após rodar o programa, a tela mostrará algo assim:

=== SUPER TRUNFO - COMPARAÇÃO AVANÇADA ===

Cartas em jogo:
Carta 1: São Paulo (SP)
Carta 2: Rio de Janeiro (RJ)

Escolha um atributo para comparar:
1 - População
2 - Área (em km²)
3 - PIB (em R$)
4 - Densidade Populacional (hab/km²)
5 - PIB per Capita (R$/habitante)
Digite a opção do primeiro atributo: 3

Escolha um atributo para comparar:
1 - População
2 - Área (em km²)
4 - Densidade Populacional (hab/km²)
5 - PIB per Capita (R$/habitante)
Digite a opção do segundo atributo: 5


Após escolher os dois atributos, o programa exibirá:

=== RESULTADOS DA COMPARAÇÃO ===

Atributo 1: PIB
Carta 1 - São Paulo: 699000000000.00
Carta 2 - Rio de Janeiro: 364000000000.00

Atributo 2: PIB per Capita
Carta 1 - São Paulo: 56829.27
Carta 2 - Rio de Janeiro: 53934.28

Soma total dos atributos:
São Paulo: 699000056829.27
Rio de Janeiro: 364000053934.28

Resultado final: Carta 1 (São Paulo) venceu!
===========================================

🧩 6. Resumo rápido dos comandos principais
Etapa	Comando
Compilar	gcc super_trunfo_avancado.c -o super_trunfo
Executar no Windows	super_trunfo
Executar no Linux/macOS	./super_trunfo
