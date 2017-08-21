# spring-web-jpa

## instalacja

Wymagania:
* Java 8
* PostgreSQL 9.4+
* Włączony plugin Gradle w IJ.

Po uruchomieniu IJ wybrać opcję "open", wskazać plik "build.gradle" z konfiguracją projektu, a następnie nacisnąć opcję "Open as Project". W oknie dialogowym nowego project zaznaczyć opcję "Use auto import".

W oknie "gradle" rozwinąć opcję "Tasks->application->bootRun", a następnie z menu kontekstowego wybrać opcję "Run 'demo [bootRun]'" - serwera zastanie uruchomiony pod adresem http://localhost:8080.

## REST API

* / GET - hello world