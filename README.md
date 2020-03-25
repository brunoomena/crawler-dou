# crawler-dou

Este é um crawler que faz buscas dentro do site https://www.jusbrasil.com.br/diarios/, ele utiliza o campo de busca do jusbrasil para localizar as páginas de relevância e, em seguida, itera por todas as páginas e armazena suas informações dentro de um dataframe que pode ser esportado para diversos formatos, como json ou csv

#### Limitações
É uma característica do site do jusbrasil que, após a busca, ele retorne somente a página do determinado diário que contém a informação buscada, não o diário todo, dessa forma, por questões técnicas, o resultado pode não ser preciso 

Após algumas consultas sobre a dinâmica dos diários oficiais, foi apurado que os diários da Justiça e Tribuinais não são relevantes para os fins de busca sobre fechamento de estabelecimentos, desta forma, estes não estão sendo lidos no código 

##### OBS

Além do código do crawler do jusbrasil, você encontrará em anexo um segundo crawler do site http://www4.planalto.gov.br/legislacao/portal-legis/legislacao-covid-19, este é um site novo que surgiu em meio ao desenvolvimento do código original, porém, suas informações estão muito melhor estruturadas e geram leituras muito mais precisas

Nos próximos dias devemos definir se continuaremos desenvolvendo a versão principal do crawler ou o novo crawler dentro do site do planalto

Atualizado em 22/03/2020 por Bruno Omena e Arthur Omena 
