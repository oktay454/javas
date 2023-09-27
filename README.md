# javas

## Türkçe

### Java JAR Dosyası Başlatıcı
JAR dosyalarını çift tıklama ile başlatabilmek için sade bir betik.
javas.desktop dosyası, masaüstü ortamında çift tıklama ile çalıştırabilmek için gerekli.
Masaüstü ortamında uygulamalar içerisinden Javas çağrılırsa dosya seçme penceresi açılır ve seçilen JAR dosyasını çalıştırır.

JAR dosyalarının öntanımlı olarak javas ile açılmasını için şu komutla da ayarlayabilirsiniz.

`xdg-mime default javas.desktop application/java-archive application/x-java-archive application/x-jar`

---

## English

### Java JAR File Launcher
A simple script to launch JAR files with a double click.
The javas.desktop file is required for double-clicking on the desktop environment.
If Javas is called from within the applications in the desktop environment, the file selection window opens and runs the selected JAR file.

You can also set JAR files to be opened with javas by default with the following command.

`xdg-mime default javas.desktop application/java-archive application/x-java-archive application/x-jar`
