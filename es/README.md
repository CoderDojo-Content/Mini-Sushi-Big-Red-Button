1. ¡Vas a crear una aplicación con un botón grande que, al pulsarlo, mostrará un mensaje sorpresa! Ve a App Inventor y selecciona "Start a new project" en el menú **Projects**. Dale un nombre a tu proyecto.

2. En **Palette** a la izquierda, haz clic en **Layout** y arrastra **VerticalArrangement** a la pantalla del teléfono.
 
3. En el panel **Properties** de la derecha, haz clic en la propiedad **Height**, selecciona **Fill parent** y haz clic en **OK**. Procede del mismo modo para la propiedad **Width**. 

4. Ahora, vete a **Palette** en **User Interface** y arrastra un **Button** en tu **VerticalArrangement** de la pantalla del teléfono.

5. Arriba a la derecha, en **Components**, haz clic en el componente `VerticalArrangement1`. En el panel **Properties**, ajusta **AlignHorizontal** y **AlignVertical** en _Center_. ¿Viste el botón moverse al medio de la pantalla del teléfono?
   ![](VertArrAlignProps_258_800.png)
   
6. Selecciona `Button1` y, en **Properties**, desplázate hacia abajo y cambia **Text** a "Do not press". Si lo deseas, cambia también las propiedades de **BackgroundColor** y **Font**.
   ![](ButtonPropsFont_290_900.png)
   
7. Cambia las propiedades de **Height** y **Width** a `150` **pixels** y cambia **Shape** a **oval**.

8. Haz clic en el botón **Add Screen** cerca de la parte superior de la página. Deja el nombre como Screen2 y haz clic en **OK**.

9. Cuando se cargue la nueva pantalla, localiza el componente **Label** en **User Interface** en la paleta y arrástralo a la pantalla. En **Properties**, cambia **Text** a "This app will self destruct in 5 seconds".

10. En **Sensors** en **Palette**, localiza **Clock** y arrástralo a la pantalla. Se trata de un componente invisible, por lo tanto, no lo verás en la pantalla. En **Properties**, cambia **TimerInterval** a `5000`.

11. Haz clic en **Blocks** arriba a la derecha. Haz clic en `Clock1` y extrae el bloque `When Clock1.Timer do`. A continuación, haz clic en **Control** en los bloques **Built-in**, agarra el bloque `close application` y colócalo en el otro bloque. 
    ![](TimerBlock_124_800.png)
    
12. Accede a `Screen1` seleccionándola en el botón cerca de la parte superior.

13. Añade los siguientes bloques de **Button1** y **Control**.
    ![](Button1BlocksA_64_800.png)
    
14. En **Built-in** selecciona **Text** saca el bloque de texto vacío \(es posible que tengas que desplazarte, está arriba del todo\) y colócalo en posición. Haz clic dentro y escribe "Screen2".
   ![](Button1BlocksB_66_800.png)
   
15. ¡Has acabado tu aplicación! Prueba usando Emulator en **Connect** en el menú o selecciona una opción de código QR en **Build** para obtener un enlace para la instalación de la aplicación en tu dispositivo Android.
 * **Nota:** Para instalar mediante códigos QR, debes activar "Permitir la instalación de aplicaciones de fuentes desconocidas" en tu dispositivo Android.
    ![](Button_160_800.png) 
![](whitespace_70_800.png)

{% callout %}<span style="color: #000000; margen derecho: 10px;">¡Esto solamente es el comienzo! Aprende a crear un concurso de preguntas en Beginner App Inventor Sushi Cards en <b>http://dojo.soy/mini-apps-begin</b>, ¡y gana una insignia digital! Para ver esta tarjeta online o para imprimir más, visita <b>http://dojo.soy/mini-sushi-appinv</b> </span>
{% endcallout %}







