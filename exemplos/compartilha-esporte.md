# Exemplo fictício — CompartilhaEsporte
**Todo o cenário, os dados, os testes e os resultados abaixo são simulados para fins formativos.** Não são resultados da experiência de origem. Adaptação do exemplo no IPIT_origin. O professor pode consultá-lo antes; mostre à turma após as primeiras ideias para reduzir cópia.

## Planejamento docente ilustrativo
- Componente: introdução à programação e organização de dados.
- Objetivo: representar entrada, regra e saída e justificar uma solução a partir de evidência.
- Turma: iniciantes que já conhecem planilhas; equipes de quatro.
- Tempo: roteiro de 240 minutos do guia.
- Recursos: uma planilha por equipe, papel e projetor; alternativa com cartões.
- Evidências: fichas, regra explicada, teste com dado fictício e reflexão.
- IA: consulta coletiva opcional para antecipar casos de teste; verificação pela turma.
- Avaliação: quatro critérios da rubrica, com observação e reflexão individual.

## Investigar
Problema: estudantes não sabem quais materiais esportivos estão disponíveis para empréstimo no intervalo.
Público: estudantes e pessoa responsável pelos materiais.
Evidência simulada: um conjunto didático de cinco situações contém três solicitações de itens já emprestados. Isso sustenta o exercício, não uma conclusão sobre uma escola real.
Hipótese pendente: consultar disponibilidade antes de solicitar reduziria essas tentativas.

## Idear
Alternativa A: quadro manual de disponibilidade; simples, mas atualização depende do responsável.
Alternativa B: planilha de consulta; permite representar regra e organizar dados, mas exige dispositivo e atualização.
Escolha didática: B, por permitir trabalhar organização de dados e condições. No contexto real, a equipe precisaria confirmar infraestrutura e rotina de atualização.
Escopo: consultar disponibilidade e simular uma solicitação. Sem cadastro, nomes, banco de dados ou aplicativo completo.

## Prototipar
Planilha com itens fictícios: bola A, bola B e rede C, com estados “disponível” ou “emprestado”.
Entrada: código do item.
Regra: verificar o estado.
Saída: “solicitação possível” ou “item indisponível”.
Fluxo: consultar → selecionar → receber retorno. A confirmação de entrega é simulada e depende do responsável.
Alternativa offline: cartões de item e estado, com a mesma regra explicada oralmente.

## IA: registro ilustrativo
Ferramenta: demonstração de IA generativa; modelo não informado.
Instrução: sugerir casos de teste para consulta de disponibilidade sem dados pessoais.
Sugestão aproveitada: testar item indisponível e código inexistente.
Verificação humana: a equipe compara a sugestão com a regra e simula as entradas.
Alteração: acrescenta mensagem para código inexistente.
Limite: a IA não verificou a rotina real nem demonstrou demanda.

## Testar e melhorar — simulação
| Tarefa | Esperado | Observado | Ajuste |
|---|---|---|---|
| Consultar bola B, emprestada | Aviso de indisponibilidade | Mensagem compreendida | Manter |
| Informar item inexistente | Aviso para rever código | Retorno vazio | Acrescentar mensagem de item não encontrado |

Novo teste simulado: código inexistente passa a produzir aviso. Próximo teste real: verificar com usuários se conseguem consultar sem ajuda. O protótipo não gerencia empréstimos reais.

## Avaliação e reflexão ilustrativas
Compreensão do problema: consistente no cenário simulado, reconhecendo limite da evidência.
Solução: em desenvolvimento; regra clara, mas atualização dos estados ainda precisa ser resolvida.
Teste: consistente para os casos descritos, sem comprovar adoção real.
Colaboração: exige observação docente; não pode ser inferida somente destes arquivos.

Reflexão individual fictícia: “Aprendi a distinguir dado de entrada e resultado. Ajudei a definir a mensagem para código inexistente. Na próxima versão, testaria como atualizar a disponibilidade.”
