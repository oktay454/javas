# javas

## Türkçe

### Java JAR Dosyası Başlatıcı
JAR dosyalarını çift tıklama ile başlatabilmek için sade bir betik.
javas.desktop dosyası, masaüstü ortamında çift tıklama ile çalıştırabilmek için gerekli.
Masaüstü ortamında uygulamalar içerisinden Javas çağrılırsa dosya seçme penceresi açılır ve seçilen JAR dosyasını çalıştırır.

#### Kurulum
Repodaki dosyaların bulunduğu dizine girerek şu komutları çalıştırıyoruz.

Çalıştırma iznini vererek paket yöneticisinin denetimi dışındaki kısma kopyalıyoruz.

`sudo install -Dm0755 javas /usr/local/bin/javas`

Masaüstü ortamı için gerekli dosyayı kopyalıyoruz.

`sudo install -Dm0644 javas.desktop /usr/local/share/applications/javas.desktop`

JAR dosyalarının öntanımlı olarak javas ile açılmasını için şu komutla da ayarlayabilirsiniz.

`xdg-mime default javas.desktop application/java-archive application/x-java-archive application/x-jar`

---

## English

### Java JAR File Launcher
A simple script to launch JAR files with a double click.
The javas.desktop file is required for double-clicking on the desktop environment.
If Javas is called from within the applications in the desktop environment, the file selection window opens and runs the selected JAR file.

#### Setup

We run the following commands by entering the directory where the files in the repo are located.

By giving the run permission, we copy it to the part outside the control of the package manager.

`sudo install -Dm0755 javas /usr/local/bin/javas`

We copy the necessary file for the desktop environment.

`sudo install -Dm0644 javas.desktop /usr/local/share/applications/javas.desktop`

You can also set JAR files to be opened with javas by default with the following command.

`xdg-mime default javas.desktop application/java-archive application/x-java-archive application/x-jar`
