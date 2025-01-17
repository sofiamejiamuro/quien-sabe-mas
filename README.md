# ¿Quién sabe más?

Esta skill de Alexa fue diseñada y desarrollada durante el Hackhaton *Women in Voice Amazon Edition* que se llevo acabo el 14 de noviembre de 2019 en CDMX.

Como resultado se obtuvimos el primer lugar.

<p  align="left">
<img src="./assets/images/hackathon-women-in-voice.jpg"  width="200"/>
</p>
El reto era de temática abierta.

## ¿Por qué un juego?

La propuesta fue crear un juego en el que pudieran existir múltiples participantes. Alexa es considerada en gran medida un dispositivo que funciona como asistente para diversas tareas, se espera que la interación sea una persona - Alexa. Sin embargo, para este proyecto la intención era que Alexa funcionase como un punto de encuentro, como una conexión entre varios individuos y que permitiera la integración a la vida cotidiana de este tipo de tecnolgías de una forma más amena.

El juego consiste en un conjuto de preguntas que Alexa hará y que los participantes responderán, será según la respuesta del participante la acción. Si el participante no responde correctamente Alexa le dará la opción de pistas, si aún así no adivina, el participante deberá beber un shot. Si la respuesta es correcta, otro participante continúa.

Para esta skill se precisó que el tono fuera casual, divertido, irreverente. El léxico que se utilizó siguió estas pautas.  

## Conversation design

[Aquí](https://github.com/sofiamejiamuro/quien-sabe-mas/blob/master/quien-sabe-mas-conversation.md) se puede ver el draft inicial de la conversación

[Aquí](https://github.com/sofiamejiamuro/quien-sabe-mas/blob/master/model.json) se puede ver el interaction model utilizado en el código.


## Intents && Utterances 

Para este MVP se definieron los siguientes *intents* con sus respectivas *utterances*:

| Intents                     |      Utterances |
|-----------------------------|-----------------|
| DifficultIntent             |'dificilito' , 'dificil
|EasyIntent                   |'facilisimo', 'facilito', 'facil'
|SuperDifficultIntent         |'muy dificil', 'super dificil', 'redificil'
|EntroIntent                  |'si','sip','simona la mona', 'venga pues'
|NoIntent                     | 'que no','nop', 'mejor luego'
|NoUnderstandIntent           |'o sea como', 'otra vez', 'hablas muy rapido', 'como dijiste'
|TitanicCorrectIntent         | 'titanic','taitanic'
|NoIdeaIntent                 | 'dame otra pista','no me aacuerdo', 'quien sabe', 'ni idea'


 

## Código

Una vez diseñada la conversación se desarrollo la skill con JavaScript en la alexa developer console. El codigo se puede ver [aquí](https://github.com/sofiamejiamuro/quien-sabe-mas/blob/master/index.js).

<img src="./assets/images/alexa-developer-console.png"  width="800"/>

## Skill ¿Quién sabe más?

A continuación se pueden escuchar tres grabaciones de la interación persona - Alexa en este juego.

[quien-sabe-mas-1](https://drive.google.com/file/d/1G6whs9w3o9X2dfRzhWdMqKMtC2pCrWr7/view?usp=sharing)

[quien-sabe-mas-2](https://drive.google.com/file/d/1mlnS5H1P6Uvk2m9o2MDq9NQu7c1jf4Nx/view?usp=sharing)

[quien-sabe-mas-flujo-completo3](https://drive.google.com/file/d/1KZPo8ieuZu4QUOZTT92pIaRqigW4anCt/view?usp=sharing)