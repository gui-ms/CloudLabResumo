# CloudLabResumo
Repositório feito para enviar as soluções dos desafios Microsoft Azure do bootcamp da DIO que requerem a criação de um resumo de cada video de laboratório feito explorando a plataforma Azure.

# Resumo do Laboratório 1: (Localizando Serviços por Categoria)

Nesta primeira aula somos apresentados à pagina inicial da Azure, também aprendemos sobre como alterar questões cosméticas como tema escuro, cores, idioma, etc. Uma informação muito importante é de que existe a possibilidade de alguns serviços e recursos estarem indisponíveis por conta do seu alto preço, mas que isso é o esperado. É feita uma análise de algumas categorias de serviços disponíveis e alguns deles são brevemente descritos como o Bastions que é um jump-server. Outra coisa que nos é explicada são os serviços em versão prévia, significando que ainda estão em análise e que podem ser repentinamente removidos caso a Microsoft decida que essa é a melhor opção.

# Resumo do Laboratório 2: (Criar máquina virtual)

Iniciamos revisando o conceito de SLA e vendo ele na prática. SLA ou Service Level Agreement é um acordo que define os padrões de serviço que devem ser ofertados pelo provedor, nesse caso o tempo de inatividade do servidor de acordo com o nível (99, 99.9, 99.999...). É importante definir o tempo de inatividade aceitável para um cliente de modo a selecionar o melhor SLA em custo-benefício e desenvolver uma estrutura, requisições, etc a partir disso. Durante este laboratório é feita uma breve análise da página de criação de máquina virtual, com foco na parte de opções de disponibilidade e zonas de disponibilidade que acarretam nos valores do SLA, além da seção de redundância com diferentes tipos que vão do menos seguro (e mais barato) ao mais seguro. Os tipos de redundância podem ser:
 - Local;
 - Geográfica;
 - De Zona;
 - De Zona Geográfica;

# Resumo do Laboratório 3: (Configurando uma instância de DB na Azure)

Iniciamos essa aula novamente na seção de criação de máquina virtual, onde vimos o funcionamento do método "pay as you go" que já mostra o valor cobrado por mês do tipo de serviço que selecionamos. Também é feita uma rápida análise da seções de disco, gerenciamento, redes, e monitoramento da máquina virtual, para ter uma ideia de tudo que é necessário fazer para criar uma máquina virtual com sucesso. Após isso seguimos para a análise do recurso de Banco de dados SQL, onde nos é mostrado os passos necessários para a criação do banco de dados, incluindo o servidor que pode ser criado do zero.
