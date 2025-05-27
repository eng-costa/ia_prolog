# Diagnóstico de Falhas em Veículo Autônomo - Prolog

Este projeto implementa um sistema especialista simples para diagnóstico de falhas em veículos autônomos, utilizando a linguagem Prolog. O sistema é capaz de identificar possíveis causas de falhas com base em sintomas fornecidos, e recomendar ações corretivas.

## 👨‍💻 Autores

Este projeto foi desenvolvido como atividade acadêmica por:

- **Lucas Silva Costa**
- **Eurderlan Freire da Silva Abreu**
- **Hissa Barbara Oliveira**

## 🧠 Objetivo

O objetivo da atividade foi completar e aprimorar um código base fornecido pelo professor, aplicando regras lógicas e conhecimentos em inteligência artificial simbólica para simular diagnósticos automáticos baseados em sintomas observáveis no veículo.

## 🛠️ Funcionalidades

- Diagnóstico de falhas comuns em veículos autônomos, incluindo:
  - Bateria fraca
  - Alternador defeituoso
  - Superaquecimento do motor
  - Baixo nível de óleo
  - Vela de ignição defeituosa
  - Sensor de oxigênio com problema
  - Falhas no sistema de injeção
  - Problemas na transmissão
  - Defeitos internos no motor
- Regras baseadas em sintomas como:
  - Luzes de advertência
  - Leituras de sensores
  - Barulhos anormais
  - Rotação do motor
- Recomendações específicas para cada diagnóstico
- Casos de teste simulados para validação do sistema
- Limpeza automática do estado entre testes

## 📋 Estrutura do Código

- **Predicados dinâmicos**: para armazenar sintomas detectados dinamicamente.
- **Fatos e regras**: associam sintomas a possíveis causas de falha.
- **Recomendações**: sugerem ações corretivas para cada diagnóstico.
- **Casos de teste**: simulações que ajudam a verificar a eficácia do sistema.
- **Interface `main`**: executa todos os casos ou permite interação (com opção de menu ou pausa, se preferido).

## ▶️ Execução

Para executar o sistema em um interpretador Prolog (ex: SWI-Prolog):

1. Carregue o arquivo:
   ```prolog
   ?- [main.].
