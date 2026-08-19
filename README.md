# LoadStrat Board

Sistema profissional unificado de gestão de treino para personal trainers. Integra periodização multi-esportes, gestão de clientes, controle financeiro e geração de relatórios em PDF.

## Funcionalidades

- **Periodização Multi-Esportes**: Rastreie treinos de corrida, musculação, pliometria, potência e resistência
- **Gestão de Clientes**: CRUD completo com histórico de sessões
- **Sessões de Treino**: Registre volume, RPE, intensidade e avaliação de risco
- **Controle de Carga**: Cálculo automático de carga (Volume × RPE)
- **Geração de Relatórios**: PDF profissional com análise completa de treino
- **Sincronização Automática**: Lê sessões do site de controle de carga via localStorage
- **Agenda Fixa + Temporária**: Compromissos semanais que se renovam automaticamente + edições pontuais

## Como Usar

1. Abra `index.html` em seu navegador
2. Adicione seus clientes na aba "Clientes"
3. Registre sessões de treino na aba "Periodização"
4. Acesse "Relatórios" para gerar PDF com análise completa
5. Conecte ao seu site de controle de carga (sincronização automática via localStorage)

## Integração com Controle de Carga

O sistema sincroniza automaticamente com seu site de controle de carga:
- Abre o dashboard e o site de controle na mesma sessão do navegador
- A sincronização ocorre a cada 60 segundos
- Sessões são deduplciadas por cliente + data
- Status de sincronização exibido no cabeçalho

## Tema

- Cores profissionais: Grafite (#1a1a1a) e Dourado (#d4af37)
- Interface responsiva
- Persistência de dados via localStorage

## Autor

Paulo Meira - Personal Trainer de Performance & Prevenção
