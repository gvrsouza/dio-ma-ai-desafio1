# Desafio DIO 
Repositório criado para entregar desafio 1 do curso de Microsoft Azure AI Fundamentals.

Passo a passo de como criar um modelo de previsão com pontos de extremidade configurados. Estou partindo do principio que sua conta no Azure já foi criada. 
1) acessar o portal do [Azure]([url](https://portal.azure.com/#home)) 
![image](https://github.com/gvrsouza/dio-ma-ai-desafio1/assets/65606402/41679723-196b-44f1-8c6a-79ef2d774e09)

2) clique em **Criar um recurso** -> no campo pesquisa digite *Machine Learning* ou pesquisa nas categorias do menu ao lado esquerdo 
![image](https://github.com/gvrsouza/dio-ma-ai-desafio1/assets/65606402/0864fbe9-f02a-49e1-bfea-118d59251a5f)

3) após clicar em **Azure Machine Learning**, clique em **Criar**
![image](https://github.com/gvrsouza/dio-ma-ai-desafio1/assets/65606402/ad277d9e-c35c-4fcc-83be-935470c1b521)

4) a tela seguinte, mostra vários campos a serem preenchidos
   ![image](https://github.com/gvrsouza/dio-ma-ai-desafio1/assets/65606402/25b51c2b-9c21-4718-abaf-ea460042045e)
  - campo assinatura: é como se fosse o CPF do usuário dentro da plataforma. Dependendo do tipo de conta, pode ser mostrado vários digítos ou *Assinatura de plataformas MSDN*
  - grupo de recursos: você não vai criar nada no Azure de uma vez, as coisas são feitas em etapas. Logo, esse campo serve para identificar um contéiner que armazena recursos relacionados para uma solução.
  - nome: defina um novo exclusivo para seu projeto.
  - região: nunca escolha a opção **Brazil** pelo simples motivo do recursos serem mais caros. Ao invés escolha **East US**.
  - conta de armazenamento: mantenha o que foi criado. A alusão aqui seria uma gaveta que guardamos nosso HD.
  - cofre de chaves: mantenha o que foi criado. Seria o seu "chaveiro" onde são guardadas segredos/chaves/certificados/entre outros.
  - application insights: mantenha o que foi criado.
  - registro de contéiner: mantenha o que foi criado.

5) após preencher todos os campos na tela anterior, clique em **Examinar e criar** e aguarde a mensagem **_Validação aprovada_** no canto superior da tela. Se isso não acontecer, volte e compare os preenchimentos com os documentos de apoio.

6) na lista de Recursos da página inicial do Azure, clique no recurso que você criou, neste caso foi laboratorioia900
![image](https://github.com/gvrsouza/dio-ma-ai-desafio1/assets/65606402/ef64413a-e0cd-49a7-8dac-58565f862677)

7) clique no botão abaixo **Iniciar o estúdio** é ṕossível que seja pedido para efetuar o login novamente na página
![image](https://github.com/gvrsouza/dio-ma-ai-desafio1/assets/65606402/1723b1d3-5d5f-40e6-a8b3-f562addda113)

8) se não estiver aparecendo a tela abaixo, não se preocupe, é provável que você precise criar um *workspace*
![image](https://github.com/gvrsouza/dio-ma-ai-desafio1/assets/65606402/495eba9e-36eb-441d-97df-fbf03781d)

9) no menu à esquerda, clique em **ML automatizado** e depois em **+Novo trabalho de ML automatizado**
![image](https://github.com/gvrsouza/dio-ma-ai-desafio1/assets/65606402/8305e1bb-0f92-4d50-be5a-ae496178e92d)

10) a janela abaixo mostra campos a serem preenchidos
![image](https://github.com/gvrsouza/dio-ma-ai-desafio1/assets/65606402/d2f4313a-8c73-4b91-8cd3-4a5259038da1)






