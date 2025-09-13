# Atalhos para um técnico usar no **CMD** ⚙

## Informação do Sistema e Hardware :

| *Códigos* | *Função* |
| --------|------- |
| *systeminfo* | **Exibe uma lista abrangente das informações do hardware e do software do sistema operacional, como processador, memória RAM e versão do Windows.** |
| *diskpart* | **Uma ferramenta para gerenciar discos e partições. Abra o CMD como administrador, digite `diskpart`, e use comandos como `list disk`, `select disk X`, `create partition primary` e `format fs=ntfs quick`.** |

### Quando eles podem ser úteis ?

`systeminfo` = *Quando o técnico precisa de algum tipo de informação do computador.*

`diskpart` = *Quando o HD do cliente tem várias repertições e você precisa mexer em alguma.* 

## Diagnóstico e Reparo de Hardware :

| *Códigos* | *Função* |
| --------|------- |
| *sfc/scannow* | **Escaneia e repara arquivos do sistema protegidos, útil para corrigir falhas no Windows.** |
| *chkdsk <unidade>: /f ou /r* | **Verifica e corrige erros no disco rígido ou SSD. Use `/f` para corrigir erros de sistema de arquivos e `/r` para localizar setores defeituosos em HDs.** |

### Quando eles podem ser úteis ?

`sfc/scannow` = Quando o têcnico precisa escanear/reparar algum arquivo expecifico.

`chkdsk : /f ou /r` = Para o técnico corrigir algum defeito de disco rigido ou SSD e acha defeitos no HD.

## Comandos de Rede :
| *Códigos* | *Função* |
| --------|------- |
| *ipconfig /all* |  **Mostra informações detalhadas sobre a configuração IP de cada adaptador de rede, incluindo endereço IP, máscara de sub-rede e gateway padrão.** |
| *ping <endereço_ip>* |  **Envia pacotes de dados para um endereço IP para verificar a conectividade e latência da rede.** |

### Quando eles podem ser úteis ?

`ipconfig /all` = Quando o técnico quer informações sobre a rede em expecifico.

`ping <endereço_ip>` = Usado principalmente para ver a conexão de uma rede e a latência.

## `✨Bonús outros Comandos Úteis :`

| *Códigos* | *Função* |
| --------|------- |
| *cls* | Limpa a tela do Prompt de Comando, tornando a visualização mais fácil.|
| *taskkill /IM <nome_imagem.exe>* | Força o encerramento de um processo ou aplicativo. |
| *shutdown /s /t 0* | Desliga o computador imediatamente. |

## 👤 Autor

### *Marco Antonio de Azevedo Kruger*

## 📅 Data

### 12/09/2025

## 📧 Contato

### Email: *contatomarcokruger@gmail.com*
### Github: https://github.com/MarcoAAKruger

## 🧠 O que aprendi?
### *Na aula de hoje aprendi um pouco de como o Github funciona, aprendi também o básico do VS Studio, aprendi sobre Markdown e fiz esse repositório todo que você acabou de ver !.*
