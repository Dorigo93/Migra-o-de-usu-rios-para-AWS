# Migrar usuários para AWS - PT-BT
Migração de usuários para AWS

# Projeto Hands-on: Implementação de Usuários na AWS

## Descrição
Este projeto tem como objetivo demonstrar a criação e gerenciamento de usuários na AWS utilizando a AWS CLI. O foco é aplicar melhores práticas de segurança, como a habilitação de MFA e a aplicação de políticas de senha.

## Arquivos Necessários
- [EquipeTIABCEmpresa.xlsx](attachment:75a7255a-fb70-4e09-823b-58e417f3c7fd:EquipeTIABCEmpresa.xlsx)
- [usuarios2.csv](attachment:ad198346-11f4-4c5d-a172-f85a0605238a:usuarios2.csv)
- [aws-iam-cria-usuario.sh](https://tcb-bootcamps.s3.amazonaws.com/bootcamp-aws/pt/module2/aws-iam-cria-usuario.sh)

## Passos para Implementação

### Parte 1: Criação de Usuários
1. Prepare a planilha `EquipeTIABCEmpresa.xlsx` e salve como `usuarios2.csv`.
2. Acesse o AWS Cloud Shell e instale `dos2unix`.
3. Baixe o script de criação de usuários e torne-o executável.
4. Faça upload do arquivo `usuarios2.csv` e execute o script.
5. Valide a criação dos usuários na Console AWS.

### Parte 2: Melhores Práticas de Segurança
1. Habilite MFA para o usuário root e para os usuários criados.
2. Anexe a política `EnforceMFAPolicy` aos grupos de usuários.
3. Aplique uma política

----------------------------------------------------------------------------------------------------------------------------

# Migrate Users to AWS - EN-US
User Migration to AWS

# Hands-on Project: Implementing Users in AWS

## Description
This project aims to demonstrate the creation and management of users in AWS using the AWS CLI. The focus is on applying best security practices, such as enabling MFA and enforcing password policies.

## Required Files
- [EquipeTIABCEmpresa.xlsx](attachment:75a7255a-fb70-4e09-823b-58e417f3c7fd:EquipeTIABCEmpresa.xlsx)
- [usuarios2.csv](attachment:ad198346-11f4-4c5d-a172-f85a0605238a:usuarios2.csv)
- [aws-iam-cria-usuario.sh](https://tcb-bootcamps.s3.amazonaws.com/bootcamp-aws/pt/module2/aws-iam-cria-usuario.sh)

## Implementation Steps

### Part 1: User Creation
1. Prepare the `EquipeTIABCEmpresa.xlsx` spreadsheet and save it as `usuarios2.csv`.
2. Access AWS Cloud Shell and install `dos2unix`.
3. Download the user creation script and make it executable.
4. Upload the `usuarios2.csv` file and execute the script.
5. Validate the user creation in the AWS Console.

### Part 2: Security Best Practices
1. Enable MFA for the root user and the created users.
2. Attach the `EnforceMFAPolicy` policy to user groups.
3. Apply a password policy.
