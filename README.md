# Android Project, contiene:
  
  - Módulo de audio del Envelope Generator generado en FAUST.
  - Boton para disparar la señal (Trigger).
  
La idea es incluir los archivos que exporta FAUST en el proyecto principal. Estos archivos son:

  - DspFaust.cpp
  - java_interface_wrap.cpp
  - DspFaust.h
  - dsp_faust.java
  - DspFaust.java
  - dsp_faustJNI.java
  
Los mismos están en app/src/main/cpp y app/src/main/java/com respectivamente. Deberían ser incluidos en el proyecto ubicado en el repositorio untref-sintetizador, dentro de Synth3F.
