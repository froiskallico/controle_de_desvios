# Sistema para controle de Desvios de Produto
## Escopo:
Aplicativo para controle de Desvios de produtos com base no documento   R.Q. 101.

- Os usuários poderão incluir (iniciar)/editar/consultar/deletar um documento de Desvio de Produto e o mesmo deverá receber aprovação de diversos outros usuários para então se tornar "liberado";
- Ao criar um documento o mesmo receberá um numero único para controle;
- Ao criar um documento os usuários deverão, obrigatoriamente, indicar:
  - O(s) motivo(s) do desvio;
  - As Ordens de Produção;
  - Os Clientes afetados;
  - Os produtos "DE-PARA" (Com consulta ao banco de Dados do Delphus);
    - O produto e o fornecedor do produto "PARA" não necessariamente deverão estar cadastrados no Banco de Dados do Delphus;
  - A Quantidade ou período do desvio;
- O aplicativo poderá buscar dados direto do banco de dados do Delphus, vinculados aos produtos. e.g.: Fabricante, Estoques, Comprometido, Subgrupo, etc;
- Para um desvio ser liberado, será necessária a aprovação por *n* indivíduos/setores, a serem definidos;
- A ultima aprovação (por parte do setor de estoque) só poderá ocorrer depois que todas as outras aprovações forem feitas;
- Os documentos ficarão armazenados em banco de dados para posterior consulta;
- Haverá controle de alçada onde necessário para garantir que somente usuários habilitados possam efetuar as ações que lhes são pertinentes;
- Os usuários poderão anexar outros documentos ao documento de Desvio (Fotos, laudos, certificados, etc).
  
## Características:
- Interface de usuário responsiva;
- PWA (Pode ser instalado como aplicativo em dispositivo Mobile);
- Login criptografado via email e senha, com possibilidade de login usando conta do Google;
- Interface com banco de dados do Delphus com consulta em tempo real;
- Upload de arquivos via Drag'n'Drop;
- Upload de fotos tiradas diretamente com a câmera do celular.

## Stack:
<img src="http://tritec.rf.gd/comercial/orcamento_datateck_webapp_desvios/stack.png" height="700px">

## Wireframes:

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Desktop:**
<iframe style="border: none;" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2Fg1ae183wxqQCVINWDuoRXE%2FWireframe-Desvios%3Fnode-id%3D2%253A504%26scaling%3Dcontain" allowfullscreen></iframe>


### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Mobile:**
<iframe style="border: none;" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2Fg1ae183wxqQCVINWDuoRXE%2FWireframe-Desvios%3Fnode-id%3D35%253A117%26scaling%3Dscale-down" allowfullscreen></iframe>

## Investimento Líquido
### R$ 2.390,00 (Dois mil trezentos e noventa reais) 

## Forma de pagamento
- ### 50% no deploy completo da aplicação conforme escopo;
- ### 50% 30dd após deploy.

## Entrega
### &nbsp;&nbsp;&nbsp;&nbsp;  Até 30 dias após aprovação da proposta;
&nbsp;&nbsp;&nbsp;&nbsp; *Neste período poderão ocorrer entregas parciais, para validação e testes da aplicação.*

## Validade da Proposta
### &nbsp;&nbsp;&nbsp;&nbsp; 30 dias


<br>

 Atenciosamente,
**Kallico Fróis**
