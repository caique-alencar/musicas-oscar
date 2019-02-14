<h1>Uma análise de dados das músicas do Oscar 2019 no Spotify</h1>

Esse foi um treino que eu fiz para usar a API do Spotify. Peguei os nomes das músicas indicadas ao Oscar 2019 na categoria de melhor música original e extrai as carecterísticas delas usando Python. Com os dados extraídos fiz gráficos comparativos de cada característica das músicas usando o Flourish. O resultado foi <a href="https://medium.com/@caiqalencar/as-músicas-do-oscar-2019-no-spotify-18a013cede8">esse post</a> que eu fiz no meu Medium.

<b>Observações:</b>
<ul>
  <li>Para rodar esse código é preciso instalar a biblioteca <code>spotipy</code></li>
  <li>É necessário inserir as chaves de acesso nas respectivas variáveis</li>
<ul>

Para acessar a API usei minhas credenciais em um arquivo separado que não subi para o repositório. Você pode definir as suas rodando o seguinte código antes:

<pre><code>import json<br>
uber_credentials = {}<br>
uber_credentials['server_token'] = 'SEU SERVER TOKEN VAI AQUI'<br>
with open('credenciais_uber.json', 'w') as secret_info:<br>
  json.dump(uber_credentials, secret_info, indent=4, sort_keys=True)<br></code></pre>
