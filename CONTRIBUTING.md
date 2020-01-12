# Guia para Contribuir

Nós amamos pull requests de todos. By participating in this project, you're encouraged to submit [pull requests](https://github.com/alagoasdev/empresas-alagoanas/pulls), [propose features and discuss issues](https://github.com/alagoasdev/empresas-alagoanas/issues). When in doubt, ask a question using issues.

## Abra uma issue

Se a empresa que você trabalha/quer adicionar ainda não está presente, [abra uma issue](https://github.com/alagoasdev/empresas-alagoanas/issues) para sinalizar para todos e evitar pull requests duplicados.

## Fork o projeto

Faça um fork do [projeto no Github](https://github.com/alagoasdev/empresas-alagoanas) e faça check out da sua cópia.

```
git clone https://github.com/<your github handle>/empresas-alagoanas.git
cd empresas-alagoanas
git remote add upstream https://github.com/alagoasdev/empresas-alagoanas.git
```

## Crie um branch

Antes de tudo, tenha certeza que seu repositório está atualizado com o este repositório. Em seguida, crie um branch.

```
git checkout master
git pull upstream master
git checkout -b my-feature-branch
```

## Adicione a empresa

Adicione a empresa no arquivo que mais faz sentido para o ramo de atuação da empresa. No arquivo relevante<sup>1</sup>, utilize o exemplo abaixo para manter o padrão. Tente adicionar em ordem alfabética, para não favorecer nenhuma empresa e facilitar a busca aos leitores.

<sup>1</sup> Caso não exista um arquivo relevante ainda, crie um arquivo com a extensão `.md` e mantenha o padrão dos arquivos já existentes. Para mais detalhes, consulte o [guia do markdown](https://daringfireball.net/projects/markdown/) (em inglês)

### Exemplo

```
### Nome da empresa
* Site: https://www.example.com
* Vagas: https://www.example.com/open-positions
* Tamanho: 15 funcionários
* Tecnologias: Ruby, Go, PHP, ASP, Javascript, HTML, CSS
* Observações: Quaisquer informações adicionais
```

## Faça commit das alterações

Tenha certeza que seu git possui seus dados corretos:

```
git config --global user.name "Your Name"
git config --global user.email "contributor@example.com"
```

Adicione os arquivos alterados e escreva uma mensagem de commit que reflete o que está sendo alterado.

```
git add .
git commit -m "<YOUR GREAT COMMIT MESSAGE>"
```

## Push

Envie o codigo pro seu fork.

```
git push origin my-feature-branch
```

## Crie um Pull Request

Vá para https://github.com/<your github handle>/empresas-alagoanas e selecione seu branch. Clique no botão 'Pull Request' e preencha o formulário. Os Pull Requests podem levar uns dias para ser avaliados. Fique de olho para corrigir quaisquer comentários solicitados pelos mantenedores.

## Obrigado

Assim que seu Pull Request for aprovado, será feito o merge ao código principal e todos poderão ver.
