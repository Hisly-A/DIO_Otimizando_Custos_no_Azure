# DIO - Otimizando Custos no Azure
Otimizando Custos no Azure


## 🔎 Calculadora do TCO (Custo Total de Propriedade)	

>A Calculadora do TCO (Custo Total de Propriedade) permite estimar a economia de custos gerada pela migração de cargas de trabalho para o Azure.

<sub>Fonte: <https://azure.microsoft.com/pt-br/pricing/tco/calculator/></sub>

Essa ferramenta permite estimar os custos da migração para a nuvem antes de efetivamente realizar a migração.

Para realizar a simulação deve-se primeiro preencher as definições de cargas de trabalho e ajustar as suposições, após fornecer essas informações a ferramenta gera um relatório:

![AZ08-01](https://github.com/user-attachments/assets/35bd2811-8d84-49a9-b785-6ddb13eae559)

Nas **Definições de cargas de trabalho** preencha as informações referentes aos **Servidores**:

![AZ08-02](https://github.com/user-attachments/assets/214e6a19-3aca-4eca-b1e1-6785de9c7263)

Preencha as informações de **Bancos de dados**:

![AZ08-03](https://github.com/user-attachments/assets/d2e2880a-1fae-44e8-bfab-f83c4a5cf0f1)

As informações de **Armazenamento**:

![AZ08-04](https://github.com/user-attachments/assets/6fefa9ca-0b50-4735-90d6-303dc87100bc)

E as informações de **Rede** e clique em **Próxima**:

![AZ08-05](https://github.com/user-attachments/assets/99d399ff-9cb4-4236-95ef-15852257cd90)

Na tela de **Ajustar suposições** é possível alterar a moeda que será utiliza no cálculo dos valores:

![AZ08-06](https://github.com/user-attachments/assets/38ef1cea-608d-461f-931b-d26b4617f23c)

Informe se irá utilizar **Cobertura do Software Assurance** e **GRS (armazenamento com redundância geográfica)**:

![AZ08-07](https://github.com/user-attachments/assets/3af378b4-b825-439a-ac37-cd8dbb5e2848)

E preencha também as demais opções conforme a necessidade:

![AZ08-08](https://github.com/user-attachments/assets/a9608584-d7d6-4826-9f22-a3ba3c989896)

![AZ08-09](https://github.com/user-attachments/assets/26003b16-8c0f-48d3-b10b-8956e91ea470)

Clique em **Próxima**:

![AZ08-10](https://github.com/user-attachments/assets/03103056-b01f-4c79-95f5-4c62beea7050)

Repare que de acordo com as entradas fornecidas não houve estimativa de redução de custos:

![AZ08-11](https://github.com/user-attachments/assets/984952f2-39b6-4bcd-9b3e-bb3a8f09d0cf)

![AZ08-12](https://github.com/user-attachments/assets/2c1ac0bc-36e7-417e-ad4e-4d2984ebb8b7)

![AZ08-13](https://github.com/user-attachments/assets/858f6346-ae9a-4393-953a-d57fbc420d8c)

![AZ08-14](https://github.com/user-attachments/assets/f309be36-87bd-4b19-8a67-a4b700be5f44)

![AZ08-15](https://github.com/user-attachments/assets/785c99ee-a922-46c5-b764-0f2728b07769)


## 🔎 Calculadora de preço

Acesse o site https://azure.microsoft.com/pt-br/pricing/calculator/.

Observe as opções de produtos passíveis de realizar a estimativa de custo:

![AZ08-16](https://github.com/user-attachments/assets/227b2650-95eb-47c6-ad46-9f4a5e741da2)

Clique nas categorias para visualizar mais produtos:

![AZ08-17](https://github.com/user-attachments/assets/db93d611-3ebe-4018-86c2-9ecda26512bf)

Clique em **Máquinas virtuais** para realizar uma estimativa:


![AZ08-18](https://github.com/user-attachments/assets/1001fa20-bec8-45cd-90c1-d6e1ccdde705)

Mantenha os campos com o preenchimento padrão:


![AZ08-19](https://github.com/user-attachments/assets/ed91e260-d1ff-4c33-94db-bc8bfeeceeb5)

![AZ08-20](https://github.com/user-attachments/assets/f9a404c7-843f-4a3a-9c0e-3cab13454470)

Repare que o valor estimado foi de US$ 137,24.

![AZ08-21](https://github.com/user-attachments/assets/32843910-bf0b-4144-b367-f5dd3ef69547)

Para a mesma máquina apenas altere o **SO (Windows)** para **Benefício Híbrido do Azure** e repare que o valor mudou para US$ 70,08:

![AZ08-22](https://github.com/user-attachments/assets/b711ebec-cbaa-4703-91e7-334ea0ef6f94)

Agora no **Plano de economia**  selecione a opção **Plano de economia de 3 anos (desconto de ~53%)** e repare que o valor mudou para US$ 32,94:

![AZ08-23](https://github.com/user-attachments/assets/859c2b29-47a4-41a3-984c-f6d1ef65189c)

Realize mais um teste alterando a quantidade de horas para 312 e marque a opção **Pago conforme o uso**:

![AZ08-24](https://github.com/user-attachments/assets/7c084f2d-33ce-4259-947e-77fa6d168852)

Repare que o valor estimado mudou para US$ 29,95:

![AZ08-25](https://github.com/user-attachments/assets/c5f10f27-bfb0-4a4b-acef-8905ff9d5e8c)




## 🔎 Cost Management + Billing

Abra o portal da [`Azure`](https://portal.azure.com), e no menu lateral clique em **Cost Management + Billing**:

![AZ08-26](https://github.com/user-attachments/assets/53918192-527c-433c-9236-839fff1c6960)

Clique na opção **Cost management**:

![AZ08-27](https://github.com/user-attachments/assets/95cd42fb-dfe7-4bac-90b5-5075059e902e)

Na opção **Cost alerts** repare no alerta de custo excedido para o budget:

![AZ08-28](https://github.com/user-attachments/assets/2b6ca616-e912-435a-b759-a35a6d63a57f)

Para criar um novo alerta clique em **+Add** e preencha as informações necessárias:

![AZ08-32](https://github.com/user-attachments/assets/7f68c096-bd74-4d29-abfa-d468e15c341f)

A opção **Advisor recommendations** traz recomendações/sugestões de melhorias relacionadas à custo:

![AZ08-29](https://github.com/user-attachments/assets/884a4da8-517d-4d41-b9da-d4254c58608d)

Na opção **Budgets** podem ser adicionados limites de gastos:

![AZ08-30](https://github.com/user-attachments/assets/8b5ba236-e3a3-4f2e-b801-abb4639d1323)

![AZ08-31](https://github.com/user-attachments/assets/b1c2cf9e-ae3d-4ae3-9e53-d1b04e70084e)


## Inclusão de tags nos recursos criados

Para incluir uma tag em um recurso existente, acesse um **Resource group**, pesquise por *Tags*, informe um nome e um valor e clique em **Aplicar**:

![AZ08-33](https://github.com/user-attachments/assets/88396e79-3347-4ef4-bfbe-7fa916a47805)

Porém quando a tag é adicionada ao Resource group, os recursos existentes dentro dele não herdam a tag adicionada.

Mas pode ser configurada uma política/condição de criação de tags em **Policy**, para permitir por exemplo, que um recurso só seja criado se for adicionada uma tag.

![AZ08-34](https://github.com/user-attachments/assets/7d67ca5f-e8a2-4005-920a-777c983bde52)


## Links utilizados

- https://azure.microsoft.com/pt-br/pricing/tco/calculator/

- https://azure.microsoft.com/pt-br/pricing/calculator/

- https://portal.azure.com
