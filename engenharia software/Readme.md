atividade 1: O texto fala como o termo "engenharia de software" parece ter um peso igual as outras engenharias como engenharia aeronáutica ou engenharia civil, mas que apesar disso a engenharia de software não é
tão rigorosa como essas outras, terminando dizendo que conforme os softwares ficam mais integrados nas nossas vidas, é necessário que a engenharia de software fique mais rigorosa.

atividade 2: O texto propõe que a engenharia de software não é apenas escrever códigos de programação, mas também a utilização de práticas, processos e ferramentas que certifiquem que o código será duradouro e possa se 
adaptar a mudanças necessárias futuras.

atividade 3:
1. Monolito vs. Microserviços (Arquitetura)
   
   -O Dilema: Decidir a estrutura da aplicação antes de começar a programar.
   
   *Monolito: Todo o código fica em um único projeto. É muito fácil e rápido de programar, testar e publicar.
   
   *Desvantagem: Se uma parte do sistema falhar (ex: módulo de relatórios pesados), o sistema inteiro cai.
   
   
   *Microserviços: O código é dividido em várias APIs independentes. Traz alta escalabilidade e resiliência.
   
   *Desvantagem: O desenvolvimento fica muito complexo, difícil de testar localmente e exige infraestrutura cara (Kubernetes, redes, etc).
   
2. ORM vs. SQL Nativo (Acesso a Banco de Dados)
   
   -O Dilema: Escolher como o código vai conversar com o banco de dados.
   
   *ORM (ex: Hibernate, Entity Framework, Prisma): Você escreve código na sua linguagem (ex: Java, JavaScript) e o ORM cria o SQL sozinho. Aumenta muito a velocidade de entrega.
   
   *Desvantagem: O ORM costuma gerar consultas SQL ineficientes e pesadas, prejudicando a performance em sistemas grandes.
   
   
   *SQL Nativo: Você escreve as queries na mão. Garante performance máxima e controle total sobre o banco.
   
   *Desvantagem: O desenvolvimento fica lento, o código fica gigante e o risco de erros de digitação ou segurança (SQL Injection) aumenta.
   
   
3. Tipagem Estática vs. Tipagem Dinâmica (Linguagem de Programação)
   
   -O Dilema: Escolher a linguagem de programação baseada na verificação de tipos de dados.
   
   *Tipagem Estática (ex: Java, C#, TypeScript): Você precisa declarar se uma variável é texto, número, etc. O compilador avisa os erros antes do código rodar.
   
   *Desvantagem: Exige mais linhas de código (boilerplate) e torna o desenvolvimento inicial mais lento e rígido.
   
   
   *Tipagem Dinâmica (ex: Python, JavaScript, PHP): Você cria variáveis livremente. O desenvolvimento é extremamente rápido e flexível.
   
   *Desvantagem: Erros bobos (como tentar somar um texto com um número) só aparecem quando o usuário final está usando o sistema, gerando bugs em produção
