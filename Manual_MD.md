# Guia Completo de Sintaxe Básica do Markdown 

## Visão Geral

A maioria dos aplicativos Markdown segue os elementos básicos definidos originalmente. Há pequenas variações entre processadores — indicadas em observações ao longo do guia.

### 1. Títulos (Headings)

Use o símbolo # antes do texto para criar títulos. A quantidade de # determina o nível do título (de 1 a 6).

Exemplos:

# Título de nível 1
## Título de nível 2
### Título de nível 3
...
###### Título de nível 6

Resultado HTML correspondente:

<h1>Título de nível 1</h1>
...
<h6>Título de nível 6</h6>

Sintaxe alternativa

Para criar títulos de nível 1 ou 2, você pode usar uma linha com = ou - logo abaixo do texto:

Título de nível 1
=================

Título de nível 2
-----------------

#### Boas práticas:
	•	Sempre insira um espaço entre os # e o texto do título.
	•	Separe o título com linhas em branco antes e depois para melhor compatibilidade.

⸻

### 2. Parágrafos

Separar parágrafos requer uma linha em branco entre blocos de texto. Não use indentação (espaços ou tabulação) no início dos parágrafos, a menos que esteja dentro de uma lista.  ￼

⸻

### 3. Quebras de Linha

Para criar uma nova linha no mesmo parágrafo (equivalente a <br> no HTML), termine a linha com dois ou mais espaços e pressione Enter. Outra opção é usar a tag HTML <br>, especialmente se precisa de mais compatibilidade entre editores.  ￼

⸻

### 4. Ênfase (Negrito e Itálico)
	•	Negrito: envolva o texto com **texto** ou __texto__.
	•	Itálico: use *texto* ou _texto_.
	•	Ambos combinados: ***texto***, ___texto___, **_texto_**, ou __*texto*__ para negrito + itálico.

Dicas:
	•	Prefira usar asteriscos (*) quando estiver aplicando ênfase no meio de uma palavra, pois sublinhados podem ter comportamento inconsistente.  ￼

⸻

### 5. Citações em bloco (Blockquotes)

Use o símbolo > no início da linha para criar um bloco de citação.

Exemplo:

> Esta é uma citação.

Para citação com múltiplos parágrafos:

> Primeiro parágrafo.
>
> Segundo parágrafo.

Para citações aninhadas:

> Exemplo original.
> >> Citação aninhada.

Você também pode combinar elementos como títulos, listas e ênfase dentro de um bloco de citação.  ￼

⸻

### 6. Listas (Ordenadas e Não Ordenadas)

	•	Listas não ordenadas: use -, * ou + antes dos itens.
	•	Listas ordenadas: use números seguidos de ponto (1., 2., etc.). Os números não precisam estar na sequência exata; o Markdown renderiza corretamente.

Exemplo de lista aninhada:

1. Item um
2. Item dois
   - Subitem
   - Outro subitem
3. Item três

⸻

### 7. Linhas Horizontais

Crie linhas divisórias com três ou mais:
Asteriscos ***
Hífens ---
Sublinhados ___

Pule ou não linhas em branco antes/depois conforme o estilo desejado.  ￼ ￼

⸻

### 8. Exemplos de Código

Código inline: use crase simples `código`.

Bloco de código: envolva o texto com três crases em linhas separadas:



Este é um bloco de código



Opcionalmente, você pode especificar a linguagem logo após as crases para realce de sintaxe.

⸻

### 9. Links
	•	Link padrão:

[Texto do link](https://exemplo.com)

	•	Link com título (tooltip):

[Texto](https://exemplo.com "Título opcional")

	•	Link automático (“naked URL”): use < > para converter automaticamente:

<https://exemplo.com>


⸻

### 10. Imagens

Sintaxe semelhante à de links, mas com ! no início:

![Texto alternativo](caminho/da/imagem.jpg)

Também permite um título opcional:

![Alt texto](imagem.jpg "Título Opcional")


⸻

### 11. Escape de Caracteres

Se precisar exibir um símbolo que o Markdown interpreta como formatação, use a barra invertida () antes dele. Exemplos:

\* Não será itálico
\# Não será cabeçalho


⸻

### 12. Boas Práticas Gerais
	•	Evite faltas de compatibilidade — use espaços após # nos títulos, linhas em branco ao redor de blocos, etc.
	•	Sempre pode testar seus documentos Markdown com renderizadores como Dillinger, StackEdit, ou editores com visualização ao vivo.
