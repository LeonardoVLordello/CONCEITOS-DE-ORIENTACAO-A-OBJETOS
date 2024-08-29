## O que é POO?
É um modelo de programação que organiza o software em “objetos”. Esses objetos são instâncias de “classes”, que definem propriedades (dados) e métodos (funções) que os objetos podem ter.

## conceitos 
bom vamos la, para iniciarmos nos conceitos vamos usar o exemplos de um carro

    Classe
     Um modelo ou molde que define as características e comportamentos dos objetos. 
     Por exemplo, uma classe “Carro” pode ter propriedades como cor e modelo, 
     e métodos como acelerar e frear.
    
    Objeto
     Uma instância de uma classe. Se a classe é “Carro”,
     um objeto pode ser um carro específico, como um “Carro Vermelho Modelo X”.

    Encapsulamento
     Esconde os detalhes internos de um objeto e expõe apenas o que é necessário.
     Isso é feito usando modificadores de acesso como private, protected e public.
     Exemplo : um carro vermelho modelo X e um carro particular onde so que tem acesso 
     pode entrar, ja um onibus de modelo X e algo publico onde todo podem subir.

    Herança
     Permite que uma classe herde propriedades e métodos de outra classe. 
     Por exemplo, uma classe “Veículo” pode ser a superclasse de “Carro” e “Moto”.

    Polimorfismo
     A capacidade de um método se comportar de diferentes maneiras, 
     dependendo do objeto que o invoca. Isso pode ser feito através de 
     sobrecarga e sobrescrita de métodos.
     Exemplo: Modificarmos a cor do carro modelo x vemelho para azul

    Abstração
     Simplifica a complexidade ao ocultar detalhes desnecessários 
     e mostrar apenas as funcionalidades essenciais.

Alem desses conceitos temos outros que sao mais aprofudados

    Composição
      É uma forma de criar objetos complexos a partir de objetos mais simples.
      Em vez de herdar de uma classe, um objeto é composto por outros objetos. 
      Exemplo: uma classe “Carro” pode ter objetos “Motor”, “Roda”, “Porta”, etc.

    Agregação
      É uma relação entre duas classes que permite que uma instância de uma 
      classe interaja com uma instância de outra classe. 
      exemplo: um “Professor” pode estar associado a várias “Turmas”.

    Interface
       Define um contrato que outras classes devem seguir. 
       Uma interface especifica métodos que devem ser implementados, 
       mas não fornece a implementação desses métodos.

    Sobrecarga de Métodos
        Permite que uma classe tenha mais de um método com o mesmo nome, 
        desde que tenham diferentes assinaturas (número ou tipo de parâmetros). 
        Isso facilita a criação de métodos que podem lidar com diferentes tipos de dados.

    Sobrescrita de Métodos
        Permite que uma subclasse forneça uma implementação específica de um método que 
        já é definido em sua superclasse. Isso é útil para personalizar ou estender 
        o comportamento herdado.

    Delegação
        É um padrão onde um objeto externo é chamado para executar uma tarefa específica.
        Em vez de herdar comportamento, um objeto delega a responsabilidade para outro objeto.
   
