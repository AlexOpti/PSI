Projekt Vagrant Drupal

Opis: Utworzenie dw�ch maszyn wirtualnych, jednej zawieraj�cej instalator CMS - Drupal, drugiej zawieraj�cej pakiet mysql z przygotowan� baz� danych. Efektem ko�cowym jest poprawne zainstalowanie CMS.

W celu uruchomienia projektu:

- Pobra� oraz zainstalowa� program VirtualBox (link poni�ej) 

- Pobra� oraz zainstalowa� program Vagrant (link poni�ej)

- W katalogu z plikiem konfiguracyjnym Vagrantfile, wykona� komend� vagrant up. Spowoduje to rozpocz�cie tworzenia si�     naszych maszyn wirtualnych (zdj�cie vagrant_up.png)


- Po zako�czonym procesie tworzenia maszyn wirtualnych, za pomoc� przegl�darki, przej�� pod adres     https://192.168.43.110/install.php. 

- Poprawane wykonanie wcze�niejszych krok�w, spowoduje rozpocz�cie instalacji Drupal'a (zdj�cie instalacja1.png)

- Przej�cie do kolejnego kroku wymusza od nas podanie danych do po��czenia z baz� danych. Podajemy jej dane u�ytkownika,   zgodnie z zapisanymi w skrypcie db.sh. Jako host bazy danych, podajemy 192.168.43.111 (zdj�cie instalacja2.png)


- W ostatnim kroku, po poprawnym po��czeniu z baz� danych, instalator prosi o podanie danych u�ytkownika przysz�ej strony   (zdj�cie instalacja3.png)



Przydatne linki:

Vrtual Box:
https://www.virtualbox.org/

Vagrant:
https://www.vagrantup.com/







