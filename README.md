Simulação de Phishing Educacional

Descrição

Este projeto demonstra como ataques de phishing podem ser realizados em um ambiente controlado e seguro, com o objetivo de conscientizar sobre segurança cibernética. O exercício utiliza ferramentas como Kali Linux e o Social-Engineer Toolkit (SET) para simular um ataque de coleta de credenciais.

⚠️ Atenção: Este projeto é estritamente para fins educacionais e de conscientização. O uso inadequado dessas técnicas é ilegal e antiético.


---

Objetivos

Simular um ataque de phishing para fins educacionais.

Demonstrar vulnerabilidades comuns.

Apresentar estratégias de mitigação e conscientização.



---

Ferramentas Utilizadas

Sistema Operacional: Kali Linux

Framework: Social-Engineer Toolkit (SET)

Redes: ifconfig para configuração de IP

Extras: ngrok (opcional, para tunelamento)



---

Configuração do Ambiente

1. Pré-requisitos

Kali Linux instalado e atualizado.

Acesso root para executar comandos administrativos.

Conexão de rede configurada.


2. Preparação do Sistema

Atualize o Kali Linux:

sudo apt update && sudo apt upgrade -y

3. Configuração do SEToolkit

Execute os seguintes passos:

1. Acesse como root:

sudo su


2. Inicie o SEToolkit:

setoolkit


3. Escolha as opções:

Tipo de ataque: Social-Engineering Attacks

Vetor de ataque: Web Site Attack Vectors

Método de ataque: Credential Harvester Attack Method

Método de ataque: Site Cloner

URL para clone: http://www.facebook.com




4. Integração com ngrok (opcional)

Para tornar o site acessível remotamente:

1. Baixe e instale o ngrok:

sudo apt install ngrok


2. Execute o ngrok:

./ngrok http 80


3. Use o endereço gerado no SET.




---

Análise de Dados

1. Logs:
O SET armazena os logs de credenciais capturadas no diretório padrão:

/var/www/html


2. Automatização com Python:
Use bibliotecas como Pandas e Matplotlib para gerar relatórios e gráficos.




---

Medidas de Mitigação

Educação:

Evitar clicar em links suspeitos.

Reconhecer sites falsificados.


Segurança:

Ativar autenticação de dois fatores (2FA).

Usar gerenciadores de senhas confiáveis.




---

Ética e Conformidade

Este projeto foi desenvolvido exclusivamente para fins educacionais e de conscientização. Não é permitido o uso para qualquer atividade maliciosa ou ilegal.


---

Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar o projeto.
