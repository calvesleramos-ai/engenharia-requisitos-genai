# Diagrama de Casos de Uso

Diagrama de casos de uso do Sistema de Gestão de Eventos da Eventus.

## Atores

- Participante
- Organizador
- Equipe Financeira
- Palestrante
- Equipe de TI

## Casos de Uso

O diagrama deverá representar as principais interações dos atores com o sistema.
                  SISTEMA EVENTUS

Participante ────────┬── Consultar eventos
                     ├── Inscrever-se
                     ├── Cancelar inscrição
                     ├── Consultar inscrição
                     ├── Consultar programação
                     └── Emitir certificado

Organizador ─────────┬── Criar evento
                     ├── Gerenciar vagas
                     ├── Gerenciar inscrições
                     ├── Gerenciar lista de espera
                     └── Consultar indicadores

Financeiro ──────────┬── Confirmar pagamento
                     └── Processar reembolso

Palestrante ─────────┬── Consultar atividades
                     └── Consultar participantes

TI ──────────────────┬── Administrar usuários
                     └── Administrar sistema
