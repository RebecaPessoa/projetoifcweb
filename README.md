# Visualizar arquivo .ifc no browser com IFCjs
Projeto webapp open BIM para carregar e visualizar arquivos [ifc](https://en.wikipedia.org/wiki/Industry_Foundation_Classes)

### Deploy no github pages: [Visitar o site](https://rebecapessoa.github.io/projetoifcweb/)

#### Landing page:
![landingpage](https://user-images.githubusercontent.com/4651221/120132669-28014780-c1a1-11eb-852f-61b6e2768509.gif)


## O que é IFCjs:

O [IFCjs](https://github.com/agviegas/web-ifc-viewer) é uma biblioteca Javascript open source que facilita a leitura e edição de arquivos ifc, permitindo desenvolvedores de aplicações de arquitetura e engenharia a trabalhar com estes arquivos com foco em diversas funcionalidades.
IFCjs pode gerar:

* Geometria: gera cenas 3D pois é  compatível com bibliotecas como Three.js ou Babylon.js. Assim pode-se criar ferramentas que iteragem com os modelos 3d utilizando a API "high-level" dessas bibliotecas.

* Dados: acesso "high-level" a todas as propriedades associadas às geometrias. Isto significa fácil acesso à informações dos componentes da edificação, seus materiais, características (estruturais, térmicas...), etc.


 ***Tecnologias Utilizadas***

* [NodeJS](https://nodejs.org/en/)
* [IFCjs](https://agviegas.github.io/ifcjs-docs/#/)
* [Threejs](https://threejs.org/)

### Funcionalidade: 

#### Upload temporário de arquivo:
![upload](https://user-images.githubusercontent.com/4651221/120133503-b3c7a380-c1a2-11eb-9f6c-39ca9377bf99.gif)

### Próximas funcionalidades:

* selecionar propriedades
* charts de informações 
* persistir modelos.ifc em banco de dados

---


### Licença

<img alt="APM" src="https://img.shields.io/apm/l/vim-mode">
