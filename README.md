# Funcionalidades
Leitura de todas as pastas em um servidor de arquivos(o exemplo está somente no primeiro nível mas pode ser também executado de forma recursiva com parametro -recurse e controlado profundidade da recursividade com o -depth <int>).  
Consulta ao Active Directory para obter as permissões de cada usuário em cada pasta.  
Armazenamento dos resultados em um arquivo JSON para fácil análise e compartilhamento.  
Interface interativa usando JSONGrid para visualizar e explorar os resultados.  

# Pré-requisitos  
->PowerShell  
->Módulo Active Directory para PowerShell (ActiveDirectory)

# Instalação e Uso
Clone ou faça o download do repositório para o seu computador.  
Execute o script PowerShell fornecido (Folderpermissions.ps1) para iniciar a auditoria das permissões de pasta.  
Após a conclusão da auditoria, um arquivo JSON será gerado com os resultados.  
Abra o arquivo HTML fornecido (index.html) em um navegador da web para visualizar os resultados na interface interativa JSONGrid.  
