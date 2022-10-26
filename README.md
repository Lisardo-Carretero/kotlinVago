# Truquitos
* Dar formato al *PUTO CODIGO*
````aidl
CONTROL+ALT+L
````
* Crear Actividades
>  startActivity(Intent(this,UserPage::class.java)

y si quieres que no se pueda volver a la anterior

>finish()
* __Asociar Botones y otros atributos__

Es como crear una varaible de tipo Button y se asocian con findViewById que es como en esta pagina o 
vista encuentra por id a tal primo.
>val botonLog:Button = findViewById(R.id.botonLogin)
> 
> val campoUsuario: String = findViewById<EditText>(R.id.userLogin).text.toString().trim()

botonLog es la variable con atributo setOnclickListener eso es que cuando le des pues se ejecuta el metodo
login()
>botonLog.setOnClickListener { login() }







### Referencias
1.  Dialogos 
* https://m2.material.io/components/dialogs
* https://www.develou.com/como-crear-dialogos-en-android/

2. Eventos
* https://developer.android.com/guide/topics/ui/ui-events?hl=es-419#kotlin

3. EditText
* https://www.develou.com/edittext-android/

4. Firebase
* https://firebase.google.com/docs?hl=es-419

5. Mockup

* https://app.diagrams.net
---
