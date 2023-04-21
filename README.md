# Orientação a Objetos com Java

#### O que é?

É uma técnica de programação baseada na construção e utilização de objetos.


#### Para que serve?

Serve para ter mais eficiencia, pois a delimitação das resposabilidades dos objetos permite que suas classes sejam utilizadas em diferentes situações (reusabilidade).
E a manutenção do código é simplificada, ou seja, é feita a modificação em elementos específicos.




## Classe: 

É um modelo para um tipo de objeto, que relaciona seus atributos (características e estado) e seus comportamentos (funcionallidades), podendo representar uma entidade real ou abstrata.

## Instanciação:

Uma instância de uma classe é um novo objeto criado dessa classe, com o operador new. Instanciar uma classe é criar um novo objeto do mesmo tipo dessa classe. 

## Objeto:

Uma entidade que possui estado e comportamento é conhecida como um objeto.




### Declaração de Classe e variáveis de instância

Para implementar uma classe em java deve se utilizar a palavra reservada class.

                  [Imagem]

É recomendado salvar cada classe em um arquivo próprio.

Para instanciar deve se utilizar o operador new e uma chamada especial utilizando o nome da classe (construtor)

                  [Imagem]

Variáveis  de instância é aquela cujo tipo declarado é uma classe. Elas são usadas para manter referências dos objetos criados por meio da instaciação.

### Denominação de classe

A convenção de nomenclatura Java define regras para denominação de classes, campos e métodos.

Nomes de classes devem ser iniciados com letras maiúsculas, sendo as demais letras em minúsculas.

                 [Imagem]

No caso de nomes compostos de várias palavras, cada inicial deve ser maiúscula para melhorar a legibilidade.
Embora permitido, nao se recomenda o uso de dígitos, cifrão $ ou sublinhado _.

                 [Imagem]

Os campos e métodos da classe devem ser nomes simples formados apenas com letras minúsculas;

                 [Imagem]

Nomes compostos com a primeira inicial minúscula e as demais iniciais maiúsculas.

                 [Imagem]

## Visibilidade

A visibilidade ou acessibilidade permite a restrição do uso de certos elementos da classe.

É com a restrição de acesso que se implementa o encapsulamento de informações e das implementações dentro das classes.

O uso dos especificadores possibilita decidir a visibilidade dos elementos da classe, ou seja, se campos ou métodos podem ser utilizados livres (public);
se devem ficar ocultos (private), evitar seu uso; ou ainda se poderão ser empregados na construção de novas subclasses (protected) por meio do mecanismo de herança.

Quando um especificador de acesso não é explicitado, fica subentendido o nível pacote (package).

Especificadores de Acesso Explícitos: 

  * public
  * protected
  * private

Especificadores de Acesso Implícito:

  * package


Podemos declarar classes empregando os especificadores de acesso

  * public - caso mais comum
  * private - apenas para classes internas

                            [Imagem]
                            

## Campos

Os campos (fields), atributos ou as variáveis-membro de uma classe são variáveis destinadas a armazenar dados que caracterizam o objeto, seu estado ou suas partes.

                            [Imagem]    

Neste exemplo a declaração apresenta um especificador de acesso, o qual define a visibilidade externa desse campo; um tipo primitivo ou classe; o nome do campo;
e uma expressão de inicialização, opcional, que pode determinar um valor inicial para o campo.

                            [Imagem]
                            
Uma classe Pessoa pode reter valores correspondentes ao nome, ao sobrenome e a idade de uma pessoa.

                            [Imagem]

Todos os objetos da classe Pessoa possuirão três campos, dois Strings nome e sobrenome e um inteiro idade independentes,cada objeto terá seus próprios campos, permitindo reter seus valores individuais (estados atual). 

Seja qual for o esecificador de acesso usado, todo campo declarado em uma classe é acessível em qualquer parte de sua implementação.

A criação de um objeto e seu uso na definição de uma pessoa pode ser assim:

                            [Imagem]

Como foi usado o especificador public para os campos da classe Pessoa esses podem ser acessados por uma variável de instância inicializada.

                            [Imagem]

Por meio de uma variável de instância (de classe), o operador . (ponto), denominado seletor, permite escolher qualquer um dos campos acessíveis (públicos)
definidos na classe.

                            [Imagem]

## Métodos

## Assinatura de método

## Tipos de métodos

## Operador seletor

## Parâmetros e argumentos

## Tipo void

## Diretiva return

## Métodos varargs

## Encadeamento de métodos

## Métodos de acesso (getters e setters)

## Construtores

## Representação de classe com UML

## Sobrecarga de métodos e construtores

## Membros estáticos

## Constantes

## Referência this

## Finalizadores e coleta de lixo

## Exceções
