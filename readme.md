# Clinica Estetica - Sistema de Agendamento

Este projeto consiste em um sistema de agendamento para a Clinica de Estética, com páginas para agendamento de serviços e consulta de agendamentos existentes.

## Estrutura do Projeto

O projeto é composto por três páginas principais:

1. **Página Inicial (index.html)**
   - Página de entrada com duas opções: "Agendar" e "Consultar Agenda"
   - Serve como ponto central de navegação para o sistema

2. **Página de Agendamento (agendamento.html)**
   - Permite ao cliente selecionar serviços, datas, barbeiros e horários
   - Coleta informações do cliente para finalizar o agendamento
   - Exibe confirmação após o agendamento ser concluído

3. **Página de Consulta (consultar.html)**
   - Permite ao cliente buscar seus agendamentos por telefone ou nome
   - Exibe os agendamentos encontrados com detalhes
   - Oferece opções para reagendar ou cancelar agendamentos

## Tecnologias Utilizadas

- HTML5
- CSS3 (com Tailwind CSS via CDN)
- JavaScript (vanilla)
- Font Awesome para ícones

## Funcionalidades

### Página Inicial
- Interface limpa e intuitiva com duas opções principais
- Animações suaves para melhorar a experiência do usuário
- Design responsivo para funcionar em dispositivos móveis e desktop

### Página de Agendamento
- Seleção de serviços com descrições e preços
- Seleção de data com calendário horizontal deslizável
- Escolha de barbeiro com base na especialidade
- Seleção de horário disponível
- Formulário para informações do cliente
- Confirmação visual do agendamento

### Página de Consulta
- Busca de agendamentos por telefone ou nome
- Exibição de agendamentos com status (confirmado, pendente, cancelado)
- Opções para reagendar ou cancelar agendamentos
- Feedback visual quando nenhum agendamento é encontrado

## Como Usar

1. Abra o arquivo `index.html` em um navegador web
2. Na página inicial, escolha entre "Agendar" ou "Consultar Agenda"
3. Siga as instruções em cada página para completar a ação desejada

## Identidade Visual

O projeto segue uma identidade visual consistente com:

- Paleta de cores em tons de azul (primária) e cinza/azul escuro (secundária)
- Tipografia clara e legível
- Componentes com bordas arredondadas e sombras sutis
- Animações e transições suaves
- Ícones intuitivos para melhorar a compreensão

## Observações

- Este é um protótipo funcional com simulação de backend
- Os dados não são persistidos entre sessões
- Para fins de demonstração, a busca na página de consulta sempre mostra resultados, exceto quando o telefone é "(11) 99999-9999" ou o nome é "sem resultados"

