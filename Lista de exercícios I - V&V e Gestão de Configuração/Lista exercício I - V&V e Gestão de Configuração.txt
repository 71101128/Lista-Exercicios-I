[VOLTAR](https://github.com/71101128/Lista-Exercicios-I)

# Lista exercício I - V&V e Gestão de Configuração

## 1. Qual o principal objetivo da validação e verificação? 
* Validação: estamos construindo o produto correto?

>Ela mostra que o sw realiza o que o cliente espera que ele faça.
>Especificações de software nem sempre refletem os reais desejos ou necessidades dos usuários.
		
* Verificação: estamos construindo o produto corretamente?

>Envolve verificar se o software está de acordo com as especificações.
>Verificar se ele atende aos requisitos funcionais e não-funcionais especificados.

## 2. Qual a diferença entre validação e verificação? 
 	
> A validação foca em confirmar se o produto de acordo com a expectativa do usuário
> A verificação foca em confirmar se o produto segue a documentação e as boas práticas

## 3. Qual a diferença entre as técnicas de validação e verificação dinâmica e estática? Dê exemplos. 
* Dinâmica

> código fonte.
> documento de requisitos.
> modelo de projeto.
> qualquer representação legível do software.

* Estática

> código fonte.
> documento de requisitos.
> modelo de projeto.
> qualquer representação legível do software.

## 4. Qual o objetivo da inspeção de software? 
#### A inspeção deverá focar:
> detecção de erros.
> conformidade aos padrões.
> programação de baixa qualidade (conhecida gambiarra ou POG).

## 5. Em quais artefatos são realizadas inspeções de software? 
> código fonte.
> documento de requisitos.
> modelo de projeto.
> qualquer representação legível do software.

## 6. O que é um checklist de inspeção? 
> lista de verificações que o tester deve seguir para garantir a qualidade dos testes

## 7. Quais os 7 princípios do teste? 
* PRINCÍPIO 1: Teste demonstra a presença de defeitos

> O teste pode demonstrar a presença de
> defeitos, mas não pode provar que eles
> não existem. O Teste reduz a
> probabilidade que os defeitos
> permaneçam em um software, mas
> mesmo se nenhum defeito for
> encontrado, não prova que ele esteja
> perfeito.

* PRINCÍPIO 2: Teste exaustivo é impossível

> Testar tudo (todas as combinações de
> entradas e pré-condições) não é viável,
> exceto para casos triviais. Em vez do
> teste exaustivo, riscos e prioridades são
> levados em consideração para dar foco
> aos esforços de teste.

* PRINCÍPIO 3: Teste antecipado

> A atividade de teste deve começar o
> mais breve possível no ciclo de
> desenvolvimento do software ou
> sistema e deve ser focado em objetivos
> definidos.

* PRINCÍPIO 4: Agrupamento de defeitos

> Um número pequeno de módulos
> contém a maioria dos defeitos
> descobertos durante o teste antes de
> sua entrega ou exibe a maioria das
> falhas operacionais.

* PRINCÍPIO 5: Paradoxo do pesticida

> Pode ocorrer de um mesmo conjunto de
> testes que são repetidos várias vezes
> não encontrarem novos defeitos após
> um determinado momento. Para
> superar este “paradoxo do pesticida”, os
> casos de testes necessitam ser
> frequentemente revisado e atualizado.
> Um conjunto de testes novo e diferente
> precisa exercita diferentes partes do
> software ou sistema com objetivo de
> aumentar a possibilidade de encontrar
> mais erros.

* PRINCÍPIO 6: Teste depende do contexto

> Testes são realizados de forma diferente
> conforme o contexto. Por exemplo,
> softwares de segurança crítica são
> testados diferentemente de um
> software de comércio eletrônico.

* PRINCÍPIO 7: A ilusão da ausência de erros

> Encontrar e consertar defeitos não
> ajuda se o sistema construído não
> atende às expectativas e necessidades
> dos usuários.

## 8. Defina teste de integração, teste de unidade, teste de aceitação, teste de regressão, teste de sistema e teste de desempenho. 
* teste de integração

> Têm por objetivo verificar
> se as unidades que
> compõem cada liberação
> funcionam corretamente

* teste de unidade

> Preocupa-se com a forma que o sistema é feito.
> O testador deve entender o código para gerar
> os casos de teste, caso estes sejam feitos após
> a codificação.

* teste de aceitação

> Valida o produto.
> Verifica se atende os requisitos.

* teste de regressão

> Verificam se alterações em segmentos do sistema
> não afetam as partes já testadas.

* teste de sistema

> O testador de software
> deve ter a postura de
> encontrar erros no
> programa.

* teste de desempenho
> Basicamente valida aspectos não funcionais do sistema

## 9. Quais os principais exemplos de testes de desempenho? Cite aplicações práticas para cada exemplo. 
* Números de acessos simultâneos ao banco de dados.
* Número de clientes simultâneos ligados ao servidor.
* Tempo gasto para trocar de tela.
* Tempo gasto para acessar a base de dados.
* Número de operações executadas.

## 10. O teste de aceitação pode ser subdividido em quais tipos de teste? Explique cada tipo identificado. 
* Testes funcionais
* Verificação do atendimento dos requisitos funcionais. 
* Testes de sistema
* Verificação do atendimento dos requisitos não funcionais. - Testes Alfa, Testes Beta.

## 11 . O que é teste caixa branca e teste de caixa preta? 
* Teste caixa branca

> quando os testes são feitos com acesso ao código por exemplo

* Teste caixa preta

> Exercita as interfaces do sistema

## 12. O que é Gerenciamento de Configuração de Software e como pode ser usada no desenvolvimento de software? 
> Desenvolvimento e o uso de padrões e
> procedimentos para o gerenciamento de
> software em desenvolvimento

## 13. Defina os conceitos abaixo relacionados a Gerência de Configuração de Software. 
### a. Baseline 
> É uma configuração formalmente
> aprovada para servir de referência para
> o desenvolvimento posterior do
> sistema

### b. Versionamento 
> é agrupar os entregáveis em versões para conseguir recuperar um estado posteriormente se necessário sem a necessidade de ficar tentando descobrir o que fazia ou não parte de uma determinada entrega

## 14. Quais são as principais tarefas dentro de um Processo de Gerência de Configuração de Software?  
* Definem como registrar e processar mudanças de sistema

* Descrevem como relacionar essas mudanças aos componentes do sistema

* Documentam os métodos usados para identificar diferentes versões desse sistema

## 15. O que são itens de configuração? 
* Qualquer componente que precisa ser gerenciado para que se possa entregar o sistema

* Código-fonte, documentos, scripts, executáveis, arquivos de help, manuais, binários, etc.

## 16. Qual a importância do controle de versão durante o desenvolvimento de um software? 
* Desenvolvimento paralelo

> Uma equipe na manutenção na versão 1.0 e
> outra na construção da versão 2.0

* Recuperação de versões anteriores

> Versões de diversos desenvolvedores
> centralizadas
> Repositório único

## 17. Imagine uma situação em que 2 desenvolvedores estão alterando 3 componentes de software simultaneamente. Quais dificuldades podem surgir ao tentar realizar o merge das mudanças? 
> Conflito nas alterações, perda de código e tempo de trabalho

## 18. Sugira 3 problemas que podem surgir caso uma empresa não desenvolva políticas de gerência de configurações. 


## 19. Explique porque é essencial que cada versão de um componente seja identificada unicamente.
> Para facilitar em um caso de rollback caso a nova versão apresente problemas, sem ela seria quase impossível lembrar de tudo que estaria em uma versão e em que estado estava.

[VOLTAR](https://github.com/71101128/Lista-Exercicios-I)
