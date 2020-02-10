<h1 id="sistema-para-controle-de-desvios-de-produto">Sistema para controle de Desvios de Produto</h1>

<br><br>
<h2 id="escopo">Escopo:</h2>
<p>Aplicativo para controle de Desvios de produtos com base no documento   R.Q. 101.</p>
<ul>
<li>Os usuários poderão incluir (iniciar)/editar/consultar/deletar um documento de Desvio de Produto e o mesmo deverá receber aprovação de diversos outros usuários para então se tornar &quot;liberado&quot;;</li>
<li>Ao criar um documento o mesmo receberá um numero único para controle;</li>
<li>Ao criar um documento os usuários deverão, obrigatoriamente, indicar:
<ul>
<li>O(s) motivo(s) do desvio;</li>
<li>As Ordens de Produção;</li>
<li>Os Clientes afetados;</li>
<li>Os produtos &quot;DE-PARA&quot; (Com consulta ao banco de Dados do Delphus);
<ul>
<li>O produto e o fornecedor do produto &quot;PARA&quot; não necessariamente deverão estar cadastrados no Banco de Dados do Delphus;</li>
</ul>
</li>
<li>A Quantidade ou período do desvio;</li>
</ul>
</li>
<li>O aplicativo poderá buscar dados direto do banco de dados do Delphus, vinculados aos produtos. e.g.: Fabricante, Estoques, Comprometido, Subgrupo, etc;</li>
<li>Para um desvio ser liberado, será necessária a aprovação por <em>n</em> indivíduos/setores, a serem definidos;</li>
<li>A ultima aprovação (por parte do setor de estoque) só poderá ocorrer depois que todas as outras aprovações forem feitas;</li>
<li>Os documentos ficarão armazenados em banco de dados para posterior consulta;</li>
<li>Haverá controle de alçada onde necessário para garantir que somente usuários habilitados possam efetuar as ações que lhes são pertinentes;</li>
<li>Os usuários poderão anexar outros documentos ao documento de Desvio (Fotos, laudos, certificados, etc).</li>
</ul>
<h2 id="caracter%c3%adsticas">Características:</h2>
<ul>
<li>Interface de usuário responsiva;</li>
<li>PWA (Pode ser instalado como aplicativo em dispositivo Mobile);</li>
<li>Login criptografado via email e senha, com possibilidade de login usando conta do Google;</li>
<li>Interface com banco de dados do Delphus com consulta em tempo real;</li>
<li>Upload de arquivos via Drag'n'Drop;</li>
<li>Upload de fotos tiradas diretamente com a câmera do celular.</li>
</ul>
<h2 id="stack">Stack:</h2>
<img src="http://www.tritec.rf.gd/images/stack.png" height="700px">
<p><em>Ficará a cargo da Datateck fornecer VPS com acesso remoto para testes, hospedagem do servidor e banco de dados da aplicação ou, se preferir, contratação de serviço de hospedagem cloud (AWS, GCP, Azuew, etc)</em></p>
<h2 id="wireframes">Wireframes:</h2>
<h3 id="desktop">         <strong>Desktop:</strong></h3>
<iframe style="border: none;" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2Fg1ae183wxqQCVINWDuoRXE%2FWireframe-Desvios%3Fnode-id%3D2%253A504%26scaling%3Dcontain" allowfullscreen></iframe>
<h3 id="mobile">         <strong>Mobile:</strong></h3>
<iframe style="border: none;" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2Fg1ae183wxqQCVINWDuoRXE%2FWireframe-Desvios%3Fnode-id%3D35%253A117%26scaling%3Dscale-down" allowfullscreen></iframe>
