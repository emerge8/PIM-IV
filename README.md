# Cadastro de pacientes com COVID-19
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/emerge8/PIM-IV/blob/main/LICENSE) 

# Sobre o projeto


O objetivo do projeto será desenvolver um sistema em C (utilizando o codeblocks – disponível de forma gratuita no seguinte link: http://www.codeblocks.org/) que será utilizado pelos hospitais para cadastrar os pacientes que forem diagnosticados com covid-19 e carecem de um acompanhamento e monitoramento.

Ao receber o diagnóstico positivo os profissionais da saúde devem realizar o login no sistema (informando o usuário e a senha) e informar os dados pessoais do paciente, como:

Nome;
CPF;
Telefone;
Endereço (Rua, Número, Bairro, Cidade, Estado e CEP);
Data de Nascimento;
E-mail;
data do diagnóstico;
informar alguma comorbidade do paciente (diabetes, obesidade, hipertensão, tuberculose, outros;
que serão salvos em um Arquivo (a principal vantagem de um arquivo é que as informações armazenadas podem ser consultadas a qualquer momento).

Após a realização do cadastro, o sistema deverá calcular a idade e verificar se o paciente possui alguma comorbidade e se pertence ao grupo de risco (maiores de 65 anos).
Caso o paciente pertença ao grupo de risco o sistema deverá salvar em um arquivo de texto o CEP e a idade do paciente para que essa informação possa ser enviada para a central da Secretaria da Saúde da cidade.

# Tecnologias utilizadas
## C

# Como executar o projeto

## Há somente Backend
Pré-requisitos: 

Instale o CodeBlocks no seu sistema. Você pode acessar o site oficial da IDE em: http://www.codeblocks.org/

Caso esteja usando uma distribuição linux baseada no Ubuntu você pode instalar o CodeBlocks executando o comando abaixo:

sudo apt install codeblocks --install-suggests

```bash
# clonar repositório
git clone https://github.com/emerge8/PIM-IV

# executar o projeto
 No seu gerenciador de arquivos, navegue até o diretório PIM-IV e abra o arquivo 'pim.cbp' utilizando o CodeBlocks.
 O projeto será aberto.Após abrir o projeto, navegue até a barra superior e selecione build and run.
 Feito isso, basta colocar o usuário e a senha.Sendo que o usuário é **Emerson** e a senha é: *1234*
```

# Autor

Emerson Gonçalves Luiz

https://www.linkedin.com/in/emerson-luiz-e8t18


