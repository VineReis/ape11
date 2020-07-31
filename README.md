# Atividade Projeto Estruturado - APE11          
Nome: Vinicius Reis Batista                    
RA: 09010003                                   
Curso: Sistemas de Informação                  
Polo: Cascavel-PR                              

# Pergunta 01 - O que é o Git?
Resposta: O Git é um sistema open-source de controle de versão utilizado pela grande maioria dos desenvolvedores atualmente. Com ele podemos criar todo histórico de alterações no código do nosso projeto e facilmente voltar para qualquer ponto para saber como o código estava naquela data.
Além disso, o Git nos ajuda muito a controlar o fluxo de novas funcionalidades entre vários desenvolvedores no mesmo projeto com ferramentas para análise e resolução de conflitos quando o mesmo arquivo é editado por mais de uma pessoa em funcionalidades diferentes.
Criado por Linus Torvalds, Engenheiro de Software responsável pela criação do Kernel do Linux, Linus criou o Git porque o BitKeeper desligou seu serviço gratuito e então criou o Git sozinho porque nenhum dos outros sistemas de controle de versão atendia às suas necessidades.

# Pergunta 02 - O que é versionamento de Software?
Resposta: O versionamento de software é um processo de controle de versões estabelecido por meio de numerações diferentes. Isso permite que os programadores saibam quando e quais alterações foram realizadas, acompanhando as mudanças aplicadas no software. Além disso, permite que os usuários finais identifiquem as novidades e reconheçam as versões mais atualizadas.
Para o versionamento, pode-se atribuir um número único ou um conjunto deles para especificar a versão utilizada de um programa de software, arquivo, firmware, driver de dispositivo ou mesmo hardware. À medida que as edições e atualizações vão sendo implementadas no programa, o número da versão deve aumentar.
Isso significa que você pode comparar o número da versão de qualquer software instalado no seu computador ou dispositivo móvel com o número da versão mais atualizada disponível atualmente e fazer um update para usar a versão mais nova.

# Pergunta 03 - Por que utilizar o Git como controle de versionamento?
Resposta: O Git é ótimo para o uso de versionamento devido a sua praticidade e agilidade no quesito instalação e configuração. Sendo um sistema Open-Source, ele possui integração com diversos softwares, onde realizamos diversas configurações que deixam para nós, programadores, mais fácil de mostrar a clientes e demais desenvolvedores as etapas de criação do Sistema e o que foi mudado nas versões atuais para as versões anteriores as criadas.
Um dos motivos principais de se usar o Git é o preço, onde o mesmo deixa gratuito para a colocação de repositórios públicos, e deixa até 3 diretórios privados onde para o aumento, deve-se efetuar o pagamento.

# Pergunta 04 - Quais as vantagens do Git?
Resposta: Rapidez: como os processos são operados localmente, deixa de ser preciso contactar o servidor central para proceder a operações como um commit, log ou diff.

Autonomia: permite trabalhar em modo desconectado, em qualquer local, só sendo necessária uma conexão com a rede para troca de revisões com outros repositórios.

Ramos individuais: contrariamente aos chamados sistemas centralizados, combinar ramos não é uma obrigação para cada commit e antes uma decisão que depende do programador; o trabalho local faz-se num ramo individual que não tem interferência com os demais ramos, mesmo em processos de sincronização entre repositórios.

Facilidade na Fusão: os DVCS (Distributed Version Control – Controle de Versão Distribuído) usam o rastreamento automático, o que facilita de forma significativa o processo de fusão.

Confiabilidade: com um sistema centralizado, qualquer problema que surja no servidor vai parar todo o trabalho de desenvolvimento. Um sistema distribuído permite que a equipa continue a trabalhar e os repositórios dos programadores servem como cópias de backup, não havendo riscos de perder nada do projeto.

Redução de custos com o servidor: o repositório "central" (se ele existir) funciona como repositório "oficial", ao invés de ter uma função de processador central dos pedidos. Assim, a carga de processamento é distribuída pelas máquinas dos programadores.

# Pergunta 05 - Qual a importância da utilização do controle de versionamento no desenvolvimento de um software?
Resposta: Análise de Ameaças: Em uma realidade marcada pela interconectividade e por organizações globais, as ameaças à segurança dos sistemas responsáveis por essas conexões têm o potencial de gerar grandes prejuízos. Como se não bastasse, elas se renovam e ressurgem a cada dia.
O processo de versionamento permite a proteção do código-fonte do sistema. Já o sequenciamento lógico das atualizações serve como registro histórico para a análise dos erros e ataques sofridos, o que possibilita também a reformulação dos sistemas para versões mais robustas.

Reparação de Bugs: O controle de versão fornece ao desenvolvedor o acesso total à codificação realizada em determinado programa ao longo do tempo. Essa facilidade favorece um alto grau de qualidade do trabalho realizado pelos programadores, uma vez que todo o trabalho pode ser revisto, alterado e corrigido.
Caso alguma atualização não seja bem recebida pelo mercado ou provoque algum tipo de insatisfação, é possível também regredir à versão anterior ao seu lançamento. Essa versatilidade no manuseio do software só é permitida devido ao versionamento.

Alterações de Arquitetura: Devido à velocidade com que a tecnologia evolui, muitas alterações precisam ser implementadas nas mais diferentes etapas de desenvolvimento principalmente após a entrega do software. Essas alterações implicam necessariamente em novos códigos que podem provocar grandes alterações de arquitetura do programa, levando à formação de uma nova versão.
Graças ao versionamento, é possível acompanhar tal evolução de maneira muito mais fácil e prática no que diz respeito tanto aos controles internos dos profissionais desenvolvedores quanto ao reconhecimento das alterações por parte do usuário final.

Potencialização do Trabalho Colaborativo: O trabalho em equipe e a colaboração entre os times representam enormes vantagens para o desempenho organizacional. Porém, quando falamos dos sistemas de informação, o uso simultâneo de softwares compartilhados pode levar a erros provocados por falha humana.
Por meio de um processo de versionamento, é possível reconhecer facilmente qualquer alteração nos programas utilizados, tornando o trabalho em conjunto mais produtivo e sem riscos à segurança da informação.

Upgrades Estéticos: Sistemas da informação surgem diante da necessidade de facilitar o trabalho humano, tornando-o mais eficiente e eficaz. Com esse objetivo em mente, os softwares e dispositivos mais recentes têm buscado aprimorar a experiência de uso para algo mais intuitivo e de fácil manuseio.
Buscando um aprimoramento, melhorias são adotadas com layouts responsivos, ao passo que designs mais atrativos, cores, botões e imagens chamativas provocam alterações significativas de códigos. Sem um sistema de controle de versão, a atividade de acompanhamento em cada uma dessas alterações se torna muito complicada.

# Pergunta 06 - Cite pelo menos três ferramentas de controle de versão e faça um breve detalhamento sobre cada uma delas.
Resposta: CVS: A CVS é uma das ferramentas de controle de software mais antigas no mercado. A primeira versão dela foi desenvolvida em 1968. Essa ferramenta possui como maior desvantagem o fato de ser considerada como uma tecnologia antiga. Porém, ainda é bastante utilizada por equipes de desenvolvedores.
É muito simples de ser operada. Isso significa que a sua equipe pode aprender rapidamente como usar todas as funcionalidades da CVS com eficiência.

Subversion: No meio corporativo, o Subversion é uma ferramenta de controle de versão de software bastante utilizada. Ela é bastante rápida na execução das funcionalidades do sistema e ainda se mostra como uma das mais simples de ser empregada. Isso significa que com um conhecimento básico de conceitos relacionados ao controle de versão de software é possível executar comandos na ferramenta. A aprendizagem da equipe também é rápida nesse aspecto.
Um dos problemas do Subversion são as críticas relacionadas à eficácia do software. No passado, essa ferramenta apresentou problemas na hora de executar as principais funções de um controle de versão de software eficiente. Porém, as últimas versões lançadas parecem ter solucionado tudo que foi apontado como desvantagem do programa.
Por fim, o Subversion é uma ferramenta de controle de versão centralizada. Isso significa que não é indicada para todas as equipes de TI, apenas para aquelas que são menores (com apenas algumas dezenas de desenvolvedores) e estão reunidas em um mesmo espaço físico.

TFS: O TFS, sigla para Team Foundation Server, é uma outra ferramenta de controle de versão de software que pode ser utilizada na sua empresa. Ele traz uma série de características interessantes, principalmente se você utiliza metodologias agile no setor de TI da sua empresa.
Isso porque ele possibilita a gestão de projetos por meio de SCRUM ou CMMI. Também permite a utilização de forma centralizada ou distribuída, sendo adequado tanto para equipes que compartilham o mesmo espaço físico quanto aquelas que trabalham à distância. Outra vantagem apresentada por esse sistema é o fato de não possuir limitações de crescimento e ter integração direta com o Microsoft Office.







