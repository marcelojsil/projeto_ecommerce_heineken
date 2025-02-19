# Refinando um Projeto Conceitual de Banco de Dados E-COMMERCE:

#### Projeto proposto no Bootcamp Heineken - IA Aplicada a Dados com Copilot na plataforma [DIO.](https://www.dio.me/)

### Descrição do Desafio
_"Modelamos juntos um contexto reduzido de e-commerce. Agora é a sua vez, podes escolher a ferramenta de modelagem para realizar o desafio. Contudo, fique atento! Caso opte por uma variação do modelo entidade relacionamento, como nas ferramentas Mysql Workbench ou DBDesigner será preciso especificar as PK e FKs corretamente. Apesar desse conceito não ser utilizado na modelagem conceitual exploramos brevemente suas definições. Sendo assim, seu empregável será o esquema conceitual para o cenário de E-commerce."_ 

Instrutora: *Juliana Mascarenhas*
</b>

### Objetivo:
Refinar o modelo apresentado no curso acrescentando os pontos abaixo:

- Cliente PJ e PF: conta PJ ou PF, usar apenas um dos dois;
- Pagamento: Pode ter cadastrado mais de uma forma de pagamento;
- Entrega: Possui status e código de rastreio;



## Ferramentas utilizadas

- [Draw](https://app.diagrams.net/)



## Respostas do Desafio

![img](https://github.com/htonioni/mysql-projeto-conceitual-bd-DIO/blob/main/ECOMMERCE/ecommerce_imagem.png)

- Para a entidade Cliente foram criadas duas novas entidades  ``PJ_Pessoa Juridica`` e ``PF_Pessoa Fisica`` contendo as informações de CNPJ e CPF.
- No caso de Pagamento a entidade esta atribuída a outras duas entidades afim de detalhar as formas de pagamento : Cartão e Boleto.
- Entrega foi criada para armazenar as informações de envio de cada pedido detalhar como data do pedido, data de envio e data de entrega.



## Certificado

![img](https://github.com/htonioni/mysql-projeto-conceitual-bd-DIO/blob/main/certificado/certificado.jpg)

