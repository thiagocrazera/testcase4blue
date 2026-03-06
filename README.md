# Test Case 4blue
# Teste Técnico – QA Tester – 4blue

## Ambiente de Teste
Sistema testado: https://qa-play-sim.lovable.app/

Navegador utilizado: Google Chrome  
Sistema operacional: Windows  

## Metodologia de Teste

Durante a análise do sistema foram aplicadas técnicas de:

- Testes exploratórios
- Testes funcionais
- Testes negativos (validação de campos)
- Avaliação básica de segurança
- Avaliação de experiência do usuário (UX)

---

# Bugs Encontrados

## 1. Cadastro permite envio de campos obrigatórios vazios

Descrição:
O sistema permite criar conta mesmo sem preencher os campos obrigatórios.

Passos:

Acessar tela "Criar conta"

Deixar campos vazios

Clicar em "Criar conta"

Resultado atual => Conta criada com sucesso.

Resultado esperado => Sistema deve bloquear envio e apresentar mensagem de erro.

Severidade: Alto
Prioridade: Alta
