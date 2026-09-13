# Relat-rios

## Status e visualização

Este repositório ainda não contém o código-fonte, uma prévia interativa ou um aplicativo compilado. Para visualizar o projeto concluído, será necessário disponibilizar os arquivos-fonte, publicar uma prévia ou anexar um build do aplicativo.

## Aplicação Móvel

Esta aplicação móvel para Android e iOS tem como objetivo auxiliar no preenchimento e geração de três modelos de relatórios específicos: **ATIVIDADE TERMINAL**, **ABERTURA DE CHAMADA NA REDE** e **MAPEAMENTO DE SINAL**. A interface apresenta três seções distintas, cada uma contendo os campos de texto correspondentes ao modelo e a funcionalidade de upload/captura de fotos conforme a sequência obrigatória definida para cada seção. A aplicação é capaz de processar as imagens enviadas pelo usuário para extrair automaticamente dados necessários, como `ISSI/TEI` de uma foto de terminal, `Hora` de uma tela, `Intensidade do sinal` de uma tela de terminal, entre outros. O usuário tem a opção de revisar e editar os dados preenchidos automaticamente. Além disso, é permitir que o usuário tire fotos diretamente pelo aplicativo ou selecione-as da galeria do dispositivo, associando cada foto ao campo de imagem correspondente no relatório. Após o preenchimento, a aplicação permite a geração de um relatório consolidado (em PDF ou texto formatado) que inclui todos os dados e as fotos anexadas, com funcionalidade para compartilhar ou exportar o relatório gerado.

## Problemas conhecidos

- Leitura da tela do radio com balanço do carro
- Captura manual de dados

## Mapeamento de sinal TETRA em deslocamento

O escopo também inclui a coleta do RSSI durante deslocamento veicular, registrando a cada 50 metros a latitude, longitude, nível de sinal e data/hora. Os dados poderão ser mantidos em tabela e exportados para KML, permitindo visualizar no Google Earth o trajeto e os níveis de RSSI por meio de marcadores coloridos. A implementação dependerá do acesso à localização do dispositivo e de uma interface confiável para leitura do RSSI do rádio TETRA.

## Aspectos pendentes de definição

Antes da implementação final, é necessário definir o formato de saída definitivo dos relatórios, a plataforma de backend ou sistema de integração, as informações específicas a extrair de cada imagem, os requisitos de segurança, o volume esperado, a tecnologia ou framework mobile e o fluxo para casos em que a extração automática não seja possível ou seja imprecisa.