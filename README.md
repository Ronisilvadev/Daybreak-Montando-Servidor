# 💥 Daybreak-Online- All In One Repo
Um repositório abrangente para o Daybreak Online, contendo diversas ferramentas, bancos de dados e arquivos necessários para configurar o servidor.

## App preview
![image](https://github.com/thebitnomad/Daybreak-Online-AIO/assets/134553365/c67e4032-a153-419c-9692-4dfb16855ed0)

## ℹ️ Considerações




## - Requisitos Minimos:

### O requisitos minimos pra rodar um server com autenticaçao de senha.

- *Windows,  minimo 16 de memoria ram, 250gb preferencia SSD*

### Caso não va fazer nada com autenticaçao de senha. (logar no jogo sem senha)

- *Windows,  minimo 8 de memoria ram, 120 gb preferencia SSD*

## ℹ️ Download de todos os arquivos 

  - senha do winrar: 0302

- [Download 1](https://www.mediafire.com/file/5ukibcvktsn7y76/daybreak_brasil_servidor_parte_2.rar/file) 

 - Arquivos e programas - mysql, workbranch, notepad++, WinSCP, VMware, Pacote visual C++, Config da vm exportada etc 
 - Todos os bancos de dados
 - Pasta master web, ja configurada e traduzida
 - Lista de permissões 
 - LAUNCHER ja configurado 

- [Download 2](https://www.mediafire.com/file/6lypobmvk3osybd/daybreak_brasil_servidor_parte_1.rar/file) 
- Apenas a VM Erating


## 📝 TUTORIAL, PASSO A PASSO!

### Passo 1:

#### *Primeiramente, caso ja tenha tentado montar um servidor, sugiro desinstalar o mysql por completo, e começar uma instalação limpa do zero *

:white_check_mark: *https://www.youtube.com/watch?v=JRktM3Qc37g&t=90s*








### 2. Configuração do Servidor

- Suba o VMWare `erating`.
- Suba o VMWare `GameServer`.
- Vá até o diretório `/sdetector/sat_detector.cfg` na maquina do GameServer. 
- A string se resume em IP "Invertido e Convertido em decimal" / PORTA / PORTA. Você deve alterar apenas o IP, apontando para o GMTools. Utilize uma ferramenta como [IPAddressGuide](https://www.ipaddressguide.com/ip) para converter o IP para decimal. Por exemplo, o IP `192.168.18.6` invertido; `6.18.168.192` convertido para decimal é `101886144`, portanto, a string completa será `101886144:9999:81920`.
- Após acessar o Saturn Master, Clique com o botão direito do mouse na página e selecione `traduzir para português` ou qualquer outro idioma de sua preferência.
- Clique em `Gerenciamento físico de maquinas` e adicione o servidor do banco, e o Game server conforme exemplos; 
![image](https://github.com/thebitnomad/Daybreak-Online-AIO/assets/134553365/741dba86-1620-4f51-afe2-5a838c467a24)
![image](https://github.com/thebitnomad/Daybreak-Online-AIO/assets/134553365/4f43c303-8a10-42a8-8232-83f33d34783f)
- No servidor do GameServer, adicione esses dois caminhos; `/home/sdetector/sdetector` e `/home/server/dbserver` "o nome muda conforme a tradução"
  
![image](https://github.com/thebitnomad/Daybreak-Online-AIO/assets/134553365/4898bb47-2815-40cb-a4d5-3027b7fc7eda)
- Se a configuração estiver certa, a linha do GameServer que estava vermelha, vai ficar toda verde. PS: A linha do banco de dados permanece vermelha.
  
![image](https://github.com/thebitnomad/Daybreak-Online-AIO/assets/134553365/374b0518-dc35-4fc8-8058-4c938cd7bfda)

### 3. Iniciar GameServer
- Clique em `Gestão de serviços distritais` , `Adicionar um grupo de servidores` 
![image](https://github.com/thebitnomad/Daybreak-Online-AIO/assets/134553365/020b1886-4e78-4ab3-a180-ffd52cdfc0e6)
- Na Progressão do jogo, selecione `/home/server/dbserver` e Ok.
- Clique no icone de engrenagem, preencha os dados do seu banco de dados, IP, usuario e senha, desabilite o log, e opção de autenticação do erating; 
![image](https://github.com/thebitnomad/Daybreak-Online-AIO/assets/134553365/f46f07e3-67fb-41ee-b788-91fbf95da1e0)
![image](https://github.com/thebitnomad/Daybreak-Online-AIO/assets/134553365/5496e722-fdc4-4987-ac96-938e683c9608)
- Após isso é só clicar em play; ![image](https://github.com/thebitnomad/Daybreak-Online-AIO/assets/134553365/c74764fc-0307-451c-af43-44f416e62f16)
- Se a configuração estiver certa, a linha do Servidor que estava vermelha, vai ficar verde. após isso, alterar o `svrlist` na pasta do [DayBreak Game Client](https://drive.google.com/file/d/1B7Mx6gyQeBXmqtlSbVgdO2RjoAxwAaJG/view?usp=drive_link)

![image](https://github.com/thebitnomad/Daybreak-Online-AIO/assets/134553365/41f18fe8-32aa-4d11-92bc-54caae66f0a6)
- Coloque o IP do GameServer e verifique a porta utilizada na VM do mesmo, utilizando o comando `netstat -tulnp`



### 🙏 Apoie o Projeto

Considere fazer uma doação.

Qualquer valor é bem-vindo e apreciado!

Endereço da Carteira (BSC/ETHEREUM/POLYGON): `0x9EEEAF03f3e3993f5C9b1Be69df3Ca94120f2eF1`

**Observação**: Aceitamos doações em qualquer rede. Sinta-se à vontade para escolher a rede que for mais conveniente para você.

Agradecemos antecipadamente por seu generoso apoio. Com sua ajuda, podemos continuar aprimorando e expandindo o projeto!









