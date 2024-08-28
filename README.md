## Projeto Integrador 4° Termo - Redes e Infra

### CondoManager

Alunos: Daniel Lucas, Erick Cirico, Iago Kater e Vinicius La Serra 

Tema do Projeto:
O CondoManager é um sistema moderno e eficiente voltado para a gestão de condomínios, com foco em facilitar a administração e melhorar a comunicação entre moradores e equipe administrativa. O projeto visa implementar funcionalidades essenciais para o dia a dia de um condomínio, concentrando-se em três pilares principais:

Reserva de Espaços Comuns: O sistema permitirá que os moradores realizem reservas de espaços comuns, como churrasqueiras, salões de festas, e quadras esportivas. Com uma interface simples e intuitiva, os moradores poderão visualizar a disponibilidade desses espaços, efetuar reservas e receber confirmações, garantindo uma gestão organizada e transparente desses recursos.

Notificações e Avisos: O CondoManager oferecerá uma plataforma centralizada para que a administração possa comunicar informações importantes aos moradores. Através de notificações diretas, os residentes serão informados sobre eventos, manutenções, e outras atualizações relevantes, assegurando que todos estejam sempre atualizados sobre o que acontece no condomínio.

Gestão de Encomendas: A gestão de encomendas será otimizada com uma ferramenta que permitirá ao porteiro registrar a chegada de pacotes, anexando fotos e detalhes da entrega. Os moradores serão notificados imediatamente sobre a chegada de suas encomendas, podendo visualizar as informações diretamente no sistema, o que trará mais segurança e controle para esse processo.

Essas funcionalidades visam transformar a experiência de vida em condomínios, proporcionando uma administração mais eficiente e uma comunicação clara e direta entre todos os envolvidos.

Principais tecnologias:
```
-Ionic
-Node
-MySql
-Minio

```

## Frontend

O repositório com o frontend dpo projeto pode ser acessado em **[Frontend - CondoManager](https://github.com/Condo-Manager/Frontend.git)**  
Para rodar o projeto localmente, basta clonar o repositório citado anteriormente e abrir um terminal na raiz desse projeto,
logo em seguida digite no o comando abaixo no seu terminal para atualizar todas as dependencias:

```
npm i
```
Em seguida digite uma das linhas de comando abaixo para abrir no seu navegador:

```
ionic s -o
ng s -o
```
#### Live server no celular

\_Você também pode rodar o projeto no seu aparelho celular !!!\_ Para isso basta ter o Android Studio instalado na sua máquina, ativar o modo de desenvolvedor do seu Android e emparelhar no Android Studio via cabo ou wi-fi.
Após isso, digite os seguintes comandos no seu terminal:

```
ionic cap build android
```
ionic cap run android -l --external
```
E após isso escolher a rede ethernet ou wi-fi nas opções do terminal