# 13/02/2025 11h00

### ATIVIDADE 01
"""
What precisely do we mean by software engineering? What distinguishes “software engineering” from “programming” or “computer science”? And why would Google have a unique perspective to add to the corpus of previous software engineering literature written over the past 50 years?
 
The terms “programming” and “software engineering” have been used interchangeably for quite some time in our industry, although each term has a different emphasis and different implications. University students tend to study computer science and get jobs writing code as “programmers.”
 
“Software engineering,” however, sounds more serious, as if it implies the application of some theoretical knowledge to build something real and precise. Mechanical engineers, civil engineers, aeronautical engineers, and those in other engineering disciplines all practice engineering. They all work in the real world and use the application of their theoretical knowledge to create something real. Software engineers also create “something real,” though it is less tangible than the things other engineers create.
 
Unlike those more established engineering professions, current software engineering theory or practice is not nearly as rigorous. Aeronautical engineers must follow rigid guidelines and practices, because errors in their calculations can cause real damage; programming, on the whole, has traditionally not followed such rigorous practices. But, as software becomes more integrated into our lives, we must adopt and rely on more rigorous engineering methods. We hope this book helps others see a path toward more reliable software practices.
"""


O que é "ENGENHARIA DE SOFTWARE"?
De maneira semelhante à outras engenharias, a Engenharia de Software aplica conhecimento teórico para resolver problemas práticos, problemas reais. Mas ao contrário das outras engenharias, não há tanto rigor com normas e cálculos. Software é intengível, é algo lógico, como um pensamento. Em Engenharia de Software, não existe solução, apenas trade-off. 


### ATIVIDADE 02
"""
Programming Over Time
We propose that “software engineering” encompasses not just the act of writing code, but all of the tools and processes an organization uses to build and maintain that code over time. What practices can a software organization introduce that will best keep its code valuable over the long term? How can engineers make a codebase more sustainable and the software engineering discipline itself more rigorous? We don’t have fundamental answers to these questions, but we hope that Google’s collective experience over the past two decades illuminates possible paths toward finding those answers.
 
One key insight we share in this book is that software engineering can be thought of as “programming integrated over time.” What practices can we introduce to our code to make it sustainable—able to react to necessary change—over its life cycle, from conception to introduction to maintenance to deprecation?
 
The book emphasizes three fundamental principles that we feel software organizations should keep in mind when designing, architecting, and writing their code:
 
Time and Change
How code will need to adapt over the length of its life
 
Scale and Growth
How an organization will need to adapt as it evolves
 
Trade-offs and Costs
How an organization makes decisions, based on the lessons of Time and Change and Scale and Growth
"""

Engenharia de Software não é apenas escrever código, mas todas as ferramentas e processos para construir e manter o código ao longo do tempo (programação integrada ao longo do tempo). Em outras palavras, o que fazer para deixar o código sustentável? Como deixar ele fácil de fazer manutenção?

Três pontos fundamentais:
* Como o código vai se adaptar ao longo da vida útil
* Como uma empresa de software vai precisar se adaptar à medida que crece
* Como a empresa toma decisões, com base nas lições aprendidas

Engenharia de Software é PROGRAMAÇÃO + ESCALABILIDADE + TEMPO + TRADE-OFF.

### ATIVIDADE 03
Listar e Exemplificar 3 trade-offs
1) Tempo de compilação X Sintaxe simplificada - A linguagem Python é mais simples, menos verbosa, com uma sintaxe mais fácil para usuários leigos/iniciantes. Porém tem uma tempo de compilação (o tempo que leva para a linguagem ser lida, interpretada, processada pelo hardware) é maior pois há muitas camadas de interpretação, antes de chegar propriamente no processador. Em contraposição, há a linguagem C++ que é muito mais verbosa, com uma sintaxe mais trabalhosa, mas que não precisa ser compilada (não passa por tantas camadas de interpretação).
2) Manutenção - Outro explo de trade-off é a manutenção do código. Escolher linguagens mais verbosas exigem profissionais mais qualificados para fazer a manutenção dele. Porém, garantem que problemas mais complexos (como alocação de memória) sejam resolvidos. Linguagens com a sintaxe mais "fácil" podem ser mais fáceis de fazer manutenção (já que são mais fáceis de identificar os erros), mas não são capazes de resolver problemas de hardware.
3) Funcionalidade X Escalabilidade - Sistemas mais complexos, exigem que a funcionalidade estejam em primeiro lugar na lista de tarefas, mas nem sempre são escaláveis (não podem ser replicadas em diversos servidores). Em contrapartida, são os sistemas mais simples (que normalmente são apenas para roubar dados) tem uma escalabilidade maior.


##### EXEMPLOS DE TRADE-OFF DADOS EM SALA (Requeisitos não funcionais (normalmente usamos adjetivos para requistos não funcionais))
* Portabilidade (Java) X Acessibilidade (Python) - Complexidade de fazer a portabilidade para diversos dispositivos 
* Usabilidade (Windows) X Segurança (Linux) - Linux é baixo nível. Windows é alto nível.
* Simplicidade X Escalabilidade (Bancos antes e após anos 2000)


##### COMENTÁRIO SOBRE O SLIDE 57 (O que é o MVP)
O slide trás uma imagem retratando o que deve ser o Produto Mínimo Viável, usando como um exemplo a construção de um carro. Ele quer mostrar que o MVP tem que trazer soluções que satisfaçam a necessidade do cliente de maneira contínua (mesmo que o cliente não saiba qual é a real necessidade dele). 
O Cliente não quer um carro. Ele quer uma forma de chegar mais rápido em um lugar mais distante.
O Cliente não quer só um produto pronto e acabado. ELe quer algo que funcione e resolva o problema que ele tem (mesmo que em partes). 
Isso significa que trazer pequenas soluções em partes menores ajuda a trazer valor para o projeto.
Dessa forma, o maior desafio passa a ser "Entender o real problema do cliente". 





