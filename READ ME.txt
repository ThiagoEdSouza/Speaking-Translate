# Speaking Translate

- Serviço de Tradução de fala criado através de ferramenta IA disponibilizada pelo Microsoft Azure.

## Procedimento para criação do serviço.

Para criar o serviço de Fala do Microsoft Azure, foram seguidos os seguintes passos:

- Acesso ao Portal do Azure: https://portal.azure.com/

- Login na conta criada no portal.

- Acessado o portal de recursos do Azure.

- Na barra de pesquisa, digitado "Speech" e selecionado "Speech" ou "Serviço de Fala". Clicado em "Criar".


## Configuração do Serviço de Fala:

- Assinatura: Escolhida a assinatura desejada do Azure, neste caso a Free0.

- Grupo de Recursos: Selecionado um grupo de recursos existente.

- Região: Escolhida a região onde o serviço será hospedado. Definida a região EastUS.

- Nome: Dado um nome ao recurso de serviço de fala, Speaking-Translate.

- Plano de Tarifas: Definido o plano de tarifas (no caso, a opção Gratuita).


## Criando o Recurso:

- Após preencher todos os campos necessários, clicado em "Revisar e criar" e depois em "Criar".


## Obtendo a Chave de Assinatura:

Após a criação do recurso de serviço de fala.
No painel de navegação do recurso, clicado em "Chaves e EndPoint".
Disponibilizadas duas chaves de assinatura. Utilizada a primeira na aplicação.


### Iniciando o código na Máquina Local:

Ao acessar a tela do recurso criado, o próprio portal dá as instruções para testes no repositório virtual ou implementação na máquina local.

- Acessada a documentação disponibilizada na página do Azure.

- Definida a linguagem a ser utilizada (Javascript).

- Definidas chave e região como variáveis de ambiente.

- Definido local do repositório do serviço na máquina local e criado o arquivo SpeechTranslation.js (conforme indicado na documentação).

- Certificado de que o node.js já estava instalado na máquina.

- Copiado e modificado o código do arquivo (conforme indicado na documentação).

- Instalado SDK (conforme indicado na documentação) / npm install microsoft-cognitiveservices-speech-sdk 
 

## Execução do recurso na máquina local:

- node.exe SpeechTranslation.js


### Saída na Máquina Local

- Saída em modo de texto via console.
