# Migrando Networking para Systemd-Networkd
O serviço Networking é o gerenciador de interfaces de rede padrão utilizado nas distribuições Debian. <br>
Por já ser um gerenciador antigo,  possui algumas desvantagens em manutenções contínuas, como arquivos de configurações bem extenso e 
pouco recurso para automações. <br>
Já o Networkd possui configurações mais simples e diretas, permitindo mais flexibilidade em maiores escalas. <br>

## Precauções
Por se tratar de configurações de rede através de acesso remoto é sempre bom garantir outro meio de acesso ao host em caso de imprevistos.
