Manual de Uso da API GPTFree:

A API GPTFree é uma ferramenta que permite fazer solicitações para obter respostas do modelo GPT-3.5 com base em prompts específicos. Ela também coleta dados de vários provedores de IA que usam o ChatGPT. Siga os passos abaixo para usar a API:

Passo 1: Formule o Prompt

O prompt é a frase ou pergunta que você deseja enviar para obter uma resposta do GPT-3.5.
Você deve incluir o prompt na URL após https://gptfree.appgps.com.br/prompt=
Por exemplo, para pesquisar "Qual é o segredo da vida?", a URL seria: https://gptfree.appgps.com.br/prompt=Qual%20%C3%A9%20o%20segredo%20da%20vida?
Passo 2: Fazer a Solicitação

Utilize um método HTTP GET para enviar a solicitação à URL que você construiu com o prompt desejado.
A resposta virá no formato JSON, contendo a resposta gerada pelo GPT-3.5.
Exemplo de Solicitação:


GET https://gptfree.appgps.com.br/prompt=Qual%20%C3%A9%20o%20segredo%20da%20vida?
Passo 3: Receber a Resposta

A resposta JSON conterá o texto gerado pelo modelo em resposta.
Dependendo da estrutura da resposta JSON, você pode acessar a resposta usando a chave apropriada.
Exemplo de Resposta JSON:

json
{
  "resposta": "A resposta para a pergunta sobre o segredo da vida é um tópico profundo e filosófico. Muitas pessoas têm suas próprias teorias e crenças, mas o segredo da vida pode ser uma jornada pessoal de descoberta e significado."
}

Passo 4: Explorar Provedores de Dados (Opcional)

Você também mencionou que a API coleta dados de provedores de IA. Se desejar acessar dados desses provedores, você pode consultar a seguinte URL: https://gpt.appgps.com.br/api/v1/chat/providers/
Esta URL fornecerá informações sobre os provedores de onde os dados são coletados.
Lembre-se de que esta é uma explicação básica do uso da API com base nas informações fornecidas. Você pode precisar de detalhes adicionais sobre autenticação, limites de uso ou qualquer outra funcionalidade específica que tenha implementado em sua API.

Certifique-se de que a API esteja de acordo com todas as regulamentações e políticas de uso de dados aplicáveis e tenha em mente que você é responsável pelo uso ético e legal da API e dos dados coletados.
