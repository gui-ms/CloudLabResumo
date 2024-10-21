# CloudLabResumo
Repositório feito para enviar a solução do desafio Microsoft Azure - Localizando Serviços por Categoria do bootcamp da DIO

# Resumo do Laboratório 1:

Nesta primeira aula somos apresentados à pagina inicial da Azure, também aprendemos sobre como alterar questões cosméticas como tema escuro, cores, idioma, etc. Uma informação muito importante é de que existe a possibilidade de alguns serviços e recursos estarem indisponíveis por conta do seu alto preço, mas que isso é o esperado. É feita uma análise de algumas categorias de serviços disponíveis e alguns deles são brevemente descritos como o Bastions que é um jump-server. Outra coisa que nos é explicada são os serviços em versão prévia, significando que ainda estão em análise e que podem ser repentinamente removidos caso a Microsoft decida que essa é a melhor opção.

# Resumo do Laboratório 2: (Criar máquina virtual)

Iniciamos revisando o conceito de SLA e vendo ele na prática. SLA ou Service Level Agreement é um acordo que define os padrões de serviço que devem ser ofertados pelo provedor, nesse caso o tempo de inatividade do servidor de acordo com o nível (99, 99.9, 99.999...). É importante definir o tempo de inatividade aceitável para um cliente de modo a selecionar o melhor SLA em custo-benefício e desenvolver uma estrutura, requisições, etc a partir disso. Durante este laboratório é feita uma breve análise da página de criação de máquina virtual, com foco na parte de opções de disponibilidade e zonas de disponibilidade que acarretam nos valores do SLA, além da seção de redundância com diferentes tipos que vão do menos seguro (e mais barato) ao mais seguro. Os tipos de redundância podem ser:
 - Local;
 - Geográfica;
 - De Zona;
 - De Zona Geográfica;
