<p><img src="https://user-images.githubusercontent.com/63436406/130539241-86d21222-0819-4831-b086-3345d9af431a.png" align="left" height="150px" width="150px">
    <h1># Criando seu Ecossistema de Big Data na Nuvem</h1> 
    <p align="justify">
    Com base no repositório disponibilizado pelo expert, te desafiamos a replicar e, porque não, melhorar o algoritmo de extração/contabilização de palavras. Para isso, você pode ordernar as palabras por ocorrência e não por ordem alfabética (apresentando as mais citadas no texto com prioridade), por exemplo. Sinta-se à vontade para evoluir o algoritmo de outras formas. 
    </p>
</p>      

---

# DIO-LiveCoding-AWS-BigData

Repositório de cógido do Dio Live Coding com AWS EMR e Python
Neste repositório há os arquivos de configuração e execução de análise de dados.

## Instruções

* Acessar S3: https://s3.console.aws.amazon.com/s3/ 
  * Criar estrutura de data lake : _dio-live-datalake_
  * Criar estrutura de pastas:
    * _data_
    * _output_
    * _temp_
* Acessar EMR: https://console.aws.amazon.com/elasticmapreduce/
  * O cluster será criado pelo MrJob e não pelo console
  * Infraestrutura como código 
* Criar chave SSH
  * Acessar  Console do EC2: https://console.aws.amazon.com/ec2/ -> Key Pairs -> Create Key Pair	
  * Download .pem file
* Obter Id e chave secreta AWS para configurar MrJob
  * Profile
  * My Security Credentials: https://console.aws.amazon.com/iam/home?region={region}#/security_credentials
  * Access Keys - Create new access key
  * Fazer download - única chance de visualizar
* Ambiente linux
  * Criar ambiente virtual python: _virtualenv --python=python3.6 venv_diolive_
  * Acessar com o vs code
* Instalar vscode no Ubuntu
  *  code .
* Criar algoritmo de análise de palavras
  * dio-live-wordcount-test.py
  * map-reduce-count : contar
  * Instalar boto3: _pip install boto3_
  * Instalar mrjob: _pip install mrjob_
* Acessar S3
  * Upload de arquivo para o bucket
* Ambiente virtual python: source venv_teste/bin/activate
  * _nano ~/.mrjob.conf_
  * _python3 dio-live-wordcount-test.py -r emr s3://{your_s3_bucket_name}/data/SherlockHolmes.txt --output-dir=s3://{your_s3_bucket_name}/output/logs1 --cloud-tmp-dir=s3://{your_s3_bucket_name}/temp/_

---

<br>
    <code><a href="https:/discord.com">
        <img src="https://img.shields.io/badge/Léo Albergaria%20-%237289DA.svg?&style=for-the-badge&logo=discord&logoColor=white" /></a></code>
    <code><a href="https://www.linkedin.com/in/adm-leo-albergaria/">
        <img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a></code>
<br>     

<a href="https://www.digitalinnovation.one/">
    <img src="https://user-images.githubusercontent.com/63436406/127776292-9ec4809a-1137-4dc8-b493-7de0186fd55c.png" align="right" height="80px" width="250px" ></a>
