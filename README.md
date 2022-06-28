# Solução Desafio Santander Dio  News App  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b8/Banco_Santander_Logotipo.svg/1280px-Banco_Santander_Logotipo.svg.png" width="100" height="30"> <img src="https://static.wixstatic.com/media/7a378f_5140deabd7d040378d740069cb692b87~mv2.png/v1/crop/x_0,y_10,w_1334,h_493/fill/w_568,h_208,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/logo%20DIO.png" height="25px" width="60px"> 

## Navegue aqui :3
* [Informações gerais](#informações-gerais)
* [Capturas de tela](#screenshots)
* [Tecnologias](#tecnologia)
* [Setup](#setup)
* [License](#license)

## Informações gerais

Antes de tudo, se você é um dos inspetores que vão analizar meu código do desafio deixe-me esclarecer uma coisa,
esse aplicativo foi feito em KOTLIN e não java como proposto pelo desafio além disso,
não se limita apenas à notícias de futebol,
visto que preferi me arriscar em terras novas e seguir um desafio de verdade,
seguindo não apenas o aplicativo proprosto em JAVA e sobre FUTEBOL nas aulas.
Sendo posto, adicionei um setor de negócios que está relacionado ao programa Santander,
além de outros variados tópicos (incluso o de esportes). Sendo assim podemos proseguir :)

Os tópicos são inclusos em quatro categorias: Melhores, Negócios, Inovação, Esportes.
Tudo implementado com o princípio SOLID, e Clean Code.


## Screenshots

<p float="left">
  <img src="images/0-splash.jpg" width="100" />
  <img src="images/1-home.jpg" width="100" /> 
  <img src="images/2-saved.jpg" width="100" />
  <img src="images/3-saved-remove.jpg" width="100" />
  <img src="images/4-network.jpg" width="100" />
  <img src="images/4-no-saved.jpg" width="100" />
  <img src="images/5-settings.jpg" width="100" />
</p>

## Tecnologia

#### Linguagens:
- Kotlin 
- Xml

#### Arquitetura usada:
- MVVM

#### Libraries:
- Retrofit  2.9.0 (https://square.github.io/retrofit/)
- Gson      2.9.6 (https://github.com/google/gson)
- Room      2.4.2 (https://developer.android.com/training/data-storage/room)
- Glide     4.13.0 (https://github.com/bumptech/glide)
- Coroutine 1.6.1 (https://developer.android.com/kotlin/coroutines)
- Paging    3.1.1 (https://developer.android.com/topic/libraries/architecture/paging/v3-overview)
- Hilt      2.40.1 (https://developer.android.com/training/dependency-injection/hilt-android)
- ViewPager 1.0.0 (https://developer.android.com/jetpack/androidx/releases/viewpager2)
- ViewModel, LiveData, Viewbinding 2.4.1 (https://developer.android.com/jetpack/androidx/releases/lifecycle)

## Setup

Para rodar esse projeto, instale-o baixando ou clonando o repositório.
Então registre no website da api (https://newsapi.org/s/google-news-api) 
para pegar a sua chave principal (substitua ela pela atual em data/local/Constants.kt/API_KEY)

#### Requisitos do sistema 
- Ter um computador
- Android Studio Chipmunk | 2021.2.1
- Minimum sdk v21
- Build tool v30.0.3
- Compile sdk v32


## Licença

```html
MIT Licence 

Copyright (c) 2022 Ahmed Zaki

Permission is hereby granted, free of charge, to any person obtaining a copy of this software
and associated documentation files (the "Software"), to deal in the Software without restriction,
including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, 
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial 
portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, 
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE
AND NONINFRINGEMENT.IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE
OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
