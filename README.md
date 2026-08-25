# ✅ Quinto Desaf;io - Projeto de Automação com AWS Lambda + S3 

🧭 Tema Escolhido: A Sequência Fibonacci e sua relação com a natureza

🥇 Objetivos do Estudo:
* Entender o que é a Sequência Fibonacci
* Saber quando foi descoberto o padrão Fibonacci presente na Natureza
* Entender como é a associação desse padrão com a Natureza


Veremos abaixo a resolução do desafio 5 do Bootcamp Santander Code Girls 2025. \ Será resumido a criação de uma insfraestrutura usando o
LocalStack contendo os recursos: Bucket S3, DynamoDB e Lambda Function. \ Esse projeto tem o intuíto de executar a seguintes tarefas: \ *
Disparar uma função lambda quando o usuário fizer o upload do arquivo no Bucket S3 \ * A função lambda deve processar os dados do
arquivo e fazer um insert no DynamoDB \ * Outra função Lambda vai consultar a tabela e expor os dados por meio de um API Gateway \ \
Inicialmente deve ser configurado o ambiente para execução do projeto, conforme descrito abaixo: 
 ⚙️ Configuração do Ambiente. 
🥇 Dicas iniciais: 
Dica 1: Antes da instalação do LocakStack é aconselhável instalar o Docker. É importante que tenhamos também o
Python já instalado. \ Dica 2: Na página de Download do LocalStack tem instruções de instalação do Docker, e
podemos fazer o registro de ambos com nossa conta do GitHub \ Dica 3: Ao instalar o Docker precisei fazer a
atualização do Windows Subsystem for Linux (WSL), o próprio Docker me forneceu o comando para rodar no
PowerShell e fazer a atualização. 
🧭 Vamos acompanhar os passos a seguir para criação de nosso ambiente. 
1️⃣ Entender os conceitos do AWS S3 e Lambda. Usar o Drawio ou programa similar para fazer um modelo de fluxograma do seu projeto de
efetivamente iniciar o projeto. 
2️⃣ Instalar o LocalStack versão gratuita na estação, antes é necessário instalar o Docker, na própria documentação do Localstack é fornecido
um link para instalação do Docker e suas devidas configurações. 
3️⃣ Verificar instalação com o comando localstack –version , atualizar o localstack com localstack update all e iniciar o ambiente com localstack
start 
4️⃣ É importante fazer a configuração do token de acesso e AWS CLI Local. 
5️⃣ Agora podemos criar nossos rescursos, inicialmente deve ser criado o Bucket S3. Em seguida a tabela no DynamoDB e por fim as funções
lambda 
6️⃣ Devemos criar uma trigger no bucket S3 para chamar a função lambda toda vez que for feito o upload de um arquivo. 
7️⃣ Por último devemos fazer o teste de execução do projeto, testando o upload do arquivo, disparo da função lambda e todos os eventos
seguintes. 
8️⃣ Acompanhar resultados nos logs do CloudWatch. 
 🥇 Dicas finais: 
Dica 1: Sempre faça as devidas configurações de regras e políticas de segurança em seus recursos criados. \ Dica 2:
Esse modelo de projeto pode ser aplicado em diversos ambientes, um exemplo seria registro do controle de ponto
digital de um funcionário, ou envio de um arquivo fiscal pela Web. \ Dica 3: Você pode fazer uma simulação do custo
efetivo do seu projeto usando o AWS Pricing Calculator, isso irá lhe auxiliar a usar da melhor forma os recursos
disponíveis com o custo mínimo necessário. \ Dica 4: Sempre desligue ou destrua seus recursos em caso da não
necessidade de uso. 
 🎲 Resumo do aprendizado pós projeto: 
✔ O LocalStack é uma ótima ferramenta para simulação de projetos para ambiente em nuvem da AWS \ ✔ Com um simples ambiente montado
com recursos AWS podemos aplicar as tecnologias em vários cenários \ ✔ O AWS Lambda é uma poderosa ferramenta Serverless que pode
ser usada até de forma avulsa. \ ✔ Os buckets S3 são uma ótimo solução para armazenamento em nuvem \ ✔ Todos os serviços AWS tem uma
integração direcionada a melhor atender os requisitos das empresas 
 Conteúdos: 
Local Stack 
Codig
