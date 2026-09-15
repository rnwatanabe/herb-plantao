# Engenharia Clínica — Hospital Estadual Represa Billings

Repositório criado em 15/09/2026 como AÇÃO CORRETIVA do evento adverso de 13/09/2026
(monitor VTL-4471, leito UTI-07, alarme de bradicardia que não disparou).

A investigação mostrou que o perfil de alarmes do monitor foi trocado durante uma
atualização de firmware sem que ninguém percebesse. A partir de agora, TODA alteração
de perfil de alarme, laudo ou inventário é registrada neste repositório, com autor,
data e motivo (rastreabilidade — RDC 509/2021).

| Pasta / arquivo                 | Conteúdo                                                   |
|---------------------------------|------------------------------------------------------------|
| `setores/<SETOR>/README.md`     | Equipamento do setor e perfil de alarmes APROVADO          |
| `setores/<SETOR>/perfil_alarme.cfg` | Perfil de alarmes configurado no equipamento           |
| `setores/<SETOR>/laudos/`       | Laudos de ensaio (não podem ser alterados)                 |
| `setores/<SETOR>/checklist_plantao.md` | Ficha do plantão de auditoria                       |
| `inventario/reservas/`          | Equipamentos reserva e o setor de cada um                  |

Regras:
1. Dados de pacientes (sinais vitais, prontuários) NUNCA entram neste repositório (LGPD).
2. Nenhuma mudança de perfil de alarme entra na main sem a revisão de outra pessoa.
3. O histórico não pode ser reescrito: erros são corrigidos com novos commits.
