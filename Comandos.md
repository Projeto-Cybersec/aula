O Windows PowerShell
Copyright (C) Microsoft Corporation. Todos os direitos reservados.

Instale o PowerShell mais recente para obter novos recursos e aprimoramentos! https://aka.ms/PSWindows

PS C:\Users\Arestides> CD cursocyber
PS C:\Users\Arestides\cursocyber> cd formacao_cybersec
cd : Não é possível localizar o caminho 'C:\Users\Arestides\cursocyber\formacao_cybersec' porque ele não existe.
No linha:1 caractere:1
+ cd formacao_cybersec
+ ~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\Aresti...rmacao_cybersec:String) [Set-Location], ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\Arestides\cursocyber> cd formacao-cybersec
PS C:\Users\Arestides\cursocyber\formacao-cybersec> cd formacao-cybersec
PS C:\Users\Arestides\cursocyber\formacao-cybersec\formacao-cybersec> cd modulo1-fundamentos
PS C:\Users\Arestides\cursocyber\formacao-cybersec\formacao-cybersec\modulo1-fundamentos> cd projeto_final_opcao_1
PS C:\Users\Arestides\cursocyber\formacao-cybersec\formacao-cybersec\modulo1-fundamentos\projeto_final_opcao_1> docker compose down
[+] Running 0/15
 - Container laptop-vastro    Removing                                                                                                     0.1s 
 - Container analyst          Removing                                                                                                     0.1s 
 - Container laptop-luiz      Removing                                                                                                     0.1s 
 - Container WS_004           Removing                                                                                                     0.1s 
 - Container legacy-server    Removing                                                                                                     0.1s 
 - Container ftp-server       Removing                                                                                                     0.1s 
[+] Running 15/1801           Removing                                                                                                     0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 15/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 15/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 15/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 16/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 16/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 16/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 16/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 17/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 17/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 17/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 17/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
[+] Running 18/1802                         Removed                                                                                        0.1s 
 ✔ Container laptop-vastro                  Removed                                                                                        0.1s 
 ✔ Container analyst                        Removed                                                                                        0.1s 
 ✔ Container laptop-luiz                    Removed                                                                                        0.1s 
 ✔ Container WS_004                         Removed                                                                                        0.1s 
 ✔ Container legacy-server                  Removed                                                                                        0.1s 
 ✔ Container ftp-server                     Removed                                                                                        0.1s 
 ✔ Container WS_001                         Removed                                                                                        0.1s 
 ✔ Container macbook-aline                  Removed                                                                                        0.1s 
 ✔ Container mysql-server                   Removed                                                                                        0.1s 
 ✔ Container WS_002                         Removed                                                                                        0.1s 
 ✔ Container notebook-carlos                Removed                                                                                        0.1s 
 ✔ Container openldap                       Removed                                                                                        0.2s 
 ✔ Container samba-server                   Removed                                                                                        0.1s 
 ✔ Container WS_003                         Removed                                                                                        0.1s 
 ✔ Container zabbix-server                  Removed                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_corp_net   Removed                                                                                        1.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Removed                                                                                        0.8s 
 ✔ Network projeto_final_opcao_1_guest_net  Removed                                                                                        0.4s 
PS C:\Users\Arestides\cursocyber\formacao-cybersec\formacao-cybersec\modulo1-fundamentos\projeto_final_opcao_1> docker compose up -d
[+] Running 3/18
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Creating                                                                                       0.1s 
 - Container openldap                       Creating                                                                                       0.1s 
 - Container notebook-carlos                Creating                                                                                       0.1s 
 - Container laptop-vastro                  Creating                                                                                       0.1s 
 - Container WS_001                         Creating                                                                                       0.1s 
 - Container macbook-aline                  Creating                                                                                       0.1s 
[+] Running 3/18bix-server                  Creating                                                                                       0.1s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Creating                                                                                       0.2s 
 - Container openldap                       Creating                                                                                       0.2s 
 - Container notebook-carlos                Creating                                                                                       0.2s 
 - Container laptop-vastro                  Creating                                                                                       0.2s 
 - Container WS_001                         Creating                                                                                       0.2s 
 - Container macbook-aline                  Creating                                                                                       0.2s 
[+] Running 10/18ix-server                  Creating                                                                                       0.2s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Creating                                                                                       0.3s 
 ✔ Container openldap                       Created                                                                                        0.2s 
 ✔ Container notebook-carlos                Created                                                                                        0.2s 
 ✔ Container laptop-vastro                  Created                                                                                        0.3s 
 - Container WS_001                         Creating                                                                                       0.3s 
 - Container macbook-aline                  Creating                                                                                       0.3s 
[+] Running 17/18ix-server                  Creating                                                                                       0.3s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Creating                                                                                       0.4s 
 ✔ Container openldap                       Created                                                                                        0.2s 
 ✔ Container notebook-carlos                Created                                                                                        0.2s 
 ✔ Container laptop-vastro                  Created                                                                                        0.3s 
 ✔ Container WS_001                         Created                                                                                        0.3s 
 ✔ Container macbook-aline                  Created                                                                                        0.3s 
[+] Running 17/18ix-server                  Created                                                                                        0.3s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Creating                                                                                       0.5s 
 ✔ Container openldap                       Created                                                                                        0.2s 
 ✔ Container notebook-carlos                Created                                                                                        0.2s 
 ✔ Container laptop-vastro                  Created                                                                                        0.3s 
 ✔ Container WS_001                         Created                                                                                        0.3s 
 ✔ Container macbook-aline                  Created                                                                                        0.3s 
[+] Running 3/18bix-server                  Created                                                                                        0.3s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       0.6s 
 - Container openldap                       Starting                                                                                       0.6s 
 - Container notebook-carlos                Starting                                                                                       0.6s 
 - Container laptop-vastro                  Starting                                                                                       0.6s 
 - Container WS_001                         Starting                                                                                       0.6s 
 - Container macbook-aline                  Starting                                                                                       0.6s 
[+] Running 3/18bix-server                  Starting                                                                                       0.6s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       0.7s 
 - Container openldap                       Starting                                                                                       0.7s 
 - Container notebook-carlos                Starting                                                                                       0.7s 
 - Container laptop-vastro                  Starting                                                                                       0.7s 
 - Container WS_001                         Starting                                                                                       0.7s 
 - Container macbook-aline                  Starting                                                                                       0.7s 
[+] Running 3/18bix-server                  Starting                                                                                       0.7s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       0.8s 
 - Container openldap                       Starting                                                                                       0.8s 
 - Container notebook-carlos                Starting                                                                                       0.8s 
 - Container laptop-vastro                  Starting                                                                                       0.8s 
 - Container WS_001                         Starting                                                                                       0.8s 
 - Container macbook-aline                  Starting                                                                                       0.8s 
[+] Running 3/18bix-server                  Starting                                                                                       0.8s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       0.9s 
 - Container openldap                       Starting                                                                                       0.9s 
 - Container notebook-carlos                Starting                                                                                       0.9s 
 - Container laptop-vastro                  Starting                                                                                       0.9s 
 - Container WS_001                         Starting                                                                                       0.9s 
 - Container macbook-aline                  Starting                                                                                       0.9s 
[+] Running 3/18bix-server                  Starting                                                                                       0.9s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       1.0s 
 - Container openldap                       Starting                                                                                       1.0s 
 - Container notebook-carlos                Starting                                                                                       1.0s 
 - Container laptop-vastro                  Starting                                                                                       1.0s 
 - Container WS_001                         Starting                                                                                       1.0s 
 - Container macbook-aline                  Starting                                                                                       1.0s 
[+] Running 3/18bix-server                  Starting                                                                                       1.0s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       1.1s 
 - Container openldap                       Starting                                                                                       1.1s 
 - Container notebook-carlos                Starting                                                                                       1.1s 
 - Container laptop-vastro                  Starting                                                                                       1.1s 
 - Container WS_001                         Starting                                                                                       1.1s 
 - Container macbook-aline                  Starting                                                                                       1.1s 
[+] Running 3/18bix-server                  Starting                                                                                       1.1s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       1.2s 
 - Container openldap                       Starting                                                                                       1.2s 
 - Container notebook-carlos                Starting                                                                                       1.2s 
 - Container laptop-vastro                  Starting                                                                                       1.2s 
 - Container WS_001                         Starting                                                                                       1.2s 
 - Container macbook-aline                  Starting                                                                                       1.2s 
[+] Running 3/18bix-server                  Starting                                                                                       1.2s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       1.3s 
 - Container openldap                       Starting                                                                                       1.3s 
 - Container notebook-carlos                Starting                                                                                       1.3s 
 - Container laptop-vastro                  Starting                                                                                       1.3s 
 - Container WS_001                         Starting                                                                                       1.3s 
 - Container macbook-aline                  Starting                                                                                       1.3s 
[+] Running 3/18bix-server                  Starting                                                                                       1.3s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       1.4s 
 - Container openldap                       Starting                                                                                       1.4s 
 - Container notebook-carlos                Starting                                                                                       1.4s 
 - Container laptop-vastro                  Starting                                                                                       1.4s 
 - Container WS_001                         Starting                                                                                       1.4s 
 - Container macbook-aline                  Starting                                                                                       1.4s 
[+] Running 3/18bix-server                  Starting                                                                                       1.4s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       1.5s 
 - Container openldap                       Starting                                                                                       1.5s 
 - Container notebook-carlos                Starting                                                                                       1.5s 
 - Container laptop-vastro                  Starting                                                                                       1.5s 
 - Container WS_001                         Starting                                                                                       1.5s 
 - Container macbook-aline                  Starting                                                                                       1.5s 
[+] Running 3/18bix-server                  Starting                                                                                       1.5s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       1.6s 
 - Container openldap                       Starting                                                                                       1.6s 
 - Container notebook-carlos                Starting                                                                                       1.6s 
 - Container laptop-vastro                  Starting                                                                                       1.6s 
 - Container WS_001                         Starting                                                                                       1.6s 
 - Container macbook-aline                  Starting                                                                                       1.6s 
[+] Running 3/18bix-server                  Starting                                                                                       1.6s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       1.7s 
 - Container openldap                       Starting                                                                                       1.7s 
 - Container notebook-carlos                Starting                                                                                       1.7s 
 - Container laptop-vastro                  Starting                                                                                       1.7s 
 - Container WS_001                         Starting                                                                                       1.7s 
 - Container macbook-aline                  Starting                                                                                       1.7s 
[+] Running 3/18bix-server                  Starting                                                                                       1.7s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       1.8s 
 - Container openldap                       Starting                                                                                       1.8s 
 - Container notebook-carlos                Starting                                                                                       1.8s 
 - Container laptop-vastro                  Starting                                                                                       1.8s 
 - Container WS_001                         Starting                                                                                       1.8s 
 - Container macbook-aline                  Starting                                                                                       1.8s 
[+] Running 3/18bix-server                  Starting                                                                                       1.8s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       1.9s 
 - Container openldap                       Starting                                                                                       1.9s 
 - Container notebook-carlos                Starting                                                                                       1.9s 
 - Container laptop-vastro                  Starting                                                                                       1.9s 
 - Container WS_001                         Starting                                                                                       1.9s 
 - Container macbook-aline                  Starting                                                                                       1.9s 
[+] Running 7/18bix-server                  Starting                                                                                       1.9s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 - Container samba-server                   Starting                                                                                       2.0s 
 - Container openldap                       Starting                                                                                       2.0s 
 ✔ Container notebook-carlos                Started                                                                                        1.9s 
 ✔ Container laptop-vastro                  Started                                                                                        1.9s 
 ✔ Container WS_001                         Started                                                                                        2.0s 
 - Container macbook-aline                  Starting                                                                                       2.0s 
[+] Running 13/18ix-server                  Starting                                                                                       2.0s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 ✔ Container samba-server                   Started                                                                                        2.0s 
 ✔ Container openldap                       Started                                                                                        2.0s 
 ✔ Container notebook-carlos                Started                                                                                        1.9s 
 ✔ Container laptop-vastro                  Started                                                                                        1.9s 
 ✔ Container WS_001                         Started                                                                                        2.0s 
 - Container macbook-aline                  Starting                                                                                       2.1s 
[+] Running 18/18ix-server                  Starting                                                                                       2.1s 
 ✔ Network projeto_final_opcao_1_corp_net   Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_infra_net  Created                                                                                        0.1s 
 ✔ Network projeto_final_opcao_1_guest_net  Created                                                                                        0.0s 
 ✔ Container samba-server                   Started                                                                                        2.0s 
 ✔ Container openldap                       Started                                                                                        2.0s 
 ✔ Container notebook-carlos                Started                                                                                        1.9s 
 ✔ Container laptop-vastro                  Started                                                                                        1.9s 
 ✔ Container WS_001                         Started                                                                                        2.0s 
 ✔ Container macbook-aline                  Started                                                                                        2.1s 
 ✔ Container zabbix-server                  Started                                                                                        2.1s 
 ✔ Container laptop-luiz                    Started                                                                                        2.0s 
 ✔ Container legacy-server                  Started                                                                                        2.0s 
 ✔ Container ftp-server                     Started                                                                                        2.1s 
 ✔ Container mysql-server                   Started                                                                                        2.0s 
 ✔ Container analyst                        Started                                                                                        2.1s 
 ✔ Container WS_002                         Started                                                                                        1.9s 
 ✔ Container WS_003                         Started                                                                                        2.0s 
 ✔ Container WS_004                         Started                                                                                        2.1s 
PS C:\Users\Arestides\cursocyber\formacao-cybersec\formacao-cybersec\modulo1-fundamentos\projeto_final_opcao_1> docker exec -it analyst bash
┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# ls -la
total 64
drwx------ 1 analyst analyst  4096 Jul 18 14:12 .
drwxr-xr-x 1 root    root     4096 Jul 18 14:12 ..
-rw-r--r-- 1 root    root     2892 Jul 18 14:12 .ANOTACAO-ULTIMO-SCAN.TXT
-rw-r--r-- 1 analyst analyst   220 May 19 18:11 .bash_logout
-rw-r--r-- 1 analyst analyst  5551 Jun  1 04:02 .bashrc
-rw-r--r-- 1 analyst analyst  3526 May 19 18:11 .bashrc.original
drwxr-xr-x 3 analyst analyst  4096 Jun  1 04:02 .config
drwxr-xr-x 3 analyst analyst  4096 Jun  1 04:02 .java
drwxr-xr-x 3 analyst analyst  4096 Jun  1 04:02 .local
-rw-r--r-- 1 analyst analyst   807 May 19 18:11 .profile
-rw-r--r-- 1 analyst analyst   336 May 21 10:39 .zprofile
-rw-r--r-- 1 analyst analyst 10856 May 21 10:39 .zshrc

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# ^C

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# cat .ANOTACAO-ULTIMO-SCAN.TXT
# NÃO APAGAR

# SE VOCÊ ACHOU ISSO E ESTÁ FAZENDO O DESAFIO DO PROJETO FINAL OPÇÃO 1 SE DEU BEM ;-) ...

# comandos que eu executei a ultima vez que estava aqui... deixar anotado pq pode salvar tempo da próxima vez.

## Primeiro pegar info das redes
ip a
ip a | grep inet
ip a | grep inet > recon-redes.txt

## Testar se tem conectividade com as redes
ping -c 3 10.10.10.1  # corp_net
ping -c 3 10.10.30.1  # guest_net
ping -c 3 10.10.50.1  # infra_net

## 1. descobrir os hosts com Nmap ping scan
nmap -sn -T4 10.10.10.0/24 -oG - | grep "Up"
nmap -sn -T4 10.10.10.0/24 -oG - | awk '/Up$/{print $2}' | tee corp_net_ips.txt
nmap -sn -T4 10.10.10.0/24 -oG - | awk '/Up$/{print $2, $3}' | tee corp_net_ips_hosts.txt

nmap -sn -T4 10.10.30.0/24 -oG - | grep "Up"
nmap -sn -T4 10.10.30.0/24 -oG - | awk '/Up$/{print $2}' | tee infra_net_ips.txt
nmap -sn -T4 10.10.30.0/24 -oG - | awk '/Up$/{print $2, $3}' | tee infra_net_ips_hosts.txt

nmap -sn -T4 10.10.50.0/24 -oG - | grep "Up"
nmap -sn -T4 10.10.50.0/24 -oG - | awk '/Up$/{print $2}' | tee guest_net_ips.txt
nmap -sn -T4 10.10.50.0/24 -oG - | awk '/Up$/{print $2, $3}' | tee guest_net_ips_hosts.txt

## 2. Scan rápido com Rustscan para pegar as portas abertas
rustscan -a 'corp_net_ips.txt' | grep Open > corp_net_ips_ports.txt
rustscan -a 'infra_net_ips.txt' | grep Open > infra_net_ips_ports.txt
rustscan -a 'guest_net_ips.txt' | grep Open > guest_net_ips_ports.txt

## 3. Analisar os serviços específicos
### FTP
nmap -p 21 --script ftp-anon 10.10.30.10
nmap -p 21 --script ftp-anon 10.10.30.10 > infra_net_servico_ftp-anon.txt

### MySQL
nmap -p 3306 --script mysql-info 10.10.30.11
nmap -p 3306 --script mysql-info 10.10.30.11 > infra_net_servico_mysql-info.txt

### LDAP
nmap -p 389 --script ldap-rootdse 10.10.30.17
nmap -p 389 --script ldap-rootdse 10.10.30.17 > infra_net_servico_ldap-rootdse.txt

### SMB
nmap -p 445 --script smb-os-discovery,smb-enum-shares 10.10.30.15
nmap -p 445 --script smb-os-discovery,smb-enum-shares 10.10.30.15 > infra_net_servico_smb.txt

### HTTP (web)
curl -I http://10.10.30.117
curl -I http://10.10.30.117 > infra_net_servico_webserver.txt
curl http://10.10.30.117
curl http://10.10.30.117 > infra_net_servico_zabbix.txt

## Extras úteis
arp -a
arp -a > recon_ip_maps.txt
cat /etc/resolv.conf

## Organizar os resultados (manter tudo limpinho)
mkdir -p /home/analyst/recon/{corp_net,guest_net,infra_net}
mv *corp*.txt /home/analyst/recon/corp_net/
mv *guest*.txt /home/analyst/recon/guest_net/
mv *infra*.txt /home/analyst/recon/infra_net/
mv *recon*.txt /home/analyst/recon/

## Copiar depois pro host local - tem que sair do docker e rodar da maquina local
docker cp analyst:/home/analyst/recon ./recon-backup

## Inventário final (manual mesmo, preenche depois)
# IP:
# Hostname:
# SO estimado:
# Portas abertas:
# Serviços:
# Notas: login anônimo? dados sensíveis? falhas visíveis?

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# ^C

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# ip a
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host proto kernel_lo
       valid_lft forever preferred_lft forever
2: eth0@if11: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc noqueue state UP group default
    link/ether 3a:97:4d:53:37:e6 brd ff:ff:ff:ff:ff:ff link-netnsid 0
    inet 10.10.10.2/24 brd 10.10.10.255 scope global eth0
       valid_lft forever preferred_lft forever
3: eth1@if26: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc noqueue state UP group default
    link/ether 5e:f1:b9:ea:53:4d brd ff:ff:ff:ff:ff:ff link-netnsid 0
    inet 10.10.50.6/24 brd 10.10.50.255 scope global eth1
       valid_lft forever preferred_lft forever
4: eth2@if27: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc noqueue state UP group default
    link/ether 72:e3:79:3b:d3:40 brd ff:ff:ff:ff:ff:ff link-netnsid 0
    inet 10.10.30.2/24 brd 10.10.30.255 scope global eth2
       valid_lft forever preferred_lft forever

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# ip a | grep inet
    inet 127.0.0.1/8 scope host lo
    inet6 ::1/128 scope host proto kernel_lo
    inet 10.10.10.2/24 brd 10.10.10.255 scope global eth0
    inet 10.10.50.6/24 brd 10.10.50.255 scope global eth1
    inet 10.10.30.2/24 brd 10.10.30.255 scope global eth2

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# ip a | grep inet > recon-redes.txt

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# ping -c 3 10.10.10.1
PING 10.10.10.1 (10.10.10.1) 56(84) bytes of data.
64 bytes from 10.10.10.1: icmp_seq=1 ttl=64 time=4.83 ms
64 bytes from 10.10.10.1: icmp_seq=2 ttl=64 time=0.111 ms
64 bytes from 10.10.10.1: icmp_seq=3 ttl=64 time=0.071 ms

--- 10.10.10.1 ping statistics ---
3 packets transmitted, 3 received, 0% packet loss, time 2012ms
rtt min/avg/max/mdev = 0.071/1.671/4.833/2.235 ms

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# ping -c 3 10.10.30.1
PING 10.10.30.1 (10.10.30.1) 56(84) bytes of data.
64 bytes from 10.10.30.1: icmp_seq=1 ttl=64 time=3.92 ms
64 bytes from 10.10.30.1: icmp_seq=2 ttl=64 time=0.072 ms
64 bytes from 10.10.30.1: icmp_seq=3 ttl=64 time=0.055 ms

--- 10.10.30.1 ping statistics ---
3 packets transmitted, 3 received, 0% packet loss, time 2035ms
rtt min/avg/max/mdev = 0.055/1.347/3.916/1.816 ms

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# ping -c 3 10.10.50.1
PING 10.10.50.1 (10.10.50.1) 56(84) bytes of data.
64 bytes from 10.10.50.1: icmp_seq=1 ttl=64 time=1.78 ms
64 bytes from 10.10.50.1: icmp_seq=2 ttl=64 time=0.064 ms
64 bytes from 10.10.50.1: icmp_seq=3 ttl=64 time=0.110 ms

--- 10.10.50.1 ping statistics ---
3 packets transmitted, 3 received, 0% packet loss, time 2028ms
rtt min/avg/max/mdev = 0.064/0.652/1.784/0.800 ms

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -sn -T4 10.10.10.0/24 -oG - | grep "Up"
Host: 10.10.10.1 ()     Status: Up
Host: 10.10.10.10 (WS_001.projeto_final_opcao_1_corp_net)       Status: Up
Host: 10.10.10.101 (WS_002.projeto_final_opcao_1_corp_net)      Status: Up
Host: 10.10.10.127 (WS_003.projeto_final_opcao_1_corp_net)      Status: Up
Host: 10.10.10.222 (WS_004.projeto_final_opcao_1_corp_net)      Status: Up
Host: 10.10.10.2 (88b92ff8a75b) Status: Up

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -sn -T4 10.10.10.0/24 -oG - | awk '/Up$/{print $2}' | tee corp_net_ips.txt
10.10.10.1
10.10.10.10
10.10.10.101
10.10.10.127
10.10.10.222
10.10.10.2

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -sn -T4 10.10.10.0/24 -oG - | awk '/Up$/{print $2, $3}' | tee corp_net_ips_hosts.txt
10.10.10.1 ()
10.10.10.10 (WS_001.projeto_final_opcao_1_corp_net)
10.10.10.101 (WS_002.projeto_final_opcao_1_corp_net)
10.10.10.127 (WS_003.projeto_final_opcao_1_corp_net)
10.10.10.222 (WS_004.projeto_final_opcao_1_corp_net)
10.10.10.2 (88b92ff8a75b)

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -sn -T4 10.10.30.0/24 -oG - | grep "Up"
Host: 10.10.30.1 ()     Status: Up
Host: 10.10.30.10 (ftp-server.projeto_final_opcao_1_infra_net)  Status: Up
Host: 10.10.30.11 (mysql-server.projeto_final_opcao_1_infra_net)        Status: Up
Host: 10.10.30.15 (samba-server.projeto_final_opcao_1_infra_net)        Status: Up
Host: 10.10.30.17 (openldap.projeto_final_opcao_1_infra_net)    Status: Up
Host: 10.10.30.117 (zabbix-server.projeto_final_opcao_1_infra_net)      Status: Up
Host: 10.10.30.227 (legacy-server.projeto_final_opcao_1_infra_net)      Status: Up
Host: 10.10.30.2 (88b92ff8a75b) Status: Up

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -sn -T4 10.10.30.0/24 -oG - | awk '/Up$/{print $2}' | tee infra_net_ips.txt
10.10.30.1
10.10.30.10
10.10.30.11
10.10.30.15
10.10.30.17
10.10.30.117
10.10.30.227
10.10.30.2

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -sn -T4 10.10.30.0/24 -oG - | awk '/Up$/{print $2, $3}' | tee infra_net_ips_hosts.txt
10.10.30.1 ()
10.10.30.10 (ftp-server.projeto_final_opcao_1_infra_net)
10.10.30.11 (mysql-server.projeto_final_opcao_1_infra_net)
10.10.30.15 (samba-server.projeto_final_opcao_1_infra_net)
10.10.30.17 (openldap.projeto_final_opcao_1_infra_net)
10.10.30.117 (zabbix-server.projeto_final_opcao_1_infra_net)
10.10.30.227 (legacy-server.projeto_final_opcao_1_infra_net)
10.10.30.2 (88b92ff8a75b)

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -sn -T4 10.10.50.0/24 -oG - | grep "Up"
Host: 10.10.50.1 ()     Status: Up
Host: 10.10.50.2 (laptop-vastro.projeto_final_opcao_1_guest_net)        Status: Up
Host: 10.10.50.3 (notebook-carlos.projeto_final_opcao_1_guest_net)      Status: Up
Host: 10.10.50.4 (laptop-luiz.projeto_final_opcao_1_guest_net)  Status: Up
Host: 10.10.50.5 (macbook-aline.projeto_final_opcao_1_guest_net)        Status: Up
Host: 10.10.50.6 (88b92ff8a75b) Status: Up

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -sn -T4 10.10.50.0/24 -oG - | awk '/Up$/{print $2}' | tee guest_net_ips.txt
10.10.50.1
10.10.50.2
10.10.50.3
10.10.50.4
10.10.50.5
10.10.50.6

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -sn -T4 10.10.50.0/24 -oG - | awk '/Up$/{print $2, $3}' | tee guest_net_ips_hosts.txt
10.10.50.1 ()
10.10.50.2 (laptop-vastro.projeto_final_opcao_1_guest_net)
10.10.50.3 (notebook-carlos.projeto_final_opcao_1_guest_net)
10.10.50.4 (laptop-luiz.projeto_final_opcao_1_guest_net)
10.10.50.5 (macbook-aline.projeto_final_opcao_1_guest_net)
10.10.50.6 (88b92ff8a75b)

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# rustscan -a 'corp_net_ips.txt'
.----. .-. .-. .----..---.  .----. .---.   .--.  .-. .-.
| {}  }| { } |{ {__ {_   _}{ {__  /  ___} / {} \ |  `| |
| .-. \| {_} |.-._} } | |  .-._} }\     }/  /\  \| |\  |
`-' `-'`-----'`----'  `-'  `----'  `---' `-'  `-'`-' `-'
The Modern Day Port Scanner.
________________________________________
: https://discord.gg/GFrQsGy           :
: https://github.com/RustScan/RustScan :
 --------------------------------------
😵 https://admin.tryhackme.com

[~] The config file is expected to be at "/root/.rustscan.toml"
[~] File limit higher than batch size. Can increase speed by increasing batch size '-b 1048476'.
Open 10.10.10.1:111
Open 10.10.10.1:56017
[!] Looks like I didn't find any open ports for 10.10.10.10. This is usually caused by a high batch size.

*I used 4500 batch size, consider lowering it with 'rustscan -b <batch_size> <ip address>' or a comfortable number for your system.

 Alternatively, increase the timeout if your ping is high. Rustscan -t 2000 for 2000 milliseconds (2s) timeout.

[!] Looks like I didn't find any open ports for 10.10.10.101. This is usually caused by a high batch size.

*I used 4500 batch size, consider lowering it with 'rustscan -b <batch_size> <ip address>' or a comfortable number for your system.

 Alternatively, increase the timeout if your ping is high. Rustscan -t 2000 for 2000 milliseconds (2s) timeout.

[!] Looks like I didn't find any open ports for 10.10.10.127. This is usually caused by a high batch size.

*I used 4500 batch size, consider lowering it with 'rustscan -b <batch_size> <ip address>' or a comfortable number for your system.

 Alternatively, increase the timeout if your ping is high. Rustscan -t 2000 for 2000 milliseconds (2s) timeout.

[!] Looks like I didn't find any open ports for 10.10.10.222. This is usually caused by a high batch size.

*I used 4500 batch size, consider lowering it with 'rustscan -b <batch_size> <ip address>' or a comfortable number for your system.

 Alternatively, increase the timeout if your ping is high. Rustscan -t 2000 for 2000 milliseconds (2s) timeout.

[!] Looks like I didn't find any open ports for 10.10.10.2. This is usually caused by a high batch size.

*I used 4500 batch size, consider lowering it with 'rustscan -b <batch_size> <ip address>' or a comfortable number for your system.

 Alternatively, increase the timeout if your ping is high. Rustscan -t 2000 for 2000 milliseconds (2s) timeout.

[~] Starting Script(s)
[>] Script to be run Some("nmap -vvv -p {{port}} {{ip}}")

[~] Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:46 UTC
Initiating ARP Ping Scan at 22:46
Scanning 10.10.10.1 [1 port]
Completed ARP Ping Scan at 22:46, 0.04s elapsed (1 total hosts)
Initiating Parallel DNS resolution of 1 host. at 22:46
Completed Parallel DNS resolution of 1 host. at 22:46, 0.06s elapsed
DNS resolution of 1 IPs took 0.06s. Mode: Async [#: 1, OK: 0, NX: 1, DR: 0, SF: 0, TR: 1, CN: 0]
Initiating SYN Stealth Scan at 22:46
Scanning 10.10.10.1 [2 ports]
Discovered open port 111/tcp on 10.10.10.1
Discovered open port 56017/tcp on 10.10.10.1
Completed SYN Stealth Scan at 22:46, 0.02s elapsed (2 total ports)
Nmap scan report for 10.10.10.1
Host is up, received arp-response (0.000068s latency).
Scanned at 2025-07-24 22:46:44 UTC for 0s

PORT      STATE SERVICE REASON
111/tcp   open  rpcbind syn-ack ttl 64
56017/tcp open  unknown syn-ack ttl 64
MAC Address: 4E:FD:3D:00:B3:DB (Unknown)

Read data files from: /usr/share/nmap
Nmap done: 1 IP address (1 host up) scanned in 0.20 seconds
           Raw packets sent: 3 (116B) | Rcvd: 3 (116B)


┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# rustscan -a 'corp_net_ips.txt' | grep Open > corp_net_ips_ports.txt

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# rustscan -a 'infra_net_ips.txt'
.----. .-. .-. .----..---.  .----. .---.   .--.  .-. .-.
| {}  }| { } |{ {__ {_   _}{ {__  /  ___} / {} \ |  `| |
| .-. \| {_} |.-._} } | |  .-._} }\     }/  /\  \| |\  |
`-' `-'`-----'`----'  `-'  `----'  `---' `-'  `-'`-' `-'
The Modern Day Port Scanner.
________________________________________
: https://discord.gg/GFrQsGy           :
: https://github.com/RustScan/RustScan :
 --------------------------------------
😵 https://admin.tryhackme.com

[~] The config file is expected to be at "/root/.rustscan.toml"
[~] File limit higher than batch size. Can increase speed by increasing batch size '-b 1048476'.
Open 10.10.30.10:21
Open 10.10.30.117:80
Open 10.10.30.1:111
Open 10.10.30.15:139
Open 10.10.30.17:389
Open 10.10.30.15:445
Open 10.10.30.17:636
Open 10.10.30.11:3306
Open 10.10.30.117:10051
Open 10.10.30.117:10052
Open 10.10.30.11:33060
Open 10.10.30.2:50050
Open 10.10.30.1:56017
Open 10.10.30.2:60036
Open 10.10.30.2:60588
[!] Looks like I didn't find any open ports for 10.10.30.227. This is usually caused by a high batch size.

*I used 4500 batch size, consider lowering it with 'rustscan -b <batch_size> <ip address>' or a comfortable number for your system.

 Alternatively, increase the timeout if your ping is high. Rustscan -t 2000 for 2000 milliseconds (2s) timeout.

[~] Starting Script(s)
[>] Script to be run Some("nmap -vvv -p {{port}} {{ip}}")

[~] Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:47 UTC
Initiating ARP Ping Scan at 22:47
Scanning 10.10.30.10 [1 port]
Completed ARP Ping Scan at 22:47, 0.04s elapsed (1 total hosts)
Initiating Parallel DNS resolution of 1 host. at 22:47
Completed Parallel DNS resolution of 1 host. at 22:47, 0.00s elapsed
DNS resolution of 1 IPs took 0.00s. Mode: Async [#: 1, OK: 1, NX: 0, DR: 0, SF: 0, TR: 1, CN: 0]
Initiating SYN Stealth Scan at 22:47
Scanning ftp-server.projeto_final_opcao_1_infra_net (10.10.30.10) [1 port]
Discovered open port 21/tcp on 10.10.30.10
Completed SYN Stealth Scan at 22:47, 0.02s elapsed (1 total ports)
Nmap scan report for ftp-server.projeto_final_opcao_1_infra_net (10.10.30.10)
Host is up, received arp-response (0.000086s latency).
Scanned at 2025-07-24 22:47:52 UTC for 0s

PORT   STATE SERVICE REASON
21/tcp open  ftp     syn-ack ttl 64
MAC Address: 22:67:97:20:F9:BC (Unknown)

Read data files from: /usr/share/nmap
Nmap done: 1 IP address (1 host up) scanned in 0.16 seconds
           Raw packets sent: 2 (72B) | Rcvd: 2 (72B)

[~] Starting Script(s)
[>] Script to be run Some("nmap -vvv -p {{port}} {{ip}}")

[~] Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:47 UTC
Initiating ARP Ping Scan at 22:47
Scanning 10.10.30.117 [1 port]
Completed ARP Ping Scan at 22:47, 0.04s elapsed (1 total hosts)
Initiating Parallel DNS resolution of 1 host. at 22:47
Completed Parallel DNS resolution of 1 host. at 22:47, 0.00s elapsed
DNS resolution of 1 IPs took 0.00s. Mode: Async [#: 1, OK: 1, NX: 0, DR: 0, SF: 0, TR: 1, CN: 0]
Initiating SYN Stealth Scan at 22:47
Scanning zabbix-server.projeto_final_opcao_1_infra_net (10.10.30.117) [3 ports]
Discovered open port 80/tcp on 10.10.30.117
Discovered open port 10051/tcp on 10.10.30.117
Discovered open port 10052/tcp on 10.10.30.117
Completed SYN Stealth Scan at 22:47, 0.02s elapsed (3 total ports)
Nmap scan report for zabbix-server.projeto_final_opcao_1_infra_net (10.10.30.117)
Host is up, received arp-response (0.000062s latency).
Scanned at 2025-07-24 22:47:52 UTC for 0s

PORT      STATE SERVICE        REASON
80/tcp    open  http           syn-ack ttl 64
10051/tcp open  zabbix-trapper syn-ack ttl 64
10052/tcp open  unknown        syn-ack ttl 64
MAC Address: BE:99:EB:D1:C5:E3 (Unknown)

Read data files from: /usr/share/nmap
Nmap done: 1 IP address (1 host up) scanned in 0.15 seconds
           Raw packets sent: 4 (160B) | Rcvd: 4 (160B)

[~] Starting Script(s)
[>] Script to be run Some("nmap -vvv -p {{port}} {{ip}}")

[~] Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:47 UTC
Initiating ARP Ping Scan at 22:47
Scanning 10.10.30.1 [1 port]
Completed ARP Ping Scan at 22:47, 0.03s elapsed (1 total hosts)
Initiating Parallel DNS resolution of 1 host. at 22:47
Completed Parallel DNS resolution of 1 host. at 22:47, 0.04s elapsed
DNS resolution of 1 IPs took 0.04s. Mode: Async [#: 1, OK: 0, NX: 1, DR: 0, SF: 0, TR: 1, CN: 0]
Initiating SYN Stealth Scan at 22:47
Scanning 10.10.30.1 [2 ports]
Discovered open port 111/tcp on 10.10.30.1
Discovered open port 56017/tcp on 10.10.30.1
Completed SYN Stealth Scan at 22:47, 0.03s elapsed (2 total ports)
Nmap scan report for 10.10.30.1
Host is up, received arp-response (0.000089s latency).
Scanned at 2025-07-24 22:47:52 UTC for 0s

PORT      STATE SERVICE REASON
111/tcp   open  rpcbind syn-ack ttl 64
56017/tcp open  unknown syn-ack ttl 64
MAC Address: 3E:BB:55:58:51:7F (Unknown)

Read data files from: /usr/share/nmap
Nmap done: 1 IP address (1 host up) scanned in 0.20 seconds
           Raw packets sent: 3 (116B) | Rcvd: 3 (116B)

[~] Starting Script(s)
[>] Script to be run Some("nmap -vvv -p {{port}} {{ip}}")

[~] Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:47 UTC
Initiating ARP Ping Scan at 22:47
Scanning 10.10.30.15 [1 port]
Completed ARP Ping Scan at 22:47, 0.04s elapsed (1 total hosts)
Initiating Parallel DNS resolution of 1 host. at 22:47
Completed Parallel DNS resolution of 1 host. at 22:47, 0.00s elapsed
DNS resolution of 1 IPs took 0.00s. Mode: Async [#: 1, OK: 1, NX: 0, DR: 0, SF: 0, TR: 1, CN: 0]
Initiating SYN Stealth Scan at 22:47
Scanning samba-server.projeto_final_opcao_1_infra_net (10.10.30.15) [2 ports]
Discovered open port 139/tcp on 10.10.30.15
Discovered open port 445/tcp on 10.10.30.15
Completed SYN Stealth Scan at 22:47, 0.02s elapsed (2 total ports)
Nmap scan report for samba-server.projeto_final_opcao_1_infra_net (10.10.30.15)
Host is up, received arp-response (0.000071s latency).
Scanned at 2025-07-24 22:47:53 UTC for 0s

PORT    STATE SERVICE      REASON
139/tcp open  netbios-ssn  syn-ack ttl 64
445/tcp open  microsoft-ds syn-ack ttl 64
MAC Address: 66:E6:84:B2:5C:6E (Unknown)

Read data files from: /usr/share/nmap
Nmap done: 1 IP address (1 host up) scanned in 0.15 seconds
           Raw packets sent: 3 (116B) | Rcvd: 3 (116B)

[~] Starting Script(s)
[>] Script to be run Some("nmap -vvv -p {{port}} {{ip}}")

[~] Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:47 UTC
Initiating ARP Ping Scan at 22:47
Scanning 10.10.30.17 [1 port]
Completed ARP Ping Scan at 22:47, 0.04s elapsed (1 total hosts)
Initiating Parallel DNS resolution of 1 host. at 22:47
Completed Parallel DNS resolution of 1 host. at 22:47, 0.00s elapsed
DNS resolution of 1 IPs took 0.00s. Mode: Async [#: 1, OK: 1, NX: 0, DR: 0, SF: 0, TR: 1, CN: 0]
Initiating SYN Stealth Scan at 22:47
Scanning openldap.projeto_final_opcao_1_infra_net (10.10.30.17) [2 ports]
Discovered open port 389/tcp on 10.10.30.17
Discovered open port 636/tcp on 10.10.30.17
Completed SYN Stealth Scan at 22:47, 0.02s elapsed (2 total ports)
Nmap scan report for openldap.projeto_final_opcao_1_infra_net (10.10.30.17)
Host is up, received arp-response (0.000051s latency).
Scanned at 2025-07-24 22:47:53 UTC for 0s

PORT    STATE SERVICE REASON
389/tcp open  ldap    syn-ack ttl 64
636/tcp open  ldapssl syn-ack ttl 64
MAC Address: 46:0C:9A:6D:0F:94 (Unknown)

Read data files from: /usr/share/nmap
Nmap done: 1 IP address (1 host up) scanned in 0.15 seconds
           Raw packets sent: 3 (116B) | Rcvd: 3 (116B)

[~] Starting Script(s)
[>] Script to be run Some("nmap -vvv -p {{port}} {{ip}}")

[~] Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:47 UTC
Initiating ARP Ping Scan at 22:47
Scanning 10.10.30.11 [1 port]
Completed ARP Ping Scan at 22:47, 0.04s elapsed (1 total hosts)
Initiating Parallel DNS resolution of 1 host. at 22:47
Completed Parallel DNS resolution of 1 host. at 22:47, 0.00s elapsed
DNS resolution of 1 IPs took 0.00s. Mode: Async [#: 1, OK: 1, NX: 0, DR: 0, SF: 0, TR: 1, CN: 0]
Initiating SYN Stealth Scan at 22:47
Scanning mysql-server.projeto_final_opcao_1_infra_net (10.10.30.11) [2 ports]
Discovered open port 3306/tcp on 10.10.30.11
Discovered open port 33060/tcp on 10.10.30.11
Completed SYN Stealth Scan at 22:47, 0.04s elapsed (2 total ports)
Nmap scan report for mysql-server.projeto_final_opcao_1_infra_net (10.10.30.11)
Host is up, received arp-response (0.000078s latency).
Scanned at 2025-07-24 22:47:53 UTC for 0s

PORT      STATE SERVICE REASON
3306/tcp  open  mysql   syn-ack ttl 64
33060/tcp open  mysqlx  syn-ack ttl 64
MAC Address: 82:55:B7:C5:9D:AA (Unknown)

Read data files from: /usr/share/nmap
Nmap done: 1 IP address (1 host up) scanned in 0.18 seconds
           Raw packets sent: 3 (116B) | Rcvd: 3 (116B)

[~] Starting Script(s)
[>] Script to be run Some("nmap -vvv -p {{port}} {{ip}}")

[~] Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:47 UTC
Initiating SYN Stealth Scan at 22:47
Scanning 88b92ff8a75b (10.10.30.2) [3 ports]
Completed SYN Stealth Scan at 22:47, 0.02s elapsed (3 total ports)
Nmap scan report for 88b92ff8a75b (10.10.30.2)
Host is up, received localhost-response (0.000032s latency).
Scanned at 2025-07-24 22:47:53 UTC for 0s

PORT      STATE  SERVICE REASON
50050/tcp closed unknown reset ttl 64
60036/tcp closed unknown reset ttl 64
60588/tcp closed unknown reset ttl 64

Read data files from: /usr/share/nmap
Nmap done: 1 IP address (1 host up) scanned in 0.08 seconds
           Raw packets sent: 3 (132B) | Rcvd: 6 (252B)


┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# rustscan -a 'infra_net_ips.txt' | grep Open > infra_net_ips_ports.txt

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# rustscan -a 'guest_net_ips.txt'
.----. .-. .-. .----..---.  .----. .---.   .--.  .-. .-.
| {}  }| { } |{ {__ {_   _}{ {__  /  ___} / {} \ |  `| |
| .-. \| {_} |.-._} } | |  .-._} }\     }/  /\  \| |\  |
`-' `-'`-----'`----'  `-'  `----'  `---' `-'  `-'`-' `-'
The Modern Day Port Scanner.
________________________________________
: https://discord.gg/GFrQsGy           :
: https://github.com/RustScan/RustScan :
 --------------------------------------
Real hackers hack time ⌛

[~] The config file is expected to be at "/root/.rustscan.toml"
[~] File limit higher than batch size. Can increase speed by increasing batch size '-b 1048476'.
Open 10.10.50.1:111
Open 10.10.50.6:34304
Open 10.10.50.1:56017
[!] Looks like I didn't find any open ports for 10.10.50.2. This is usually caused by a high batch size.

*I used 4500 batch size, consider lowering it with 'rustscan -b <batch_size> <ip address>' or a comfortable number for your system.

 Alternatively, increase the timeout if your ping is high. Rustscan -t 2000 for 2000 milliseconds (2s) timeout.

[!] Looks like I didn't find any open ports for 10.10.50.3. This is usually caused by a high batch size.

*I used 4500 batch size, consider lowering it with 'rustscan -b <batch_size> <ip address>' or a comfortable number for your system.

 Alternatively, increase the timeout if your ping is high. Rustscan -t 2000 for 2000 milliseconds (2s) timeout.

[!] Looks like I didn't find any open ports for 10.10.50.4. This is usually caused by a high batch size.

*I used 4500 batch size, consider lowering it with 'rustscan -b <batch_size> <ip address>' or a comfortable number for your system.

 Alternatively, increase the timeout if your ping is high. Rustscan -t 2000 for 2000 milliseconds (2s) timeout.

[!] Looks like I didn't find any open ports for 10.10.50.5. This is usually caused by a high batch size.

*I used 4500 batch size, consider lowering it with 'rustscan -b <batch_size> <ip address>' or a comfortable number for your system.

 Alternatively, increase the timeout if your ping is high. Rustscan -t 2000 for 2000 milliseconds (2s) timeout.

[~] Starting Script(s)
[>] Script to be run Some("nmap -vvv -p {{port}} {{ip}}")

[~] Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:48 UTC
Initiating ARP Ping Scan at 22:48
Scanning 10.10.50.1 [1 port]
Completed ARP Ping Scan at 22:48, 0.05s elapsed (1 total hosts)
Initiating Parallel DNS resolution of 1 host. at 22:48
Completed Parallel DNS resolution of 1 host. at 22:48, 0.03s elapsed
DNS resolution of 1 IPs took 0.03s. Mode: Async [#: 1, OK: 0, NX: 1, DR: 0, SF: 0, TR: 1, CN: 0]
Initiating SYN Stealth Scan at 22:48
Scanning 10.10.50.1 [2 ports]
Discovered open port 111/tcp on 10.10.50.1
Discovered open port 56017/tcp on 10.10.50.1
Completed SYN Stealth Scan at 22:48, 0.02s elapsed (2 total ports)
Nmap scan report for 10.10.50.1
Host is up, received arp-response (0.000057s latency).
Scanned at 2025-07-24 22:48:48 UTC for 0s

PORT      STATE SERVICE REASON
111/tcp   open  rpcbind syn-ack ttl 64
56017/tcp open  unknown syn-ack ttl 64
MAC Address: 0A:6F:5A:22:45:0D (Unknown)

Read data files from: /usr/share/nmap
Nmap done: 1 IP address (1 host up) scanned in 0.17 seconds
           Raw packets sent: 3 (116B) | Rcvd: 3 (116B)

[~] Starting Script(s)
[>] Script to be run Some("nmap -vvv -p {{port}} {{ip}}")

[~] Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:48 UTC
Initiating SYN Stealth Scan at 22:48
Scanning 88b92ff8a75b (10.10.50.6) [1 port]
Completed SYN Stealth Scan at 22:48, 0.03s elapsed (1 total ports)
Nmap scan report for 88b92ff8a75b (10.10.50.6)
Host is up, received localhost-response (0.000051s latency).
Scanned at 2025-07-24 22:48:48 UTC for 0s

PORT      STATE  SERVICE REASON
34304/tcp closed unknown reset ttl 64

Read data files from: /usr/share/nmap
Nmap done: 1 IP address (1 host up) scanned in 0.08 seconds
           Raw packets sent: 1 (44B) | Rcvd: 2 (84B)


┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# rustscan -a 'guest_net_ips.txt' | grep Open > guest_net_ips_ports.txt

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -p 21 --script ftp-anon 10.10.30.10
Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:50 UTC
Nmap scan report for ftp-server.projeto_final_opcao_1_infra_net (10.10.30.10)
Host is up (0.00018s latency).

PORT   STATE SERVICE
21/tcp open  ftp
MAC Address: 22:67:97:20:F9:BC (Unknown)

Nmap done: 1 IP address (1 host up) scanned in 0.24 seconds

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -p 21 --script ftp-anon 10.10.30.10 > infra_net_servico_ftp-anon.txt

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -p 3306 --script mysql-info 10.10.30.11
Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:50 UTC
Nmap scan report for mysql-server.projeto_final_opcao_1_infra_net (10.10.30.11)
Host is up (0.00015s latency).

PORT     STATE SERVICE
3306/tcp open  mysql
| mysql-info:
|   Protocol: 10
|   Version: 8.0.42
|   Thread ID: 12
|   Capabilities flags: 65535
|   Some Capabilities: SwitchToSSLAfterHandshake, Support41Auth, LongPassword, ConnectWithDatabase, Speaks41ProtocolOld, DontAllowDatabaseTableColumn, IgnoreSpaceBeforeParenthesis, SupportsCompression, InteractiveClient, IgnoreSigpipes, Speaks41ProtocolNew, SupportsTransactions, FoundRows, SupportsLoadDataLocal, ODBCClient, LongColumnFlag, SupportsMultipleStatments, SupportsMultipleResults, SupportsAuthPlugins
|   Status: Autocommit
|   Salt: \x1EcEj?\x01nObd+r\x01\x01\R\x1E@\x0D^
|_  Auth Plugin Name: caching_sha2_password
MAC Address: 82:55:B7:C5:9D:AA (Unknown)

Nmap done: 1 IP address (1 host up) scanned in 0.19 seconds

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -p 3306 --script mysql-info 10.10.30.11 > infra_net_servico_mysql-info.txt

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -p 389 --script ldap-rootdse 10.10.30.17
Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:51 UTC
Nmap scan report for openldap.projeto_final_opcao_1_infra_net (10.10.30.17)
Host is up (0.000070s latency).

PORT    STATE SERVICE
389/tcp open  ldap
| ldap-rootdse:
| LDAP Results
|   <ROOT>
|       namingContexts: dc=example,dc=org
|       supportedControl: 2.16.840.1.113730.3.4.18
|       supportedControl: 2.16.840.1.113730.3.4.2
|       supportedControl: 1.3.6.1.4.1.4203.1.10.1
|       supportedControl: 1.3.6.1.1.22
|       supportedControl: 1.2.840.113556.1.4.319
|       supportedControl: 1.2.826.0.1.3344810.2.3
|       supportedControl: 1.3.6.1.1.13.2
|       supportedControl: 1.3.6.1.1.13.1
|       supportedControl: 1.3.6.1.1.12
|       supportedExtension: 1.3.6.1.4.1.1466.20037
|       supportedExtension: 1.3.6.1.4.1.4203.1.11.1
|       supportedExtension: 1.3.6.1.4.1.4203.1.11.3
|       supportedExtension: 1.3.6.1.1.8
|       supportedLDAPVersion: 3
|       supportedSASLMechanisms: SCRAM-SHA-1
|       supportedSASLMechanisms: SCRAM-SHA-256
|       supportedSASLMechanisms: GS2-IAKERB
|       supportedSASLMechanisms: GS2-KRB5
|       supportedSASLMechanisms: GSSAPI
|       supportedSASLMechanisms: GSS-SPNEGO
|       supportedSASLMechanisms: DIGEST-MD5
|       supportedSASLMechanisms: OTP
|       supportedSASLMechanisms: NTLM
|       supportedSASLMechanisms: CRAM-MD5
|_      subschemaSubentry: cn=Subschema
MAC Address: 46:0C:9A:6D:0F:94 (Unknown)

Nmap done: 1 IP address (1 host up) scanned in 0.20 seconds

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -p 389 --script ldap-rootdse 10.10.30.17 > infra_net_servico_ldap-rootdse.txt

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -p 445 --script smb-os-discovery,smb-enum-shares 10.10.30.15
Starting Nmap 7.95 ( https://nmap.org ) at 2025-07-24 22:51 UTC
Nmap scan report for samba-server.projeto_final_opcao_1_infra_net (10.10.30.15)
Host is up (0.000084s latency).

PORT    STATE SERVICE
445/tcp open  microsoft-ds
MAC Address: 66:E6:84:B2:5C:6E (Unknown)

Nmap done: 1 IP address (1 host up) scanned in 0.24 seconds

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# nmap -p 445 --script smb-os-discovery,smb-enum-shares 10.10.30.15 > infra_net_servico_smb.txt

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# curl -I http://10.10.30.117
HTTP/1.1 200 OK
Server: nginx
Date: Thu, 24 Jul 2025 22:52:04 GMT
Content-Type: text/html; charset=UTF-8
Connection: keep-alive
Keep-Alive: timeout=20
X-Powered-By: PHP/7.3.14
Set-Cookie: PHPSESSID=41129e569a3c65d27a5906d8660a949a; HttpOnly
Expires: Thu, 19 Nov 1981 08:52:00 GMT
Cache-Control: no-store, no-cache, must-revalidate
Pragma: no-cache
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Frame-Options: SAMEORIGIN


┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# curl -I http://10.10.30.117 > infra_net_servico_webserver.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# curl http://10.10.30.117
<!DOCTYPE html>
<html>
        <head>
                <meta http-equiv="X-UA-Compatible" content="IE=Edge"/>
                <meta charset="utf-8" />
                <meta name="viewport" content="width=device-width, initial-scale=1">
                <meta name="Author" content="Zabbix SIA" />
                <title>Zabbix docker: Zabbix</title>
                <link rel="icon" href="favicon.ico">
                <link rel="apple-touch-icon-precomposed" sizes="76x76" href="assets/img/apple-touch-icon-76x76-precomposed.png">
                <link rel="apple-touch-icon-precomposed" sizes="120x120" href="assets/img/apple-touch-icon-120x120-precomposed.png">
                <link rel="apple-touch-icon-precomposed" sizes="152x152" href="assets/img/apple-touch-icon-152x152-precomposed.png">
                <link rel="apple-touch-icon-precomposed" sizes="180x180" href="assets/img/apple-touch-icon-180x180-precomposed.png">
                <link rel="icon" sizes="192x192" href="assets/img/touch-icon-192x192.png">
                <meta name="csrf-token" content=""/>
                <meta name="msapplication-TileImage" content="assets/img/ms-tile-144x144.png">
                <meta name="msapplication-TileColor" content="#d40000">
                <meta name="msapplication-config" content="none"/>
<link rel="stylesheet" type="text/css" href="assets/styles/blue-theme.css" />
<style type="text/css">.na-bg, .na-bg input[type="radio"]:checked + label, .na-bg:before, .flh-na-bg, .status-na-bg { background-color: #97AAB3 }
.info-bg, .info-bg input[type="radio"]:checked + label, .info-bg:before, .flh-info-bg, .status-info-bg { background-color: #7499FF }
.warning-bg, .warning-bg input[type="radio"]:checked + label, .warning-bg:before, .flh-warning-bg, .status-warning-bg { background-color: #FFC859 }
.average-bg, .average-bg input[type="radio"]:checked + label, .average-bg:before, .flh-average-bg, .status-average-bg { background-color: #FFA059 }
.high-bg, .high-bg input[type="radio"]:checked + label, .high-bg:before, .flh-high-bg, .status-high-bg { background-color: #E97659 }
.disaster-bg, .disaster-bg input[type="radio"]:checked + label, .disaster-bg:before, .flh-disaster-bg, .status-disaster-bg { background-color: #E45959 }

</style><script>var PHP_TZ_OFFSET = 10800,PHP_ZBX_FULL_DATE_TIME = "Y-m-d H:i:s";</script><script src="js/browsers.js"></script>
</head>
<body lang="en">
<output class="msg-global-footer msg-warning" id="msg-global-footer"></output>
<main><div class="server-name">Zabbix docker</div><div class="signin-container"><div class="signin-logo"></div><form method="post" action="index.php" accept-charset="utf-8" aria-label="Sign in"><ul><li><label for="name">Username</label><input type="text" id="name" name="name" value="" maxlength="255" autofocus="autofocus"></li><li><label for="password">Password</label><input type="password" id="password" name="password" value="" maxlength="255"></li><li><input type="checkbox" id="autologin" name="autologin" value="1" class="checkbox-radio" checked="checked"><label for="autologin"><span></span>Remember me for 30 days</label></li><li><button type="submit" id="enter" name="enter" value="Sign in">Sign in</button></li></ul></form></div><div class="signin-links"><a target="_blank" class="grey link-alt" href="https://www.zabbix.com/documentation/4.4/">Help</a>&nbsp;&nbsp;•&nbsp;&nbsp;<a target="_blank" class="grey link-alt" href="https://www.zabbix.com/support">Support</a></div></main><footer role="contentinfo">&copy; 2001&ndash;2020, <a class="grey link-alt" target="_blank" href="https://www.zabbix.com/">Zabbix SIA</a></footer></body>      

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# curl http://10.10.30.117 > infra_net_servico_zabbix.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  3412    0  3412    0     0  67362      0 --:--:-- --:--:-- --:--:-- 68240

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# arp -a
mysql-server.projeto_final_opcao_1_infra_net (10.10.30.11) at 82:55:b7:c5:9d:aa [ether] on eth2
notebook-carlos.projeto_final_opcao_1_guest_net (10.10.50.3) at e6:9b:8f:73:8f:22 [ether] on eth1
WS_001.projeto_final_opcao_1_corp_net (10.10.10.10) at fa:6a:cf:e0:77:b0 [ether] on eth0
? (10.10.30.1) at 3e:bb:55:58:51:7f [ether] on eth2
ftp-server.projeto_final_opcao_1_infra_net (10.10.30.10) at 22:67:97:20:f9:bc [ether] on eth2
laptop-vastro.projeto_final_opcao_1_guest_net (10.10.50.2) at 12:bf:70:62:37:8e [ether] on eth1
WS_003.projeto_final_opcao_1_corp_net (10.10.10.127) at ca:b9:1d:05:f5:1a [ether] on eth0
? (10.10.50.1) at 0a:6f:5a:22:45:0d [ether] on eth1
zabbix-server.projeto_final_opcao_1_infra_net (10.10.30.117) at be:99:eb:d1:c5:e3 [ether] on eth2
? (10.10.10.1) at 4e:fd:3d:00:b3:db [ether] on eth0
WS_004.projeto_final_opcao_1_corp_net (10.10.10.222) at 3e:35:3d:36:7f:d5 [ether] on eth0
samba-server.projeto_final_opcao_1_infra_net (10.10.30.15) at 66:e6:84:b2:5c:6e [ether] on eth2
legacy-server.projeto_final_opcao_1_infra_net (10.10.30.227) at a6:5e:5c:56:25:07 [ether] on eth2
macbook-aline.projeto_final_opcao_1_guest_net (10.10.50.5) at 42:67:44:09:00:7c [ether] on eth1
openldap.projeto_final_opcao_1_infra_net (10.10.30.17) at 46:0c:9a:6d:0f:94 [ether] on eth2
laptop-luiz.projeto_final_opcao_1_guest_net (10.10.50.4) at 6a:47:b1:e9:70:a5 [ether] on eth1
WS_002.projeto_final_opcao_1_corp_net (10.10.10.101) at 7e:9b:70:cf:a9:32 [ether] on eth0

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# arp -a > recon_ip_maps.txt

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# cat /etc/resolv.conf
# Generated by Docker Engine.
# This file can be edited; Docker Engine will not make further changes once it
# has been modified.

nameserver 127.0.0.11
options ndots:0

# Based on host file: '/etc/resolv.conf' (internal resolver)
# ExtServers: [host(192.168.65.7)]
# Overrides: []
# Option ndots from: internal

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# mkdir -p /home/analyst/recon/{corp_net,guest_net,infra_net}

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# mv *corp*.txt /home/analyst/recon/corp_net/

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# mv *guest*.txt /home/analyst/recon/guest_net/

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# mv *infra*.txt /home/analyst/recon/infra_net/

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# mv *recon*.txt /home/analyst/recon/

┌──(root㉿88b92ff8a75b)-[/home/analyst]
└─# exit
exit
PS C:\Users\Arestides\cursocyber\formacao-cybersec\formacao-cybersec\modulo1-fundamentos\projeto_final_opcao_1> docker cp analyst:/home/analyst/recon ./recon-backup
Successfully copied 26.1kB to C:\Users\Arestides\cursocyber\formacao-cybersec\formacao-cybersec\modulo1-fundamentos\projeto_final_opcao_1\recon-backup
PS C:\Users\Arestides\cursocyber\formacao-cybersec\formacao-cybersec\modulo1-fundamentos\projeto_final_opcao_1>