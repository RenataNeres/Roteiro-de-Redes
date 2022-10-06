# Roteiro-de-Redes

## Orientador: Alaelson Jatobá <br /> Disciplina: Infraestrutura de Redes <br /> Data: 13/10/2022 <br /> Turma: 923 - Grupo: 07

### Integrantes
* Nome: Renata Neres da Silva
* Nome: Allana Silva de Mendonça Ataíde
* Nome: Amanda da Silva Lima

Tabela 1: Definições de endereços IPs da Rede e Nomes de Hosts

```
-------------------------------------------------------------------------------------------------
|  DESCRICAO  |  IP               |   hostname        |          FQDN           |     aliase    |
-------------------------------------------------------------------------------------------------
| VM1-PC1     | 192.168.23.101/28  |   srv-vm1-pc1     | lan1.grupo7.ifalara.net |      ara      |
| VM2-PC1     | 192.168.23.102/28  |   srv-vm2-pc1     | lan2.grupo7.ifalara.net |      aar      |
| VM1-PC2     | 192.168.23.105/28  |   srv-vm1-pc3     | vm3-ifalara.net         |      raa      |
| VM2-PC2     | 192.168.23.106/28  |   srv-vm2-pc3     | vm4-ifalara.net         |      rrr      |
| VM1-PC3     | 192.168.23.107/28  |   srv-vm1-pc4     | reh6.grupo7.ifalara.net |      aaa      |
| VM2-PC3     | 192.168.23.108/28  |   srv-vm2-pc4     | reh7.grupo7.ifalara.net |      rra      |
-------------------------------------------------------------------------------------------------
```
Antes de configurar as VMs foi necessário acessar a pasta da turma, no caso a pasta 923, que está nos arquivos do sistema (Linux), e para acessar precisamos entrar pelo terminal. Após acessar e configurar, fomos para o VirtualBox, onde criamos uma VM e clonamos nos outros pcs de acordo com o passo a passo, fizemos a instalação do SSH e adicionamos os Users para cada VM.<br/>
![WhatsApp Image 2022-10-05 at 21 44 06](https://user-images.githubusercontent.com/108026050/194366649-e26f329b-9a3e-432b-b4ed-ac7d8764d345.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 44 05 (2)](https://user-images.githubusercontent.com/108026050/194366655-42817fcf-28ad-45d7-ba3a-1b2a779b9c0e.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 44 05 (1)](https://user-images.githubusercontent.com/108026050/194366658-b212373b-65bf-4277-8947-e1be9d5a3074.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 44 05](https://user-images.githubusercontent.com/108026050/194366661-6d215779-247d-4490-8189-6e1888f469c0.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 44 04 (2)](https://user-images.githubusercontent.com/108026050/194366665-619d0123-ae0f-4d27-9719-c34f1263b82c.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 44 04 (1)](https://user-images.githubusercontent.com/108026050/194366668-e3ac3f0a-7ed6-4359-8552-b79a67e6758f.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 44 04](https://user-images.githubusercontent.com/108026050/194366681-413e94c2-c577-4f74-a94d-873abe51ea2a.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 44 03 (2)](https://user-images.githubusercontent.com/108026050/194366684-d2121a27-9e6e-4056-b499-912e4af024b4.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 44 03 (1)](https://user-images.githubusercontent.com/108026050/194366693-e9ff46c8-18b6-4923-af72-aace52a979b4.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 44 03](https://user-images.githubusercontent.com/108026050/194366700-ccb78424-e981-4c5d-b503-f2ed08598b23.jpeg)<br/><br/>

![WhatsApp Image 2022-10-05 at 21 49 36 (2)](https://user-images.githubusercontent.com/108026050/194367849-f2ac9931-6f4f-4418-bede-10b01846f514.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 36 (1)](https://user-images.githubusercontent.com/108026050/194367855-9566aec1-46d8-4bd0-8ba0-9538c90d852b.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 36](https://user-images.githubusercontent.com/108026050/194367864-7ab81207-c4f1-4624-871e-e404eaf54144.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 32](https://user-images.githubusercontent.com/108026050/194367873-b7d51a32-e29e-4617-b480-02b0a5030ae6.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 36 (2)](https://user-images.githubusercontent.com/108026050/194368690-ed6388fe-65bd-438d-ab80-6dcd6dba90fb.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 36 (1)](https://user-images.githubusercontent.com/108026050/194368696-9c4d74ee-8cc4-4c2f-a1c8-08b800cb6998.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 36](https://user-images.githubusercontent.com/108026050/194368704-1296f5db-a163-45b0-9d4e-af18cceb7543.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 32](https://user-images.githubusercontent.com/108026050/194368708-e4f9d28a-c5a0-4927-a7c4-8a8466d30009.jpeg)<br/>

### Topologia física
![WhatsApp Image 2022-10-05 at 21 49 39 (1)](https://user-images.githubusercontent.com/108026050/194368666-d0d32249-39a9-4407-bfee-d4dbdc930505.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 39](https://user-images.githubusercontent.com/108026050/194368670-aa259b13-bb01-48e7-9ea3-57d5c2f3d8f6.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 38](https://user-images.githubusercontent.com/108026050/194368673-cde5380b-5e46-41d3-85cb-3760257ab215.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 37 (2)](https://user-images.githubusercontent.com/108026050/194368675-ccc7e257-8109-49e6-8e58-8c373f1dff1f.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 37 (1)](https://user-images.githubusercontent.com/108026050/194368677-ad1bc0cd-acdd-4033-9e80-a11da5f8e2a9.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 37](https://user-images.githubusercontent.com/108026050/194368679-193c2753-322d-4638-a790-c20aefa7c769.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 36 (4)](https://user-images.githubusercontent.com/108026050/194368685-98c67b88-2e47-470c-aa23-53a6c871d471.jpeg)<br/>
![WhatsApp Image 2022-10-05 at 21 49 36 (3)](https://user-images.githubusercontent.com/108026050/194368687-efdc7a18-8b98-44df-8d5e-4715ac26965e.jpeg)<br/>
