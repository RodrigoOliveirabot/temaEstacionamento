#  Descansador de Carros

 Integrantes da Equipe:
 Rodrigo Camargo de Oliveira
 Ruan Gabriel Benatti

Tema:
Estacionamento — Gestão operacional e reservas para estacionamentos

Objetivo do Sistema:
O Descansador de Carros é um sistema desenvolvido para otimizar a rotina de estacionamentos.Ele permite que os funcionários tenham controle total dos veículos estacionados e das operações do local, ao mesmo tempo em que oferece aos clientes a praticidade de reservar vagas antecipadamente.

Tecnologias Utilizadas:
Linguagem: C# 
Banco de Dados: MySQL 
Prototipagem: Figma 

 Descrição do Funcionamento:

O acesso ao sistema é realizado via tela de login, onde o usuário é identificado de acordo com seu perfil:
 Perfil Cliente: Pode visualizar vagas disponíveis em tempo real, realizar reservas antecipadas e efetuar o pagamento da reserva.
 Perfil Funcionário: Gerencia as vagas, efetua o cadastro manual de reservas/veículos no local, edita informações de usuários/veículos e calcula o valor do tempo de permanência.

 Principais atores:
Clientes: Condutores de veículos que buscam reservar e pagar por vagas de forma prática.
Funcionários / Operadores:** Profissionais responsáveis pela gestão diária do estacionamento, veículos e atendimento.


 Levantamento de Requisitos:

 Requisitos Funcionais:
1: Cadastro de Clientes
2: Cadastro de Funcionários
3: Cadastro e Gestão de Vagas
4: Cadastro e Edição de Veículos
5: Reserva de Vagas (por Clientes e Funcionários)  
6: Determinação e controle do tempo de permanência
7: Cálculo do valor referente ao tempo de permanência
8: Exibição em tempo real da quantidade de vagas disponíveis
9: Pagamento online da reserva (Perfil Cliente)
10: Edição de dados de perfil (Cliente e Funcionário)

 Requisitos Não Funcionais (RNF)
* RNF01 (Usabilidade): Interface intuitiva e de fácil navegação, para usuarios com um pre conhecimento em C#.
* RNF02 (Desempenho): Respostas rápidas(40ms) e atualização de até 50ms para o status da vagas.
* RNF03 (Confiabilidade): Garantia da integridade dos dados de pagamentos e reservas.
* RNF04 (Disponibilidade): O sistema deve estar disponível continuamente para consultas e reservas.
* RNF05 (Manutenibilidade): Código modular para facilitar atualizações e correções futuras.


  Protótipo das Telas:
O protótipo interativo das telas do sistema foi desenvolvido no Figma e pode ser acessado pelo link abaixo:
(https://www.figma.com/proto/bpD6mZIAZ9H4joWTtchJSh/Prototipo-do-DESCANSADOR-DE-CARROS?node-id=0-1&t=xVZcSZZvQxI4KNAS-1)


