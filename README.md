# CursoHTML
Esse diretorio se refere aos arquivos dos exercicios do curso da HCode Treinamentos da Udemy para desenvolvimento HTML

## Estrutura de um arquivo HTML
- Conhecendo a propriedades Head e Body

## Estrutura da pagina HTML
- Elementos de blocos

## Atributos globais 
- **accesskey** - Define uma tecla de atalho para focar em algum elemento;
- **class** - Define quais classes CSS serão aplicadas no elemento. (Muito utilizado quando queremos aplicar a mesma formatação em CSS para diversos elementos);
- **contenteditable** - Define se o conteúdo do elemento pode ou não ser editável. (Ele pode ser editado em execução do codigo, não altera os dados do arquivo, não substitui o formulario);
- __data-*__ - Usado para armazenar dados em um elemento. No lugar do (*) deve definir um nome.(Os dados serao apenas armazenados e não exibidos);
- **dir** - Define a direção do conteúdo de um elemento.(Valores Utilizados são: Auto (Identifica o padrão do sistema operacional do usuario), Ltr(Padrão do ingles: da esquerda para direita), rtl(Da direita para esquerda));
- **draggable** - Define se o elemento pode ser arrastado ou não. (Valores que podem ser utilizados: True e False);
- **dropzone** - Define o que acontece quando o elemento arrastado é solto neste elemento;
- **hidden** - Define o elemento como oculto.(Esse atributo tem por valor o mesmo nome. Consultar sessão de notas para mais explicações sobre atributos com o valor igual ao nome);
- **id** - Define uma identificação única para o elemento;
- **lang** - Define a linguagem do conteúdo do elemento;
- **spellcheck** - Define se o conteúdo do elemento deve ter sua ortografia verificada.(Valores podem ser True e False);
- **style** - Define estilos CSS diretamente no elemento;
- **tabindex** - Define a posição do elemento na ordem de tabulação da página;
- **title** - Define informações sobre o elemento;
- **translate** - Define se o conteúdo do elemento pode ser traduzido ou não;


### Notas
#### Valores (TRUE e FALSE)
- Alguns atributos tem como valores True e False, por padrão os atributos tem como valor false, ou seja caso eu não passe o valor TRUE ele vai estar definido com FALSE

#### Atributos com o valor igual ao nome
- Quando um atributo global tem o valor igual ao nome não é necessario declarar o valor desse atributo.
**Exemplo:**
<div hidden="hidden">Div</div>
Pode ser declarado apenas como:
<div hidden>div</div>

#### Diversas
- Não será colocado em pratica todos os exercicios pois o objetivo de fazer esse curso é para atualização de conhecimento.