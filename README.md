
## Sobre o Autor
<img   style="border-radius: 50%"  align="left" width="190" height="190" margin-right="150px"  src="https://lh3.googleusercontent.com/pw/AM-JKLUq-TgjEzhoVY_CtieDZgnZNOoIGyAubOEKisc2FKt7HMCSVv4DGHZjixw4Z2_yomTtgUKr0kxFUyUdmOuTyJnQfhgzXEyOVk6JoajO58wYDtWcrDF-EPRjaE1hj2EsZtM-OYgQsDjHGjdny1yGetxeWw=s250-no?authuser=0"> Oi, meu nome é Pedro Savio, faço engenharia de computação no IFPB, sou desenvolvedor Fullstack e esse é o meu linkedin,  [ir para meu linkdin](https://www.linkedin.com/in/pedro-s-04a300129/).

<br/><br/><br/><br/><br/>


# Login Base para aplicações android utilizando o Google.
<br/>
###1. Crie um novo projeto em java no android studio
<br/>

###2. Vá em grandle script no build .app e cole as dpendencias a baixo

<br/>
```javascript
implementation 'com.google.android.gms:play-services-auth:20.1.0'
implementation 'com.github.bumptech.glide:glide:3.7.0'
```
<br/>
###3. Nesse link configure um novo projeto [Configure um novo projeto Google](https://developers.google.com/identity/sign-in/android/start-integrating)
<br/>

<br/>

###4. De um nome a seu novo proejo "logargogle"

<br/>

<br/>

###5. Configure seu Oauth cliente para android
configure seu Oauth cliente para android
pegue o packgaje name no main activity do projeto "com.example.logingoogle"
em grandle encontre o SHA1 DIGITANDO gradle signingReport
DEPOS QUE POR OS DADOS NO SITE DA GOOGLE BASTA BAIXAR O CLIENT
MOVA O ARQUIVO BAIXADO PARA RAIZ DA PASTA APP DO PROJETO ONDE FICA O GITGNORE
<br/>
<br/>
###6. Criar a permissao pra usar a internet em android manifest.xml add essa permissao em baixo do packge 
```javascript
 <uses-permission android:name="android.permission.INTERNET"/>
```
<br/>
<br/>
###7. Apos isso copie as linhas de codigos e faça as imporações se necessário dos arquivos do mainActivity e do profilectvit

<br/>

<br/>
###8. Em grandl.properties adicione
```javascript
android.enableJetifier=true
```

<br/>



##Pronto, com isso vc ja tem seu base login google, parabens!

