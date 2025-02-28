# Sistema de Gestão de Clínica - PHP & MySQL
Gestão Fácil de Clínicas 

## Descrição
Este é um sistema web desenvolvido em PHP e MySQL para a gestão de clínicas médicas. O sistema permite o cadastro de pacientes, agendamento de consultas, gerenciamento de médicos e usuários administrativos, além de relatórios e controle de prontuários eletrônicos.

## Funcionalidades
- Cadastro e gerenciamento de pacientes
- Agendamento e gerenciamento de consultas
- Cadastro de médicos e especialidades
- Prontuário eletrônico
- Geração de relatórios
- Controle de usuários e permissões

## Tecnologias Utilizadas
- PHP 7.4
- MySQL 5.7+
- Bootstrap 5 (para interface responsiva)
- jQuery (para interações dinâmicas)

## Requisitos
- Servidor Apache com suporte a PHP
- MySQL instalado e configurado
- Composer instalado

## Instalação
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/gestao-clinica.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd gestao-clinica
   ```
3. Configure o banco de dados:
   - Crie um banco de dados no MySQL
   - Importe o arquivo `database.sql` localizado na pasta `database/`
   - Configure as credenciais no arquivo `config/database.php`

5. Acesse o sistema no navegador:
   ```
   http://localhost/gestao-de-clinica
   ```
## Contribuição
Se deseja contribuir com o projeto, siga estes passos:
1. Fork o repositório
2. Crie uma branch para sua feature (`git checkout -b minha-feature`)
3. Commit suas alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Faça o push para a branch (`git push origin minha-feature`)
5. Abra um Pull Request

## Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
