# Progressbarpersonalizado
Barra de progreso personalizada en Android studio.

1º Creamos el xml para el background del progressbar progressbar_background.xml

2º En este paso crearemos el XML Drawable que lo englobará todo y que será el que pasaremos como parámetro a nuestro Progresbar. Lo llamaremos progressbar_progress.xml

3º Nos queda usar nuestros drawables en el Progressbar que queramos, para ello bastara con indicar el atributo progressDrawable el drawable que hemos creado en el paso 2.
  
  Ejemplo:
      
      <SeekBar
        android:id="@+id/frequency_slider"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:max="20"
        android:progress="0"
        android:secondaryProgress="0"
        android:progressDrawable="@drawable/progressbar_progress" 
        android:thumb="@drawable/seek_thumb"
      />
