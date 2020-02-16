## 📝Installationsanleitung

⚠️ Bitte beachten Sie, dass die Beispiele vom Buch mit der Version 1.x von TensorFlow ausführbar sind! Hierbei müssen Sie bei der Installation von TensorFlow auf den Versionszusatz achten, wie unten aufgeführt (```pip install tensorflow==1.13.2``` bzw. ```pip install tensorflow-gpu==1.13.2```).

Zum schnellen Einstieg empfehlen wir die Python-Installation mit Anaconda: https://www.anaconda.com/distribution/

NB: Unter Windows müssen Sie, nachdem Anaconda etwa unter C:\Users\<IHRNAME>\Anaconda3 installiert wurde, C:\Users\<IHRNAME>\Anaconda3\condabin zu Ihrer Umgebungsvariable PATH hinzufügen. <br>

#### Organisation der Arbeitsumgebung
Wir empfehlen Ihnen ein Projektverzeichnis in Ihrem HOME-Verzeichnis anzulegen, etwa <i>deeplearning_buch</i>:<br>
```mkdir deeplearning_buch```

Dann wechseln Sie zu diesem Verzeichnis und können dort die Beispiele vom Buch speichern.

#### Python-Installation mit Anaconda
Erzeugen Sie eine Umgebung namens <i>dl_env</i> mit der Python Version 3.6:<br>
```conda create -n dl_env python=3.6```


Nachdem die Umgebung erzeugt wurde, muss sie nun aktiviert werden:<br>
```conda activate dl_env```

Um alle Beispiele der ersten Kapitel des Buches zu bearbeiten, empfehlen wir Ihnen in einer einzigen Aktion folgende Pakete zu installieren:

```conda install numpy scipy pandas scikit-learn matplotlib```<br>
```conda install tensorflow==1.13.1```<br>
```conda install keras```<br>
```pip install tensorflowjs==1.0.1```  <br><br> *(Dank an Andreas)*

Ein Vorteil von conda ist es, dass beim Installieren eines Pakets nicht nur dieses sondern auch alle vom ihm benötigten Pakete mitinstalliert werden.


Wenn Sie die Liste aller definierten Umgebungen bekommen möchten, können Sie folgendes Kommando ausführen:<br>
```conda env list```

#### Starten der Umgebung
Jedesmal, wenn Sie mit dem Buch arbeiten möchten, empfiehlt es sich zu Ihrem Arbeitsverzeichnis zu wechseln und die Python-Umgebung <i>dl_env</i> im Terminal zu aktivieren mit:<br>
```conda activate dl_env```

#### Beendigung der Arbeiten 
Nach Beendigung Ihrer Arbeiten sollten Sie die <i>dl_env</i> Umgebung deaktivieren:<br>
```conda deactivate```
