# POO
O que é:

Classes: é a representação de um objeto da vida real, um "molde" com os atributos e metodos de um objeto.

Objeto: é a classe instanciada, podemos dizer que é a classe sendo posta em pratica e se tornando real dentro do programa.

Principais Pilares de POO

Abstração: abstrair um objeto da vida real consciderando unicamente os atributos importantes para o contexto

Encapsulamento: protejer uma classe e impor limites para suas propriedades

Herança: permite a reutilização de atributos e metodos de outra classe

Polimorfismo: 

Override(sobrescrever): sobrescrever metodos dos pais nas classes filhas, deixar os metodos mais expecificos para uma situação
Overload(sobrecarga): fazer versoes do mesmometodo com parametros diferentes

  virtual: no pai siguinifica que pode se sobrescrever
  override: no filho, é usado pra sobrescrever

Classe abstrata: uma classe que só pode servir de modelo, não podendo ser instanciada, mas unicamente ser herdada por outras
  Metodos abstratos: não possui corpo, mas sua implementação nos filhos é obrigatorio

Classe selada: classe que não pode ser herdada
  metodo selado: metodo que não pode ser sobrescrito

Classe Object: no C# todas as classes herdam indiretamente da classe object, já vindo com metodos padroes

Interface: é um contrato implementado por uma classe, tem metodos abstratos e tambem não pode ser instanciada, uma interface obriga a classe que está a implementando a implementar tudo que não há corpo nela, caso um metodo tenha corpo, ele não será obrigatorio
