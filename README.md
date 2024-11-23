# Sistema de Instrumentos Musicais

## 📝 Descrição
Este projeto implementa um sistema de gerenciamento de instrumentos musicais utilizando conceitos de Programação Orientada a Objetos (POO). O sistema demonstra o uso prático de herança, polimorfismo, abstração e encapsulamento através de uma hierarquia de classes de instrumentos musicais.

## 🔨 Funcionalidades
- Classe abstrata base para Instrumentos Musicais
- Implementações específicas para diferentes tipos de instrumentos (Violão e Piano)
- Gerenciamento de estado dos instrumentos (afinação)
- Métodos específicos para cada tipo de instrumento
- Sistema de verificação de afinação antes de tocar

## 🛠️ Tecnologias Implementadas
### Versão JavaScript
- JavaScript (ES6+)
- Classes e Herança
- Tratamento de Exceções
- Métodos e Propriedades
- Simulação de Classes Abstratas


## 📚 Estrutura do Projeto
```
instrumentos-musicais/
│
├── javascript/
│   └── instrumentos.js 
│
└── README.md
```

## 🚀 Como Executar

### JavaScript
```bash
# Execute via Node.js
node instrumentos.js

# Ou abra no navegador
# Abra o console do navegador para ver os resultados
```


## 📋 Classes e Hierarquia

### InstrumentoMusical (Classe Abstrata)
- Atributos base: marca, modelo, preço
- Estado de afinação
- Método abstrato: tocar()
- Método concreto: afinar()

### Violao (Classe Concreta)
- Herda de InstrumentoMusical
- Atributos específicos: tipo (aço/nylon), número de cordas
- Implementa método tocar()
- Método adicional: trocarCordas()

### Piano (Classe Concreta)
- Herda de InstrumentoMusical
- Atributos específicos: tipo de piano, número de teclas
- Implementa método tocar()
- Método adicional: regularPedais()

## 🎯 Conceitos de POO Demonstrados

1. **Abstração**
   - Classe base abstrata
   - Métodos abstratos

2. **Encapsulamento**
   - Atributos privados/protegidos
   - Métodos de acesso

3. **Herança**
   - Hierarquia de classes
   - Reuso de código

4. **Polimorfismo**
   - Sobrescrita de métodos
   - Comportamentos específicos por tipo

## 💡 Exemplos de Uso
```javascript
// Criando instrumentos
const violao = new Violao("Yamaha", "C40", 800.00, "Nylon");
const piano = new Piano("Casio", "CDP-S100", 3200.00, "Digital");

// Utilizando os instrumentos
violao.afinar();
violao.tocar();
piano.regularPedais();
```

## 🤝 Contribuindo
Sinta-se à vontade para contribuir com este projeto. Algumas sugestões:
- Adicionar novos tipos de instrumentos
- Implementar novas funcionalidades
- Melhorar a documentação
- Adicionar testes unitários

## ✅ Checklist de Implementação
- [x] Classe abstrata base
- [x] Duas classes herdeiras
- [x] Três instâncias de objetos
- [x] Métodos específicos por instrumento
- [x] Validações e tratamento de erros
- [x] Documentação básica




---
Desenvolvido para demonstração de conceitos de Programação Orientada a Objetos
