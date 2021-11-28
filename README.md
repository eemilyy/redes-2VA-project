# redes-2VA-project
Project for course Redes de Computadores

## :page_facing_up: Description
Uma rede de supermercado irá inaugura uma nova unidade na cidade de Garanhuns e contratou você como engenheiro de redes para projetar e configurar toda a infraestrutura da nova unidade. O Gerente Geral da unidade fez as seguintes exigências para o projeto:
1. Deve existir uma rede que separa os caixas.
2. Deve existir uma rede para disponibilizar WIFI para os clientes no interior da loja.
3. Existe um setor administrativo onde ficam as gerências e os chefes de departamento.
Gerentes e chefes devem estar em redes diferentes.
4. Existe um setor reservado para o NTI, onde terá um servidor DHCP, um servidor DNS e
um servidor de arquivos FTP. Todos os computadores da loja devem ser capazes de
acessar os servidores do NTI.

Considere que a loja, o setor administrativo e o NTI estão em prédio distintos e que você deve
prover redundância da comunicação entre os prédios. Cada prédio tem seu próprio roteador e
deve haver um algoritmo de roteamento dinâmico configurado para conectar as redes.

O prédio administrativo tem dois andares, no térreo fica apenas um roteador e um switch
principal, nos demais andares têm: uma sala para as gerencias e outra para os chefes de
departamento. No prédio do NTI ficarão os servidores. Na loja terá os caixas e um Acess Point
para a rede WIFI.

