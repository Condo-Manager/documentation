## Projeto Integrador 4° Termo - Redes e Infra

### CondoManager

 ![Lgerogo CondoMana](https://avatars.githubusercontent.com/u/178331720?s=400&u=e5f16fbf67758545c901386babac5e83f938e188&v=4)

Alunos: 
- [Daniel Lucas](https://github.com/DanielLucas2305)
- [Erick Cirico](https://github.com/erickom8)
- [Iago Kater](https://github.com/iagokater)
- Vinicius La Serra 

Tema do Projeto:
O CondoManager é um sistema moderno e eficiente voltado para a gestão de condomínios, com foco em facilitar a administração e melhorar a comunicação entre moradores e equipe administrativa. O projeto visa implementar funcionalidades essenciais para o dia a dia de um condomínio, concentrando-se em três pilares principais:

* Reserva de Espaços Comuns:  
    O sistema permitirá que os moradores realizem reservas de espaços comuns, como churrasqueiras, salões de festas, e quadras esportivas. Com uma interface simples e intuitiva, os moradores poderão visualizar a disponibilidade desses espaços, efetuar reservas e receber confirmações, garantindo uma gestão organizada e transparente desses recursos.

* Notificações e Avisos:  
    O CondoManager oferecerá uma plataforma centralizada para que a administração possa comunicar informações importantes aos moradores. Através de notificações diretas, os residentes serão informados sobre eventos, manutenções, e outras atualizações relevantes, assegurando que todos estejam sempre atualizados sobre o que acontece no condomínio.

* Gestão de Encomendas:  
    A gestão de encomendas será otimizada com uma ferramenta que permitirá ao porteiro registrar a chegada de pacotes, anexando fotos e detalhes da entrega. Os moradores serão notificados imediatamente sobre a chegada de suas encomendas, podendo visualizar as informações diretamente no sistema, o que trará mais segurança e controle para esse processo.

Essas funcionalidades visam transformar a experiência de vida em condomínios, proporcionando uma administração mais eficiente e uma comunicação clara e direta entre todos os envolvidos.

Principais tecnologias:
```
-Ionic
-Node
-MySql
-Minio

```

## Frontend

O repositório com o frontend do projeto pode ser acessado em **[Frontend - CondoManager](https://github.com/Condo-Manager/Frontend.git)**  
Para rodar o projeto localmente, basta clonar o repositório citado anteriormente, abrir um terminal na raiz desse projeto,
e logo em seguida digite no o comando abaixo no seu terminal para atualizar todas as dependencias:

```
npm i
```
Em seguida digite uma das linhas de comando abaixo para abrir no seu navegador:

```
ionic s -o
ng s -o
```
#### Live server no celular

**Você também pode rodar o projeto no seu aparelho celular !!!** Para isso basta ter o Android Studio instalado na sua máquina, ativar o modo de desenvolvedor do seu Android e emparelhar no Android Studio via cabo ou wi-fi.
Após isso, digite os seguintes comandos no terminal raiz do projeto:

```
ionic cap build android
```
```
ionic cap run android -l --external
```
E após isso escolher a rede ethernet ou wi-fi nas opções do terminal  
  
## Backend

O repositório com o backend do projeto(API) pode ser acessado em **[Backend - CondoManager](https://github.com/Condo-Manager/Backend.git)**  
