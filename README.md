<h1 align="center">
    POC Embedded Superset
</h1>

<p align="center">
 <a href="#sobre-o-projeto">Sobre o Projeto</a> •
 <a href="#tecnologias">Tecnologias</a> •
 <a href="#configurações-necessárias">Configurações necessárias</a> •
 <a href="#autor">Autor</a>
</p>

## Sobre o projeto

O projeto tem como objetivo validar a utilização do Superset como visualizador de dados através de dashboards.

O repositório está separado em duas pastas principais:

- superset_bkp (Fonte do superset)
- doc_prod_superset (Fonte de teste embedded)

---

## Tecnologias

Abaixo as tecnologias utilizadas para construção da aplicação

- [Superset](https://superset.apache.org)
- [Python](https://www.python.org)

---

### **Clone do projeto**

```bash
# Execute o comando git clone para realizar o clone do repositório
$ git clone https://github.com/carlosnunesjr/poc_superset.git
# Entre na pasta do repositório clonado
$ cd poc_superset
```

### **Iniciando o projeto**

```bash
# Entre na pasta superset_bkp
$ cd superset_bkp
# Os parâmetros configurados do Superset para esse projeto estão na sessão #Custom
# localizados no arquivo: /docker/pythonpath_dev/superset_config.py
# Execute o comando:
docker-compose -f docker-compose-non-dev.yml up

# Em outro terminal acessar a pasta doc_prod_superset
$ cd doc_prod_superset
# Abra o vscode
# Instale o plugin Live Server
# Clique com o botão direito em cima do arquivo teste.html e abrir com o Live Server

```

---

## Autor

Feito por Carlos Nunes
