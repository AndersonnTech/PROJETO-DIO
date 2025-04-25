# PROJETO-DIO
Descrição do Desafio
Este laboratório tem como objetivo praticar o processo de criação e configuração de uma máquina virtual na plataforma Microsoft Azure.
Como entregável, o desafio proposto é a criação de um repositório contendo resumos, anotações e dicas sobre o uso da Azure, 
servindo como material de apoio para estudos e futuras implementações.

Computação em Nuvem Microsoft Azure

  A computação em nuvem, é um serviço de inovação tecnologiaca, que visa trazer mais recursos flexiveis e economicos em grande escala. Pode optar
  por modelos de nuvem como, Nuvem Privada, Nuvem publica e Nuvem Hibrida, escolhendo aquela que se adequar melhor ao ramo de negocio.
  É uma tecnologia que vem crescendo e usanda em grande escala para diversos fins. Pois garantem beneficios como:

  Alta disponibilidade: esta sempre funcionando, e a partir do SLA escolhido, que visa a garantia de disponibilidade maxima do serviço,
    podendo haver interrupços minimas no serviço, e se caso essas interrupções ultrapassem o limite descrito em contrato,
    a propria Microsoft ressarce em creditos para utilizar no sistema. 

  Escalabilidade: é capacidade de ajustar os recursos como bem quiser e necessitar, ou seja, só paga por aquilo que usar; 
    exemplo: alta demanda, escala mais recursos; demanda diminuiu, redução de recursos.
  
  Elasticidade: é uma função usada para que se houver uma demanda muito grande, os recursos podem ser expandidos automaticamente ou manualmente.

  Confiabilidade: A nuvem permite um Design descentralizado, que visa ter recursos implantados em varias regiões,
    assim caso aconteçam imprevistos em determinada região, os serviços podem continuar a partir de outra.

 Previsibilidade: Confiança no desempenho ou no custo, garantido pelo Microsoft Azure Well-Architected.

 Segurança: A nuvem oferece ferramentas de segurança que atendem as necessidades dos clientes mas, é de grande importância lembrar que a segurança
   deve ser implementada pelo cliente.

Governança: Auditoria baseada em nuvem ajuda sinalizando qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estrategias de mitigação.

Gerenciamento: Capacidade de gerenciamento por meio do portal da web, interface de linhas de comando, usando APIs ou usando o PowerShell.


CRIAÇÂO DE UMA MAQUINA VIRTUAL NO AZURE

No portal web na Azure, pesquisar por Máquinas virtuais; selecionar serviços e logo em seguida selecionar Máquinas virtuais;
Clicar em Criar Máquina virtual Azure

Definir nome da maquina virtual; Em "Opções de disponibilidade" selecionar a opção mais viável, pois essas opções estão ligadas ao SLA e diferem uma das outras;
em "Zona de disponibilidade" a quantidade de zonas escolhidas será a mesma em relação a quantidade de maquinas virtuais a serem criadas, então seleciona de acordo
com a necessidade para não gerar desperdicio de custos. 

Na "Imagem" deixe selecionado "Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2"; e as outra opções deixar em configuração padrão;

Na "Conta de administrador", colocar nome de usuário e senha;

Na "Regras de porta de entrada, selecionar "Permitir portas selecionadas", e selecionar RDP(3389) e HTTP (80) na lista suspensa;

Agora proximo passo é selecionar o botão "Examinar + criar";

Depois de validar a configuração da Máquina virtual, selecionar o botão "Criar"

Após a conclusão clicar em "Ir para o recurso";


Depois destes procedimentos a máquina virtual está disponivel para ser utilizada.




