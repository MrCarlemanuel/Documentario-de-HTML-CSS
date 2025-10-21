🌐 Introdução a Domínio, Hospedagem e CSS

Este documento apresenta uma explicação simples e objetiva sobre os conceitos de domínio, hospedagem e CSS (Cascading Style Sheets).
É voltado para iniciantes que estão aprendendo os fundamentos do desenvolvimento web.

🏷️ 1. O que é Domínio?

O domínio é o nome que identifica o endereço do seu site na internet.
Exemplo: www.meusite.com

Ele serve como um “rastreador” que permite que os usuários encontrem o seu site facilmente.

💾 2. O que é Hospedagem?

A hospedagem é o serviço que armazena os arquivos e dados do seu site na internet.
É como o “terreno” onde o seu site fica hospedado.

🔹 O domínio é o endereço.
🔹 A hospedagem é o local onde o site realmente está.

⚖️ 3. Diferença entre Domínio e Hospedagem
Conceito	Função Principal	Exemplo
Domínio	Endereço do site na web	www.minhaempresa.com
Hospedagem	Armazena arquivos e dados do site	Servidor onde o site está hospedado
🎨 4. O que é CSS?

CSS (Cascading Style Sheets) é uma linguagem usada para definir o estilo e o layout visual de uma página web.
Com o CSS, você pode alterar cores, tamanhos, fontes e posicionamentos de elementos HTML.

🧩 5. Tipos de Seletores CSS

Seletor simples: seleciona elementos pelo nome, classe ou ID.

Seletores combinados: baseiam-se na relação entre elementos.

Pseudoclasse: seleciona elementos em um estado específico (ex: :hover).

Pseudoelemento: estiliza uma parte específica do elemento (ex: ::first-letter).

Seletor de atributo: seleciona elementos com atributos específicos.

💡 6. Exemplos de Seletores
#nome {
  color: blue; /* Seleciona elemento com id="nome" */
}

.intro {
  font-size: 18px; /* Seleciona elementos com class="intro" */
}

p.intro {
  color: red; /* Seleciona apenas <p> com class="intro" */
}

* {
  margin: 0; /* Seleciona todos os elementos */
}

div, p {
  padding: 10px; /* Seleciona <div> e <p> */
}

📘 7. Conceitos-Chave de CSS
✅ Estrutura de uma Regra CSS

Cada regra CSS é formada por:

Seletor: define qual elemento será afetado.

Declaração: entre {}, define as propriedades e valores.

Exemplo:

h1 {
  color: blue;
  font-size: 24px;
}

🧮 Especificidade (Peso)

A prioridade das regras CSS segue esta hierarquia:

Tipo de Seletor	Peso	Exemplo
ID (#)	100	#menu
Classe (.)	10	.intro
Tipo (tag)	1	p

💬 Quando há conflito, a regra com maior peso é aplicada.

🔗 8. Agrupamento e Combinadores

Agrupamento: aplica o mesmo estilo a vários elementos.

p, a { color: black; }


Combinadores: definem relações hierárquicas.

p a { color: red; } /* Seleciona links dentro de parágrafos */

🧭 9. Conclusão

CSS é uma das linguagens fundamentais para o desenvolvimento web.
Com ele, é possível transformar um simples documento HTML em uma página visualmente atrativa e bem estruturada.

✍️ Autor

Material revisado e adaptado por Carlos Gomes
📅 Data: Outubro de 2025
📚 Projeto: Introdução a CSS e Estrutura Web
